---
swagger: "2.0"
x-collection-name: Docsmore
x-complete: 1
info:
  title: Docsmore API 2.1
  description: alt-texthttpswww-docsmore-comwpcontentuploads201802docsmoreapi-png-titleh3create-a-developer-account-at-docsmore-io-and-start-unleashing-the-power-of-docsmore-into-your-own-applications--to-make-it-easier-we-have-provided-client-libraries-and-sdk-in-several-languages-for-you-to-get-started-and-hit-the-ground-running-in-no-time-h3brbrh4note-if-you-dont-see-api-setting-under-top-right-menu-that-means-you-will-need-to-be-a-developer-account--please-contact-supportdocsmore-com-and-a-customer-service-expert-will-switch-your-account-to-developer-account--h4brbrh5just-head-over-to-httpsdocsmore-io-and-sign-up-for-your-30-days-trial-h5
  version: "1.0"
host: api.docsmore.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/clientdocs/getrawdata/:authToken/:documentKey:
    get:
      summary: Get Raw Data For A Given Document
      description: |-
        This API call gets you underlying raw data of the document. All you need to do is supply Auth token and Document Key as part of the call.

        Document Key can be obtained from "Document Gallery" Page and Clicking on the sub-menu of the desired document.

        As a response object, jsondata and metadata information is passed. Jsondata is basically raw data and metadata is data columns information.
      operationId: ApiClientdocsGetrawdataAuthTokenDocumentKeyGet
      x-api-path-slug: apiclientdocsgetrawdataauthtokendocumentkey-get
      parameters:
      - in: header
        name: Accept
      - in: query
        name: authToken
      - in: header
        name: Content-Type
      - in: query
        name: documentKey
      responses:
        200:
          description: OK
      tags:
      - Raw
      - Data
      - Given
      - Document
---