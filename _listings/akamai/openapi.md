---
swagger: "2.0"
x-collection-name: Akamai
x-complete: 1
info:
  title: Akamai API
  description: the-akamai-api-for-managing-your-akamai-service
  version: 1.0.0
host: developer.akamai.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /sla-api/v1/tests/{slaTestId}/reports/performance:
    get:
      summary: List Performance Reports
      description: List Performance Reports
      operationId: slaapiv1testsslatestidreportsperformancestartend
      x-api-path-slug: slaapiv1testsslatestidreportsperformance-get
      parameters:
      - in: query
        name: end
        description: Timestamp for the end of the data window, in UTC 8601 format
        type: string
      - in: query
        name: slaTestId
        description: Unique identifier for the test you wish to run a report on
        type: string
      - in: query
        name: start
        description: Timestamp for the start of the data window, in UTC 8601 format
        type: string
      responses:
        200:
          description: OK
      tags:
      - Sla
      - Tests
      - Slatest
      - Reports
      - Performance
      - Start
      - end
---