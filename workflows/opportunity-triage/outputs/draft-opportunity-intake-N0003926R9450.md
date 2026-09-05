# Draft Opportunity Intake Worksheet

> Draft internal workflow aid for training. Qualified human review required before live use. This is not a final pursuit decision and does not provide legal, procurement, compliance, pricing, cybersecurity, or proposal advice.

## Source Information

| Field | Value | Status | Source |
|---|---|---|---|
| Public opportunity source | User-provided SAM.gov workspace link: `https://sam.gov/workspace/contract/opp/e12ecf785bc84bdd8438c40a6035e4e0/view` | Known | User-provided public link |
| Public detail source used for this draft | NAVWAR Open CSO Calls page for Generative Artificial Intelligence Electronic Performance Support System | Known | NAVWAR Open CSO Calls page, accessed 2026-09-03 |
| Solicitation number | `N0003926R9450` | Known | NAVWAR Open CSO Calls page; SAM Directory metadata |
| Opportunity title | Generative Artificial Intelligence Electronic Performance Support System under CSO `N0003925S001` | Known | NAVWAR Open CSO Calls page |
| Agency/customer | Naval Information Warfare Systems Command on behalf of PMW 160, Department of the Navy | Known | NAVWAR Open CSO Calls page |
| Response due date | September 17, 2026 at 2:00 PM PDT | Known | NAVWAR Open CSO Calls page |
| Questions due date | August 28, 2026 at 2:00 PM PDT | Known, already passed as of 2026-09-03 | NAVWAR Open CSO Calls page |
| Submission method | Phase 1 Solution Brief through PIEE Solicitation Module; emailed submissions not accepted | Known | NAVWAR Open CSO Calls page |
| Requested capability | Commercial Generative AI-powered Electronic Performance Support System with operations and sustainment support | Known | NAVWAR Open CSO Calls page |
| Primary need | Help users adopt rapidly changing tactical network capabilities by reducing cognitive workload and information overload | Known | NAVWAR Open CSO Calls page |
| Primary technical attributes | RAG grounding with citations, hybrid retrieval, Zero Trust/offline security, RBAC/data masking, graceful degradation, audit logging, prompt-injection defense, memory safeguards, CPU fallback, TRL 6 or higher, CVE remediation SLA, air-gapped updates, active RAG pipeline support, critical incident SLAs | Known at a high level | NAVWAR Open CSO Calls page |
| Desired attributes | Hardware-constrained inference, conversational orchestration, adaptive scaffolding, modular updates, continuous fine-tuning, low-bandwidth diagnostics, model swapping, train-the-trainer and SME enablement | Known at a high level | NAVWAR Open CSO Calls page |
| Evaluation weighting | Primary and desired attributes are both evaluated; primary attributes carry higher weighting | Partial | NAVWAR Q&A on Open CSO Calls page |
| Pricing information | Phase 2 vendors are expected to provide a preliminary cost estimate and commercial pricing model; no ceiling value was identified in the reviewed public source | Partial | NAVWAR Open CSO Calls page and Q&A |
| Government-furnished data | Additional details and artifacts are expected for selected vendors in later phases | Partial | NAVWAR Q&A on Open CSO Calls page |
| Synthetic company | Synthetic Organization Alpha | Known, fictional | `workflows/opportunity-triage/data/synthetic-capability-statement.md` |
| Synthetic company core capabilities | Workflow discovery, process documentation, remote workshop facilitation, job aids, stakeholder synthesis, training rollout planning, draft governance checklists | Known, fictional | `workflows/opportunity-triage/data/synthetic-capability-statement.md` |

## Initial Fit Factors

| Factor | Score (0-2 or unknown) | Source-based reasoning | Reviewer question |
|---|---:|---|---|
| Customer fit | 0 | The public opportunity is from NAVWAR/PMW 160. The synthetic capability statement lists commercial operations teams, nonprofit service organizations, and internal administrative support groups, with no documented Navy, NAVWAR, PMW 160, tactical-network, or DoD customer relationship. | BD lead: Is there any approved evidence of prior relationship or customer knowledge outside the synthetic training files? |
| Capability fit | 0 | Synthetic Organization Alpha has workflow documentation, job-aid, facilitation, and training rollout experience, but the public opportunity asks for a commercial GenAI-powered EPSS with RAG, XAI, Zero Trust/offline security, RBAC, prompt-injection defense, audit logging, incident SLAs, and TRL 6 or higher. The supplied synthetic evidence does not show a commercial software product or GenAI EPSS capability. | Technical SME: Does the organization have an approved product, prototype, or partner capability that can meet the GenAI EPSS primary attributes? |
| Past performance fit | 1 | Past-performance snapshots show workflow documentation, job aids, remote enablement, and some accessibility-comment support. They do not show GenAI software delivery, Navy tactical-network support, TRL 6 demonstration, RAG systems, cybersecurity/IA delivery, or operations and sustainment support. | Capture lead: Which past examples, if any, could credibly support a narrow content-engineering or training-support role? |
| Delivery readiness | 0 | Synthetic delivery capacity shows small-team staffing, no named accessibility reviewer, no pricing review, and only partial partner support. The public opportunity requires a mature software solution and operational support attributes that are not evidenced in the synthetic delivery files. | Executive reviewer: Should this be treated as outside current synthetic capacity unless a committed technical partner or product owner is identified? |
| Partner readiness | 1 | Synthetic Partner Beta could provide two facilitators if committed, but no signed teaming agreement or commitment is documented. The partner evidence is facilitation-oriented and does not prove GenAI EPSS software, security, or TRL 6 capability. | BD lead: Is there an approved, committed partner with the required GenAI EPSS product and security/operations capabilities? |

## Missing or Conflicting Information

| Item | Why it matters | Suggested reviewer role |
|---|---|---|
| Existing GenAI EPSS product or prototype | The public opportunity requires a commercial solution and TRL 6 or higher; the synthetic files do not show such a product. | technical SME |
| Evidence of RAG/XAI, hybrid retrieval, prompt-injection defense, audit logging, offline operation, RBAC, data masking, and CVE remediation | These are central public opportunity attributes and cannot be inferred from workflow documentation or facilitation experience. | technical SME |
| Personnel security clearance readiness | The public source says companies must meet personnel security clearance requirements designated by the Government; the synthetic files do not identify clearance readiness. | contracts reviewer |
| SAM/PIEE registration readiness | NAVWAR Q&A says all offerors, including subcontractors, need active SAM registrations at submission; the synthetic files do not document registration status. | contracts reviewer |
| ROM, pricing model, and company viability information | The public source asks vendors to address ROM, pricing model, company overview, commercialization, and go-to-market strategy in later materials; the synthetic files do not provide live pricing or company financial evidence. | pricing lead |
| Data rights, IP, and licensing position | The public source asks companies to state positions on IP, technical data rights, and licensing; the synthetic files do not provide this. | contracts reviewer |
| Committed technical/product partner | The synthetic partner note is not a commitment and appears facilitation-oriented, not proof of a GenAI EPSS platform. | BD lead |
| Detailed evaluation and acceptance criteria | Some public Q&A clarifies weighting and minimum compute/storage requirements, but many acceptance details are reserved for later phases. | capture lead |

## Working Note For Reviewers

This intake uses a real public opportunity as the practice target and fictional internal evidence as the pretend company profile. The draft should be reviewed as a training artifact only. Do not treat any score, gap, risk, or recommendation as a qualified procurement or pursuit decision.
