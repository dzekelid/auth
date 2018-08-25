---
swagger: "2.0"
x-collection-name: AWS Security Token Service
x-complete: 1
info:
  title: AWS Security Token Service API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DecodeAuthorizationMessage:
    get:
      summary: Decode Authorization Message
      description: |-
        Decodes additional information about the authorization status of a request from an
              encoded message returned in response to an AWS request.
      operationId: decodeAuthorizationMessage
      x-api-path-slug: actiondecodeauthorizationmessage-get
      parameters:
      - in: query
        name: EncodedMessage
        description: The encoded message that was returned with the response
        type: string
      responses:
        200:
          description: OK
      tags:
      - Roles
---