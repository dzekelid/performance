---
swagger: "2.0"
x-collection-name: nFusion Solutions
x-complete: 0
info:
  title: nFusion API Get Historical Performance for requested metals
  description: Get historical performance for requested metals.
  contact:
    name: nFusion Solutions
    url: https://nfusionsolutions.com/contact
    email: support@nfusionsolutions.com
  version: 1.0.0
host: api.nfusionsolutions.biz
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v{version}/Metals/spot/performance:
    get:
      summary: Get Historical Performance for requested metals
      description: Get historical performance for requested metals.
      operationId: ApiV{versionMetalsSpotPerformanceGet
      x-api-path-slug: apivversionmetalsspotperformance-get
      parameters:
      - in: query
        name: currency
        description: comma separated list of conversion currencies, defaults to USD
      - in: query
        name: format
        description: to override content negotiation specify a value of json or xml
      - in: query
        name: metals
        description: comma separated list of metals
      - in: query
        name: token
        description: auth token
      - in: query
        name: unitofmeasure
        description: unit of meaure, defaults to troy ounces
      - in: path
        name: version
        description: The requested API version
      responses:
        200:
          description: OK
      tags:
      - Historical
      - Performancerequested
      - Metals
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---