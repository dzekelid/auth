---
swagger: "2.0"
x-collection-name: Shopify
x-complete: 1
info:
  title: Shopify API
  description: todo-add-description
  version: 1.0.0
host: DefaultParameterValue:DefaultParameterValue@DefaultParameterValue.myshopify.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /account/login:
    post:
      summary: Hack Authentication
      description: Hack authentication.
      operationId: postAccountLogin
      x-api-path-slug: accountlogin-post
      parameters:
      - in: header
        name: Content-Type
      - in: formData
        name: customer[email]
      - in: formData
        name: customer[{{password}}]
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Hack
      - Authentication
---