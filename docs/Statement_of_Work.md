# Statement of Work

**Security Posture Assessment Engagement**

**Prepared for:** FinSecure
**Prepared by:**  Safempire Consulting
**Date:** June 28, 2026
**SOW Reference Number:** SEC-FS-2026-001



## 1\. Introduction and Overview

This Statement of Work ("SOW") is entered into between Safempire Consulting ("Consultant") and FinSecure ("Client"), a mid-sized financial institution with approximately 500 employees and an expanding online presence.

This engagement follows a recent phishing incident in which a limited number of employee email accounts were compromised. No customer data was confirmed to be affected, but the incident prompted Ms. Dora Chris, CEO of FinSecure, to commission an independent review of the institution's overall security posture.

The purpose of this SOW is to define the scope, deliverables, timeline, assumptions, responsibilities, and pricing for a comprehensive security assessment of FinSecure's environment. The assessment will evaluate the institution's ability to withstand common threats facing financial institutions, including phishing, ransomware, and insider threats, and will assess alignment with the Payment Card Industry Data Security Standard (PCI DSS) and the Gramm-Leach-Bliley Act (GLBA) Safeguards Rule.

This engagement is designed with two priorities the CEO raised directly: a clear, itemized cost structure suited to a limited budget, and minimal disruption to day-to-day banking operations.



## 2\. Scope of Work

### 2.1 In-Scope Systems

The following systems, networks, and applications are included in this assessment:

* **Internal corporate network**, including workstations, servers, internal applications, and Active Directory infrastructure (assessed from an internal vantage point, network segment to be confirmed during scoping)
* **External-facing web applications**, including the Client's public website and online/mobile banking portal
* **Email and collaboration infrastructure**, specifically the platform involved in the recent phishing incident (e.g., Microsoft 365 or equivalent), limited to configuration, authentication controls, and anti-phishing protections
* **Cloud infrastructure**, limited to the production environment(s) hosting customer-facing services (provider to be confirmed during the kickoff meeting)
* **Identity and access management controls**, including password policy, multi-factor authentication (MFA) coverage, and privileged account management
* **Physical and procedural controls relevant to social engineering**, limited to a sample population of employees as described in Section 2.2

A finalized list of in-scope IP ranges, domains, and application URLs will be documented in a Rules of Engagement (RoE) document, signed by both parties prior to the start of any technical testing.

### 2.2 Assessment Activities

Safempire Consulting will perform the following activities:

1. **External Penetration Testing** — A controlled attempt to identify and exploit vulnerabilities in internet-facing systems, including the public website and online banking portal, conducted outside business-critical processing windows to minimize disruption.
2. **Internal Vulnerability Assessment** — A non-disruptive, credentialed and uncredentialed scan of the internal network to identify known vulnerabilities, missing patches, and misconfigurations. This activity does not include active exploitation of internal systems.
3. **Phishing and Social Engineering Simulation** — A simulated phishing campaign targeting a representative, mutually agreed sample of employees (not to exceed 15% of staff), designed to measure susceptibility and the effectiveness of existing email security controls, directly informed by the recent incident.
4. **Cloud Configuration Review** — A review of identity and access controls, storage permissions, logging, and network configuration within the in-scope cloud environment against CIS Benchmarks and relevant best practices.
5. **Insider Threat and Access Control Review** — An assessment of privileged access management, least-privilege enforcement, and account lifecycle practices (onboarding, offboarding, and access recertification).
6. **PCI DSS and GLBA Gap Assessment** — A documentation and control review (not a formal audit or certification) to identify gaps relative to applicable PCI DSS requirements and the GLBA Safeguards Rule, focused on the systems in scope.
7. **Policy and Procedure Review** — A review of existing information security policies, incident response procedures, and security awareness training materials against industry best practices, including direct relevance to the recent phishing incident.

All testing activities will be scheduled in coordination with the Client's designated point of contact and will avoid known peak processing periods (e.g., end-of-month settlement) unless otherwise agreed in writing.

### 2.3 Out-of-Scope Activities

The following are explicitly excluded from this engagement:

* Remediation of identified vulnerabilities or implementation of recommended controls
* Formal PCI DSS Qualified Security Assessor (QSA) certification or attestation of compliance
* Incident response services related to the recent phishing incident or any other active security event
* Denial-of-service (DoS/DDoS) testing of any kind
* Physical penetration testing of facilities (e.g., attempts to gain unauthorized physical entry)
* Assessment of third-party vendors, partners, or systems not directly controlled by the Client
* Source code review of proprietary applications, unless added by a signed change order
* Testing of production payment processing systems during active transaction windows
* Any system, network segment, or application not explicitly listed in Section 2.1 or the accompanying Rules of Engagement document

Any work outside this defined scope will require a written change order, signed by both parties, with an associated adjustment to timeline and cost.



## 3\. Deliverables

1. **Security Assessment Report** — A comprehensive written report detailing all findings, risk ratings (using a Critical/High/Medium/Low scale, consistent with a likelihood-and-impact matrix), supporting evidence, and prioritized, actionable recommendations mapped to the in-scope assessment activities.
2. **Executive Summary Presentation** — A concise, business-focused presentation (approximately 30 minutes) for Ms. Reed and other C-suite stakeholders, summarizing key findings, overall risk posture, and recommended next steps in non-technical language, with attention to regulatory exposure (PCI DSS, GLBA).
3. **Technical Debriefing** — A working session (approximately 2 hours) with the Client's IT and security personnel to walk through detailed findings, supporting technical evidence, and remediation guidance.
4. **PCI DSS / GLBA Gap Summary** — A standalone summary mapping identified gaps to relevant PCI DSS requirements and GLBA Safeguards Rule provisions, to support the Client's internal compliance planning.
5. **Raw Scan Data and Evidence Package** — Supporting artifacts (scan outputs, screenshots, phishing simulation metrics) provided as a supplementary appendix for the Client's internal records.

All written deliverables will be provided in PDF format. Editable source files (e.g., presentation slides) will be provided upon request.



## 4\. Timeline

This engagement is structured in three phases over an estimated **6 to 8 week period**, beginning upon execution of this SOW and receipt of the signed Rules of Engagement.

|Phase|Activities|Estimated Duration|
|-|-|-|
|**Phase 1: Planning and Scoping**|Kickoff meeting, finalization of Rules of Engagement, collection of network diagrams and access credentials, scheduling of testing windows|Week 1|
|**Phase 2: Assessment**|External and internal testing, phishing simulation, cloud configuration review, policy and access control review, PCI DSS/GLBA gap analysis|Weeks 2–5|
|**Phase 3: Reporting and Debriefing**|Findings consolidation, draft report review, delivery of final Security Assessment Report, Executive Summary Presentation, and Technical Debriefing|Weeks 6–8|

Key milestones, including the phishing simulation launch date and the final presentation date, will be confirmed in writing during Phase 1 and documented in a shared project schedule. Any delay caused by the Client's failure to provide timely access, documentation, or personnel availability may extend this timeline proportionally and will be communicated promptly.



## 5\. Assumptions

This SOW, and the associated timeline and pricing, are based on the following assumptions:

1. The in-scope environment does not exceed approximately 500 employees, 3 internal network segments, and 2 production cloud environments. Environments materially larger than this will require a scope and pricing adjustment.
2. The Client will designate a single primary point of contact with the authority to grant access approvals and schedule resources.
3. All testing will be conducted during the Client's standard business hours unless otherwise requested, with after-hours testing available at the rates specified in Section 7.
4. The Client holds, or will obtain prior to testing, all necessary authorization to permit security testing of in-scope systems, including any systems hosted by third-party providers (e.g., cloud or SaaS vendors), where required by those providers' acceptable use policies.
5. No major infrastructure changes (e.g., network migrations, M\&A activity, core banking platform changes) will occur during the engagement that would materially alter the in-scope environment.
6. This assessment is a point-in-time evaluation and does not constitute a guarantee against future security incidents.
7. English is the primary language for all deliverables and communications.



## 6\. Client Responsibilities

To support a timely, accurate, and minimally disruptive engagement, the Client agrees to:

1. Designate a primary point of contact available throughout the engagement to coordinate access, scheduling, and approvals.
2. Provide timely access to relevant personnel for interviews, including IT, security, and compliance staff.
3. Provide accurate and current network diagrams, asset inventories, and system documentation prior to the start of Phase 2.
4. Grant necessary access credentials (e.g., scoped credentials for credentialed vulnerability scanning) at least 3 business days before scheduled testing.
5. Notify internal teams (e.g., SOC, IT help desk) of the testing windows to prevent unnecessary incident escalations, while maintaining appropriate confidentiality of specific testing details to preserve assessment integrity.
6. Provide existing security policies, procedures, and prior audit or assessment reports relevant to the scope of this engagement.
7. Review and provide feedback on the draft Security Assessment Report within 5 business days of receipt, to support the agreed delivery timeline for the final report.
8. Promptly disclose any changes to the in-scope environment that occur during the engagement.

Delays attributable to the Client's inability to meet these responsibilities may result in adjustments to the project timeline.



## 7\. Pricing and Payment Terms

### 7.1 Professional Fees

|Phase / Activity|Estimated Hours|Rate|Subtotal|
|-|-|-|-|
|Phase 1: Planning and Scoping|16|$185/hr|$2,960|
|External Penetration Testing|40|$195/hr|$7,800|
|Internal Vulnerability Assessment|24|$175/hr|$4,200|
|Phishing and Social Engineering Simulation|20|$175/hr|$3,500|
|Cloud Configuration Review|20|$190/hr|$3,800|
|Insider Threat and Access Control Review|16|$175/hr|$2,800|
|PCI DSS / GLBA Gap Assessment|24|$185/hr|$4,440|
|Policy and Procedure Review|12|$165/hr|$1,980|
|Phase 3: Reporting, Presentation, and Debriefing|28|$175/hr|$4,900|
|**Total Professional Fees**|**200 hrs**||**$36,380**|

### 7.2 Travel and Expenses

This engagement is anticipated to be performed primarily on a remote basis. If on-site work is requested by the Client (e.g., for in-person interviews or the Executive Summary Presentation), reasonable travel and lodging expenses will be billed at cost, with prior written approval from the Client. No travel expenses are included in the total above.

### 7.3 Optional Add-On Services

The following are not included in the base price but are available by signed change order:

* After-hours or weekend testing windows: additional 15% surcharge on associated hours
* Extended phishing simulation covering 100% of staff: $2,200
* 30-day post-engagement advisory retainer (email/call support on findings): $3,000

### 7.4 Payment Schedule

* **25% deposit** ($9,095) due upon signature of this SOW, prior to the start of Phase 1
* **50% progress payment** ($18,190) due upon completion of Phase 2 testing activities
* **25% final payment** ($9,095) due upon delivery of the final Security Assessment Report

Payment terms are net 15 days from invoice date. Late payments may be subject to a 1.5% monthly late fee. All fees are quoted in USD and are exclusive of any applicable taxes.



## 8\. Terms and Conditions

### 8.1 Confidentiality

Both parties agree to treat all information exchanged during this engagement, including findings, vulnerabilities, credentials, and business information, as strictly confidential. This obligation survives the completion or termination of this engagement. Where a Master Services Agreement (MSA) or Non-Disclosure Agreement (NDA) is already in place between the parties, the confidentiality terms of that agreement shall govern; otherwise, the parties agree to execute a mutual NDA prior to the commencement of Phase 1.

### 8.2 Authorization to Test

The Client confirms it has the legal authority to authorize the testing activities described in Section 2 against the in-scope systems. The Client will provide a signed Rules of Engagement document, which serves as written authorization for the Consultant's testing activities and provides a defense against claims of unauthorized access, prior to any technical testing.

### 8.3 Limitation of Liability

The Consultant will perform all services using reasonable care consistent with prevailing industry standards. Given the dynamic nature of security testing, the Consultant cannot guarantee the discovery of all vulnerabilities, nor can it guarantee that the Client will not experience a security incident following the engagement. The Consultant's total liability under this SOW shall not exceed the total fees paid by the Client under this engagement, except in cases of gross negligence or willful misconduct.

### 8.4 Data Handling

Any sensitive data accessed during testing (including but not limited to credentials, personally identifiable information, or cardholder data) will be handled in accordance with applicable regulatory requirements (PCI DSS, GLBA) and will be securely destroyed by the Consultant within 30 days of the engagement's conclusion, unless otherwise required for legal or compliance purposes.

### 8.5 Termination

Either party may terminate this engagement with 14 days' written notice. In the event of termination, the Client will be invoiced for all work performed and expenses incurred up to the termination date, on a prorated basis.

### 8.6 Governing Document

This SOW operates under the terms of the Master Services Agreement (MSA) between FinSecure and Safempire Consulting, where one exists. In the absence of an executed MSA, the terms outlined in this SOW shall govern the engagement in full.



## 9\. Acceptance

By signing below, both parties agree to the terms outlined in this Statement of Work.

**For FinSecure:**

Name: Dora Chris, Chief Executive Officer
Signature: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_
Date: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

**For Safempire Consulting:**

Name: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_
Signature: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_
Date: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_


