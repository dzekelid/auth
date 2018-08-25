---
swagger: "2.0"
x-collection-name: AWS Storage Gateway Service
x-complete: 1
info:
  title: AWS Storage Gateway Service API
  version: 1.0.0
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
  /?Action=DescribeChapCredentials:
    get:
      summary: Describe Chap Credentials
      description: |-
        Returns an array of Challenge-Handshake Authentication Protocol (CHAP) credentials
                 information for a specified iSCSI target, one for each target-initiator pair.
      operationId: describeChapCredentials
      x-api-path-slug: actiondescribechapcredentials-get
      parameters:
      - in: query
        name: TargetARN
        description: The Amazon Resource Name (ARN) of the iSCSI volume target
        type: string
      responses:
        200:
          description: OK
      tags:
      - Chap Credentials
  /?Action=UpdateChapCredentials:
    get:
      summary: Update Chap Credentials
      description: |-
        Updates the Challenge-Handshake Authentication Protocol (CHAP) credentials for a
                 specified iSCSI target.
      operationId: updateChapCredentials
      x-api-path-slug: actionupdatechapcredentials-get
      parameters:
      - in: query
        name: InitiatorName
        description: The iSCSI initiator that connects to the target
        type: string
      - in: query
        name: SecretToAuthenticateInitiator
        description: The secret key that the initiator (for example, the Windows client)
          must provide to         participate in mutual CHAP with the target
        type: string
      - in: query
        name: SecretToAuthenticateTarget
        description: The secret key that the target must provide to participate in
          mutual CHAP with the         initiator (e
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
---