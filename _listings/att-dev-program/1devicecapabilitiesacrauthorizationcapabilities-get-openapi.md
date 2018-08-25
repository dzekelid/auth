---
swagger: "2.0"
x-collection-name: AT&T Dev Program
x-complete: 0
info:
  title: AT&T API Get Devicecapabilities Acr Authorization Capabilities
  description: /1/devicecapabilities/acr:authorization/capabilities
  version: "1"
host: api.att.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /1/devicecapabilities/acr:authorization/capabilities:
    get:
      summary: Get Devicecapabilities Acr Authorization Capabilities
      description: /1/devicecapabilities/acr:authorization/capabilities
      operationId: 1devicecapabilitiesacrauthorizationcapabilities
      x-api-path-slug: 1devicecapabilitiesacrauthorizationcapabilities-get
      responses:
        200:
          description: OK
      tags:
      - Devicecapabilities
      - Acr:authorization
      - Capabilities
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