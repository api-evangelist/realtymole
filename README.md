# RealtyMole (realtymole)

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
