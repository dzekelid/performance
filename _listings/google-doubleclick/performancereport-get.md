---
swagger: "2.0"
info:
  title: Google Doubleclick API Get Performance Report
  version: 1.0.0
  description: Retrieves the authenticated user's list of performance metrics.
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
      description: Retrieves the authenticated user's list of performance metrics
      operationId: adexchangebuyer.performanceReport.list
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
      - advertising
      - performance report
definitions: []
x-collection-name: Google Doubleclick
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