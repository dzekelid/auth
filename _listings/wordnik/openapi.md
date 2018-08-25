---
swagger: "2.0"
x-collection-name: Wordnik
x-complete: 1
info:
  title: Wordnik
  description: wordnik-is-the-worlds-biggest-online-english-dictionary-by-number-of-words
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
    post:
      summary: Authenticates a user
      description: Authenticates a user.
      operationId: authenticatePost
      x-api-path-slug: account-jsonauthenticateusername-post
      parameters:
      - in: body
        name: body
        description: The users password
        schema:
          $ref: '#/definitions/holder'
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
---