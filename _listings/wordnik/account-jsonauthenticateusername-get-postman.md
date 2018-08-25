{
  "info": {
    "name": "Wordnik Authenticates a User",
    "_postman_id": "47aec9d5-3fd2-459d-baac-e6f88b033950",
    "description": "Authenticates a user.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Account",
      "item": [
        {
          "id": "8422e41a-76b2-4fd6-888e-35643b2cd9a1",
          "name": "getApiTokenStatus",
          "request": {
            "url": "http://api.wordnik.com/v4/account.json/apiTokenStatus",
            "method": "GET",
            "header": [
              {
                "key": "api_key",
                "value": "{}",
                "description": "Wordnik authentication token",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Returns usage statistics for the api account.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "73e9985b-c5b3-41ab-84a3-07e768a87d5b"
            }
          ]
        },
        {
          "id": "d804acce-e284-4a0f-9a4d-946dfc5184ea",
          "name": "authenticate",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.wordnik.com",
              "path": [
                "v4",
                "account.json/authenticate/:username"
              ],
              "query": [
                {
                  "key": "password",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "username",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Authenticates a user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e267b8d3-80ca-4d5b-90d0-0f9394facd3d"
            }
          ]
        }
      ]
    }
  ]
}