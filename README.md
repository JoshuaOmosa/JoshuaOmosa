# Joshua Omosa

### Software Engineer | Application Security | DevSecOps | Cloud Security

I build software and security systems with a focus on **application security, secure software delivery, security automation, and cloud-native infrastructure**.

My work focuses on integrating security into the software development lifecycle through automated security controls, vulnerability management, secure CI/CD pipelines, infrastructure hardening, and policy enforcement.

I am particularly interested in the intersection of **software engineering and security engineering**, where security controls can be designed as part of the system rather than added after development.

---

## Core Areas

* **Application Security:** SAST, DAST, SCA, secrets detection, vulnerability management, SBOMs
* **DevSecOps:** CI/CD security, automated security gates, security testing, pipeline automation
* **Cloud Security:** AWS, IAM, least-privilege access, cloud architecture and hardening
* **Infrastructure Security:** Terraform, Infrastructure as Code, Docker, container security
* **Security Automation:** Python, REST APIs, automated security workflows and tooling
* **Threat Modeling:** STRIDE, attack-surface analysis, security requirements
* **Policy as Code:** Open Policy Agent (OPA), automated policy enforcement
* **Security Monitoring:** Splunk, application telemetry, security event analysis

---



## Featured Projects

### Security & DevSecOps

| Project | What it is | Stack |
| ------- | ---------- | ----- |
| [**Devsecops-gate**](https://github.com/JoshuaOmosa/Devsecops-gate) | CI/CD security gate that ranks findings by exploitability, enforces severity-based SLA windows with OPA policy, and blocks unverified builds | GitHub Actions, OPA/Rego, Terraform, Checkov, Docker |
| [**Isolated-Sandbox**](https://github.com/JoshuaOmosa/Isolated-Sandbox) | Locked-down Docker sandboxes for running and grading AI-agent code: read-only root, no network, custom seccomp allowlist, dropped capabilities, resource ceilings | Python, Docker, seccomp, Pytest |

### Applied AI (local-first, privacy-preserving)

| Project | What it is | Stack |
| ------- | ---------- | ----- |
| [**MedgemmaV2**](https://github.com/JoshuaOmosa/MedgemmaV2) | Offline clinical voice-to-SOAP pipeline with input/output guardrails, network isolation checks, and a written threat model | Python, Whisper, MedGemma, NeMo Guardrails, Docker |
| [**medgemma-aegis**](https://github.com/JoshuaOmosa/medgemma-aegis) | Clinician-facing scribe: record, transcribe, draft a SOAP note, review, and export as FHIR R4 | Python, Streamlit, Whisper, MedGemma, FHIR |
| [**aimo-marks-v1**](https://github.com/JoshuaOmosa/aimo-marks-v1) | LoRA fine-tune of DeepSeek-Math-7B for step-by-step math reasoning, 4-bit quantized for consumer GPUs | PyTorch, PEFT/LoRA, bitsandbytes, Gradio |

### Full-Stack Applications

| Project | What it is | Stack |
| ------- | ---------- | ----- |
| [**kelly-rogers**](https://github.com/JoshuaOmosa/kelly-rogers) | Production site and practice-management workflow for a private psychotherapy practice: intake, admin dashboard, quotes, payments, automated follow-ups ([live](https://kelly-rogers-one.vercel.app)) | Next.js, TypeScript, Supabase, Paystack, Resend |
| [**socialsNETTs**](https://github.com/JoshuaOmosa/socialsNETTs) | Brand-monitoring and social intelligence dashboard: mentions, sentiment, crisis tracking, reporting | Next.js, TypeScript, Django REST |
| [**NexusCore**](https://github.com/JoshuaOmosa/NexusCore) | Patient-records backend demonstrating the Repository pattern, env-based config, and prepared statements, with tests | PHP 8, PDO, MySQL |

More (game prototypes in Godot, tooling experiments) are in the [repository list](https://github.com/JoshuaOmosa?tab=repositories).

---

## Engineering Approach

I approach security as an engineering discipline.

The systems I build aim to make security controls:

* **Automated** where practical
* **Repeatable** across environments
* **Risk-based** rather than dependent solely on severity scores
* **Observable** through meaningful telemetry
* **Reproducible** through Infrastructure and Security as Code
* **Maintainable** through clear architecture and documentation

I value engineering practices that make systems easier to secure, operate, test, and maintain.

---

## Technologies

| Category               | Technologies                             |
| ---------------------- | ---------------------------------------- |
| Languages              | Python, TypeScript, C#, PHP, C, SQL      |
| Frameworks             | .NET, Flask, FastAPI, Django, Next.js    |
| AI / ML                | PyTorch, Hugging Face, Whisper, LoRA     |
| Cloud                  | AWS                                      |
| Infrastructure as Code | Terraform                                |
| Containers             | Docker                                   |
| CI/CD                  | GitHub Actions, Jenkins                  |
| Application Security   | SAST, DAST, SCA, Secrets Detection, SBOM |
| Policy                 | Open Policy Agent (OPA)                  |
| Threat Modeling        | STRIDE                                   |
| Monitoring & SIEM      | Splunk                                   |
| Version Control        | Git, GitHub                              |

---

## Software Engineering

My security work is supported by a broader software engineering foundation.

I build applications, APIs, automation tools, and backend systems with an emphasis on:

* Clean architecture
* Maintainability
* Testing
* API design
* Data handling
* Secure coding practices
* Version control
* Documentation

I am particularly interested in building security tooling that integrates naturally into existing engineering workflows.

---

## Security Engineering

My security projects cover the lifecycle from **identification and prevention through detection and remediation**.

Areas of hands-on work include:

* Application security
* Vulnerability management
* Secure CI/CD
* Cloud security
* Infrastructure security
* Container security
* Threat modeling
* Security automation
* Security monitoring
* Incident investigation

Project repositories include implementation details, architecture, configuration, testing, security considerations, and documented results where applicable.

---

## Certifications & Continuous Learning

I continuously develop my engineering and security capabilities through hands-on projects, technical challenges, security labs, certifications, and independent study.

My approach is:

**Learn → Build → Test → Secure → Automate → Document**

---

## Professional Interests

I am interested in opportunities across:

**Software Engineering · Application Security · DevSecOps · Cloud Security · Security Engineering**
