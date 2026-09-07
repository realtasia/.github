# realTasia Archive and Editorial Policy

## Purpose

The realTasia organisation preserves the source and engineering history of the realTasia social-property platform developed and operated between 2012 and 2014.

The archive has two simultaneous duties:

1. preserve the strongest possible historical record of the software;
2. prevent the publication of personal data, credentials and private operational material while documenting unresolved third-party provenance honestly.

Neither duty is permitted to quietly consume the other.

## Archival layers

### Private archival masters

The surviving original repositories remain private and unchanged. They are the evidentiary masters.

No sanitisation, documentation work or public-release preparation is performed directly on those masters.

### Public archival snapshots

Each public source repository is a derived snapshot with exactly one root commit. Original Git objects, branch history and contributor metadata remain in the private archival master and are not reachable from the public repository.

A public snapshot differs from its private master where the source contained personal information, authentication material, credentials, production records, private communications or operational logs. Third-party material with unresolved provenance is removed where practical or retained only with an explicit historical-archive caveat and no repository-level licence.

### Modern editorial material

READMEs, architectural guides, annotated histories, diagrams and sanitisation records added during the 2026 archival project are contemporary documents.

They must never be represented as original project documentation.

## Snapshot-preservation order

When preparing a public snapshot, preservation is prioritised as follows:

1. first-party executable source structure;
2. architecture and behaviour that can be evidenced safely;
3. clearly identified modern commentary and provenance;
4. first-party assets with a defensible publication basis;
5. licensed third-party material with its notices;
6. incidental binary and generated material.

The complete Git history is preserved only in the unchanged private master. Private transformation records identify the source refs, reviewed paths and sanitisation work used to produce the public snapshot.

## Required snapshot documentation

Each repository's sanitisation record must state:

- the source repository and snapshot model;
- the affected path or category of values;
- the reason for alteration;
- whether material was omitted, redacted or replaced with synthetic data;
- whether application behaviour was affected.

The public record should identify categories rather than repeat the sensitive values that required removal.

## Commentary and evidence

Modern technical commentary should be architecture-led and readable as a standalone public document.

Material claims should identify their evidence through one or more of:

- an archival commit identifier retained in the private master;
- a linked source file;
- a small, relevant source excerpt;
- a cross-repository event path;
- a contemporary primary source establishing period context.

Descriptions should neither inflate the system nor diminish it through anachronistic expectations.

Historical defects may be discussed directly. Missing modern conventions are not evidence that an operated product was unfinished.

## Personal data

Real people are not part of the public artefact.

Public snapshots must exclude identifiable records concerning users, property agents, staff, sales prospects and counterparties. This includes names, contact details, professional identifiers, photographs, biographies, addresses, messages, interactions, tokens, payments and any combinations that could reasonably identify a person.

Hashing or pseudonymising predictable identifiers is insufficient. Where a source example is architecturally useful, it should be replaced with clearly synthetic data while preserving the schema and behaviour.

## Credentials and operational material

All credentials are removed even where their accounts and infrastructure no longer exist.

Database dumps, private keys, session collections, access tokens and comparable material are excluded from the snapshot. The public repository must contain no older Git object through which excluded material remains reachable.

## Third-party source and assets

Authorship does not automatically establish the right to relicense every file in a historical repository.

Vendored libraries retain their original notices and licences where redistribution is permitted. Unlicensed templates, images, fonts or other third-party material are removed where practical or separately accounted for as unresolved historical material.

No repository receives an open-source licence until the relevant ownership and dependency review is complete.

## Modern change record

Archive work uses explicit commit messages explaining what changed and why.

Each repository will maintain:

- `README.md` for orientation;
- `COMMIT_COMMENTARY.md` for the annotated historical account;
- `SANITISATION.md` for publication changes;
- links back to this organisation-level policy.

The public snapshot documents its transformation, while the organisation publication log records the archive-level decision and release.

## Status language

The following terms have fixed meanings:

- **Original**: an untouched private archival master.
- **Sanitised**: a snapshot reviewed and transformed where publication required.
- **Editorial**: material added after the historical development period.
- **Synthetic**: invented replacement data carrying no real person's identity.
- **Published**: a repository that has passed privacy and secret review, documents any unresolved rights caveats, and is publicly visible.

## Governing principle

Preserve the engineering record. Remove the former occupants.

The architecture belongs in the public snapshot. Their data does not.
