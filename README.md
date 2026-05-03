# SeatGeek (seatgeek)

SeatGeek is a live event ticketing and discovery platform that aggregates ticket inventory from multiple sources and provides a transparent, data-driven ticket buying experience. The SeatGeek Platform API gives developers access to a canonical dataset of live events including concerts, sports, and theater performances, along with performer and venue information, seating maps, ticket pricing, and personalized event recommendations. The API uses HTTP Basic Auth or query parameter authentication with a client ID and supports RESTful access to events, performers, venues, and taxonomies.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/seatgeek/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
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
- **Modified:** 2026-05-02

## APIs

### SeatGeek Platform API

The SeatGeek Platform API provides access to SeatGeek's comprehensive dataset of live events in the United States and Canada. The API enables developers to search events, performers, and venues, retrieve seat maps, get event recommendations, and deep-link users directly to the SeatGeek ticketing purchase flow. It supports JSON, JSONP, and XML response formats, with pagination, geolocation filtering, and price-range filtering across all event types.

#### Properties

- [OpenAPI](openapi/seatgeek-platform-openapi.yml)
- [Documentation](https://seatgeek.github.io/)
- [Developer Portal](https://seatgeek.com/build)

## Common Properties

- [Website](https://seatgeek.com)
- [Developer Portal](https://seatgeek.com/build)
- [API Documentation](https://seatgeek.github.io/)
- [GitHub Organization](https://github.com/seatgeek)
- [iOS SDK](https://github.com/seatgeek/SGAPI)
- [API Support](https://github.com/seatgeek/api-support)
- [API Terms](https://seatgeek.com/api-terms)

## Artifacts

### JSON Schema

- [Event Schema](json-schema/seatgeek-event-schema.json)

### JSON Structure

- [Event Structure](json-structure/seatgeek-event-structure.json)

### JSON-LD

- [Context](json-ld/seatgeek-context.jsonld)

### Examples

- [List Events](examples/seatgeek-list-events-example.json)

### Rules

- [Spectral Ruleset](rules/seatgeek-rules.yml)

### Capabilities

- [Event Discovery](capabilities/event-discovery.yaml)
  - Shared: [Platform](capabilities/shared/platform.yaml)

### Vocabulary

- [SeatGeek Vocabulary](vocabulary/seatgeek-vocabulary.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
