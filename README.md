# Cloud Forensic Readiness and Preservation Framework (CFRPF)

## Overview

I developed the CFRPF as my master's thesis for an MSIT in Digital Forensics at American Public University System. The framework addresses three problems that kept surfacing as I researched cloud forensics: how do you maintain evidentiary integrity in environments you don't physically control, how do you make AI-generated actions traceable and legally defensible, and how do you build forensic readiness into an organization before an incident forces the question?

The result is 38 design principles organized across four components, with AI auditability as a cross-cutting principle that applies to all four:

- **Telemetry and Log Aggregation:** collecting and centralizing the logs that evidence depends on
- **Immutable Evidence Preservation:** keeping evidence in a form that can't be quietly altered, with chain of custody intact
- **Governance and Compliance Controls:** aligning forensic readiness with regulatory and legal requirements
- **Incident Response Orchestration:** connecting forensic readiness to how incidents actually get worked

**AI Auditability** isn't a fifth component. AI tooling now operates at every layer of the architecture, so making AI-driven security decisions traceable and defensible is a requirement that runs across all four.

## Preprints

Two working papers derived from this research are available as preprints on SSRN:

- **Designing a Forensic Readiness Framework for Evidence Preservation in Cloud and Hybrid Enterprise Environments:** the full CFRPF architecture and its 38 design principles. [SSRN](https://ssrn.com/abstract=7055360) | [DOI: 10.2139/ssrn.7055360](https://doi.org/10.2139/ssrn.7055360)
- **Closing the AI Audit Gap: Forensic Design Requirements for AI-driven Security Operations:** the cross-cutting AI Auditability principle developed as a standalone paper, covering five structural gaps AI introduces into security operations and five corresponding design requirements for auditable AI. [SSRN](https://ssrn.com/abstract=7101678) | [DOI: 10.2139/ssrn.7101678](https://doi.org/10.2139/ssrn.7101678)

## Who This Is For

I designed the CFRPF with practitioners in mind, not just researchers. The target audience is architects, compliance teams, and security engineers working in regulated industries (banking, defense, healthcare) or hybrid cloud environments, particularly on Microsoft Azure. The goal was a framework someone could actually implement, not one that lives in a journal and never touches production.

## Author

**Joshua E. Newbrey**  
MSIT in Digital Forensics (conferred August 2026)  
CompTIA Security+ | CySA+ (exam target January 2027) | SC-200 and SC-500 to follow

[LinkedIn](https://www.linkedin.com/in/jnewbrey87/) | [GitHub Profile](https://github.com/JNewbrey87) | [ORCID](https://orcid.org/0009-0000-6116-3098)
