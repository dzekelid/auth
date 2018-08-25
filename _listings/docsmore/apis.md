---
name: Docsmore
x-slug: docsmore
description: FORM.FILL.SIGN - With Docsmore, the process of setting up a form and
  sending to users to complete or sign is simplified.  Use our platform to easily
  upload a document, specify form fields/signage, and send to users for completion.  Present
  forms to you...
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28946-api-docsmore-com.jpg
x-kinRank: "7"
x-alexaRank: "7238418"
tags: Auth
created: "2018-08-25"
modified: "2018-08-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/auth/master/_listings/docsmore/apis.md
specificationVersion: "0.14"
apis:
- name: Docsmore API 2.1 - Get Raw Data For A Given Document
  x-api-slug: apiclientdocsgetrawdataauthtokendocumentkey-get
  description: |-
    This API call gets you underlying raw data of the document. All you need to do is supply Auth token and Document Key as part of the call.

    Document Key can be obtained from "Document Gallery" Page and Clicking on the sub-menu of the desired document.

    As a response object, jsondata and metadata information is passed. Jsondata is basically raw data and metadata is data columns information.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28946-api-docsmore-com.jpg
  humanURL: http://api.docsmore.com
  baseURL: https://api.docsmore.com//
  tags: SaaS, Technology, Documents, Forms
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/auth/master/_listings/docsmore/apiclientdocsgetrawdataauthtokendocumentkey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/auth/master/_listings/docsmore/apiclientdocsgetrawdataauthtokendocumentkey-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://digitalocean.api.gallery.streamdata.io
- type: x-email
  url: contact@docsmore.com
- type: x-twitter
  url: https://twitter.com/docsmore
- type: x-website
  url: http://api.docsmore.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---