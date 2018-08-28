---
swagger: "2.0"
x-collection-name: Google Doubleclick
x-complete: 1
info:
  title: Google Doubleclick Merged API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /performancereport:
    get:
      summary: Get Performance Report
      description: Retrieves the authenticated user's list of performance metrics.
      operationId: adexchangebuyer.performanceReport.list
      x-api-path-slug: performancereport-get
      parameters:
      - in: query
        name: accountId
        description: The account id to get the reports
      - in: query
        name: endDateTime
        description: The end time of the report in ISO 8601 timestamp format using
          UTC
      - in: query
        name: maxResults
        description: Maximum number of entries returned on one result page
      - in: query
        name: pageToken
        description: A continuation token, used to page through performance reports
      - in: query
        name: startDateTime
        description: The start time of the report in ISO 8601 timestamp format using
          UTC
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Performance Report
---