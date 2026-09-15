# Portability

Portability means a project can be resumed in a different AI environment without relying on the previous provider's memory or conversation history.

It does not mean every provider supports the same tools. A replacement environment may require different execution steps, reduced scope, or a human handoff. The continuity contract is that durable context, source routing, boundaries, and verification requirements survive the change.

## Boot sequence

![Portable boot sequence](assets/diagrams/boot-sequence.svg)

### 1. Read OS instructions

Load the stable operating principles, terminology, security rules, and escalation conditions. Do not infer authority from access to the files.

### 2. Identify project and scope

Determine which person, organization, project, repository, systems, and intended outcome the work affects. If the request crosses boundaries, split the work or escalate the ambiguity.

### 3. Load project context

Read the project's entrypoint, scoped operating instructions, source map, and current dated handoff. Historical reviews should be consulted only when their reasoning is relevant.

### 4. Locate canonical sources

Identify the named durable artifact or authoritative system for the specific question. Do not substitute a convenient copy, conversation, generated view, or stale export without clearly labeling the limitation.

### 5. Verify current state

Check that the source still exists, is accessible, is the intended source, and is current enough for the task. Validate material claims against live state before consequential action.

### 6. Confirm authority and boundaries

Identify the actor, applicable human or organizational authority, permitted actions, prohibited disclosures, expected effect, validation method, and recovery path.

### 7. Resume bounded work

Execute only the portion supported by the available source, authority, tools, and evidence. Continue unaffected work when a separate issue is blocked.

### 8. Validate the result

Test the intended effect. A generated file, changed status, completed command, or checked task does not establish successful closure by itself.

### 9. Preserve material continuity

Update durable context when another operator would otherwise be unable to understand what materially changed, what remains open, where evidence lives, or what should happen next.

## Minimum project portability packet

A portable project environment should provide:

- a project definition and scope;
- operating and security rules;
- a source map using safe references;
- decision and authority boundaries;
- a current dated handoff;
- open questions, risks, and blockers;
- validation and recovery expectations;
- a clear next action.

The packet should point to canonical sources rather than duplicating their contents.

## Freshness rules

Revalidate a pointer or source when:

- a file or system moves;
- a documented location no longer resolves;
- a new operational system appears;
- an ownership or authority boundary changes;
- a handoff is superseded;
- sources contradict one another;
- current state affects a decision or external action.

Record the contradiction or missing source rather than silently choosing the most convenient version.

## Failure handling

| Condition | Safe response |
|---|---|
| Provider history is unavailable | Reconstruct from durable OS and project context |
| Handoff may be stale | Treat it as a dated snapshot and check the canonical source |
| Pointer is broken | Stop source-dependent work, record the break, and identify the owner |
| Sources conflict | Preserve both claims, identify scope and authority, and escalate resolution |
| Access is missing | Continue only work that does not require the source; request authorized access |
| Authority is unclear | Prepare evidence or a recommendation, but do not take the consequential action |
| Sensitive data appears in the wrong lane | Stop transfer, minimize exposure, and follow the applicable incident process |
| Provider lacks a required capability | Change runtime or hand off the bounded operation without changing source authority |

## Handoff update test

Before ending a substantial work cycle, ask whether the next person or AI environment can answer:

- What is the current objective?
- What materially changed?
- What remains open or uncertain?
- Which decisions are applicable?
- What should happen next?
- Where is the supporting evidence?
- Which state must be reverified?

If not, update the appropriate dated handoff without copying protected source content into it.

## Portability test

A practical test is to give a fresh AI environment only the approved portability packet and source access appropriate to its role. It should be able to:

1. explain the project and its boundaries;
2. identify the correct source for a representative question;
3. distinguish snapshot information from live state;
4. identify a decision requiring human authority;
5. complete one bounded task;
6. validate the result;
7. produce a privacy-safe handoff.

Failure reveals a continuity gap in documentation, source routing, access, verification, or authority—not a reason to make provider memory canonical.
