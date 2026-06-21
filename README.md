# RealtyMole (realtymole)

RealtyMole (Realty Mole Property API) is a US real-estate and property data API distributed primarily through RapidAPI. It returns property records, AVM-based rental estimates and sale-price (value) estimates with comparable properties, and active for-sale and for-rent listings by address or latitude/longitude. RealtyMole is the predecessor product to RentCast (rentcast.io); the standalone Realty Mole Property API on RapidAPI is legacy and superseded by the RentCast API.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/realtymole/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/realtymole/refs/heads/main/apis.yml)

> **Status note:** The Realty Mole Property API is legacy. RealtyMole rebranded/evolved into **RentCast** ([rentcast.io](https://www.rentcast.io/api), base URL `https://api.rentcast.io/v1`). New integrations should use the RentCast API; existing Realty Mole RapidAPI users should follow the [Realty Mole Migration Guide](https://developers.rentcast.io/reference/realty-mole-migration-guide). This catalog documents the Realty Mole Property API surface as historically distributed on RapidAPI and notes the RentCast successor throughout.

## Tags

- Real Estate
- Property Data
- Rental Estimate
- Valuation
- Listings

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### RealtyMole Property Records API

Look up residential property records by address or latitude/longitude, returning attributes such as property type, bedrooms, bathrooms, square footage, lot size, year built, last sale price/date, owner and assessor data.

- **Human URL:** [https://rapidapi.com/realtymole/api/realty-mole-property-api](https://rapidapi.com/realtymole/api/realty-mole-property-api)
- **Base URL:** `https://realty-mole-property-api.p.rapidapi.com`

#### Tags

- Property Data
- Property Records
- Real Estate

#### Properties

- [Documentation](https://rapidapi.com/realtymole/api/realty-mole-property-api)
- [API Reference](https://rapidapi.com/realtymole/api/realty-mole-property-api/details)
- [OpenAPI](openapi/realtymole-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/realtymole.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/realtymole.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### RealtyMole Rental Estimate API

Estimate the long-term monthly rent for a target property by address or latitude/longitude using a comparable-properties (AVM) algorithm, returning a rent estimate, a low/high range, and the comparable listings used.

- **Human URL:** [https://rapidapi.com/realtymole/api/realty-mole-property-api](https://rapidapi.com/realtymole/api/realty-mole-property-api)
- **Base URL:** `https://realty-mole-property-api.p.rapidapi.com`

#### Tags

- Rental Estimate
- AVM
- Comparables

#### Properties

- [Documentation](https://rapidapi.com/realtymole/api/realty-mole-property-api)
- [OpenAPI](openapi/realtymole-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/realtymole.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/realtymole.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### RealtyMole Sale Estimate API

Estimate the market sale price (value) of a target property by address or latitude/longitude using a comparable-sales (AVM) algorithm, returning a price estimate, a low/high range, and the comparable sales used.

- **Human URL:** [https://rapidapi.com/realtymole/api/realty-mole-property-api](https://rapidapi.com/realtymole/api/realty-mole-property-api)
- **Base URL:** `https://realty-mole-property-api.p.rapidapi.com`

#### Tags

- Valuation
- Sale Price
- AVM

#### Properties

- [Documentation](https://rapidapi.com/realtymole/api/realty-mole-property-api)
- [OpenAPI](openapi/realtymole-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/realtymole.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/realtymole.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### RealtyMole Listings API

Retrieve active for-sale and for-rent listings around a location (address or latitude/longitude with a radius), returning listing price, property attributes, days on market, and listing status.

- **Human URL:** [https://rapidapi.com/realtymole/api/realty-mole-property-api](https://rapidapi.com/realtymole/api/realty-mole-property-api)
- **Base URL:** `https://realty-mole-property-api.p.rapidapi.com`

#### Tags

- Listings
- For Sale
- For Rent

#### Properties

- [Documentation](https://rapidapi.com/realtymole/api/realty-mole-property-api)
- [OpenAPI](openapi/realtymole-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/realtymole.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/realtymole.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Authentication

The Realty Mole Property API is gated behind RapidAPI. Requests authenticate with RapidAPI headers:

- `X-RapidAPI-Key: <your-rapidapi-key>`
- `X-RapidAPI-Host: realty-mole-property-api.p.rapidapi.com`

The successor RentCast API authenticates instead with an `X-Api-Key` header against base URL `https://api.rentcast.io/v1`.

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/rentcast)
- [Website](https://www.realtymole.com)
- [Documentation](https://rapidapi.com/realtymole/api/realty-mole-property-api)
- [Plans](plans/realtymole-plans-pricing.yml)
- [Rate Limits](rate-limits/realtymole-rate-limits.yml)
- [Fin Ops](finops/realtymole-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
