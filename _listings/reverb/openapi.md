---
swagger: "2.0"
x-collection-name: Reverb
x-complete: 1
info:
  title: reverb
  description: reverb
  termsOfService: https://reverb.com/page/terms
  contact:
    name: Reverb API
    url: https://dev.reverb.com
    email: integrations@reverb.com
  version: "3.0"
host: api.reverb.com
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /auth/forgot_password:
    post:
      summary: Post Auth Forgot Password
      description: Send a password reset email
      operationId: postAuthForgotPassword
      x-api-path-slug: authforgot-password-post
      parameters:
      - in: body
        name: body
        description: the content of the request
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Auth
      - Forgot
      - Password
  /auth/logout:
    put:
      summary: Put Auth Logout
      description: Logout (primarily for mobile clients)
      operationId: putAuthLogout
      x-api-path-slug: authlogout-put
      parameters:
      - in: body
        name: body
        description: the content of the request
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Auth
      - Logout
---