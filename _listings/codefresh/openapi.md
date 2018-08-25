---
swagger: "2.0"
x-collection-name: Codefresh
x-complete: 1
info:
  title: Codefresh API
  description: codefresh-api-swagger2-0-specification
  termsOfService: http://www.codefresh.io
  contact:
    name: Codefresh api team
    url: http://www.codefresh.io
  version: 1.0.0
host: g.codefresh.io
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /registry/auth/token:
    post:
      summary: Post Registry Auth Token
      description: Post registry auth token.
      operationId: postRegistryAuthToken
      x-api-path-slug: registryauthtoken-post
      parameters:
      - in: body
        name: options
        description: Description of the token
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Registry
      - Auth
      - Token
---