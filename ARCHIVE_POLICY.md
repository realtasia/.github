# RealtAsia Archive and Editorial Policy

## Purpose

The RealtAsia organisation preserves the source and engineering history of the RealtAsia social-property platform developed and operated between 2012 and 2014.

The archive has two simultaneous duties:

1. preserve the strongest possible historical record of the software;
2. prevent the publication of personal data, credentials, private operational material or source that cannot lawfully be licensed.

Neither duty is permitted to quietly consume the other.

## Archival layers

### Private archival masters

The surviving original repositories remain private and unchanged. They are the evidentiary masters.

No sanitisation, documentation work or public-release preparation is performed directly on those masters.

### Public archival mirrors

The public repositories are derived mirrors. They retain the original history wherever publication permits.

A public mirror may differ from its private master because a historical revision contained personal information, authentication material, credentials, production records, private communications, operational logs or third-party material without a suitable redistribution right.

### Modern editorial material

READMEs, architectural guides, annotated histories, diagrams and sanitisation records added during the 2026 archival project are contemporary documents.

They must never be represented as original project documentation.

## History-preservation order

When preparing a public mirror, preservation is prioritised as follows:

1. author and committer timestamps;
2. original commit messages;
3. authorship;
4. parentage and branch topology;
5. executable source structure;
6. incidental binary and generated material.

A commit receives a new object identifier whenever its contents or ancestry must change. That is an unavoidable property of Git, not an attempt to manufacture or obscure history.

The rewrite map produced during sanitisation is retained with the private archival material.

## Required documentation for a rewritten commit

When a historical commit must be altered for publication, the repository's sanitisation record must state:

- the public commit;
- the original commit date and message;
- the affected path or category of values;
- the reason for alteration;
- whether the path was removed, redacted or replaced with synthetic data;
- whether application behaviour was affected.

The public record should identify categories rather than repeat the sensitive values that required removal.

## Commentary and evidence

Modern technical commentary should be architecture-led and readable as a standalone public document.

Material claims should identify their evidence through one or more of:

- a linked historical commit;
- a linked source file;
- a small, relevant source excerpt;
- a cross-repository event path;
- a contemporary primary source establishing period context.

Descriptions should neither inflate the system nor diminish it through anachronistic expectations.

Historical defects may be discussed directly. Missing modern conventions are not evidence that an operated product was unfinished.

## Personal data

Real people are not part of the public artefact.

Public history must exclude identifiable records concerning users, property agents, staff, sales prospects and counterparties. This includes names, contact details, professional identifiers, photographs, biographies, addresses, messages, interactions, tokens, payments and any combinations that could reasonably identify a person.

Hashing or pseudonymising predictable identifiers is insufficient. Where a source example is architecturally useful, it should be replaced with clearly synthetic data while preserving the schema and behaviour.

## Credentials and operational material

All credentials are removed even where their accounts and infrastructure no longer exist.

Database dumps, private keys, session collections, access tokens and comparable material are purged from every reachable public revision. Removing a file only from the current tree is insufficient.

## Third-party source and assets

Authorship does not automatically establish the right to relicense every file in a historical repository.

Vendored libraries retain their original notices and licences where redistribution is permitted. Unlicensed templates, images, fonts or other third-party material are removed or separately accounted for.

No repository receives an open-source licence until the relevant ownership and dependency review is complete.

## Modern change record

Archive work uses explicit commit messages explaining what changed and why.

Each repository will maintain:

- `README.md` for orientation;
- `COMMIT_COMMENTARY.md` for the annotated historical account;
- `SANITISATION.md` for publication changes;
- links back to this organisation-level policy.

The archival project itself is therefore reviewable through Git rather than existing only as an undocumented transformation.

## Status language

The following terms have fixed meanings:

- **Original**: an untouched private archival master.
- **Sanitised**: history reviewed and rewritten where publication required.
- **Editorial**: material added after the historical development period.
- **Synthetic**: invented replacement data carrying no real person's identity.
- **Published**: a repository that has passed privacy, secret and rights review and is publicly visible.

## Governing principle

Preserve the engineering record. Remove the former occupants.

The architecture belongs in public history. Their data does not.
