{
  "info": {
    "name": "Dezrez Returns a URL that will start the process of authorisation with the external provider - normally using the OAuth1/2 protocol suite.",
    "_postman_id": "59e130ad-1ee7-47be-97fb-cc4551cc4e8f",
    "description": "Returns a url that will start the process of authorisation with the external provider - normally using the oauth1/2 protocol suite..",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Returns",
      "item": [
        {
          "id": "48add460-4883-4e47-9efa-f607c23ae3fe",
          "name": "ExternalProvider_GetAuthoriseAgencyUrlByexternalProviderId",
          "request": {
            "url": "http://api.dezrez.com/api/ExternalProvider?externalProviderId=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Rezi-Api-Version",
                "value": "{}",
                "description": "Specifies which version of the API to call",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Returns a url that will start the process of authorisation with the external provider - normally using the oauth1/2 protocol suite.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "60f66b4f-4534-4008-b5a7-8b88c727f146"
            }
          ]
        }
      ]
    }
  ]
}