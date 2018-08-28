---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: Dezrez Set the performance level of a database node
  version: 1.0.0
  description: Set the performance level of a database node.
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/admin/database/setperformancelevel:
    post:
      summary: Set the performance level of a database node
      description: Set the performance level of a database node.
      operationId: Database_SetNodeDatabasePerformanceLevelBynodeIdBylevel
      x-api-path-slug: apiadmindatabasesetperformancelevel-post
      parameters:
      - in: query
        name: level
        description: The level to scale to
      - in: query
        name: nodeId
        description: The id of the database node to scale
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Set
      - Performance
      - Level
      - Of
      - Database
      - Node
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