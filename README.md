<div align="center">

```
  ┌──────────────────────────────────────────────────────────────────────┐
  │   AI GOVERNANCE · COMPLIANCE AUTOMATION · SECURITY FOR AI            │
  │   Making AI systems auditable, one control at a time.                │
  └──────────────────────────────────────────────────────────────────────┘
```

# David Yeti

**GRC Automation Engineer | AI Governance & Security | Python · SOC 2 · ISO 42001 · NIST 800-53**

[![Website](https://img.shields.io/badge/🌐_davidyeti.com-0a0f1e?style=for-the-badge)](https://davidyeti.com)
[![YouTube](https://img.shields.io/badge/▶_YouTube-@DavidYeti-FF0000?style=for-the-badge&logo=youtube)](https://youtube.com/@DavidYeti)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-davidyeti-0A66C2?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/davidyeti)
[![CompTIA Security+](https://img.shields.io/badge/Security%2B-Certified-EA0000?style=for-the-badge&logo=comptia)](https://www.credly.com/users/davidyeti)
[![Securtopia](https://img.shields.io/badge/Securtopia_LLC-AI_Governance_Consulting-00d4aa?style=for-the-badge)](https://securtopia.com)

</div>

---

## What I Build

I am a GRC Automation Engineer working at the intersection of **AI governance**, **compliance automation**, and **Security for AI** — the discipline of assessing and governing AI systems themselves, not using AI to detect threats.

Two years at Cisco Systems — the last four months actively embedded in the Security and Trust Organization conducting live SOC 2 control implementation reviews across identity and access management and change management domains. I map controls across frameworks, identify gaps, build Python tooling that automates the evidence collection and reporting cycle, and deliver findings to engineering and product leadership.

The focus right now is the intersection that almost nobody owns: the compliance engineer who can also assess the security risk of an LLM deployment, map it to the OWASP LLM Top 10 and NIST AI RMF, and build the tooling that makes the assessment continuous rather than point-in-time.

> Most compliance engineers can tell you what a control requires.
> Most AI engineers can build the model but cannot assess its governance risk.
> This portfolio is closing the gap between those two lanes.

**Securtopia LLC** — independent AI governance and compliance consulting firm serving SMBs and organizations preparing for SOC 2, CMMC, FedRAMP, and ISO 42001 AI governance requirements.

---

## 🥼 The Lab

```yaml
focus:        AI Governance · Compliance Automation · Security for AI · LLM Risk Assessment
frameworks:   ISO 42001 · NIST AI RMF · OWASP LLM Top 10 · SOC 2 · NIST 800-53 · CMMC · FedRAMP
platforms:    AWS · Python · GitHub Actions · Claude API
certs_active: Security+ (earned) · CISA (retake) · AWS Cloud Practitioner (in progress)
active_repos: AI Governance Toolkit · WorkScribe · LLM Security Assessment (in development)
```

---

## 🔧 Projects

### [AI Governance Toolkit](https://github.com/DavidYeti/ai-governance-toolkit)
Multi-framework Python compliance automation suite covering ISO 42001, ISO 27017, ISO 27018, and Cisco CCF. Three tools in production:

- **Multi-Framework Control Checker** — single engine running ISO 42001, ISO 27017, ISO 27018, and Cisco CCF gap assessments via CLI flag or Streamlit GUI. Generates findings reports with compliance scores and maturity ratings.
- **AI Tool Intake Automation** — scores new AI tool adoption requests as Low, Medium, or High risk based on data classification and PII handling. Generates formal intake reports and saves persistent JSON audit log.
- **ISO 42001 Control Checker v2** — 20 controls, four-level maturity ratings, confidence scoring, and actionable remediation recommendations per non-compliant control.

---

### [WorkScribe](https://github.com/DavidYeti/workscribe) *(In Development)*
AI-powered audit workpaper automation tool. Ingests session transcripts, evidence files (PDF, DOCX, XLSX, screenshots), and a control list — auto-populates compliance work papers mapped per control. Reduces manual documentation from hours to minutes.

- Evidence re-request workflow — flags insufficient evidence submissions and generates follow-up requests automatically
- Built with Python, OpenAI API, python-docx
- Target use case: SOC 2 and ISO 42001 audit delivery acceleration

---

### LLM Security Assessment Tool *(In Development)*
Practical prompt injection and LLM security assessment tooling built on the OWASP LLM Top 10 framework. Designed to assess enterprise LLM deployments — including RAG architectures — for the attack surfaces that compliance engineers need to evaluate before production deployment.

- Prompt injection detection and classification
- RAG pipeline risk assessment mapping
- NIST AI RMF control alignment
- Built with Python and the Anthropic Claude API

---

## Certification Roadmap

Every credential maps directly to something in active use or the next stop on the career ladder.

```
  ✅ 2025   CompTIA Security+               ← earned · DoD 8140 approved

  ◐  2026   AWS Cloud Practitioner          ← in progress · closes AWS skill gap
  ◐  2026   CISA                            ← retake · ISACA active member · Atlanta chapter

     2026   AWS Solutions Architect Assoc.  ← cloud architecture foundation
     2026   SANS SEC545                     ← Gen AI & LLM Security · work study · Sep/Nov 2026

     2027   ISO 42001 Lead Implementer      ← AI governance depth · Securtopia differentiator
     2027   AWS Security Specialty          ← primary salary multiplier · cloud security lane
     2027   HashiCorp Terraform Associate   ← infrastructure as code for compliance automation

     2028   CRISC                           ← ISACA · enterprise risk management leadership

     2029+  CCSP                            ← cloud security governance · 5yr experience gate
     2029+  CISSP                           ← Director / vCISO positioning
```

---

## 🌉 The Bridge

I came into compliance engineering through enterprise security sales — two years of technical conversations with CISOs, security architects, and infrastructure engineers at a Fortune 50 company, diagnosing gaps across identity, access, endpoint, and network security.

That background led directly into a compliance engineering stretch assignment inside the Cisco Security and Trust Organization: conducting SOC 2 control implementation reviews across identity and access management (CC6) and change management (CC8) domains for Duo Security and Cisco Cloud Security Controls. Gap assessments, evidence collection, remediation recommendations delivered to engineering and product leadership, and Python automation tooling that reduced manual audit effort by 70%.

Most compliance engineers have never spoken to a CISO about what keeps them up at night. I had hundreds of those conversations before I built a single tool. That is why I understand *why* controls exist — not just how to check them.

The independent study of ISO 42001 AI governance frameworks that followed led directly to the **AI Governance Toolkit** and the **AI Tool Intake Automation** system you see pinned below — and now into the emerging space of assessing the security risk of LLM systems themselves.

**Currently enrolled** in Computer Science at Georgia State University (Fall 2026) and building **Securtopia LLC** as an independent AI governance and compliance consulting firm targeting SOC 2, CMMC Level 2, FedRAMP, and ISO 42001 engagements.

---

## What Lane Is This?

There are two disciplines inside AI security. Most people are building the first one.

**AI for Security** — using machine learning to detect threats, automate SOC triage, and speed up incident response. That lane has no shortage of talent.

**Security for AI** — assessing and governing AI systems themselves. Protecting LLM deployments from prompt injection. Evaluating RAG pipeline architectures for data poisoning and extraction risk. Mapping AI system risk to OWASP LLM Top 10, NIST AI RMF, and ISO 42001. This is the lane with a structural talent shortage and no agreed-upon standard for what the practitioner looks like.

This portfolio is building that practitioner profile — compliance automation depth combined with practical LLM security assessment capability.

---

## Content

I document the work across three series:

📺 **[The Lab](https://www.youtube.com/playlist?list=PLH63k_nzflR2OVFrf_3ZrXI3bma_Hz8GD)** — hands-on cloud compliance, NIST and ISO control mapping, AWS security, and GitHub walkthroughs. Watch me build the tools and map the frameworks in real time.

📺 **[The Bridge](https://www.youtube.com/playlist?list=PLH63k_nzflR1qvx_jgGO7Tk4I4qmQJl5C)** — career architecture, certifications, day-in-the-life, and the thinking behind building a compliance engineering career from a non-traditional background.

💰 **[Slow Money](https://www.youtube.com/playlist?list=PLH63k_nzflR12-oMVGKXZeg_DhXp41tt-)** — financial strategy and wealth building for practitioners who are building a career and a company at the same time.

---

## A Note on What I Share

Everything in this portfolio is built from public frameworks — NIST, ISO, OWASP, CIS, AWS documentation, and vendor compliance reports. I do not publish internal tooling, proprietary processes, or anything that is not mine to share. Securtopia client deliverables are always anonymized before any reference to them appears publicly.

---

<div align="center">

*Updated as the work progresses.*

**[→ davidyeti.com](https://davidyeti.com)**

📧 david@davidyeti.com

</div>
