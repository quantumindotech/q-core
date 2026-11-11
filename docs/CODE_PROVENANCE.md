# Code Provenance Register

## Purpose

Track the origin, authorship, license, and review status of every code component before it is redistributed, modified under a new license, or released.

## Required record

For each component, record:

| Field | Required information |
|---|---|
| Component/path | Exact repository path and component name |
| Origin | Original author, repository, URL, or source record |
| Author/contributor | Known author(s); use `UNKNOWN` when unresolved |
| License | Exact license and version, or `UNKNOWN` |
| Modifications | Original, modified, generated, or adapted |
| Evidence | Commit, source URL, permission, notice, or review record |
| Status | `VERIFIED`, `REVIEW_REQUIRED`, or `PROVENANCE_PENDING` |
| Reviewer/date | Reviewer and review date |

## Release gate

- Unknown origin or license: `PROVENANCE_PENDING`.
- Conflicting or incompatible terms: `REVIEW_REQUIRED`.
- Do not remove upstream notices or copyright statements.
- Do not relicense third-party material as Q-CORE material.
- AI-assisted output is not automatically free of third-party rights or source restrictions; review it like any other contribution.
- Preserve source references and the exact version used.

## Initial repository status

At foundation setup, this repository contains architecture and policy documentation. No code provenance clearance is implied for future code, imported snippets, generated code, contracts, or dependencies. Populate this register as components are introduced.
