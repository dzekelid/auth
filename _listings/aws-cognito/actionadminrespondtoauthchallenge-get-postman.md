{
  "info": {
    "name": "AWS Cognito API Admin Respond To Auth Challenge",
    "_postman_id": "8a221f5f-1934-41d2-a6e8-9c2d6937fc8d",
    "description": "Responds to an authentication challenge, as an administrator.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Authentication Challenge",
      "item": [
        {
          "id": "8d165208-09dc-408b-9188-b16879be9734",
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
              "id": "dfd63c63-f73e-4054-8301-c3e568099e25"
            }
          ]
        }
      ]
    }
  ]
}