# Geocodio (geocodio)

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

Geocodio is a US and Canada geocoding API that converts addresses to coordinates (forward), coordinates to addresses (reverse), processes batches and spreadsheet lists, and enriches results with appended data such as congressional and state legislative districts, census geographies, ACS demographics, school districts, and timezones. Authentication is via an api_key query parameter and the first 2,500 lookups per day are free.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/geocodio/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/geocodio/refs/heads/main/apis.yml)

## Tags

- Geocoding
- Reverse Geocoding
- Addresses
- Data Append
- Census

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Geocodio Forward Geocoding

Converts a single address (full string or components) into latitude and longitude with normalized address components, accuracy score, and accuracy type, optionally enriched with appended data fields.

- **Human URL:** [https://www.geocod.io/docs/#geocoding](https://www.geocod.io/docs/#geocoding)
- **Base URL:** `https://api.geocod.io/v1.7`

#### Tags

- Geocoding
- Addresses
- Coordinates

#### Properties

- [Documentation](https://www.geocod.io/docs/#geocoding)
- [API Reference](https://www.geocod.io/docs/)
- [OpenAPI](openapi/geocodio-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/geocodio.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/geocodio.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Geocodio Reverse Geocoding

Converts a single latitude and longitude coordinate pair into the nearest matching street address, optionally enriched with appended data fields.

- **Human URL:** [https://www.geocod.io/docs/#reverse-geocoding](https://www.geocod.io/docs/#reverse-geocoding)
- **Base URL:** `https://api.geocod.io/v1.7`

#### Tags

- Reverse Geocoding
- Coordinates
- Addresses

#### Properties

- [Documentation](https://www.geocod.io/docs/#reverse-geocoding)
- [OpenAPI](openapi/geocodio-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/geocodio.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/geocodio.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Geocodio Batch Geocoding

Geocodes or reverse geocodes up to 10,000 addresses or coordinates in a single synchronous POST request using a JSON array or keyed JSON object.

- **Human URL:** [https://www.geocod.io/docs/#batch-geocoding](https://www.geocod.io/docs/#batch-geocoding)
- **Base URL:** `https://api.geocod.io/v1.7`

#### Tags

- Batch
- Geocoding
- Bulk

#### Properties

- [Documentation](https://www.geocod.io/docs/#batch-geocoding)
- [OpenAPI](openapi/geocodio-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/geocodio.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/geocodio.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Geocodio Data Appends

Enriches geocoding and reverse geocoding results via the fields parameter with congressional districts, state legislative districts, census geographies and FIPS codes, ACS demographics, school districts, timezone, ZIP+4, and Canadian electoral data; each requested field counts as an additional lookup.

- **Human URL:** [https://www.geocod.io/docs/#fields](https://www.geocod.io/docs/#fields)
- **Base URL:** `https://api.geocod.io/v1.7`

#### Tags

- Data Append
- Census
- Congressional Districts

#### Properties

- [Documentation](https://www.geocod.io/docs/#fields)
- [OpenAPI](openapi/geocodio-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/geocodio.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/geocodio.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Geocodio Lists

Asynchronously geocodes uploaded spreadsheet files (CSV, TSV, Excel) as a list job, with endpoints to create, list, check status, download results, and delete the job, plus optional webhook callbacks.

- **Human URL:** [https://www.geocod.io/docs/#lists](https://www.geocod.io/docs/#lists)
- **Base URL:** `https://api.geocod.io/v1.7`

#### Tags

- Lists
- Spreadsheet
- Async

#### Properties

- [Documentation](https://www.geocod.io/docs/#lists)
- [OpenAPI](openapi/geocodio-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/geocodio.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/geocodio.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/Geocodio)
- [LinkedIn](https://www.linkedin.com/company/geocodio)
- [Website](https://www.geocod.io)
- [Documentation](https://www.geocod.io/docs/)
- [Plans](plans/geocodio-plans-pricing.yml)
- [Rate Limits](rate-limits/geocodio-rate-limits.yml)
- [Fin Ops](finops/geocodio-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
