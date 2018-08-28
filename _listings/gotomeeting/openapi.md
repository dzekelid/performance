swagger: "2.0"
x-collection-name: GoToMeeting
x-complete: 1
info:
  title: SCIM
  description: the-scim-api-lets-you-manage-users-in-your-organization--you-can-then-automate-the-provisioning-of-product-licenses-for-these-users-and-they-can-use-your-companys-single-signon-solution-through-an-identity-provider-
  termsOfService: https://developer.citrixonline.com/terms-use
  contact:
    name: Developer Support
    url: https://developer.citrixonline.com
    email: developer-support@citrixonline.com
  version: N/A
host: api.citrixonline.com
basePath: /identity/v1
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