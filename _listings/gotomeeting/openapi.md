---
swagger: "2.0"
x-collection-name: GoToMeeting
x-complete: 1
info:
  title: Go To Webinar
  description: the-gotowebinar-api-provides-seamless-integration-of-webinar-registrant-and-attendee-data-into-your-existing-infrastructure-or-thirdparty-applications--the-ability-to-register-participants-as-well-as-pull-lists-of-registrants-and-attendees-for-a-webinar-allows-organizers-to-manage-the-flow-of-information-between-their-primary-applications-without-manual-intervention-
  termsOfService: https://developer.citrixonline.com/terms-use
  contact:
    name: Developer Support
    url: https://developer.citrixonline.com
    email: developer-support@citrixonline.com
  version: 1.0.0
host: api.citrixonline.com
basePath: /G2W/rest
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /organizers/{organizerKey}/webinars/{webinarKey}/performance:
    get:
      summary: Get performance for all webinar sessions
      description: Gets performance details for all sessions of a specific webinar.
      operationId: getPerformanceForAllWebinarSessions
      x-api-path-slug: organizersorganizerkeywebinarswebinarkeyperformance-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Organizers
      - OrganizerKey
      - Webinars
      - WebinarKey
      - Performance
  /organizers/{organizerKey}/webinars/{webinarKey}/sessions/{sessionKey}/performance:
    get:
      summary: Get session performance
      description: Get performance details for a session. For technical reasons, this
        call cannot be executed from this documentation. Please use the curl command
        to execute it.
      operationId: getPerformance
      x-api-path-slug: organizersorganizerkeywebinarswebinarkeysessionssessionkeyperformance-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Organizers
      - OrganizerKey
      - Webinars
      - WebinarKey
      - Sessions
      - SessionKey
      - Performance
---