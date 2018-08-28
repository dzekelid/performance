swagger: "2.0"
x-collection-name: CloudFlare
x-complete: 1
info:
  title: CloudFlare
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /railguns:
    get:
      summary: List, search, sort and filter your Railguns
      description: List, search, sort and filter your Railguns
      operationId: cloudflare-railgun-api
      x-api-path-slug: railguns-get
      parameters:
      - in: query
        name: direction
        description: Direction to order Railgunsttttttttttttttdesc
      - in: query
        name: page
        description: Page number of paginated resultstttttttttttttt1
      - in: query
        name: per_page
        description: Number of items per pagetttttttttttttt20
      - in: header
        name: X-AUTH-EMAIL
        description: Email address associated with your account
      - in: header
        name: X-AUTH-KEY
        description: API key generated on the My Account page
      responses:
        200:
          description: OK
      tags:
      - Performance
    post:
      summary: Readable identifier of the railgun
      description: Readable identifier of the railgun
      operationId: cloudflare-railgun-api
      x-api-path-slug: railguns-post
      parameters:
      - in: query
        name: name
        description: Readable identifier of the railgunttttttttttttttMy Railgun
      - in: header
        name: X-AUTH-EMAIL
        description: Email address associated with your account
      - in: header
        name: X-AUTH-KEY
        description: API key generated on the My Account page
      responses:
        200:
          description: OK
      tags:
      - Performance
  /railguns/:identifier:
    delete:
      summary: Disable and delete a Railgun
      description: Disable and delete a Railgun
      operationId: cloudflare-railgun-api
      x-api-path-slug: railgunsidentifier-delete
      responses:
        200:
          description: OK
      tags:
      - Performance
    get:
      summary: Railgun details
      description: Railgun detailsntt
      operationId: cloudflare-railgun-api
      x-api-path-slug: railgunsidentifier-get
      responses:
        200:
          description: OK
      tags:
      - Performance
    patch:
      summary: Enable or disable a Railgun for all zones connected to it
      description: Enable or disable a Railgun for all zones connected to it
      operationId: cloudflare-railgun-api
      x-api-path-slug: railgunsidentifier-patch
      parameters:
      - in: query
        name: enabled
        description: Flag to determine if the Railgun is accepting connectionstttttttttttttttrue
      - in: header
        name: X-AUTH-EMAIL
        description: Email address associated with your account
      - in: header
        name: X-AUTH-KEY
        description: API key generated on the My Account page
      responses:
        200:
          description: OK
      tags:
      - Performance
  /railguns/:identifier/zones:
    get:
      summary: The zones that are currently using this Railgun
      description: The zones that are currently using this Railgun
      operationId: cloudflare-railgun-api
      x-api-path-slug: railgunsidentifierzones-get
      responses:
        200:
          description: OK
      tags:
      - Performance
  /zones/:zone_identifier/railguns:
    get:
      summary: A list of available Railguns the zone can use
      description: A list of available Railguns the zone can use
      operationId: cloudflare-railgun-connections-for-a-zone-api
      x-api-path-slug: zoneszone-identifierrailguns-get
      responses:
        200:
          description: OK
      tags:
      - Performance
  /zones/:zone_identifier/railguns/:identifier:
    get:
      summary: Details about a specific Railgun
      description: Details about a specific Railgun
      operationId: cloudflare-railgun-connections-for-a-zone-api
      x-api-path-slug: zoneszone-identifierrailgunsidentifier-get
      responses:
        200:
          description: OK
      tags:
      - Performance
    patch:
      summary: Connect or disconnect a Railgun
      description: Connect or disconnect a Railgun
      operationId: cloudflare-railgun-connections-for-a-zone-api
      x-api-path-slug: zoneszone-identifierrailgunsidentifier-patch
      parameters:
      - in: query
        name: connected
        description: A flag indicating whether the given zone is connected to the
          Railguntttttttttttttttrue
      - in: header
        name: X-AUTH-EMAIL
        description: Email address associated with your account
      - in: header
        name: X-AUTH-KEY
        description: API key generated on the My Account page
      responses:
        200:
          description: OK
      tags:
      - Performance
  /zones/:zone_identifier/railguns/:identifier/diagnose:
    get:
      summary: Test Railgun connection to the Zone
      description: Test Railgun connection to the Zone
      operationId: cloudflare-railgun-connections-for-a-zone-api
      x-api-path-slug: zoneszone-identifierrailgunsidentifierdiagnose-get
      responses:
        200:
          description: OK
      tags:
      - Performance