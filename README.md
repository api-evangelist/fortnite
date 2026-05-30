# Fortnite Tracker (fortnite)

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
