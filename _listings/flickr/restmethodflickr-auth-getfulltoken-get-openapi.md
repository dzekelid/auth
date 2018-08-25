---
swagger: "2.0"
x-collection-name: Flickr
x-complete: 0
info:
  title: Flickr Auth Get Full Token
  description: Get the full authentication token for a mini-token. This method call
    must be signed.
  version: 1.0.0
host: api.flickr.com
basePath: /services/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/?method=flickr.auth.checkToken:
    get:
      summary: Auth Check Token
      description: Returns the credentials attached to an authentication token. This
        call must be signed as specified in the authentication API spec.
      operationId: getRestMethodFlickr.auth.checktoken
      x-api-path-slug: restmethodflickr-auth-checktoken-get
      parameters:
      - in: query
        name: api_key
        description: Your API application key
      - in: query
        name: auth_token
        description: The authentication token to check
      - in: query
        name: format
        description: Response format
      responses:
        200:
          description: OK
      tags:
      - Auth
      - CheckToken
  /rest/?method=flickr.auth.getFrob:
    get:
      summary: Auth Get Frob
      description: Returns a frob to be used during authentication. This method call
        must be signed, and is deprecated in favour of OAuth.
      operationId: getRestMethodFlickr.auth.getfrob
      x-api-path-slug: restmethodflickr-auth-getfrob-get
      parameters:
      - in: query
        name: api_key
        description: Your API application key
      - in: query
        name: format
        description: Response format
      responses:
        200:
          description: OK
      tags:
      - Auth
      - GetFrob
  /rest/?method=flickr.auth.getFullToken:
    get:
      summary: Auth Get Full Token
      description: Get the full authentication token for a mini-token. This method
        call must be signed.
      operationId: getRestMethodFlickr.auth.getfulltoken
      x-api-path-slug: restmethodflickr-auth-getfulltoken-get
      parameters:
      - in: query
        name: api_key
        description: Your API application key
      - in: query
        name: format
        description: Response format
      - in: query
        name: mini_token
        description: The mini-token typed in by a user
      responses:
        200:
          description: OK
      tags:
      - Auth
      - GetFullToken
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