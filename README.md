<div align="center">

# 🛡️ Threat Shield

### *Advanced Threat Modeling & Security Intelligence Platform*

<br />

   <img width="200" height="200" alt="Threat Shield Logo" src="./Static Assets/Blue-Logo.png" />
   <br />
   <em>Threat Shield, a part of <a href="https://zeroshield.ai">ZeroShield</a></em>

   
</div>
  <div align="center">
    <a href="https://opensource.org/licenses/MIT">
      <img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="License: MIT" />
    </a>
    <a href="https://www.python.org/downloads/">
      <img src="https://img.shields.io/badge/python-3.8+-blue.svg" alt="Python" />
    </a>
    <a href="https://nodejs.org/">
      <img src="https://img.shields.io/badge/node.js-18+-green.svg" alt="Node.js" />
    </a>
    <a href="https://nextjs.org/">
      <img src="https://img.shields.io/badge/Next.js-14-black.svg" alt="Next.js" />
    </a>
    <a href="https://www.typescriptlang.org/">
      <img src="https://img.shields.io/badge/TypeScript-5.0-blue.svg" alt="TypeScript" />
    </a>
    <a href="https://openai.com/">
      <img src="https://img.shields.io/badge/OpenAI-GPT--4-purple.svg" alt="OpenAI" />
    </a>
    <a href="https://fastapi.tiangolo.com/">
      <img src="https://img.shields.io/badge/FastAPI-0.110+-green.svg" alt="FastAPI" />
    </a>
    <a href="https://tailwindcss.com/">
      <img src="https://img.shields.io/badge/TailwindCSS-3.3+-blue.svg" alt="TailwindCSS" />
    </a>
    <a href="https://lucide.dev/">
      <img src="https://img.shields.io/badge/Lucide-React-orange.svg" alt="Lucide React" />
    </a>
    <a href="https://react.dev/">
      <img src="https://img.shields.io/badge/React-18+-blue.svg" alt="React" />
    </a>
  </div>


## Table of Contents

- [About](#about)
- [Core Mission](#core-mission)
- [Key Capabilities](#key-capabilities)
- [Security Frameworks & Methodologies](#security-frameworks--methodologies)
- [Target Users](#target-users)
- [Feature Overview](#feature-overview)
  - [1. Threat Modeling of Normal Systems](#1-threat-modeling-of-normal-systems)
  - [2. LLM Threat Modeling](#2-llm-threat-modeling)
  - [3. MCP Server Vulnerability Scanning](#3-mcp-server-vulnerability-scanning)
- [Compliance Mapping](#compliance-mapping)
- [Example Workflows & User Benefits](#example-workflows--user-benefits)
- [Use Cases](#use-cases)
- [Tech Stack](#tech-stack)
- [Trial License & Security](#trial-license--security)
- [Case Studies](#case-studies)
- [Support](#support)
- [Get Involved](#get-involved)

---

## About Threat Shield
**Threat Shield** is an advanced threat modelling platform within the **[ZeroShield](https://zeroshield.ai)** platform, designed to give organizations deep, actionable insight into risks across classic applications, codebases, and cutting-edge GenAI/LLM integrations.Threat Shield unifies real-time threat modeling, LLM threat modeling, and MCP codebase vulnerability scanning for a complete, **compliance**-ready view of your security posture.


---

## Core Mission

Empower teams to rapidly identify, understand, and remediate security risks—across all technologies—by automating threat analysis, vulnerability detection, and compliance mapping. Threat Shield bridges the gap between security, development, and compliance, enabling secure digital innovation.


---

## Key Capabilities

- Automated Threat Modeling for Classic and Cloud-Native Systems
- Advanced LLM Threat Modeling (comprehensive security analysis)
- MCP Server-Based Vulnerability Scanning & **Compliance** (LLM analysis)
- Real-Time **Compliance** & **OWASP** Top 10 for API Security Mapping (ISO, PCI, SOC2, NIST, GDPR)
- Unified Risk Analytics & Visualizations

---

## Security Frameworks & Methodologies

Threat Shield employs industry-standard security frameworks to ensure comprehensive threat analysis:

### **STRIDE** Threat Classification
**STRIDE** is a threat modeling framework that categorizes security threats into six fundamental types:

- **S** - **Spoofing**: Impersonating someone or something else
- **T** - **Tampering**: Modifying data or code in unauthorized ways
- **R** - **Repudiation**: Denying having performed an action
- **I** - **Information Disclosure**: Exposing information to unauthorized parties
- **D** - **Denial of Service**: Disrupting or degrading service availability
- **E** - **Elevation of Privilege**: Gaining unauthorized elevated access

### **DREAD** Risk Assessment
**DREAD** is a risk assessment model that evaluates threats across five dimensions:

- **D** - **Damage**: Potential impact if the threat is exploited
- **R** - **Reproducibility**: How easily the threat can be reproduced
- **E** - **Exploitability**: How difficult it is to exploit the threat
- **A** - **Affected Users**: Number of users potentially impacted
- **D** - **Discoverability**: How easily the threat can be discovered

Each threat receives a **DREAD** score (1-10 scale) across all five dimensions, providing a quantitative risk assessment for prioritization and remediation planning.

---

## Target Users

### **Security Engineers**
*Automate threat modeling, vulnerability scanning, and **compliance**.*

**Real World Scenario:** Sarah, a Senior Security Engineer at a fintech startup, is tasked with conducting a comprehensive security assessment of their new payment processing system before the PCI audit next month. Using Threat Shield, she uploads the system architecture diagrams and connects the GitHub repository. Within hours, she receives a detailed threat model identifying 23 **STRIDE** threats, including critical API key exposure and authentication bypass vulnerabilities. The **DREAD** heatmap helps her prioritize the 7 high-risk issues that could fail PCI **compliance** controls. She exports an audit-ready report showing all findings mapped to PCI DSS requirements, saving weeks of manual analysis and ensuring the system passes the audit on the first try.

### **Developers & DevOps**
*Integrate risk analysis into CI/CD and shift security left.*

**Real World Scenario:** Mike, a DevOps Lead at a SaaS company, needs to implement security scanning in their CI/CD pipeline for 15 microservices. He integrates Threat Shield into their GitHub Actions workflow, enabling automatic threat modeling on every pull request. When a developer pushes code with a hardcoded database password, Threat Shield immediately flags it as a **STRIDE** Information Disclosure threat with a high **DREAD** score. The system blocks the merge, provides the developer with an actionable fix, and creates a **compliance** tracking ticket. This prevents 3 potential security incidents in the first month, reducing their security debt by 40% and accelerating their SOC2 certification timeline.

### **AI/ML & Product Teams**
*Secure and validate LLM/GenAI features with real threat modeling security probes.*

**Real World Scenario:** Dr. Lisa Chen, an AI Product Manager at a healthcare technology company, is launching an AI-powered patient consultation chatbot that handles sensitive medical data. Before going live, she runs Threat Shield's LLM threat modeling assessment, which executes 40+ threat modeling security probes. The results reveal high vulnerability to prompt injection attacks that could expose patient data, triggering failed HIPAA **compliance** controls. Using the detailed remediation suggestions, her team implements input sanitization and context filtering. After re-running the assessment, the risk level drops to "Low" and all **compliance** checks pass, allowing the chatbot to launch securely and handle thousands of patient interactions without security incidents.

### **Compliance & Audit Teams**
*Map vulnerabilities to **compliance** frameworks and track remediation.*

**Real World Scenario:** Robert, a **Compliance** Manager at a financial services company, needs to prepare for an annual ISO 27001 audit covering 8 different applications. Instead of manually reviewing hundreds of security controls, he uses Threat Shield to generate comprehensive **compliance** reports for each system. The platform automatically maps all identified vulnerabilities to ISO 27001 controls, showing that 15 out of 114 controls need attention. He creates remediation tickets with clear priorities based on **DREAD** scores and tracks progress through the dashboard. The audit-ready reports demonstrate 95% control coverage, impressing the external auditors and resulting in a clean audit report with only minor observations.

### **Cloud & Solution Architects**
*Design secure architectures with instant, actionable feedback.*

**Real World Scenario:** Elena, a Cloud Solution Architect at a global e-commerce company, is designing a new multi-cloud infrastructure for handling Black Friday traffic spikes. She uses Threat Shield to model the architecture with 12 microservices across AWS and Azure, including payment processing, user authentication, and inventory management. The threat model identifies 31 potential attack vectors, with the **DREAD** heatmap highlighting that 5 threats could cause service outages affecting millions of users. She redesigns the architecture to eliminate single points of failure, adds proper encryption at rest and in transit, and implements zero-trust networking. The final architecture passes all **OWASP** Top 10 for API Security checks and **compliance** requirements, ensuring a secure and scalable Black Friday deployment that handles 10x traffic without security incidents.

---

## Feature Overview

### 1. Threat Modeling of Normal Systems

#### Architecture Overview

<img width="800" height="600" alt="Threat Modeling of Normal Systems Architecture" src="./Static Assets/Threat-modelling-Normal-systems.png" />

**Description:** This diagram illustrates the comprehensive threat modeling architecture for normal systems, showing how Threat Shield analyzes system components, data flows, trust boundaries, and generates **STRIDE**-based threat assessments with **compliance** mapping.

#### Demo Video

https://github.com/user-attachments/assets/10ec45b0-a35f-45a7-a03f-c11f754e11b8

#### What Users See & How It Works

- **Project List Screen:**  
  - Table: [Name, Repo URL, Total Threats, Unresolved Threats, Total Non-Conformant, **OWASP** Found, Created At]
  - “Create Project” button to launch new assessment
- **Project Creation Dialog:**  
  - Tabs: Threat modeling / LLM Threat Modeling / MCP Scanning  
  - Fields: System Name, Architecture Type, Description, Internet Facing (Y/N), Upload Architecture/DFD/UML, GitHub Repo connect, Auth Type, Data Sensitivity, Dependencies
- **Project Dashboard:**  
  - **Summary Cards:**  
      - Total **STRIDE** Threats Identified  
      - Threats Unresolved  
      - Threats Resolved  
      - Threat Score (overall risk indicator)
  - **DREAD Heatmap:** Visualizes risk by **Damage**, **Reproducibility**, **Exploitability**, **Affected Users**, **Discoverability** (the five components of DREAD risk assessment).
  - **Failed Controls Card:** Number of failed **compliance** controls.
  - **OWASP** Top 10 for API Security Tracker: Visual (circle graph) and list of which categories are triggered.
  - **Attack Trees:** Visual graph showing attack paths and relationships.
  - **Threat Details Table:**  
      - Columns: Threat, **DREAD** Score, Severity, **Compliance**, Location, **STRIDE** Category, Status, Suggested Fixes
      - Search & filter options
  - **Generate Report Button:** Exportable audit-ready report.

### Threat Modeling Project Dashboard

<img width="800" height="600" alt="Screenshot 2025-09-29 173615" src="https://github.com/user-attachments/assets/a1e67280-139d-4392-a8db-52b77ae312ae" />


**Description:** The main dashboard for a **Threat Modeling** project, showcasing the system's overall risk score (6.5), key metrics like **Total STRIDE Threats** (6 identified, 6 unresolved), and the high-level **DREAD Heat Map** for rapid risk prioritization.



#### What/Why of Each Visualization
- **Summary Cards:** Instantly see the scale and urgency of risk in the system.
- **DREAD Heatmap:** Pinpoints highest-impact threats for prioritization using the five DREAD risk factors.
- **Failed Controls:** Shows direct **compliance** gaps (e.g., SOC2, PCI).
- **OWASP** Tracker: Maps findings to industry standards for external reporting.
- **Attack Trees:** Helps visualize possible attack paths and lateral movement.
- **Threat Table:** Enables fast triage, assignment, and remediation tracking.


### Threat Modeling Attack Tree and **OWASP** Tracker

<img width="800" height="600" alt="Screenshot 2025-09-29 173641" src="https://github.com/user-attachments/assets/8c002fc9-6bcb-44cd-b4f9-d83b1006568f" />


**Description:** An in-depth view of the **Threat Modeling** dashboard, displaying the **PASTA Attack Tree** visualization to map out potential attack paths and lateral movement. It also highlights the **OWASP** Top 10 for API Security Tracker, showing 3 of 10 categories triggered, including **Identification and Authentication Failures** (A07) and **Security Misconfiguration** (A05).




### Threat Modeling Finding Details

<img width="800" height="600" alt="Screenshot 2025-09-29 173717" src="https://github.com/user-attachments/assets/5676290d-9dcd-4cb3-835f-d0aced641e6f" />


**Description:** An expanded view of a Threat Modeling finding, detailing an **API Key Exposure** threat. It shows the impact across five major **compliance** frameworks (**ISO, NIST, PCI DSS, GDPR, SOC 2**), the associated **OWASP** Broken Access Control (A01:2021) vulnerability, and a comprehensive, actionable **Suggested Fix** for secure key management.



### Threat Modeling Finding Scoring and **Compliance**

<img width="800" height="600" alt="Screenshot 2025-09-29 173703" src="https://github.com/user-attachments/assets/a84bcd7b-2472-4962-9474-1b548e0ff671" />


**Description:** The top portion of the Threat Modeling finding details, clearly showing the threat's **High Severity**, the associated **STRIDE Categories** (S-Spoofing, I-Information Disclosure), **DREAD Scores** for risk calculation, and a comprehensive list of affected **Compliance** Controls across ISO, NIST, PCI DSS, GDPR, and SOC 2.failed **compliance** controls like **Malware Detection and Prevention**, and the specific **LLM-generated remediation fix** to update detection rules.




#### Deep-Dive: How It Works
- Upload system diagrams, code, and metadata.
- The engine analyzes flows, trust boundaries, and identifies threats using **STRIDE** (Spoofing, Tampering, Repudiation, Information Disclosure, Denial of Service, Elevation of Privilege), **DREAD** (Damage, Reproducibility, Exploitability, Affected Users, Discoverability), and **OWASP** logic.
- Each threat is auto-mapped to **compliance** controls.
- Dashboard and report update in real-time as threats are resolved.

#### Hypothetical User Scenario

> **Alice**, a Security Engineer, is onboarding a new payments platform. She uploads the system's DFDs and architecture, connects the GitHub repo, and sets data sensitivity. Threat Shield instantly generates a threat model showing 23 **STRIDE** threats, highlighting 7 unresolved high-risk issues and 2 failed PCI **compliance** controls. Using the **DREAD** heatmap and attack tree, Alice quickly triages which risks to escalate to DevOps for urgent fixes, and exports a report to satisfy the next audit.



### 2. LLM Threat Modeling

#### Architecture Overview

<img width="800" height="600" alt="LLM Threat Modeling Architecture" src="./Static Assets/Threat-modelling-LLM.png" />

**Description:** This diagram shows the LLM threat modeling architecture, demonstrating how Threat Shield performs comprehensive security analysis on Large Language Models, including threat modeling security probe execution, vulnerability assessment, and **compliance** mapping for AI systems.

#### Demo Video

https://github.com/user-attachments/assets/8dd9b7b6-4781-4b37-8a62-788bc274b79d

#### What Users See & How It Works

- **LLM Threat Modeling Projects:**  
  - Table: [Name, Total Tests, Total Hits, Hit Rate, Risk Level, Created At]
  - "Create Project" button to launch new threat modeling assessment
- **LLM Threat Modeling Project Dashboard:**  
  - **Summary Cards:**  
      - Total Tests  
      - Total Hits  
      - Hit Rate  
      - Risk Level (visual/highlight)
  - **Failed Controls:** Number of non-conformant controls triggered by LLM findings.
  - **OWASP** Vulnerabilities Card: Number and list of **OWASP** Top 10 for API Security categories found.
  - **Threat Graph:** Distribution of exploit hits across threat modeling security probes.
  - **Threat Modeling Security Probe Details Table:**  
      - Columns: Probe Name, Passed, Total, Hit Rate, Detector, Suggested Fixes
      - "View Suggestions" for every threat modeling security probe

#### What/Why of Each Visualization
- **Summary Cards:** High-level risk/weakness snapshot of LLM.
- **Failed Controls:** Links AI security to **compliance** posture.
- **OWASP** Card: Shows if LLM flaws could impact web/app security standards.
- **Threat Modeling Security Probe Table:** Full transparency—see exactly which prompts/threat modeling security probes succeeded, failed, and why.


#### Comprehensive LLM Security Analysis

- **Threat modeling** analyzes LLM systems for:  
  - ANSI escapes, attack generation, audio attacks, antivirus/spam bypass, data leakage, prompt injection, roleplay/jailbreaks, SQLi, XSS, hallucinated package names, adversarial suffixes, emotional manipulation, and more.
- **LLM Exposure Analysis:**  
  - Beyond threat modeling security probe results, Threat Shield analyzes the LLM's exposure and risk posture, surfaces all successful bypasses, and maps to **OWASP** Top 10 for API Security and failed **compliance** controls.

### LLM Threat Modeling Security Probe Finding Details

<img width="800" height="600" alt="Screenshot 2025-09-29 173750" src="https://github.com/user-attachments/assets/cd7f2baf-b9ee-48fa-8492-1d30119877ca" />


**Description:** A deep-dive into an LLM security finding, showing the results of a **malware evasion** threat analysis. The panel displays the **Medium Risk Level**, a **20.8% hit rate**, failed **compliance** controls like **Malware Detection and Prevention**, and the specific **LLM-generated remediation fix** to update detection rules.



#### Deep-Dive: LLM Threat Modeling System

Threat Shield performs comprehensive threat modeling for LLM systems, analyzing dozens of security categories:

| Threat Category        | What It Analyzes                                                          | Why It Matters                        |
|-----------------------|--------------------------------------------------------------------------|---------------------------------------|
| ANSI Escape           | Model exposes terminal codes                                              | Downstream system compromise          |
| Attack Generation     | Can model be tricked into toxic/illegal output                            | Content moderation, brand risk        |
| Audio                 | Multimodal attacks bypassing text safety                                 | Jailbreaks on non-text input          |
| AV/Spam Scanning      | Will model output malware/spam test strings                              | Bypassing security scanning           |
| Continuation/Slurs    | Model completes offensive/inappropriate words                            | Social/ethical risk                   |
| Data Leakage          | Model repeats training data                                               | Confidentiality breach                |
| Doctor/Roleplay       | Policy puppetry to bypass safety                                         | Regulatory/safety risk                |
| Encoding/Jailbreak    | Can model decode/obfuscate harmful payloads                              | Filter bypass, prompt injection       |
| Exploitation (SQLi)   | Model can output exploitable code                                        | Direct app/system compromise          |
| Fileformats           | Model exposes details about underlying files                             | Environment leakage                   |
| Glitch Tokens         | Model misbehaves on edge tokens                                          | Model stability, DoS                  |
| Goodside/Malwaregen   | Known adversarial/prompt injection patterns                              | Real-world exploit research           |
| Grandma/Emotional     | Will model yield to emotional manipulation                               | Social engineering risk               |
| Hallucination         | Model invents fake package/library names                                 | Supply chain attack                   |
| Prompt Injection      | Model can be hijacked to output specific strings                         | LLM-powered app hijacking             |
| XSS/Visual Jailbreak  | Model outputs code/image links for data exfiltration                     | Web/visual AI security                |
| Latent Injection      | Model attacked through hidden instructions in data                        | RAG, document QA system risk          |

> **Further Analysis:**  
> Beyond these threat categories, Threat Shield analyzes all threat modeling results for exposure patterns—automatically scoring LLM risk, mapping incidents to **OWASP** Top 10 for API Security and **compliance** controls, and surfacing which prompt/attack types are most dangerous in your use case.

#### How It Benefits Users

- **Real-world threat modeling** using comprehensive security analysis techniques.
- **Immediate understanding of LLM weaknesses and exposure.**
- **Human-readable explanations and remediation steps** for every finding.
- **Continuous assessment** as models/prompts evolve.
- **Supports secure, compliant AI adoption** in any environment.

#### Hypothetical User Scenario

> **Raj**, an AI/ML Product Lead, is launching a GenAI-powered helpdesk. He runs a Threat Shield LLM threat modeling assessment, which analyzes 40+ security threat vectors. The dashboard reveals high-risk prompt injection and roleplay vulnerabilities, and a failed GDPR control. Raj reviews the suggested fixes, patches the prompt template, and re-runs the assessment—dropping risk level to "Low" and passing all **compliance** checks before go-live.




### 3. MCP Server Vulnerability Scanning

#### Architecture Overview

<img width="800" height="600" alt="MCP Server Vulnerability Scanning Architecture" src="./Static Assets/Threat-modelling-MCP.png" />

**Description:** This diagram presents the MCP Server vulnerability scanning architecture, illustrating how Threat Shield performs static code analysis on MCP repositories, identifies security vulnerabilities, and generates LLM-powered explanations with **compliance** mapping.

#### Demo Video

https://github.com/user-attachments/assets/b41ce23a-b494-49ae-81d4-46ec39a3a7ef

#### What Users See & How It Works


- **MCP Scans List:**  
  - Table: [Repository Name, Total Results, Language, Status, Created At]
  - “Create Project” for new scan
- **MCP Scanning Project Dashboard:**  
  - **Summary Cards:**  
      - Total Results  
      - Total Resolved  
      - Total High Risk
  - **Failed Controls:** **Compliance** controls failed by code issues.
  - **OWASP** Vulnerabilities: Number and list of Top 10 for API Security triggered.
  - **Threat Graph:** Shows trends/types/frequency across findings.
  - **Result Table:**  
      - Columns: Result Class, Severity, Rule Detected, Status, Suggested Fixes

### MCP Scan Project Dashboard

<img width="800" height="600" alt="Screenshot 2025-09-29 173159" src="https://github.com/user-attachments/assets/3d041883-97bb-48b0-bbab-c5029d929e57" />


**Description:** The dashboard for an **MCP Server Vulnerability Scan**, providing an executive summary with **Total Findings** (5), **High Risk** items (5), and the primary development language (Python). It also displays a list of detected **OWASP** Vulnerabilities (A03, A06, A04, A01) and a visualization of **Failed Compliance** Controls over time.




### MCP Finding Details

<img width="800" height="600" alt="Screenshot 2025-09-29 173534" src="https://github.com/user-attachments/assets/9e787855-371a-45c5-8daa-855e9798819c" />


**Description:** A detailed view of a security finding from the MCP Server scan, specifically the **detect-command-execution** rule. The panel highlights the affected code snippet, relevant **compliance** controls (**NIST SP 800-53** and **PCI DSS**), the associated **OWASP** Injection vulnerability (A03:2021), and the **LLM-generated recommended fix** to prevent unauthorized command execution.


#### What/Why of Each Visualization
- **Summary Cards:** Snapshot of codebase health and urgency.
- **Failed Controls:** Highlights direct **compliance** impact.
- **OWASP** Card: Maps code issues to industry standards.
- **Threat Graph:** Visualizes risk over time or per category.
- **Result Table:** Drill down to every finding, fix, and **compliance** mapping.

  
#### Technical Workflow

- **Phase 1:**  
  - Repository is temporarily cloned and scanned for static code analysis.
  - The system flags all code patterns matching vulnerability rules.
- **Phase 2:**  
  - Each finding is analyzed by an LLM to generate explanations and actionable fixes.
  - Further mapped to **OWASP** Top 10 for API Security vulnerabilities and failed **compliance** controls (ISO 27001, PCI DSS, NIST, SOC2, GDPR, etc.).
  - **Compliance** mapping is visualized per finding and overall scan.


### Code-Level Finding Explanation

<img width="800" height="600" alt="Screenshot 2025-09-29 173512" src="https://github.com/user-attachments/assets/445c5c0b-95bd-4cb7-9167-b0466bb3a638" />


**Description:** A close-up view of the code analysis within the MCP Scan, showing the exact file (**mcp_server.py**) and code snippet where the vulnerability was detected. The finding is given a **Medium** risk severity, accompanied by an LLM-generated **Explanation** of the command execution risk found in the code.


 

#### Deep-Dive: Analysis Pipeline

- **Step 1: Static Analysis**
    - When a scan is triggered, Threat Shield temporarily clones the selected MCP repository.
    - The system runs a suite of static analysis rules covering **OWASP** Top 10 for API Security, common code smells, secrets, and insecure configurations.
    - The analysis engine is chosen for its speed, accuracy, and extensibility (custom rules per project/language).
- **Step 2: LLM-Powered Findings**
    - Each finding is passed to an LLM for further analysis, generating:
        - Human-readable explanation of risk
        - Contextual remediation steps
        - Mapping to **compliance** controls (ISO, PCI, SOC2, NIST, GDPR, etc.)
- **Step 3: Dashboard and Reporting**
    - All results are visualized in the MCP scan dashboard, showing severity, status, **compliance** impact, and suggested fixes.
    - Reports can be exported for audit/evidence.


#### How It Benefits Users

- **Automated, deep static analysis** on every codebase.
- **LLM-powered explanations** for fast triage and remediation.
- **Clear compliance** gap visibility for every finding.
- **Audit-ready reporting** and **compliance** evidence on demand.

#### Hypothetical User Scenario

> **Jane**, DevSecOps Lead, pushes a new release to the MCP repo. Threat Shield automatically kicks off a scan. Within minutes, Jane sees 13 new findings—two critical SQL injection issues, several failed PCI controls, and a high-risk secrets leak. The LLM-generated explanations help her prioritize fixes, and she exports a **compliance** report for the next audit.


---

## **Compliance** Mapping

| Vulnerability / Threat Type                | **OWASP** Top 10 for API Security | ISO 27001 | PCI DSS | SOC2 | NIST | GDPR |
|--------------------------------------------|:------------:|:---------:|:-------:|:----:|:----:|:----:|
| Insecure Authentication                    | A07          | ✓         | ✓       | ✓    | ✓    | ✓    |
| Injection (SQLi, Command, etc.)            | A03          | ✓         | ✓       | ✓    | ✓    |      |
| Data Exposure/Leakage                      | A01, A06     | ✓         | ✓       | ✓    | ✓    | ✓    |
| Security Misconfiguration                  | A05          | ✓         | ✓       | ✓    | ✓    |      |
| Vulnerable/Outdated Components             | A06          | ✓         | ✓       | ✓    | ✓    |      |
| Prompt Injection (LLM)                     | A01, A05     |           |         |      |      | ✓    |
| Malicious Code Generation                  | A06, A10     | ✓         |         |      |      |      |
| Compliance Control Failure (General)       | All          | ✓         | ✓       | ✓    | ✓    | ✓    |

*Each finding in the dashboard is automatically mapped to these standards using threat modeling security probe/static analysis metadata and logic. **Compliance** impact is shown per issue and in summary cards.*


## Example Workflows & User Benefits

**Threat Modeling Workflow:**  
- Upload system diagrams and architecture details, review generated threat model, prioritize/assign remediation, track resolution and **compliance** mapping.
- Dashboard instantly shows unresolved **STRIDE** threats, failed PCI **compliance** controls, and actionable fixes.

**LLM Security Workflow:**  
- Register LLMs for assessment, receive prioritized threat modeling reports with detailed analysis, act on LLM-generated fix steps, monitor ongoing risk.
-  AI/ML lead performs threat modeling on a chatbot; dashboard highlights prompt injection risk and GDPR **compliance** issues; fixes are applied and risk drops.

**MCP Vulnerability Workflow:**  
- Trigger scan for MCP repositories, review findings and LLM explanations, analyze **OWASP**/**compliance** mapping, assign remediations, produce **compliance**-ready reports.
- DevSecOps lead triggers a code scan; the system finds vulnerabilities, LLM explains and maps them to **OWASP** and **compliance**, all results are reviewed and exported for audit.

**Benefits:**  
- Prevent real-world security incidents and **compliance** failures before they happen.
- Save time with automation and actionable guidance.
- Communicate risk and progress clearly to all stakeholders.

---

## Use Cases

- Security architecture reviews for new/evolving systems
- Continuous **compliance** (ISO, PCI, NIST, SOC2, GDPR)
- DevSecOps integration into CI/CD
- GenAI/LLM security validation and monitoring
- MCP workload/codebase security

---

## Tech Stack

- **Backend:** Python (FastAPI), REST API, JWT Auth
- **Frontend:** Next.js (TypeScript), Tailwind CSS, Lucide React, React
- **AI Analysis:** LLM/AI-powered threat modeling and security analysis
- **Threat Modelling Methods Used to Analyze Source Code:** Static Analysis Engine
- **Database:** Configurable (e.g., SQLite/Postgres)

---

## Trial License & Security

### Trial License Limits
- **Trial accounts** have a limit of up to **5 scans** per license period
- Upgrade to a full license for unlimited scanning and advanced features

### Security Measures & Data Protection

Threat Shield implements enterprise-grade security measures to protect your data and ensure the highest level of application security:

#### File Security
- **Antivirus scanning** is automatically performed on all file uploads to prevent malware transmission
- All uploaded files are scanned in real-time before processing

#### Application Security
- **OWASP** Top 10 for API Security **compliance** - Threat Shield has been thoroughly tested against **OWASP** Top 10 for API Security vulnerabilities for application security
- **Secure authentication** with JWT tokens and encrypted session management
- **Input validation** and sanitization for all user inputs to prevent injection attacks

#### Data Privacy & Protection
- **No sensitive data storage** - Repository source code, DFDs, API keys, and Personal Access Tokens submitted to the application are **never stored permanently**
- **Temporary processing only** - Sensitive data is used solely to initiate scans and is immediately purged after analysis completion
- **Minimal data retention** - Only trivial information is retained for record-keeping:
  - Repository URLs (for scan tracking)
  - System names (for project identification)
  - Model names (for LLM assessment tracking)
- **Encrypted data transmission** using TLS 1.3 for all communications
- **Secure cloud infrastructure** with regular security audits and compliance certifications

#### Additional Security Features
- **Automated security monitoring** with real-time threat detection
- **Regular penetration testing** by certified security professionals

---

## Case Studies

A public repository of case studies and technical deep-dives are available below, demonstrating Threat Shield's real-world impact across various security domains.

- **Case Study 1: Securing a High-Risk Payments Platform (Threat Modeling)**
    - [View Source Documentation](./case-studies/securing-payments-platform.md)
    - **[View Full Report](https://www.canva.com/design/DAG0pHcZfCU/view)**

- **Case Study 2: Validating a GenAI Chatbot against Prompt Injection (LLM Security Testing)**
    - [View Source Documentation](./case-studies/validating-ai-chatbot.md)
    - **[View Full Report](https://www.canva.com/design/DAG0pBZZH0M/view)**

---
## Support

- 📧 Contact: [vartul@zeroshield.ai](mailto:vartul@zeroshield.ai)
- 📧 Support Queries: [support@zeroshield.ai](mailto:support@zeroshield.ai)

---


> **Value Proposition:**  
> Unified, automated threat modeling and vulnerability management for the next generation of enterprise security
> "Thraet Shield turns complex, manual security and compliance challenges into automated, actionable insights—empowering teams to move faster, safer, and with confidence."
*Threat Shield, a part of [ZeroShield](https://zeroshield.ai), brings in-depth, practical security to every step of your development and deployment lifecycle.*

---

## Get Involved

We welcome contributions from the security community! Here's how you can get involved with [Threat Shield](https://zeroshield.ai):

### 🤝 Contributing

- **Report Issues**: Found a bug or have a feature request? Open an issue on our repository
- **Code Contributions**: Submit pull requests to help improve [Threat Shield](https://zeroshield.ai)
- **Documentation**: Help improve our documentation and examples
- **Security Research**: Contribute new threat models, attack patterns, or vulnerability tests

### 🔗 Community

- **GitHub Discussions**: Join our community discussions and share ideas
- **Security Research**: Collaborate on new security analysis techniques
- **Feedback**: Share your experience using [Threat Shield](https://zeroshield.ai) in your organization

### 📞 Contact

- **General Contact**: [vartul@zeroshield.ai](mailto:vartul@zeroshield.ai)
- **Support**: [support@zeroshield.ai](mailto:support@zeroshield.ai)

---

All rights reserved. This software and its documentation are the intellectual property of [ZeroShield](https://zeroshield.ai).

---
