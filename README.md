# Entity Sport (entitysport)

Entity Sport (Entity Digital Sports) provides real-time sports data APIs, with cricket as its flagship product. The Cricket API V2 delivers competitions and seasons, fixtures and results, ball-by-ball live scoring, detailed scorecards, fantasy points, player and team profiles, standings, and betting odds over a token-authenticated REST interface.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/entitysport/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/entitysport/refs/heads/main/apis.yml)

## Tags

- Sports Data
- Cricket
- Live Scores
- Fantasy
- Odds

## Timestamps

- **Created:** 2026-06-25
- **Modified:** 2026-06-25

## APIs

### Entity Sport Competitions API

Lists cricket competitions (tournaments, tours, cups) and seasons, and exposes per-competition matches and standings/points tables, keyed by the competition identifier cid and season identifier sid.

- **Human URL:** [https://www.doc.entitysport.com/cricket-api-v2](https://www.doc.entitysport.com/cricket-api-v2)
- **Base URL:** `https://restapi.entitysport.com/v2`

#### Tags

- Competitions
- Seasons
- Standings

#### Properties

- [Documentation](https://www.doc.entitysport.com/cricket-api-v2)
- [API Reference](https://www.doc.entitysport.com/cricket-api-v2)
- [OpenAPI](openapi/entitysport-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/entitysport.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/entitysport.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Entity Sport Matches & Live Scoring API

Lists fixtures, live, and completed matches and returns per-match info plus ball-by-ball live scoring keyed by the match identifier mid.

- **Human URL:** [https://www.doc.entitysport.com/cricket-api-v2](https://www.doc.entitysport.com/cricket-api-v2)
- **Base URL:** `https://restapi.entitysport.com/v2`

#### Tags

- Matches
- Live Scoring
- Ball by Ball

#### Properties

- [Documentation](https://www.doc.entitysport.com/cricket-api-v2)
- [OpenAPI](openapi/entitysport-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/entitysport.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/entitysport.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Entity Sport Scorecards API

Returns the full match scorecard with batting, bowling, and innings detail for a given match identifier mid.

- **Human URL:** [https://www.doc.entitysport.com/cricket-api-v2](https://www.doc.entitysport.com/cricket-api-v2)
- **Base URL:** `https://restapi.entitysport.com/v2`

#### Tags

- Scorecards
- Innings
- Statistics

#### Properties

- [Documentation](https://www.doc.entitysport.com/cricket-api-v2)
- [OpenAPI](openapi/entitysport-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/entitysport.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/entitysport.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Entity Sport Fantasy Points API

Serves Entity Sport fantasy cricket points for a match plus the pre-match fantasy squad/roster with player roles and fantasy credits, keyed by the match identifier mid.

- **Human URL:** [https://www.doc.entitysport.com/cricket-api-v2](https://www.doc.entitysport.com/cricket-api-v2)
- **Base URL:** `https://restapi.entitysport.com/v2`

#### Tags

- Fantasy
- Points
- Roster

#### Properties

- [Documentation](https://www.doc.entitysport.com/cricket-api-v2)
- [OpenAPI](openapi/entitysport-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/entitysport.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/entitysport.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Entity Sport Players & Teams API

Returns player profiles and career statistics keyed by player identifier pid, and team profiles and rosters keyed by team identifier tid.

- **Human URL:** [https://www.doc.entitysport.com/cricket-api-v2](https://www.doc.entitysport.com/cricket-api-v2)
- **Base URL:** `https://restapi.entitysport.com/v2`

#### Tags

- Players
- Teams
- Profiles

#### Properties

- [Documentation](https://www.doc.entitysport.com/cricket-api-v2)
- [OpenAPI](openapi/entitysport-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/entitysport.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/entitysport.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Entity Sport Odds API

Exposes live cricket betting odds and exchange data per match via the Cricket Exchange product, keyed by the match identifier mid.

- **Human URL:** [https://www.doc.entitysport.com/cricket-exchange](https://www.doc.entitysport.com/cricket-exchange)
- **Base URL:** `https://restapi.entitysport.com/v2`

#### Tags

- Odds
- Cricket Exchange
- Betting

#### Properties

- [Documentation](https://www.doc.entitysport.com/cricket-exchange)
- [OpenAPI](openapi/entitysport-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/entitysport.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/entitysport.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/entitysport)
- [LinkedIn](https://www.linkedin.com/company/entitysport)
- [Website](https://www.entitysport.com)
- [Documentation](https://www.doc.entitysport.com)
- [Plans](plans/entitysport-plans-pricing.yml)
- [Rate Limits](rate-limits/entitysport-rate-limits.yml)
- [Fin Ops](finops/entitysport-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
