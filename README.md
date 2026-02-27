# 🔐 Web Application Penetration Testing Lab

This project demonstrates a **hands-on Web Application Penetration Testing assessment** conducted on the intentionally vulnerable application **OWASP Juice Shop** in a controlled lab environment.

The goal of this project was to simulate a **real-world security assessment**, identify vulnerabilities, and document findings in a professional penetration testing report.

# 🧪 Lab Environment

**Attacker Machine**
- Parrot OS

**Target Machine**
- Windows 11

**Virtualization Platform**
- VirtualBox

**Network Configuration**
- Adapter 1: NAT (Internet access)
- Adapter 2: Internal Network (Isolated penetration testing environment)

This setup ensured safe and controlled security testing.

# 🔎 Security Testing Methodology

The penetration testing process followed a structured workflow:

1. Reconnaissance  
2. Traffic Interception and Analysis  
3. Vulnerability Scanning  
4. Exploitation  
5. Risk Classification  
6. Remediation Recommendations  

# 🛠 Tools Used

- Nmap – Network reconnaissance and service detection  
- Burp Suite – Web traffic interception and request analysis  
- Nikto – Web server vulnerability scanning  
- sqlmap – SQL Injection exploitation and database enumeration  

# ⚠️ Vulnerabilities Identified

The following vulnerabilities were discovered during the assessment:

### SQL Injection
- Allowed database enumeration and extraction of sensitive data such as user email and password fields.

### Reflected Cross-Site Scripting (XSS)
- Malicious scripts executed through user input in the search functionality.

### DOM-Based Cross-Site Scripting
- Client-side JavaScript manipulation allowed execution of injected payloads.

### Broken Access Control
- Unauthorized access to restricted administrative functionality.

# 📊 Project Outcome

The project resulted in a **professional penetration testing report** containing:

- Detailed vulnerability findings
- Evidence screenshots
- Risk classification
- Security recommendations
- Mitigation strategies

This project helped strengthen practical understanding of **web application security testing and vulnerability assessment methodologies**.

# 💡 Skills Demonstrated

- Web Application Penetration Testing
- Vulnerability Assessment
- Security Tool Usage
- Security Reporting
- Offensive Security Fundamentals

# 📂 Repository Contents
