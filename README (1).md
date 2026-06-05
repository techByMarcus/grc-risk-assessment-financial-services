# Pinnacle Lending Solutions — GRC Risk Assessment Project

**Author:** Marcus Albright | GRC Risk Analyst  
**Completed:** June 2026  
**Frameworks:** NIST Cybersecurity Framework (CSF) 2.0 · ISO/IEC 27001:2022 · GLBA Safeguards Rule · CFPB

---

## Project Overview

This project is a full information security GRC assessment for **Pinnacle Lending Solutions**, a fictional residential mortgage lender. It was built to demonstrate applied GRC skills in a domain I know deeply — regulated financial services, mortgage lending, and consumer data protection.

I spent 20+ years in regulated mortgage environments with direct exposure to GLBA, CFPB, RESPA, and TILA compliance requirements, audit-ready documentation, third-party vendor oversight, and protection of sensitive borrower PII. This project translates that operational experience into a structured GRC work product.

Everything in this project reflects real risks, real regulatory obligations, and real remediation approaches — grounded in the mortgage lending environment, not generic IT security templates.

---

## What's Inside

| File | Description |
|---|---|
| `Risk_Register.xlsx` | 15 risks scored by likelihood × impact, mapped to NIST CSF and ISO 27001 controls. Includes existing controls, gaps, remediation, owner, and target dates. |
| `GLBA_Safeguards_Checklist.docx` | Current-state compliance assessment against all FTC GLBA Safeguards Rule requirements. Identifies gaps and prioritizes remediation. |
| `Controls_Gap_Analysis.docx` | 20 control areas assessed for current vs. target maturity (0–4 scale). Includes 3-phase implementation roadmap. |
| `Vendor_Risk_Assessment_Template.docx` | Third-party vendor security assessment form with scoring rubric and approval decision framework. |
| `Vendor_Assessment_Sample.docx` | Completed sample vendor assessment for a fictional title company — demonstrates how the template is used in practice. |
| `Executive_Summary.pdf` | One-page leadership summary of key findings, risk priorities, and recommendations. |

---

## Why Mortgage Lending?

Mortgage lenders are a high-value target for threat actors and a high-scrutiny environment for regulators — for good reason. Every loan file contains the most sensitive combination of PII imaginable: Social Security numbers, full financial histories, bank account details, employment records, and property information.

The regulatory framework is layered and unforgiving:
- **GLBA Safeguards Rule** requires a written information security program, annual risk assessments, and vendor oversight
- **CFPB** expects rigorous controls around consumer data handling and breach response
- **RESPA / TILA** create audit-ready documentation obligations across the loan lifecycle

Most entry-level GRC candidates learn these frameworks from textbooks. I learned them from inside the regulated environment — originating loans, managing compliance, overseeing third-party relationships, and maintaining audit-ready files under examination pressure. This project applies that experience to a formal GRC assessment structure.

---

## Frameworks Applied

### NIST Cybersecurity Framework (CSF) 2.0
Used as the primary organizing structure. Each risk in the register is mapped to a NIST CSF function (Govern, Identify, Protect, Detect, Respond, Recover) and specific category.

### ISO/IEC 27001:2022
Annex A controls mapped alongside NIST CSF for each risk — providing dual-framework coverage relevant to organizations pursuing ISO certification or working with internationally-focused partners.

### GLBA Safeguards Rule (FTC, 2023 Update)
All nine core elements of the Safeguards Rule are assessed in the compliance checklist — from the qualified individual requirement through incident response and vendor oversight obligations.

### CFPB Consumer Data Standards
Consumer data handling obligations mapped to risk register and gap analysis, reflecting direct regulatory exposure from residential mortgage origination.

---

## Key Findings

- **1 Critical risk** (Score 20/25): Unauthorized PII access in LOS/CRM — no MFA, no documented access reviews
- **8 High risks**: No written IR plan, no WISP, no formal vendor assessments, no offboarding SLA, ransomware/BCP exposure
- **6 Medium risks**: SIEM gap, network segmentation, phishing training, password management
- **Top remediation priorities**: MFA enforcement, WISP documentation, IR plan, SIEM deployment, vendor risk program

---

## Skills Demonstrated

- Risk identification, scoring, and prioritization (likelihood × impact)
- NIST CSF and ISO 27001 control mapping
- Regulatory compliance assessment (GLBA, CFPB)
- Controls gap analysis and maturity modeling
- Third-party / vendor risk management
- Remediation roadmap development and phased implementation planning
- Executive-level documentation and communication
- Audit-ready record keeping and evidence collection

---

## About the Author

I am transitioning into GRC and information security from a 20+ year career in regulated financial services — mortgage origination, branch management, client operations, and compliance. I bring direct experience with the regulatory frameworks (GLBA, CFPB, RESPA, TILA) and business processes (loan origination, vendor relationships, third-party data sharing) that GRC teams in financial services work to protect every day.

**Certifications:** EC-Council NDE · EC-Council EHE · LetsDefend SOC Analyst Path · LetsDefend MITRE ATT&CK · AWS Cloud Essentials · IBM Technical Support · CompTIA Security+ (in progress) · ISC2 CC (in progress)  
**Training:** QuickStart Cybersecurity Bootcamp — University of Tennessee, Knoxville (May 2025)  
**Portfolio:** [techbymarcus.github.io/aboutMarcus](https://techbymarcus.github.io/aboutMarcus)  
**LinkedIn:** [linkedin.com/in/marcus-a-69ab2989](https://linkedin.com/in/marcus-a-69ab2989)

---

*This project uses a fictional company (Pinnacle Lending Solutions) to demonstrate applied GRC methodology. All risks, controls, and findings are realistic representations of information security challenges common to residential mortgage lending operations.*
