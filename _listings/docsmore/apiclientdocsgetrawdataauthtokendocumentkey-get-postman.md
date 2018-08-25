{
  "info": {
    "name": "Docsmore Get Raw Data For A Given Document",
    "_postman_id": "68fbdbdf-af29-408f-a4ed-3f8a245f025f",
    "description": "This API call gets you underlying raw data of the document. All you need to do is supply Auth token and Document Key as part of the call.\n\nDocument Key can be obtained from \"Document Gallery\" Page and Clicking on the sub-menu of the desired document.\n\nAs a response object, jsondata and metadata information is passed. Jsondata is basically raw data and metadata is data columns information.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Raw",
      "item": [
        {
          "id": "fc9022b9-33bc-47c1-87aa-4aa136c422ae",
          "name": "ApiClientdocsGetrawdataAuthTokenDocumentKeyGet",
          "request": {
            "url": "http://api.docsmore.com/api/clientdocs/getrawdata/:authToken/:documentKey?authToken=%7B%7D&documentKey=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "This API call gets you underlying raw data of the document. All you need to do is supply Auth token and Document Key as part of the call.\n\nDocument Key can be obtained from \"Document Gallery\" Page and Clicking on the sub-menu of the desired document.\n\nAs a response object, jsondata and metadata information is passed. Jsondata is basically raw data and metadata is data columns information."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6e128fa2-49e4-4ce6-91b9-3cc55f59cee1"
            }
          ]
        }
      ]
    }
  ]
}