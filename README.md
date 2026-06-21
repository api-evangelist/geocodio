# Geocodio (geocodio)

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
