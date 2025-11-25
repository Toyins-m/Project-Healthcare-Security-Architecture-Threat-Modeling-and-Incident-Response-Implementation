# Healthcare Security Architecture, Threat Modeling, and Incident Response Implementation

## 📌 Project Description
This repository contains all deliverables for a healthcare cybersecurity architecture and threat-modeling engagement. The project simulates the end-to-end security lifecycle for a healthcare provider, including:
- Data classification & governance
- Risk assessments using NIST CSF
- Threat analysis & mitigation
- Incident response (USB-borne malware attack scenario)
- System hardening (server, OS, network, database, physical security)
- Security auditing (based on the IIA toolkit)
- Strategic recommendations for ongoing compliance and resilience
Deliverables were created using real cybersecurity frameworks and mapped directly to healthcare regulatory requirements.

## 🎯 Objectives / Goals
- Implement a healthcare-grade data classification standard to protect PHI, PII, and financial data 
- Conduct a risk assessment & action plan following NIST CSF Identify → Protect → Detect → Respond → Recover
- Perform threat modeling and analyze vulnerabilities across IT and clinical systems
- Simulate and document a malware attack & breach scenario, including containment and lessons learned
- Implement system hardening & auditing for Windows-based healthcare systems
- Strengthen organizational resilience by applying cybersecurity controls aligned with HIPAA, NIST CSF, and industry standards

## 🧠 Skills Learned
- Threat Modeling (healthcare infrastructure)
- Security Architecture & Hardening
- Data Classification & Governance (HIPAA compliance)
- Malware analysis (USB-borne malware) & incident response
- Risk Assessment & Mitigation (NIST CSF)
- Identity & Access Management (RBAC, MFA)
- SIEM, IDS, logging, and continuous monitoring
- Vulnerability assessments & penetration testing principles
- Policy writing and audit documentation (IIA toolkit)

## 🛠 Tools & Technologies

| Category                                       | Tools / Methods         |
|------------------------------------------------|----------------------------|
| Frameworks                                     | NIST CSF, HIPAA Security & Privacy Rules, IIA Cybersecurity Toolkit |
| Security Controls                              | RBAC, MFA, Encryption, DLP, SIEM, IDS/IPS |
| System Hardening                               | Windows Defender, Patch Management, Application Control |
| Monitoring & Detection                         | Event Logs, SIEM Alerts, IDS Rules |
| Threat Modeling                                | Malware analysis, case-study comparison, vulnerability analysis |
| Governance                                     | SOC Automation Lab|


## 📐 Methodology
### 1. Data Classification
Created a four-tier classification model—Public, Internal, Classified, Private—mapped to all CareAtHome data assets such as patient data, payroll, insurance, PHI/PII, and vendor information.

### 2. Risk Assessment (NIST)
Performed a full asset-based risk evaluation, including threat likelihood, impact, and justification.

Assessed 20+ assets, including:
- Patient personal data
- Payroll systems
- Medical equipment
- Insurance records
- Networking infrastructure
- Software keys & login tokens

### 3. Threat Modeling
Analyzed threats such as ransomware, unauthorized access, insider threats, third-party compromise, and DDoS.

Mapped these threats to:
- CIA Triad
- HIPAA compliance risks
- Likelihood & mitigation strategies

### 4. Malware Incident Response Simulation
Simulated a malware attack caused by unauthorized USB use.

Documented:
- Root cause analysis
- Forensics
- Healthcare breach case studies
- Outcomes on confidentiality, integrity & availability
- Immediate + long-term countermeasures

### 5. System Hardening & Auditing
Performed System hardening across:
- Servers
- OS
- Networks
- Databases
- Applications
- Physical security assets

Integrated:
- IDS/IPS
- SIEM logging
- RBAC & MFA
- Encryption at rest & in transit

### 6. Continuous Monitoring & Review
Established:
- Quarterly risk reassessments
- Annual HIPAA compliance audits
- Ongoing patch & vulnerability management
- Updated IRP (Incident Response Plan)

## 📊 Outcomes / Results
- Reduced identified cybersecurity risks through targeted NIST-aligned controls.
- Implemented RBAC + MFA, decreasing unauthorized access risk.
- Deployed IDS + SIEM logging, improving threat detection visibility.
- Eliminated USB-related malware vectors by enforcing endpoint protection + device control.
- Hardened Windows systems, reducing vulnerability exposure scores.
- Achieved HIPAA-aligned handling of PHI/PII through formal data classification and access control.
- Built an IRP, enabling simulated recovery within 30–60 minutes after malware events.

## 📁 Repository Structure
- [Data-classification](DataClassification)
- [Risk-assessment](risk-assessment/)
- [Incident-response](incident-response/)
- [System-hardening](system-hardening/)
- [Docs](docs/)
- [README.md](README.md)

