# Reusable Capabilities

A capability is a reusable ability, independent of the particular model, tool, project, or repository used to perform it. A workflow exercises capabilities in a specific context. A capability does not carry authority by itself.

The capabilities below are a public practical taxonomy. Projects can combine them differently and may operate them manually or through bounded automation.

## Common operating contract

Every capability should define:

- authorized inputs and their provenance;
- the scope and source of truth;
- the intended output and destination;
- applicable human or organizational authority;
- validation and exception handling;
- privacy and retention boundaries;
- a portable handoff when the result is material.

## Meeting Intelligence

Transforms authorized meeting evidence into durable operational knowledge.

Typical flow:

```text
Meeting evidence
→ attributed notes and claims
→ decisions, commitments, questions, and risks
→ proposed task updates
→ human or governed review
→ durable project records
```

Meeting transcripts and summaries remain evidence unless explicitly designated otherwise. The workflow should preserve speaker attribution where authorized, distinguish discussion from decision, and avoid inventing owners or deadlines. Validation checks that extracted commitments match the source and that approved updates reached the intended system.

## Evidence-Based Research

Turns a bounded question into a traceable body of evidence, findings, uncertainty, and recommendations.

The capability should:

- define the decision or question being supported;
- prioritize authoritative and primary sources;
- record source date, scope, and limitations;
- distinguish fact, inference, hypothesis, and recommendation;
- identify contradictions and missing evidence;
- make freshness requirements explicit;
- preserve citations or safe source pointers.

Research output supports judgment. It is not a decision merely because it is thorough or model-generated.

## Commercial Account Intelligence

Combines authorized public, proprietary, operational, and relationship evidence into a structured view of a commercial account.

Possible outputs include:

- an account brief;
- stakeholder and relationship maps;
- needs and hypothesis registers;
- opportunity and risk summaries;
- meeting preparation;
- follow-up proposals;
- evidence-backed account priorities.

The canonical customer, contract, financial, and pipeline systems retain authority for their respective fields. Contact information, pricing, private communications, relationship context, and commercial strategy require strict access and disclosure controls.

## Geospatial Intelligence Automation

AI-assisted workflows ingest authorized provided data — public, proprietary, operational or third-party — together with geospatial files, documents, operational constraints and business objectives. They clean, transform and combine that information; build and maintain layered GIS environments; and convert geographic evidence into operational and commercial intelligence.

Public data is not required. The workflow can operate entirely on authorized proprietary or operational inputs.

Typical stages include:

- inventory and validate input data;
- preserve coordinate systems, provenance, licenses, and usage constraints;
- clean, normalize, join, and enrich layers;
- document transformations and assumptions;
- create reproducible analyses and derived layers;
- generate maps, tables, or decision-support artifacts;
- verify geometry, calculations, layer dependencies, and exports;
- route durable outputs to the correct project system.

The GIS environment, original datasets, and governed operational systems remain canonical for their defined scopes. Generated maps are decision-support artifacts, not automatically authoritative data. Sensitive locations and commercially derived intelligence must not be disclosed without approval.

## Decision and Task Orchestration

Connects questions, evidence, recommendations, authorized decisions, tasks, execution, and closure without collapsing them into one status field.

The capability maintains traceability among:

- the question or objective;
- supporting evidence;
- the recommendation or decision request;
- the authorized decision and owner;
- implementation tasks;
- dependencies and exceptions;
- validation evidence;
- durable closure.

A task can be complete while the intended outcome remains unvalidated. A decision can be authorized while implementation remains open. The system should preserve those distinctions.

## Automatic Follow-up

Monitors authorized events, dates, commitments, missing evidence, or unresolved tasks and proposes or performs bounded follow-up.

Follow-up may be manual or automated. Automation should define:

- the trigger;
- the source used to evaluate it;
- the permitted response;
- retry and failure behavior;
- escalation conditions;
- duplicate prevention;
- a stop or override mechanism;
- evidence that the follow-up occurred.

External messages, commitments, payments, filings, or other consequential effects require applicable authorization. Silence is not evidence of resolution.

## Artifact Generation

Produces useful representations from authorized sources, such as briefs, reports, plans, diagrams, presentations, spreadsheets, maps, code changes, or handoffs.

Generated artifacts should identify:

- their purpose and audience;
- sources and date range;
- assumptions and transformations;
- review or approval status;
- whether they are canonical, derived, or temporary;
- validation requirements.

Presentation quality does not establish factual correctness. Generated views should not silently become parallel sources of truth.

## Source-of-Truth and Confidence Governance

Routes questions and updates to the right source while preserving provenance, freshness, confidence, status, ownership, and authority.

It should prevent common failures such as:

- treating model memory as canonical;
- confusing a copy with its source;
- reading a stale handoff as live state;
- interpreting confidence as approval;
- merging contradictory sources silently;
- storing protected information in an inappropriate repository;
- treating access as authority.

The output may be a source determination, confidence assessment, contradiction, validation result, safe pointer, or escalation—not necessarily a new document.

## Engineering Execution and Verification

Uses AI-assisted engineering roles to understand a repository, plan bounded changes, implement them, review diffs, run tests, inspect outputs, and preserve evidence.

The project repository remains canonical for code and accepted engineering documentation. A portable workflow may include:

```text
Read project instructions
→ inspect current repository state
→ locate accepted architecture and decisions
→ form a bounded implementation plan
→ change code or documentation
→ review the diff
→ run relevant tests and checks
→ inspect behavior or generated artifacts
→ record material decisions and handoff state
```

An engineering role can be performed by a person, one AI environment, or multiple bounded tools. This document does not establish autonomous agent identity or grant deployment, merge, deletion, or production authority.

## Capability compounding

Capabilities compound when their outputs remain portable and reusable. Meeting intelligence can create evidence for commercial analysis. Research can resolve roadmap questions. Geospatial work can produce decision support. Decisions can create bounded tasks. Verification can close them with evidence. Updated context lets the next provider continue without reconstructing the work from conversation history.
