{
  "info": {
    "name": "Shopify Hack Authentication",
    "_postman_id": "a89332bf-126e-41a0-b7c0-caaa78652520",
    "description": "Hack authentication.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Commerce",
      "item": [
        {
          "id": "62ff87e7-2663-4e9d-a56c-0d4c1bc867cc",
          "name": "postAccountLogin",
          "request": {
            "url": "http://DefaultParameterValue:DefaultParameterValue@DefaultParameterValue.myshopify.com/account/login",
            "method": "POST",
            "header": [
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "customer[email]",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "customer[{{password}}]",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "Hack authentication."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "becac85e-94a9-460b-9ed2-111be41c1bad"
            }
          ]
        }
      ]
    }
  ]
}