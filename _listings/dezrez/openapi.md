swagger: "2.0"
x-collection-name: Dezrez
x-complete: 1
info:
  title: Dezrez.Rezi.Client.Api
  version: 1.0.0
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