<div align="center">

<img src="https://raw.githubusercontent.com/realtasia/.github/main/profile/assets/realtasia-orange-card.png" alt="Original realTasia orange wordmark" width="360">

# realTasia

### The Right Now Real Estate

**A live social-property platform built and operated in Singapore. Its surviving Git history runs from 2012 to 2014.**

![Period](https://img.shields.io/badge/surviving_history-2012%E2%80%932014-7c3aed)
![Repositories](https://img.shields.io/badge/system-6_repositories-2563eb)
![Status](https://img.shields.io/badge/status-preserved_archive-d97706)
![Source](https://img.shields.io/badge/source-pre--AI-059669)

</div>

This is the public source archive of realTasia: six repositories, their surviving histories, and modern technical commentary tied to the commits it discusses.

## What was realTasia?

realTasia was a working property network, social graph and real-estate marketplace. It ran as one distributed product across six repositories.

It was not a mock-up, a pitch deck or an abandoned weekend prototype. People, property listings, companies, conversations, feeds, notifications, subscriptions, testimonials, media, sales attribution and paid registration all belonged to the same operating system.

The source includes:

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

## The system

<img src="https://raw.githubusercontent.com/realtasia/.github/main/profile/assets/system-map.svg" alt="Architecture map of the six realTasia repositories" width="640">

The diagram is a modern reading aid. The architecture is historical.

## The six repositories

### [`app-rta`](https://github.com/realtasia/app-rta)

The product itself: the hybrid PHP and JavaScript application, browser-side domain model, listing workflow, conversations, search, media and interface behaviour.

[Read the annotated commit history](https://github.com/realtasia/app-rta/blob/main/COMMIT_COMMENTARY.md)

### [`api-rta`](https://github.com/realtasia/api-rta)

OAuth, resources, permissions, interactions and the rules connecting people, companies, properties and activity.

[Read the annotated commit history](https://github.com/realtasia/api-rta/blob/main/COMMIT_COMMENTARY.md)

### [`common-rta`](https://github.com/realtasia/common-rta)

Shared framework and domain code, including Ticker feed materialisation and the notification machinery used by the API and workers.

[Read the annotated commit history](https://github.com/realtasia/common-rta/blob/main/COMMIT_COMMENTARY.md)

### [`queue-rta`](https://github.com/realtasia/queue-rta)

Durable asynchronous work: projecting social activity into feeds, constructing recipient-specific notifications and dispatching downstream delivery.

[Read the annotated commit history](https://github.com/realtasia/queue-rta/blob/main/COMMIT_COMMENTARY.md)

### [`sockets-rta`](https://github.com/realtasia/sockets-rta)

The narrow live-delivery edge between durable notification state and connected browsers. A small service displaying the increasingly rare discipline of knowing exactly what it was for.

[Read the annotated commit history](https://github.com/realtasia/sockets-rta/blob/main/COMMIT_COMMENTARY.md)

### [`deployment-rta`](https://github.com/realtasia/deployment-rta)

Provisioning, Nginx, process management, S3 delivery and the automation that turned six repositories into a running product.

[Read the annotated commit history](https://github.com/realtasia/deployment-rta/blob/main/COMMIT_COMMENTARY.md)

## Where to start

1. **[`app-rta`](https://github.com/realtasia/app-rta)** for the complete product and its substantial JavaScript application.
2. **[`api-rta`](https://github.com/realtasia/api-rta)** for the resource grammar, OAuth boundary and social interaction model.
3. **[`common-rta`](https://github.com/realtasia/common-rta)** for the shared domain, Ticker and notification records.
4. **[`queue-rta`](https://github.com/realtasia/queue-rta)** for the asynchronous consequences of social activity.
5. **[`sockets-rta`](https://github.com/realtasia/sockets-rta)** for the hundred-line service that understood its job.
6. **[`deployment-rta`](https://github.com/realtasia/deployment-rta)** for the point where source code became somebody's problem at three in the morning.

For one system explained from end to end, read [The Invisible CDN We Built in 2012 for Dynamic Avatars](https://geekist.co/the-invisible-cdn-we-built-in-2012-for-dynamic-avatars/).

## Why the dates matter

The OAuth implementation appears in commits dated 20–22 October 2012. [RFC 6749 was published in October 2012](https://www.rfc-editor.org/info/rfc6749/).

The resource and interaction architecture was already developing before [React's first public release on 29 May 2013](https://react.dev/versions). The substantial Knockout application grew while today's component-era frontend vocabulary was only beginning to form.

The archive does not use those dates to retrofit novelty. It preserves the code, the decisions and the record of when they were made.

## Provenance

The public repositories are privacy-sanitised mirrors of sealed archival masters. Commit dates, messages, authorship and parent relationships are preserved wherever the contents permit.

Sanitisation changes a commit SHA. Every necessary deviation records:

1. the original archival commit;
2. the corresponding public commit;
3. what changed and why;
4. whether dates, authorship, messages or topology were affected.

Modern commentary identifies itself as modern and links to the public commits it discusses. Historical source remains historical source.

The original orange wordmark demonstrates the standard. Its public copy is byte-for-byte identical to the asset in the archival `app-rta` master. Both have Git blob SHA `ddfed7c71f874d9cb2efbaf3a1c8cba9bd3e4d64`.

Read the [archive and editorial policy](https://github.com/realtasia/.github/blob/main/ARCHIVE_POLICY.md) and the [publication log](https://github.com/realtasia/.github/blob/main/ARCHIVE_LOG.md).

---

<div align="center">

Original engineering by [Jason Nathan](https://github.com/pipewrk).

**Preserved with its timestamps, architecture and magnificent commit messages intact.**

</div>
