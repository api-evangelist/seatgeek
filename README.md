# SeatGeek (seatgeek)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

SeatGeek is a live event ticketing and discovery platform that aggregates ticket inventory from multiple sources and provides a transparent, data-driven ticket buying experience. The SeatGeek Platform API gives developers access to a canonical dataset of live events including concerts, sports, and theater performances, along with performer and venue information, seating maps, ticket pricing, and personalized event recommendations. The API uses HTTP Basic Auth or query parameter authentication with a client ID and supports RESTful access to events, performers, venues, and taxonomies.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/seatgeek/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/seatgeek/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Events
- Tickets
- Live Events
- Concerts
- Sports
- Venues
- Ticketing

## Timestamps

- **Created:** 2026-05-02
- **Modified:** 2026-05-19

## APIs

### SeatGeek Platform API

The SeatGeek Platform API provides access to SeatGeek's comprehensive dataset of live events in the United States and Canada. The API enables developers to search events, performers, and venues, retrieve seat maps, get event recommendations, and deep-link users directly to the SeatGeek ticketing purchase flow. It supports JSON, JSONP, and XML response formats, with pagination, geolocation filtering, and price-range filtering across all event types including sports, concerts, and theater.

- **Human URL:** [https://seatgeek.com/build](https://seatgeek.com/build)
- **Base URL:** `https://api.seatgeek.com/2`

#### Tags

- Events
- Tickets
- Performers
- Venues
- Live Events

#### Properties

- [OpenAPI](openapi/seatgeek-platform-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/seatgeek-platform.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/seatgeek-platform.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://seatgeek.github.io/)
- [Portal](https://seatgeek.com/build)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/seatgeek)
- [Website](https://seatgeek.com)
- [Portal](https://seatgeek.com/build)
- [Documentation](https://seatgeek.github.io/)
- [GitHub Organization](https://github.com/seatgeek)
- [SDK](https://github.com/seatgeek/SGAPI)
- [Support](https://github.com/seatgeek/api-support)
- [Terms of Service](https://seatgeek.com/api-terms)
- [JSON Schema](json-schema/seatgeek-event-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/seatgeek-event-structure.json)
- [J S O N L D Context](json-ld/seatgeek-context.jsonld)
- [Example](examples/seatgeek-list-events-example.json)
- [Spectral Ruleset](rules/seatgeek-rules.yml)
- [Vocabulary](vocabulary/seatgeek-vocabulary.yml)
- [M C P Server](https://github.com/seatgeek/mcp-pdb)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
