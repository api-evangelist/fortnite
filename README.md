# Fortnite Tracker

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Fortnite Tracker, by Tracker Network, exposes a small REST API surface (api.fortnitetracker.com/v1) covering player profile lifetime stats, regional leaderboards, competitive power rankings, the rotating in-game store, and the weekly challenges feed for Fortnite. Authentication is a single TRN-Api-Key header obtained from the Fortnite Tracker site. The service has reached a silent end-of-life in recent years (some endpoints are intermittently unavailable) but remains the canonical community profile of how Tracker Network packages Epic Games' Fortnite telemetry as a developer API.

**Areas:** Public APIs · Fortnite · Player Statistics · Esports · Tracker Network · Gaming · Video Games

## Fortnite Tracker on APIs.io

Everything profiled for Fortnite Tracker is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/fortnite/](https://apis.io/providers/fortnite/)** — or go straight to one of the APIs or properties below.

### APIs (5)

- [Fortnite Tracker Challenges API](https://apis.io/apis/fortnite/fortnite-challenges-api/) — Current Battle Pass weekly challenges.
- [Fortnite Tracker Leaderboards API](https://apis.io/apis/fortnite/fortnite-leaderboards-api/) — Top-player leaderboards by platform and region.
- [Fortnite Tracker Power Rankings API](https://apis.io/apis/fortnite/fortnite-power-rankings-api/) — Competitive Fortnite power rankings across professional events.
- [Fortnite Tracker Profile API](https://apis.io/apis/fortnite/fortnite-profile-api/) — Per-player Fortnite lifetime and per-mode statistics.
- [Fortnite Tracker Store API](https://apis.io/apis/fortnite/fortnite-store-api/) — Current Fortnite in-game store rotation.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Fortnite Agentic Access](https://apis.io/agentic-access/fortnite/fortnite-agentic-access/)

#### JSON Schema (10)

The data models the API reads and writes.

- [Challenge](https://apis.io/schemas/fortnite/fortnite-tracker-challenge/)
- [LeaderboardEntry](https://apis.io/schemas/fortnite/fortnite-tracker-leaderboard-entry/)
- [MatchSummary](https://apis.io/schemas/fortnite/fortnite-tracker-match-summary/)
- [PlayerProfile](https://apis.io/schemas/fortnite/fortnite-tracker-player-profile/)
- [PowerRankingDetail](https://apis.io/schemas/fortnite/fortnite-tracker-power-ranking-detail/)
- [PowerRankingEntry](https://apis.io/schemas/fortnite/fortnite-tracker-power-ranking-entry/)
- [StatBlock](https://apis.io/schemas/fortnite/fortnite-tracker-stat-block/)
- [StatLine](https://apis.io/schemas/fortnite/fortnite-tracker-stat-line/)
- [StatValue](https://apis.io/schemas/fortnite/fortnite-tracker-stat-value/)
- [StoreItem](https://apis.io/schemas/fortnite/fortnite-tracker-store-item/)

#### JSON Structure (10)

Data models expressed in JSON Structure.

- [Fortnite Tracker Challenge Structure](https://apis.io/json-structure/fortnite/fortnite-tracker-challenge-structure/)
- [Fortnite Tracker Leaderboard Entry Structure](https://apis.io/json-structure/fortnite/fortnite-tracker-leaderboard-entry-structure/)
- [Fortnite Tracker Match Summary Structure](https://apis.io/json-structure/fortnite/fortnite-tracker-match-summary-structure/)
- [Fortnite Tracker Player Profile Structure](https://apis.io/json-structure/fortnite/fortnite-tracker-player-profile-structure/)
- [Fortnite Tracker Power Ranking Detail Structure](https://apis.io/json-structure/fortnite/fortnite-tracker-power-ranking-detail-structure/)
- [Fortnite Tracker Power Ranking Entry Structure](https://apis.io/json-structure/fortnite/fortnite-tracker-power-ranking-entry-structure/)
- [Fortnite Tracker Stat Block Structure](https://apis.io/json-structure/fortnite/fortnite-tracker-stat-block-structure/)
- [Fortnite Tracker Stat Line Structure](https://apis.io/json-structure/fortnite/fortnite-tracker-stat-line-structure/)
- [Fortnite Tracker Stat Value Structure](https://apis.io/json-structure/fortnite/fortnite-tracker-stat-value-structure/)
- [Fortnite Tracker Store Item Structure](https://apis.io/json-structure/fortnite/fortnite-tracker-store-item-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Fortnite Tracker Context](https://apis.io/jsonld/fortnite/fortnite-tracker-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Fortnite Vocabulary](https://apis.io/vocabularies/fortnite/fortnite-vocabulary/)

#### Examples (10)

Example requests and responses.

- [Fortnite Tracker Challenge Example](https://apis.io/examples/fortnite/fortnite-tracker-challenge-example/)
- [Fortnite Tracker Leaderboard Entry Example](https://apis.io/examples/fortnite/fortnite-tracker-leaderboard-entry-example/)
- [Fortnite Tracker Match Summary Example](https://apis.io/examples/fortnite/fortnite-tracker-match-summary-example/)
- [Fortnite Tracker Player Profile Example](https://apis.io/examples/fortnite/fortnite-tracker-player-profile-example/)
- [Fortnite Tracker Power Ranking Detail Example](https://apis.io/examples/fortnite/fortnite-tracker-power-ranking-detail-example/)
- [Fortnite Tracker Power Ranking Entry Example](https://apis.io/examples/fortnite/fortnite-tracker-power-ranking-entry-example/)
- [Fortnite Tracker Stat Block Example](https://apis.io/examples/fortnite/fortnite-tracker-stat-block-example/)
- [Fortnite Tracker Stat Line Example](https://apis.io/examples/fortnite/fortnite-tracker-stat-line-example/)
- [Fortnite Tracker Stat Value Example](https://apis.io/examples/fortnite/fortnite-tracker-stat-value-example/)
- [Fortnite Tracker Store Item Example](https://apis.io/examples/fortnite/fortnite-tracker-store-item-example/)

#### Collections (5)

Postman and Open Collection request collections.

- [Fortnite Tracker Challenges API](https://apis.io/collections/fortnite/open-fortnite-challenges-api/)
- [Fortnite Tracker Challenges Leaderboards API](https://apis.io/collections/fortnite/open-fortnite-leaderboards-api/)
- [Fortnite Tracker Challenges Power Rankings API](https://apis.io/collections/fortnite/open-fortnite-power-rankings-api/)
- [Fortnite Tracker Challenges Profile API](https://apis.io/collections/fortnite/open-fortnite-profile-api/)
- [Fortnite Tracker Challenges Store API](https://apis.io/collections/fortnite/open-fortnite-store-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Fortnite Tracker — jsonschema rules](https://apis.io/rules/fortnite/fortnite-jsonschema-spectral-rules/)
- [Fortnite Tracker API Rules](https://apis.io/rules/fortnite/fortnite-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Fortnite Authentication](https://apis.io/security/fortnite/fortnite-authentication/)
- [Fortnite Domain Security](https://apis.io/security/fortnite/fortnite-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Fortnite Plans Pricing](https://apis.io/plans/fortnite/fortnite-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Fortnite Rate Limits](https://apis.io/rate-limits/fortnite/fortnite-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Fortnite Finops](https://apis.io/finops/fortnite/fortnite-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://fortnitetracker.com/site-api)
- [GitHub](https://github.com/TrackerNetwork)

## API Evangelist rating

**Kin Score 27.7** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 78.6 |
| Contract quality | 21.7 |
| Contract governance | 27.3 |
| Operational transparency | 7.9 |
| Developer ergonomics | 31.0 |
| Access clarity | 18.4 |

**Agent readiness 33.2** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | na |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | na |
| Error Semantics | verified |
| OpenAPI Examples | verified |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | na |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 16.7** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/fortnite/](https://apis.io/providers/fortnite/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Fortnite Tracker: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/fortnite/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
