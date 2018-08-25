---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: Dezrez Returns a URL that will start the process of authorisation with the
    external provider - normally using the OAuth1/2 protocol suite.
  version: 1.0.0
  description: Returns a url that will start the process of authorisation with the
    external provider - normally using the oauth1/2 protocol suite..
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/ExternalProvider:
    get:
      summary: Returns a URL that will start the process of authorisation with the
        external provider - normally using the OAuth1/2 protocol suite.
      description: Returns a url that will start the process of authorisation with
        the external provider - normally using the oauth1/2 protocol suite..
      operationId: ExternalProvider_GetAuthoriseAgencyUrlByexternalProviderId
      x-api-path-slug: apiexternalprovider-get
      parameters:
      - in: query
        name: externalProviderId
        description: The external provider identifier
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Returns
      - URL
      - That
      - Will
      - Start
      - Process
      - Of
      - Authorisation
      - External
      - Provider
      - '-'
      - Normally
      - Using
      - OAuth1
      - "2"
      - Protocol
      - Suite
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