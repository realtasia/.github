<div align="center">

<img src="https://raw.githubusercontent.com/realtasia/.github/main/profile/assets/realtasia-orange-card.png" alt="Original realTasia orange wordmark" width="360">

# realTasia

### The Right Now Real Estate

**A live social-property platform built and operated in Singapore. Its surviving Git history runs from 2012 to 2014.**

![Period](https://img.shields.io/badge/surviving_history-2012%E2%80%932014-7c3aed)
![Repositories](https://img.shields.io/badge/system-6_repositories-2563eb)
![Status](https://img.shields.io/badge/status-archive_in_progress-d97706)
![Source](https://img.shields.io/badge/source-pre--AI-059669)

</div>

> [!IMPORTANT]
> **This is a public archive in progress.** The organisation profile, publication policy, archive log and original wordmark are public. The six historical source repositories remain private while every reachable revision is checked for credentials, production data, personal information and third-party material. They are not yet offered here as public evidence.

## What was realTasia?

realTasia was a working property network, social graph and real-estate marketplace. It ran as a distributed product across six repositories.

It was not a mock-up, a pitch deck or an abandoned weekend prototype. People, property listings, companies, conversations, feeds, notifications, subscriptions, testimonials, media, sales attribution and paid registration all belonged to the same operating system.

The surviving source contains:

- a hand-built OAuth 2 service;
- capability-driven API resources;
- polymorphic browser-side domain models;
- bidirectional likes and subscriptions;
- a materialised personal feed called Ticker;
- durable background jobs and per-recipient notifications;
- email and live Socket.IO delivery;
- property listings modelled as social objects;
- conversations, testimonials and professional profiles;
- a six-stage property-listing editor;
- chunked media ingestion, image derivation and S3 storage;
- stable avatar URLs resolved through Nginx and S3;
- salesperson attribution through short presentation and signup tokens;
- paid registration and PayPal IPN processing;
- reproducible Ubuntu provisioning and repository-driven deployment.

That list describes the historical code in the private archival masters. It is an editorial inventory, dated 2026. It is not being passed off as text written during the product's operation.

## Archive status

### Public now

- this organisation profile;
- the [archive and editorial policy](https://github.com/realtasia/.github/blob/main/ARCHIVE_POLICY.md);
- the [archive log](https://github.com/realtasia/.github/blob/main/ARCHIVE_LOG.md);
- the original orange wordmark and its recorded provenance;
- [The Invisible CDN We Built in 2012 for Dynamic Avatars](https://geekist.co/the-invisible-cdn-we-built-in-2012-for-dynamic-avatars/), a public technical account of one part of the system.

### Preserved privately

- all six original repository histories;
- their commit dates, messages, authorship and topology;
- modern annotated commit commentaries maintained separately from the historical source;
- the material required to construct privacy-sanitised public mirrors.

No source repository is described as published until its sanitised history can actually be inspected in this organisation.

## The system

<img src="https://raw.githubusercontent.com/realtasia/.github/main/profile/assets/system-map.svg" alt="Architecture map of the six realTasia repositories" width="640">

The diagram is a modern reading aid. It describes relationships found in the historical source; it is not a recovered period artefact.

## The six repositories

### `app-rta`

The product itself: the hybrid PHP and JavaScript application, browser-side domain model, listing workflow, conversations, search, media and interface behaviour.

**Archive state:** private master preserved; public mirror not released.

### `api-rta`

OAuth, resources, permissions, interactions and the rules connecting people, companies, properties and activity.

**Archive state:** private master preserved; public mirror not released.

### `common-rta`

Shared framework and domain code, including Ticker feed materialisation and the notification machinery used by the API and workers.

**Archive state:** private master preserved; public mirror not released.

### `queue-rta`

Durable asynchronous work: projecting social activity into feeds, constructing recipient-specific notifications and dispatching downstream delivery.

**Archive state:** private master preserved; public mirror not released.

### `sockets-rta`

The narrow live-delivery edge between durable notification state and connected browsers. A small service displaying the increasingly rare discipline of knowing exactly what it was for.

**Archive state:** private master preserved; public mirror not released.

### `deployment-rta`

Provisioning, Nginx, process management, S3 delivery and the automation that turned six repositories into a running product.

**Archive state:** private master preserved; public mirror not released.

## Why the dates matter

The surviving OAuth implementation appears in private commits dated 20–22 October 2012. [RFC 6749 was published in October 2012](https://www.rfc-editor.org/info/rfc6749/).

The resource and interaction architecture was already developing before [React's first public release on 29 May 2013](https://react.dev/versions). The substantial Knockout application grew while today's component-era frontend vocabulary was only beginning to form.

Those are observations from the preserved masters. They become independently checkable only when the relevant sanitised histories are public. Until then, they are labelled here for what they are.

## Provenance without theatre

The private masters remain untouched. Public mirrors require history rewriting wherever a reachable revision exposes personal data, credentials or material that cannot responsibly be republished.

A rewritten commit receives a new SHA. The publication record therefore keeps:

1. the original private commit;
2. the corresponding public commit;
3. the reason the contents changed;
4. whether dates, authorship, messages or parent relationships were affected.

The objective is maximum historical fidelity subject to privacy, security and rights. The code is not being modernised to flatter its author, and the defects are not being polished out of existence.

The original orange wordmark demonstrates the approach. Its public copy is byte-for-byte identical to the asset in the private `app-rta` master, and both have Git blob SHA `ddfed7c71f874d9cb2efbaf3a1c8cba9bd3e4d64`. Its surviving Git provenance and modern publication are recorded in the [archive log](https://github.com/realtasia/.github/blob/main/ARCHIVE_LOG.md).

---

<div align="center">

Original engineering by [Jason Nathan](https://github.com/pipewrk).

**Preserved with its timestamps, architecture and magnificent commit messages intact.**

</div>
