# 🔐 Zscaler Identity Integration & Web Security Assessment

> Secure authentication and authorization using **Zscaler + Identity Providers (Azure AD, Okta, Active Directory)** while implementing **Zero Trust security architecture** and performing **web vulnerability assessment based on OWASP Top 10**.

---

## 📖 Project Description

This project focuses on integrating the **Zscaler security platform with enterprise Identity Providers (IdPs)** such as:

- Microsoft Entra ID (Azure AD)
- Okta
- Active Directory

The integration enables **secure authentication, Single Sign-On (SSO), Multi-Factor Authentication (MFA), and centralized identity management**.

Additionally, the project includes **web application security testing and vulnerability analysis** using industry-standard tools and OWASP security guidelines.

---

## 🎯 Project Goals

- Implement **Zero Trust security model**
- Enable **Single Sign-On authentication**
- Centralize identity management
- Replace legacy **VPN access with secure identity-based access**
- Detect and mitigate **web security vulnerabilities**
- Improve **network and application security posture**

---

## 👥 Team Members

| Roll No | Name | College |
|--------|------|---------|
| 2322JA01 | Aakash V | KG College of Arts and Science |
| 2322JA02 | Abdul Waheed A | KG College of Arts and Science |
| 2322JA03 | Abitheesh M | KG College of Arts and Science |
| 2322JA04 | Adhithyan R | KG College of Arts and Science |
| 2322JA05 | Alwin E | KG College of Arts and Science |

---

## 🏗️ System Architecture

```
User → Identity Provider → Authentication → Zscaler Security Platform → Application Access
```

### Components

| Component | Role |
|--------|------|
| Zscaler | Cloud security gateway |
| Azure AD | Microsoft identity provider |
| Okta | Identity management platform |
| Active Directory | On-premises user directory |
| SAML / OIDC | Authentication protocols |
| SCIM | User provisioning protocol |

---

## 🔑 Key Security Features

### 🔹 Single Sign-On (SSO)
Users authenticate once and access multiple services without repeated login.

### 🔹 Multi-Factor Authentication (MFA)
Additional verification step to enhance security.

### 🔹 Identity-Based Access Control
Access policies based on:

- User role
- Device status
- Location
- Risk profile

### 🔹 Automated User Provisioning
User lifecycle management using **SCIM synchronization**.

---

## 📊 Real-World Use Cases

### 👨‍🏫 Remote Faculty Access
- Secure access to research data
- MFA authentication
- Restricted access to specific server

### 🎓 Student Library Access
- Secure access to digital journals
- Identity verification
- No administrative system access

### 👩‍💼 HR Payroll System
- Time-based access restrictions
- Step-up MFA authentication
- Full activity logging

### 🖥️ IT Helpdesk Access
- Just-in-Time administrative access
- Session monitoring
- Temporary elevated privileges

### 👨‍💻 Contractor Access
- Limited application access
- Automatic account expiration

---

## 🛡️ Web Application Vulnerability Analysis

The project also includes **security testing of websites based on OWASP Top 10 vulnerabilities**.

### Tools Used

- Nessus
- Nmap
- SSL Labs
- SecurityHeaders
- Shodan

### Example Vulnerabilities Detected

| Vulnerability | CWE |
|---------------|------|
| Improper Access Control | CWE-284 |
| Invalid Certificate Validation | CWE-395 |
| Missing X-Frame-Options Header | CWE-1021 |
| Cross-Site Scripting (XSS) | CWE-79 |
| SQL Injection | CWE-20 |
| Server-Side Request Forgery | CWE-918 |
| Denial of Service | CWE-400 |
| TLS 1.0 Protocol Detection | CWE-327 |

Each vulnerability includes:

- Description  
- Business impact  
- Reproduction steps  
- Remediation strategy  

---

## 🔎 Vulnerability Scanning using Nessus

Nessus was used to scan the target system and identify potential security risks.

### Target

```
Website : http://testfire.net
IP Address : 65.61.137.117
```

### Example Scan Results

| Vulnerability | Severity |
|---------------|---------|
| TLS 1.0 Protocol Detection | Medium |
| TLS 1.1 Deprecated | Medium |
| Weak Diffie-Hellman Cipher | Low |
| ICMP Timestamp Disclosure | Info |
| HSTS Missing | Info |

---

## 🧰 Technologies & Tools

| Category | Technology |
|--------|-------------|
| Security Platform | Zscaler |
| Identity Providers | Azure AD, Okta, Active Directory |
| Protocols | SAML, OIDC, SCIM |
| Security Tools | Nessus, Nmap |
| Security Framework | OWASP Top 10 |

---

## 📈 Benefits of the System

- Strong identity-based security
- Reduced attack surface
- Secure remote access
- Centralized identity management
- Improved compliance with security standards

---

## 👨‍💻 Author

**Abdul Waheed A**  
KG College of Arts and Science  

---

## 📜 License

This project is developed for **educational and cybersecurity research purposes**.
