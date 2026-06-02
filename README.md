# FUTURE_CS_01

# Web Application Vulnerability Assessment Portfolio

## Project Overview
This repository hosts a formal security vulnerability assessment performed on the public demonstration application `https://testfire.net`. The project showcases standard engineering workflows across network service mapping, automated application auditing, and manual client-side inspection patterns.

## Technical Scope & Toolkit
* **Infrastructure Auditing:** Nmap (Zenmap) for port state identification.
* **Application Mapping:** OWASP ZAP 2.17.0 for manual context routing and spidering.
* **Security Verification:** Microsoft Edge DevTools for live HTTP header audit testing.

## Summary of Core Security Gaps
1. **Information Leakage:** Broadcasts explicit technology stack signatures (`Apache-Coyote/1.1`).
2. **Defensive Configuration Absence:** Complete lack of anti-clickjacking (`X-Frame-Options`) and injection protection infrastructure policies.

## Project Deliverables
* [Click Here to View the Full PDF Assessment Report](./Vulnerability Assessment Report.pdf)
