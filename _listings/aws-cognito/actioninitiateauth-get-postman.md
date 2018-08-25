{
  "info": {
    "name": "AWS Cognito API Initiate Auth",
    "_postman_id": "f66b6c2b-4df0-4f79-a329-40cb933e7bd3",
    "description": "Initiates the authentication flow.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Authentication Challenge",
      "item": [
        {
          "id": "39a0e17a-8c86-443d-8c76-6aa857281a16",
          "name": "adminRespondToAuthChallenge",
          "request": {
            "url": "http://example.com/api/?Action=AdminRespondToAuthChallenge?ChallengeName=ChallengeName&ChallengeResponses=ChallengeResponses&ClientId=ClientId&Session=Session&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Responds to an authentication challenge, as an administrator."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "82e57694-5df8-483b-8d64-6da84415fbed"
            }
          ]
        }
      ]
    },
    {
      "name": "Authentication",
      "item": [
        {
          "id": "f4857f8a-5c56-4d19-8482-4606902048ce",
          "name": "initiateAuth",
          "request": {
            "url": "http://example.com/api/?Action=InitiateAuth?AuthFlow=AuthFlow&AuthParameters=AuthParameters&ClientId=ClientId&ClientMetadata=ClientMetadata",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Initiates the authentication flow."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fe67a58e-f98b-4dc9-94c9-f4a3219050c1"
            }
          ]
        }
      ]
    }
  ]
}