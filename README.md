# Cybersecurity GRC Portfolio

Welcome to my Governance, Risk, and Compliance (GRC) portfolio. This repository contains practical artifacts, risk assessment reports, and compliance frameworks based on industry standards like NIST and ISO/IEC 27001.

---

## Project 1: NIST SP 800-30 Based Risk Assessment Report

### 1. Objective
To evaluate the security posture of a hypothetical enterprise e-commerce web application, identify potential threats and vulnerabilities, and formulate risk mitigation strategies in accordance with the NIST SP 800-30 framework.

### 2. Asset Identification
* **Customer Database:** Stores Personally Identifiable Information (PII) and authentication credentials.
* **Web Application Server:** Handles user requests and business logic.
* **Payment Gateway Integration:** Processes financial transactions.

### 3. Threat & Vulnerability Analysis
* **Threat Source:** External attackers, malicious insiders.
* **Vulnerabilities Identified:**
  * Lack of multi-factor authentication (MFA) for administrative access.
  * Unencrypted sensitive data storage in transit and at rest.
  * Outdated software dependencies prone to known vulnerabilities.

### 4. Risk Analysis Matrix
| Threat / Vulnerability | Likelihood | Impact | Risk Level |
| :--- | :--- | :--- | :--- |
| SQL Injection in Login Portal | High | High | **Critical** |
| Missing MFA for Admin Accounts | Medium | High | **High** |
| Weak Password Policies | High | Medium | **Medium** |

### 5. Mitigation & Remediation Recommendations
* Implement parameterized queries and input validation to eliminate SQL injection vectors.
* Enforce Multi-Factor Authentication (MFA) across all administrative portals.
* Adopt robust encryption standards (AES-256 for data at rest, TLS 1.3 for data in transit).

---

## Connect with me
* **GitHub:** [Aksha08092004](https://github.com/Aksha08092004)
* **Email:** akshaysajeevan557@gmail.com
