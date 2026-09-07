# realTasia archive log

This log records the modern work used to publish the historical realTasia system. It exists so that editorial additions, safety rewrites and original material remain distinguishable.

## 4 September 2026 — public archive established

The `realtasia` GitHub organisation and its public `.github` repository were created as the front door for the archive.

| Change | Modern commit | Why |
|---|---|---|
| Organisation profile | [`465efb5`](https://github.com/realtasia/.github/commit/465efb5e935d8610e678cbbb555a881bd979b561) | Give the six-repository system one navigable public introduction. |
| Archive policy | [`fc555b2`](https://github.com/realtasia/.github/commit/fc555b22663b6c5e0f46b84af3c02f3c82294a4c) | State how history will be preserved and when privacy, security or rights require a rewrite. |
| Original orange wordmark restored | [`0935bf0`](https://github.com/realtasia/.github/commit/0935bf04a3f71411a0f5c39a1d2d4ba8d602ed1e) | Use the surviving period identity instead of manufacturing a tasteful 2026 hallucination. |
| Wordmark added to the profile | [`ca0c533`](https://github.com/realtasia/.github/commit/ca0c5333e08a64b68fdd66e395d0d72c3e29206a) | Put the original mark back on the product's public front door. |
| Initial organisation avatar attempt | GitHub organisation setting, 4 September 2026 | The complete wide wordmark was uploaded. GitHub's square crop reduced it to an unfortunate fragment resembling **al(**. Superseded after mobile review. |

### Logo provenance

The restored file is a byte-for-byte copy of `img/realtlogo5.png` from the private archival master of `app-rta`.

Its first visible Git provenance is the repository's 6 August 2013 import commit, “Removed weird unwanted stuff from repo” (`a1d8ac7`). The identifier is a private archival reference. That commit establishes when the asset entered this surviving Git history; it does not claim that the logo itself was designed that day.

The source and public copies have the same Git blob SHA:

```text
ddfed7c71f874d9cb2efbaf3a1c8cba9bd3e4d64
```

No tracing, redesign, enlargement, recolouring or generative reconstruction was applied.

## 4 September 2026 — public profile corrected after mobile review

Screenshots from GitHub's mobile view exposed several presentation and accuracy failures in the first profile: the brand casing was wrong, the relative logo URL failed, Mermaid appeared as source code, and the repository table did not fit the viewport.

| Change | Modern commit | Why |
|---|---|---|
| Mobile-safe display assets | [`3428e01`](https://github.com/realtasia/.github/commit/3428e0101cad3b010f2bb30473b0f644c5573fef) | Preserve the original artwork while providing a light-backed wordmark, square avatar crop and static architecture diagram that survive GitHub mobile and dark mode. |
| Profile rewritten | [`8f64c8e`](https://github.com/realtasia/.github/commit/8f64c8eba8aa0159dfddd5f04b85e295df8b8cf7) | Replace future promises with present-tense publication status, identify private-source claims honestly, restore canonical `realTasia` casing and remove mobile-hostile layout. |
| Policy casing corrected | [`f448a63`](https://github.com/realtasia/.github/commit/f448a634a6045f582b4733f8a8025998a99720d7) | Apply the historical `realTasia` styling consistently to public editorial material. |
| Archive-log casing corrected | [`0b4d3ad`](https://github.com/realtasia/.github/commit/0b4d3ad32f959c5349d527a4f3b684cfc469a7f8) | Correct the same editorial error in this publication record. |
| Organisation avatar corrected | GitHub organisation setting, 4 September 2026 | Replace the failed wide crop with the original circled **T**, mechanically extracted and placed on a light square for dark-mode contrast. |
| Organisation display name corrected | GitHub organisation setting, 4 September 2026 | Restore the canonical **realTasia** casing. The account handle remains GitHub's lowercase `realtasia`. |
| `.github` description corrected | GitHub repository metadata, 4 September 2026 | Replace the incorrect **RealtAsia** spelling and describe the repository as the archive's publication record. |

The untouched historical wordmark remains available separately. The light-backed header and square avatar are explicitly modern display derivatives made from that source because GitHub's dark theme and square crop otherwise conceal or mutilate it.

## 4 September 2026 — permanent publication voice adopted

The profile briefly described the archive through temporary workflow states such as “in progress”, “public now” and “not yet released”. That language would have made the permanent front door read like construction hoarding.

| Change | Modern commit | Why |
|---|---|---|
| Timeless organisation profile | [`4d7c1f4`](https://github.com/realtasia/.github/commit/4d7c1f4a6cf04595b97b989988b85ad7bd6d5784) | Present the archive from its completed state: six linked repositories, their commentary, their architecture and their provenance. |
| Timeless repository README | [`4da3e10`](https://github.com/realtasia/.github/commit/4da3e100c6d3f368fa2a06951763e68400a7d37a) | Remove operational status reporting from the repository's permanent public description. |

The archive has no ceremonial completion state. Its landing pages describe the record itself; ongoing publication work belongs in this log.

## 7 September 2026 — single-snapshot publication model adopted

The source-publication model was narrowed to minimise risk and avoid altering the private archival repositories. Each public source repository contains exactly one modern root commit holding a sanitised snapshot. Original commit objects, parent relationships, authorship metadata and historical file states are not published.

Private source repositories and their branches remain untouched. Transformation records, verification evidence and any source-to-snapshot mappings remain private because they can disclose the material removed from publication.

| Repository | Public snapshot commit | Publication note |
|---|---|---|
| [`app-rta`](https://github.com/realtasia/app-rta) | [`8431dab`](https://github.com/realtasia/app-rta/commit/8431dabd6c2d16bde490d1807061203b387cbb00) | Sanitised application snapshot |
| [`api-rta`](https://github.com/realtasia/api-rta) | [`4b87aea`](https://github.com/realtasia/api-rta/commit/4b87aea160a860c85a8e5d7057e4302710fed156) | Sanitised API snapshot |
| [`common-rta`](https://github.com/realtasia/common-rta) | [`fd54b4d`](https://github.com/realtasia/common-rta/commit/fd54b4d5d2d6a114859e3ef6e8ffca6312f46639) | Historical snapshot with unresolved third-party provenance documented in-repository |
| [`queue-rta`](https://github.com/realtasia/queue-rta) | [`1a09ee0`](https://github.com/realtasia/queue-rta/commit/1a09ee042425f7939cc9edeae602df790451528b) | Sanitised queue-worker snapshot |
| [`sockets-rta`](https://github.com/realtasia/sockets-rta) | [`938ac2d`](https://github.com/realtasia/sockets-rta/commit/938ac2ddf369fec215a093238fc3cd87cd417e93) | Historical snapshot with upstream provenance caveat documented in-repository |
| [`deployment-rta`](https://github.com/realtasia/deployment-rta) | [`b873a56`](https://github.com/realtasia/deployment-rta/commit/b873a56c7406e38eafc0dec88bd5f434c437564f) | Sanitised deployment snapshot |

All six final trees passed a checksum-verified Gitleaks v8.30.1 scan with no findings before publication. Each public repository was independently checked to contain one commit.

## Rules for future entries

Every public snapshot must record:

- the private source repository and source revision;
- the corresponding public snapshot commit;
- what changed;
- why the change was required;
- the verification applied before publication.

Routine documentation commits should identify themselves plainly as modern editorial work.
