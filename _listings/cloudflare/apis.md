---
name: CloudFlare
x-slug: cloudflare
description: Here at Cloudflare, we make the Internet work the way it should. Offering
  CDN, DNS, DDoS protection and security, find out how we can help your site.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18929-cloudflare.jpg
x-kinRank: "9"
x-alexaRank: "1685"
tags: Performance
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/performance/master/_listings/cloudflare/apis.md
specificationVersion: "0.14"
apis:
- name: CloudFlare List, search, sort and filter your Railguns
  x-api-slug: cloudflare
  description: List, search, sort and filter your Railguns
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18929-cloudflare.jpg
  humanURL: https://www.cloudflare.com
  baseURL: https://///railguns
  tags: Performance
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/performance/master/_listings/cloudflare/railguns-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/performance/master/_listings/cloudflare/railguns-get-openapi.md
- name: CloudFlare Readable identifier of the railgun
  x-api-slug: cloudflare
  description: Readable identifier of the railgun
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18929-cloudflare.jpg
  humanURL: https://www.cloudflare.com
  baseURL: https://///railguns
  tags: Performance
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/performance/master/_listings/cloudflare/railguns-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/performance/master/_listings/cloudflare/railguns-post-openapi.md
- name: CloudFlare Disable and delete a Railgun
  x-api-slug: cloudflare
  description: Disable and delete a Railgun
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18929-cloudflare.jpg
  humanURL: https://www.cloudflare.com
  baseURL: https://///railguns/:identifier
  tags: Performance
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/performance/master/_listings/cloudflare/railgunsidentifier-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/performance/master/_listings/cloudflare/railgunsidentifier-delete-openapi.md
- name: CloudFlare Railgun details
  x-api-slug: cloudflare
  description: Railgun detailsntt
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18929-cloudflare.jpg
  humanURL: https://www.cloudflare.com
  baseURL: https://///railguns/:identifier
  tags: Performance
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/performance/master/_listings/cloudflare/railgunsidentifier-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/performance/master/_listings/cloudflare/railgunsidentifier-get-openapi.md
- name: CloudFlare Enable or disable a Railgun for all zones connected to it
  x-api-slug: cloudflare
  description: Enable or disable a Railgun for all zones connected to it
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18929-cloudflare.jpg
  humanURL: https://www.cloudflare.com
  baseURL: https://///railguns/:identifier
  tags: Performance
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/performance/master/_listings/cloudflare/railgunsidentifier-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/performance/master/_listings/cloudflare/railgunsidentifier-patch-openapi.md
- name: CloudFlare The zones that are currently using this Railgun
  x-api-slug: cloudflare
  description: The zones that are currently using this Railgun
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18929-cloudflare.jpg
  humanURL: https://www.cloudflare.com
  baseURL: https://///railguns/:identifier/zones
  tags: Performance
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/performance/master/_listings/cloudflare/railgunsidentifierzones-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/performance/master/_listings/cloudflare/railgunsidentifierzones-get-openapi.md
- name: CloudFlare A list of available Railguns the zone can use
  x-api-slug: cloudflare
  description: A list of available Railguns the zone can use
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18929-cloudflare.jpg
  humanURL: https://www.cloudflare.com
  baseURL: https://///zones/:zone_identifier/railguns
  tags: Performance
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/performance/master/_listings/cloudflare/zoneszone-identifierrailguns-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/performance/master/_listings/cloudflare/zoneszone-identifierrailguns-get-openapi.md
- name: CloudFlare Details about a specific Railgun
  x-api-slug: cloudflare
  description: Details about a specific Railgun
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18929-cloudflare.jpg
  humanURL: https://www.cloudflare.com
  baseURL: https://///zones/:zone_identifier/railguns/:identifier
  tags: Performance
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/performance/master/_listings/cloudflare/zoneszone-identifierrailgunsidentifier-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/performance/master/_listings/cloudflare/zoneszone-identifierrailgunsidentifier-get-openapi.md
- name: CloudFlare Connect or disconnect a Railgun
  x-api-slug: cloudflare
  description: Connect or disconnect a Railgun
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18929-cloudflare.jpg
  humanURL: https://www.cloudflare.com
  baseURL: https://///zones/:zone_identifier/railguns/:identifier
  tags: Performance
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/performance/master/_listings/cloudflare/zoneszone-identifierrailgunsidentifier-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/performance/master/_listings/cloudflare/zoneszone-identifierrailgunsidentifier-patch-openapi.md
- name: CloudFlare Test Railgun connection to the Zone
  x-api-slug: cloudflare
  description: Test Railgun connection to the Zone
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18929-cloudflare.jpg
  humanURL: https://www.cloudflare.com
  baseURL: https://///zones/:zone_identifier/railguns/:identifier/diagnose
  tags: Performance
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/performance/master/_listings/cloudflare/zoneszone-identifierrailgunsidentifierdiagnose-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/performance/master/_listings/cloudflare/zoneszone-identifierrailgunsidentifierdiagnose-get-openapi.md
- name: CloudFlare
  x-api-slug: cloudflare
  description: Here at Cloudflare, we make the Internet work the way it should. Offering
    CDN, DNS, DDoS protection and security, find out how we can help your site.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18929-cloudflare.jpg
  humanURL: https://www.cloudflare.com
  baseURL: https:///
  tags: Performance
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/performance/master/_listings/cloudflare/openapi.md
x-common:
- type: x-blog
  url: https://blog.cloudflare.com/
- type: x-blog-rss
  url: http://blog.cloudflare.com/rss/
- type: x-crunchbase
  url: https://crunchbase.com/organization/cloudflare
- type: x-developer
  url: https://www.cloudflare.com/docs/client-api.html
- type: x-github
  url: https://github.com/cloudflare
- type: x-partners
  url: https://www.cloudflare.com/partners/
- type: x-pricing
  url: https://www.cloudflare.com/plans/
- type: x-privacy
  url: https://www.cloudflare.com/security-policy
- type: x-security
  url: https://www.cloudflare.com/security-policy/
- type: x-terms-of-service
  url: https://www.cloudflare.com/terms/
- type: x-transparency-report
  url: https://www.cloudflare.com/transparency/
- type: x-twitter
  url: https://twitter.com/CloudFlare
- type: x-website
  url: https://www.cloudflare.com
- type: x-website
  url: http://cloudflare.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---