swagger: "2.0"
x-collection-name: LogMeIn
x-complete: 1
info:
  title: GoToWebinar API
  description: todo-add-description
  version: 1.0.0
host: api.getgo.com
basePath: /G2W/rest/organizers
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{organizerKey}/webinars/{webinarKey}/performance:
    get:
      summary: Get performance for all webinar sessions
      description: Get performance for all webinar sessions.
      operationId: WebinarsPerformanceByOrganizerKeyAndWebinarKeyGet
      x-api-path-slug: organizerkeywebinarswebinarkeyperformance-get
      parameters:
      - in: header
        name: Accept
      - in: header
        name: Content-Type
      - in: path
        name: organizerKey
      - in: path
        name: webinarKey
      responses:
        200:
          description: OK
      tags:
      - Performance
      - Webinar
      - Sessions
  /{organizerKey}/webinars/{webinarKey}/sessions/{sessionKey}/performance:
    get:
      summary: Get session performance
      description: Get session performance.
      operationId: WebinarsSessionsSessionKeyPerformanceByOrganizerKeyAndWebinarKeyGet
      x-api-path-slug: organizerkeywebinarswebinarkeysessionssessionkeyperformance-get
      parameters:
      - in: header
        name: Accept
      - in: header
        name: Content-Type
      - in: path
        name: organizerKey
      - in: path
        name: sessionKey
      - in: path
        name: webinarKey
      responses:
        200:
          description: OK
      tags:
      - Session
      - Performance