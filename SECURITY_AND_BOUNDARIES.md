# Security and Boundaries

This public repository explains an architecture. It is not an operational data store and must not become a mirror of any private project.

## Private by default

Treat every source repository, project workspace, account, document, dataset, screenshot, transcript, and generated artifact as private unless a person with applicable authority explicitly approves that specific material for public disclosure.

When safety is uncertain, exclude the material and request human review.

## Never include

- credentials, passwords, tokens, private keys, recovery material, or secrets;
- account, workspace, document, repository, database, customer, or other private identifiers;
- private URLs, remotes, local paths, usernames, or machine configuration;
- personal contact information or private information about any person;
- contracts, pricing, financial records, pipeline data, or confidential commercial information;
- internal decisions, task lists, meeting contents, or operational status;
- proprietary datasets, source documents, database contents, or GIS layers;
- private media, metadata, exports, fixtures, or experiment results;
- protected legal, medical, identity, family, tax, banking, or insurance information;
- copied private repository files, history, configuration, or metadata.

Removing obvious secrets is not enough. Filenames, directory layouts, timestamps, map labels, chart legends, commit history, terminal prompts, and document metadata can reveal protected information.

## Safe public material

Prefer:

- original architectural explanations;
- synthetic examples;
- category-level source descriptions;
- new diagrams built from approved public abstractions;
- fictional identifiers, names, data, and geographies;
- general workflow and validation patterns;
- intentionally selected public facts with clear provenance and authority.

Sanitization must remove both direct identifiers and combinations of details that could reconstruct private operations.

## Source and authority boundaries

- A public explanation does not supersede a private canonical source.
- Repository access does not grant publication rights.
- A model cannot authorize disclosure.
- Corporate, contractual, professional, personal, and third-party restrictions continue to apply.
- A generated summary can still disclose protected source content.
- Public information combined with proprietary analysis may create confidential derived intelligence.

## Screenshot policy

Screenshots are permitted only after explicit individual human approval.

No screenshots are included in the initial implementation. The evidence set being considered separately includes:

- an Iñaqui OS private repository structure;
- a POW Water project-OS repository structure;
- a PhotoVault engineering repository structure;
- a Codex project environment;
- a Claude/Cowork POW project environment;
- a ChatGPT project environment;
- a POW Water QGIS environment.

Listing a screenshot here does not approve it.

Before approval, inspect each screenshot at full resolution for:

- names, faces, email addresses, avatars, and account details;
- repository owners, remotes, URLs, branches, and commit messages;
- local paths, usernames, device names, and terminal history;
- source IDs, database identifiers, tokens, and configuration;
- filenames that reveal confidential projects or decisions;
- contacts, pricing, tasks, calendars, transcripts, and notifications;
- maps, coordinates, layer names, legends, tables, and proprietary geography;
- browser tabs, sidebars, recent files, hidden panels, and background windows;
- image and file metadata.

Redaction must be irreversible in the exported asset. Cropping or drawing a translucent shape over sensitive content is insufficient. Reinspect the final flattened file and its metadata before inclusion.

## Contribution review

Every proposed change should be checked for:

1. secrets and high-entropy credentials;
2. private paths, URLs, IDs, email addresses, and phone numbers;
3. copied or closely paraphrased private content;
4. proprietary business or technical details;
5. source and image metadata;
6. claims that overstate automation, authority, or current system behavior;
7. conflicts with the manual, provider-independent architecture;
8. licensing or ownership concerns.

Security scans reduce risk but do not replace contextual human review.

## If sensitive content is found

1. Stop publication and further distribution.
2. Identify the affected material and source.
3. Remove it from the working tree and any generated assets.
4. If it entered Git history or a remote, treat deletion as a history and exposure incident rather than a normal edit.
5. Rotate any exposed credential through its authoritative system.
6. Notify the applicable owner or authority.
7. Verify that caches, releases, artifacts, forks, and mirrors are addressed where possible.
8. Record a privacy-safe incident outcome without repeating the sensitive content.

## Public/private separation test

Before publication, a reviewer should be able to confirm:

- the public repository was created from fresh files and fresh history;
- no private repository was copied, filtered, forked, or used as Git ancestry;
- examples are synthetic or explicitly approved;
- case studies reveal patterns, not private operating state;
- diagrams contain no hidden source data;
- every screenshot has its own approval record;
- no private canonical document has been published;
- licensing and asset rights have been resolved.
