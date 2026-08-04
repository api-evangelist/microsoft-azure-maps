# Azure Maps (microsoft-azure-maps)

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

Azure Maps provides geospatial APIs for maps, routing, geocoding, traffic, weather, and spatial analysis. The service offers a comprehensive suite of REST APIs to embed location intelligence into applications spanning mobile, web, and IoT scenarios across multiple transport modes.

**APIs.json:** [https://azure.microsoft.com/en-us/services/azure-maps/](https://azure.microsoft.com/en-us/services/azure-maps/)

## Tags

- Geocoding
- Geospatial
- Location
- Maps
- Mobility
- Routing
- Traffic
- Weather

## Timestamps

- **Created:** 2026-03-13
- **Modified:** 2026-05-19

## APIs

### Azure Maps Search API

Provides geocoding, reverse geocoding, address parsing, point of interest search, and structured search. Returns candidate matches ranked by relevance for free-form, structured, and POI queries with worldwide coverage.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/maps/search](https://learn.microsoft.com/en-us/rest/api/maps/search)
- **Base URL:** `https://atlas.microsoft.com`

#### Tags

- Address
- Geocoding
- POI
- Reverse Geocoding
- Search

#### Properties

- [OpenAPI](openapi/microsoft-azure-maps-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/microsoft-azure-maps.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-azure-maps.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://learn.microsoft.com/en-us/rest/api/maps/search)
- [Authentication](https://learn.microsoft.com/en-us/azure/azure-maps/azure-maps-authentication)
- [Getting Started](https://learn.microsoft.com/en-us/azure/azure-maps/how-to-use-search-service)

### Azure Maps Route API

Calculates routes between origin and destination, provides turn-by-turn directions, supports multiple travel modes, traffic-aware routing, route matrices, and route range (isochrone) calculations.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/maps/route](https://learn.microsoft.com/en-us/rest/api/maps/route)
- **Base URL:** `https://atlas.microsoft.com`

#### Tags

- Directions
- Isochrone
- Routing
- Traffic-Aware
- Travel Modes

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/maps/route)
- [Getting Started](https://learn.microsoft.com/en-us/azure/azure-maps/how-to-use-best-practices-for-routing)
- [Postman Collection](collections/microsoft-azure-maps.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-azure-maps.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure Maps Render API

Returns map tiles, static images, and vector tiles in multiple styles including satellite, road, and hybrid. Supports raster and vector tile formats, custom imagery, and traffic overlays for embedding maps into applications.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/maps/render](https://learn.microsoft.com/en-us/rest/api/maps/render)
- **Base URL:** `https://atlas.microsoft.com`

#### Tags

- Map Tiles
- Raster
- Render
- Static Images
- Vector Tiles

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/maps/render)
- [Reference](https://learn.microsoft.com/en-us/azure/azure-maps/zoom-levels-and-tile-grid)
- [Postman Collection](collections/microsoft-azure-maps.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-azure-maps.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure Maps Traffic API

Provides real-time and historical traffic data including traffic flow, incident reports, and traffic tile imagery. Useful for routing, fleet management, and applications requiring up-to-date road conditions.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/maps/traffic](https://learn.microsoft.com/en-us/rest/api/maps/traffic)
- **Base URL:** `https://atlas.microsoft.com`

#### Tags

- Flow
- Incidents
- Real-Time
- Traffic

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/maps/traffic)
- [Reference](https://learn.microsoft.com/en-us/azure/azure-maps/traffic-coverage)
- [Postman Collection](collections/microsoft-azure-maps.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-azure-maps.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure Maps Weather API

Provides current weather conditions, hourly and daily forecasts, severe weather alerts, weather along a route, and historical weather. Powered by AccuWeather data and global coverage.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/maps/weather](https://learn.microsoft.com/en-us/rest/api/maps/weather)
- **Base URL:** `https://atlas.microsoft.com`

#### Tags

- Alerts
- Forecast
- Historical
- Weather

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/maps/weather)
- [Reference](https://learn.microsoft.com/en-us/azure/azure-maps/weather-coverage)
- [Postman Collection](collections/microsoft-azure-maps.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-azure-maps.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure Maps Timezone API

Returns time zone information for a given coordinate, IANA time zone ID, or Windows time zone ID. Includes current time, daylight saving offsets, and time zone metadata.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/maps/timezone](https://learn.microsoft.com/en-us/rest/api/maps/timezone)
- **Base URL:** `https://atlas.microsoft.com`

#### Tags

- DST
- IANA
- Time Zone
- UTC Offset

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/maps/timezone)
- [Postman Collection](collections/microsoft-azure-maps.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-azure-maps.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure Maps Geolocation API

Returns the ISO country code for a supplied IP address, useful for content localization, regulatory compliance, and access control based on user geographic location.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/maps/geolocation](https://learn.microsoft.com/en-us/rest/api/maps/geolocation)
- **Base URL:** `https://atlas.microsoft.com`

#### Tags

- Country Code
- Geolocation
- IP Address
- Localization

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/maps/geolocation)
- [Postman Collection](collections/microsoft-azure-maps.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-azure-maps.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure Maps Spatial API

Performs spatial computations such as distance, closest point, point in polygon, geofence evaluation, and great circle distance. Enables location analytics and spatial reasoning workloads.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/maps/spatial](https://learn.microsoft.com/en-us/rest/api/maps/spatial)
- **Base URL:** `https://atlas.microsoft.com`

#### Tags

- Geofencing
- Point in Polygon
- Spatial Analysis
- Spatial Operations

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/maps/spatial)
- [Reference](https://learn.microsoft.com/en-us/azure/azure-maps/geofence-geojson)
- [Postman Collection](collections/microsoft-azure-maps.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-azure-maps.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure Maps Elevation API

Returns elevation data in meters above sea level for points, polylines, and bounding boxes. Useful for terrain analysis, topographic visualization, and elevation profile calculations along a route.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/maps/elevation](https://learn.microsoft.com/en-us/rest/api/maps/elevation)
- **Base URL:** `https://atlas.microsoft.com`

#### Tags

- DEM
- Elevation
- Terrain
- Topography

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/maps/elevation)
- [Postman Collection](collections/microsoft-azure-maps.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-azure-maps.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure Maps Creator API

Indoor maps service for creating, managing, and rendering custom indoor maps. Supports drawing package conversion, dataset and tileset management, feature state, and wayfinding for indoor environments.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/maps/creator](https://learn.microsoft.com/en-us/rest/api/maps/creator)
- **Base URL:** `https://atlas.microsoft.com`

#### Tags

- Creator
- Indoor Maps
- Tileset
- Wayfinding

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/maps/creator)
- [Getting Started](https://learn.microsoft.com/en-us/azure/azure-maps/creator-indoor-maps)
- [Postman Collection](collections/microsoft-azure-maps.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-azure-maps.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://portal.azure.com)
- [Documentation](https://learn.microsoft.com/en-us/azure/azure-maps/)
- [Getting Started](https://learn.microsoft.com/en-us/azure/azure-maps/quick-demo-map-app)
- [Authentication](https://learn.microsoft.com/en-us/azure/azure-maps/azure-maps-authentication)
- [S D Ks](https://learn.microsoft.com/en-us/azure/azure-maps/about-azure-maps)
- [Pricing](https://azure.microsoft.com/en-us/pricing/details/azure-maps/)
- [Status Page](https://status.azure.com/)
- [Support](https://azure.microsoft.com/en-us/support/options/)
- [Blog](https://azure.microsoft.com/en-us/blog/tag/azure-maps/)
- [Changelog](https://learn.microsoft.com/en-us/azure/azure-maps/release-notes-map-control)
- [Terms of Service](https://azure.microsoft.com/en-us/support/legal/)
- [Privacy Policy](https://privacy.microsoft.com/en-us/privacystatement)
- [GitHub Organization](https://github.com/Azure)
- [Website](https://azure.microsoft.com/en-us/products/azure-maps)
- [Login](https://portal.azure.com)
- [Sign Up](https://azure.microsoft.com/en-us/free)
- [L L Ms Txt](https://portal.azure.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
