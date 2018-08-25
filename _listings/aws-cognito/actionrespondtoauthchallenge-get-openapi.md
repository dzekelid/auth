---
swagger: "2.0"
x-collection-name: AWS Cognito
x-complete: 0
info:
  title: AWS Cognito API Respond To Auth Challenge
  version: 1.0.0
  description: Responds to the authentication challenge.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=AdminInitiateAuth:
    get:
      summary: Admin Initiate Auth
      description: Initiates the authentication flow, as an administrator.
      operationId: adminInitiateAuth
      x-api-path-slug: actionadmininitiateauth-get
      parameters:
      - in: query
        name: AuthFlow
        description: The authentication flow
        type: string
      - in: query
        name: AuthParameters
        description: The authentication parameters
        type: string
      - in: query
        name: ClientId
        description: The client app ID
        type: string
      - in: query
        name: ClientMetadata
        description: The client app metadata
        type: string
      - in: query
        name: UserPoolId
        description: The ID of the Amazon Cognito user pool
        type: string
      responses:
        200:
          description: OK
      tags:
      - Authnetication
  /?Action=AdminRespondToAuthChallenge:
    get:
      summary: Admin Respond To Auth Challenge
      description: Responds to an authentication challenge, as an administrator.
      operationId: adminRespondToAuthChallenge
      x-api-path-slug: actionadminrespondtoauthchallenge-get
      parameters:
      - in: query
        name: ChallengeName
        description: The name of the challenge
        type: string
      - in: query
        name: ChallengeResponses
        description: The challenge response
        type: string
      - in: query
        name: ClientId
        description: The client ID
        type: string
      - in: query
        name: Session
        description: The session
        type: string
      - in: query
        name: UserPoolId
        description: The ID of the Amazon Cognito user pool
        type: string
      responses:
        200:
          description: OK
      tags:
      - Authentication Challenge
  /?Action=InitiateAuth:
    get:
      summary: Initiate Auth
      description: Initiates the authentication flow.
      operationId: initiateAuth
      x-api-path-slug: actioninitiateauth-get
      parameters:
      - in: query
        name: AuthFlow
        description: The authentication flow
        type: string
      - in: query
        name: AuthParameters
        description: The authentication parameters
        type: string
      - in: query
        name: ClientId
        description: The client ID
        type: string
      - in: query
        name: ClientMetadata
        description: The client apps metadata
        type: string
      responses:
        200:
          description: OK
      tags:
      - Authentication
  /?Action=RespondToAuthChallenge:
    get:
      summary: Respond To Auth Challenge
      description: Responds to the authentication challenge.
      operationId: respondToAuthChallenge
      x-api-path-slug: actionrespondtoauthchallenge-get
      parameters:
      - in: query
        name: ChallengeName
        description: The name of the challenge
        type: string
      - in: query
        name: ChallengeResponses
        description: The responses to the authentication challenge
        type: string
      - in: query
        name: ClientId
        description: The client ID
        type: string
      - in: query
        name: Session
        description: The session
        type: string
      responses:
        200:
          description: OK
      tags:
      - Authentication Challenges
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