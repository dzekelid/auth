---
swagger: "2.0"
x-collection-name: AWS Storage Gateway Service
x-complete: 0
info:
  title: AWS Storage Gateway Service API Delete Chap Credentials
  version: 1.0.0
  description: |-
    Deletes Challenge-Handshake Authentication Protocol (CHAP) credentials for a
             specified iSCSI target and initiator pair.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DeleteChapCredentials:
    get:
      summary: Delete Chap Credentials
      description: |-
        Deletes Challenge-Handshake Authentication Protocol (CHAP) credentials for a
                 specified iSCSI target and initiator pair.
      operationId: deleteChapCredentials
      x-api-path-slug: actiondeletechapcredentials-get
      parameters:
      - in: query
        name: InitiatorName
        description: The iSCSI initiator that connects to the target
        type: string
      - in: query
        name: TargetARN
        description: The Amazon Resource Name (ARN) of the iSCSI volume target
        type: string
      responses:
        200:
          description: OK
      tags:
      - Chap Credentials
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