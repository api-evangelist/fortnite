# Fortnite Tracker (fortnite)

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

**URL:** [Visit APIs.json URL](https://fortnitetracker.com/site-api)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Games And Comics, Public APIs, Fortnite, Player Statistics, Esports, Tracker Network

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-30

## APIs

### Fortnite Tracker

REST API exposing Fortnite player profiles, leaderboards, power rankings, store rotation, and challenges. All endpoints live under https://api.fortnitetracker.com/v1 and require a TRN-Api-Key header.

**Human URL:** [https://fortnitetracker.com/site-api](https://fortnitetracker.com/site-api)

#### Tags:

 - Games And Comics, Fortnite, Player Statistics

#### Properties

- [Documentation](https://fortnitetracker.com/site-api)
- [SignUp](https://fortnitetracker.com/site-api/create)
- [OpenAPI](openapi/fortnite-tracker.yaml)
- [NaftikoCapability — Profile](capabilities/fortnite-tracker-profile.yaml)
- [NaftikoCapability — Leaderboards](capabilities/fortnite-tracker-leaderboards.yaml)
- [NaftikoCapability — Power Rankings](capabilities/fortnite-tracker-power-rankings.yaml)
- [NaftikoCapability — Store](capabilities/fortnite-tracker-store.yaml)
- [NaftikoCapability — Challenges](capabilities/fortnite-tracker-challenges.yaml)

## Common Properties

- [Website](https://fortnitetracker.com/site-api)
- [PublicAPIsListing](https://github.com/public-apis/public-apis)
- [GitHubOrganization](https://github.com/TrackerNetwork)
- [DeveloperPortal](https://tracker.gg/developers)
- [Plans](plans/fortnite-plans-pricing.yml)
- [RateLimits](rate-limits/fortnite-rate-limits.yml)
- [FinOps](finops/fortnite-finops.yml)
- [Rules](rules/fortnite-spectral-rules.yml)
- [Vocabulary](vocabulary/fortnite-vocabulary.yaml)
- [JSONLD](json-ld/fortnite-tracker-context.jsonld)

## Features

| Name | Description |
|------|-------------|
| Player Lifetime Stats | Lifetime aggregate Battle Royale statistics (matches, wins, kills, K/D, score) per platform and username. |
| Regional Leaderboards | Top players by platform and region across global, NA, EU, and OCE cohorts. |
| Power Rankings | Competitive power rankings tracking professional Fortnite players' point totals across events. |
| Store Rotation | Snapshot of the rotating in-game item shop (daily and weekly storefronts) with prices in vBucks. |
| Weekly Challenges | Current Battle Pass weekly challenges list with completion criteria and rewards. |

## Use Cases

| Name | Description |
|------|-------------|
| Competitive Esports Dashboards | Aggregate professional player power-ranking standings into competitive Fortnite leaderboard sites and event broadcast graphics. |
| Player Profile Widgets | Embed lifetime player stat cards into community sites, Discord bots, and streaming overlays. |
| Store Tracking Bots | Poll the store endpoint on a schedule to notify players when specific cosmetics or returning skins appear in the daily rotation. |

## Integrations

| Name | Description |
|------|-------------|
| Epic Games Fortnite | Upstream source of all player telemetry; Tracker Network ingests Epic's player data and exposes a developer surface on top of it. |
| Discord Bots | Common consumer of the profile and store endpoints to render player cards and shop rotations in Discord servers. |
| Streaming Overlays | OBS and Streamlabs overlay widgets pull live stats from the profile endpoint during Fortnite streams. |

## Solutions

| Name | Description |
|------|-------------|
| Tracker Network Site Family | fortnitetracker.com is one of several Tracker Network properties (overwatch.tracker.gg, apex.tracker.gg, valorant.tracker.gg) that wrap game-publisher telemetry behind a uniform TRN-Api-Key surface. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Fortnite Tracker API](openapi/fortnite-tracker.yaml) — 7 operations across 5 tags (Profile, Leaderboards, Power Rankings, Store, Challenges); v1 surface with TRN-Api-Key header auth.

### JSON Schema

- [Challenge](json-schema/fortnite-tracker-challenge-schema.json)
- [LeaderboardEntry](json-schema/fortnite-tracker-leaderboard-entry-schema.json)
- [MatchSummary](json-schema/fortnite-tracker-match-summary-schema.json)
- [PlayerProfile](json-schema/fortnite-tracker-player-profile-schema.json)
- [PowerRankingDetail](json-schema/fortnite-tracker-power-ranking-detail-schema.json)
- [PowerRankingEntry](json-schema/fortnite-tracker-power-ranking-entry-schema.json)
- [StatBlock](json-schema/fortnite-tracker-stat-block-schema.json)
- [StatLine](json-schema/fortnite-tracker-stat-line-schema.json)
- [StatValue](json-schema/fortnite-tracker-stat-value-schema.json)
- [StoreItem](json-schema/fortnite-tracker-store-item-schema.json)

### JSON Structure

- [Challenge](json-structure/fortnite-tracker-challenge-structure.json)
- [LeaderboardEntry](json-structure/fortnite-tracker-leaderboard-entry-structure.json)
- [MatchSummary](json-structure/fortnite-tracker-match-summary-structure.json)
- [PlayerProfile](json-structure/fortnite-tracker-player-profile-structure.json)
- [PowerRankingDetail](json-structure/fortnite-tracker-power-ranking-detail-structure.json)
- [PowerRankingEntry](json-structure/fortnite-tracker-power-ranking-entry-structure.json)
- [StatBlock](json-structure/fortnite-tracker-stat-block-structure.json)
- [StatLine](json-structure/fortnite-tracker-stat-line-structure.json)
- [StatValue](json-structure/fortnite-tracker-stat-value-structure.json)
- [StoreItem](json-structure/fortnite-tracker-store-item-structure.json)

### JSON-LD

- [Fortnite Tracker Context](json-ld/fortnite-tracker-context.jsonld) — 9 type declarations and 56 property terms aligned with schema.org and Tracker Network's `ft:` namespace.

### Examples

- [Challenge](examples/fortnite-tracker-challenge-example.json)
- [LeaderboardEntry](examples/fortnite-tracker-leaderboard-entry-example.json)
- [MatchSummary](examples/fortnite-tracker-match-summary-example.json)
- [PlayerProfile](examples/fortnite-tracker-player-profile-example.json)
- [PowerRankingDetail](examples/fortnite-tracker-power-ranking-detail-example.json)
- [PowerRankingEntry](examples/fortnite-tracker-power-ranking-entry-example.json)
- [StatBlock](examples/fortnite-tracker-stat-block-example.json)
- [StatLine](examples/fortnite-tracker-stat-line-example.json)
- [StatValue](examples/fortnite-tracker-stat-value-example.json)
- [StoreItem](examples/fortnite-tracker-store-item-example.json)

## Capabilities

Naftiko capabilities organized as one self-contained file per OpenAPI tag, each declaring both a REST and an MCP exposer.

### Fortnite Tracker

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Profile](capabilities/fortnite-tracker-profile.yaml) | fortnite-tracker | 2 | community-developer, esports-analyst |
| [Leaderboards](capabilities/fortnite-tracker-leaderboards.yaml) | fortnite-tracker | 1 | community-developer, esports-analyst |
| [Power Rankings](capabilities/fortnite-tracker-power-rankings.yaml) | fortnite-tracker | 2 | esports-analyst, broadcast-producer |
| [Store](capabilities/fortnite-tracker-store.yaml) | fortnite-tracker | 1 | community-developer, cosmetics-collector |
| [Challenges](capabilities/fortnite-tracker-challenges.yaml) | fortnite-tracker | 1 | community-developer, casual-player |

## Vocabulary

- [Fortnite Vocabulary](vocabulary/fortnite-vocabulary.yaml) — Unified taxonomy mapping 5 resources, 2 actions, 5 workflows, and 5 personas across operational (OpenAPI) and capability (Naftiko) dimensions.

## Rules

- [Fortnite Tracker Spectral Rules](rules/fortnite-spectral-rules.yml) — 39 rules across 12 categories enforcing Fortnite Tracker API conventions (kebab-case paths, camelCase operationIds, TRN-Api-Key header auth, /v1 versioning).

## Plans

- [Fortnite Plans & Pricing](plans/fortnite-plans-pricing.yml) — Free tier (single key-gated tier) + Rate Limit Uplift via Tracker Network support.

## Rate Limits

- [Fortnite Rate Limits](rate-limits/fortnite-rate-limits.yml) — 1 request per 2 seconds per TRN-Api-Key; HTTP 429 on overage; discretionary key revocation policy.

## FinOps

- [Fortnite FinOps](finops/fortnite-finops.yml) — FOCUS 1.3-aligned FinOps profile; free tier with self-instrumented usage telemetry and per-key allocation.

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
