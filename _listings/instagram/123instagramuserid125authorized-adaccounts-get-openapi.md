---
swagger: "2.0"
x-collection-name: Instagram
x-complete: 0
info:
  title: Instagram Instagram User Authorized Adaccounts
  version: 1.0.0
  description: Instagram User Authorized Adaccounts
host: graph.facebook.com
basePath: /v3.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /&#123;instagram-user-id&#125;/authorized_adaccounts:
    get:
      summary: Instagram User Authorized Adaccounts
      description: Instagram User Authorized Adaccounts
      operationId: getInstagramUserAuthorizedAdaccounts
      x-api-path-slug: 123instagramuserid125authorized-adaccounts-get
      parameters:
      - in: query
        name: "100"
        description: Invalid parameter
        type: string
      responses:
        200:
          description: OK
      tags:
      - Instagram
      - User
      - Authorized
      - Adaccounts
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