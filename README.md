# Zero Trust Network Access (ZTNA) with Zscaler Enabling Secure and Direct Application Connectivity**

## 📋 Overview

This project focuses on implementing a modern security framework using **Zero Trust Network Access (ZTNA)** with **Zscaler**. Unlike traditional perimeter-based security (the "castle-and-moat" model), this system operates on the principle of **"never trust, always verify"**. It ensures that every user and device is authenticated and authorized before granting access to specific enterprise applications, rather than the entire internal network.

## 🚀 Key Features

*Identity-Based Access**: Establishes application-specific connections based on user identity, device posture, and granular security policies.

* 
**AI-Enhanced User Protection (AIUP)**: Uses AI and Machine Learning to monitor user behavior, detect anomalies (like unusual login locations), and prevent unauthorized access in real-time.


* 
**Reduced Attack Surface**: Keeps internal applications hidden from the public internet, preventing lateral movement by attackers within the network.


* 
**Secure Direct Connectivity**: Facilitates encrypted, direct user-to-application connections without the need for traditional, broad-access VPNs.

## 🛡️ Security Analysis (Vulnerability Assessment)

The project includes a comprehensive security evaluation conducted in multiple stages:

### Stage 1: Web Application Testing

Manual and systematic testing based on **OWASP Top 10** risks. Identified vulnerabilities include:

* 
**Broken Access Control (CWE-282)**: Improper ownership management.


* 
**Security Misconfiguration (CWE-315)**: Cleartext storage of sensitive data in cookies.


* 
**Cryptographic Failures (CWE-331)**: Insufficient entropy in random value generation.



### Stage 2: Automated Scanning with Nessus

Utilized the **Nessus Vulnerability Scanner** to identify infrastructure-level weaknesses. Key findings:

* 
**TLS Vulnerabilities**: Detection of deprecated TLS 1.0 and 1.1 protocols (Medium Severity).


* 
**Weak Encryption**: SSL/TLS Diffie-Hellman Modulus $\le$ 1024 bits (Logjam).


* 
**HSTS Missing**: HTTPS server not enforcing HTTP Strict Transport Security.



## 📈 Use Case Scenarios

1. 
**Secure Remote Access**: Verifying home-based employees through device posture checks before granting access to internal apps.


2. 
**Third-Party Vendor Access**: Providing temporary, restricted access to specific maintenance tools without exposing other internal systems.


3. 
**Anomaly Detection**: Automatically triggering Multi-Factor Authentication (MFA) when a login attempt is detected from an unusual device or location.



## 🛠️ Tools Explored

* 
**Zscaler Private Access (ZPA)**: For ZTNA implementation.


* 
**Nessus**: For remote vulnerability scanning and reporting.


* 
**Security Stack**: ZTNA, Secure Web Gateways (SWG), and Cloud Access Security Brokers (CASB).



## 👥 Team Members (SWTID-2026-1768)

* Akalya M 


* Anne Debora P 


* Mohammed Suhail Akthar J 


* Narendran S 


* Vishnu Pradeep S 



---

This project was developed at Sri Krishna Adithya College of Arts and Science.
