# Azure Maps (microsoft-azure-maps)

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
