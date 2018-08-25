---
swagger: "2.0"
x-collection-name: AWS EC2 Container Registry Service
x-complete: 1
info:
  title: AWS EC2 Container Registry API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=GetAuthorizationToken:
    get:
      summary: Get Authorization Token
      description: Retrieves a token that is valid for a specified registry for 12
        hours.
      operationId: getAuthorizationToken
      x-api-path-slug: actiongetauthorizationtoken-get
      parameters:
      - in: query
        name: registryIds
        description: A list of AWS account IDs that are associated with the registries
          for which to get authorization tokens
        type: string
      responses:
        200:
          description: OK
      tags:
      - Authorization Tokens
---