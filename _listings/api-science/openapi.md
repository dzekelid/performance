---
swagger: "2.0"
x-collection-name: API Science
x-complete: 1
info:
  title: API Science
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /monitors/{id}/performance:
    get:
      summary: Performance Report
      description: Performance Report
      operationId: performanceReport
      x-api-path-slug: monitorsidperformance-get
      parameters:
      - in: query
        name: end
        description: The end point you want to build a performance report from
      - in: path
        name: id
        description: The id for the monitor
      - in: query
        name: preset
        description: Present for commonly requested reports
      - in: query
        name: resolution
        description: The resolution is the time unit for aggregating data, with allowable
          values of hour, day, and week
      - in: query
        name: start
        description: The start point you want to build a performance report from
      responses:
        200:
          description: OK
      tags:
      - Performance
---