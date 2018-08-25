---
swagger: "2.0"
x-collection-name: Wordnik
x-complete: 0
info:
  title: Wordnik Authenticates a User
  description: Authenticates a user.
  version: "4.0"
host: api.wordnik.com
basePath: /v4
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /account.json/authenticate/{username}:
    get:
      summary: Authenticates a User
      description: Authenticates a user.
      operationId: authenticate
      x-api-path-slug: account-jsonauthenticateusername-get
      parameters:
      - in: query
        name: password
        description: The users password
      - in: path
        name: username
        description: A confirmed Wordnik username
      responses:
        200:
          description: OK
      tags:
      - Account
      - Authenticate
      - Username
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