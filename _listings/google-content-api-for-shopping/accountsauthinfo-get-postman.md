{
  "info": {
    "name": "Google Content API for Shopping API Authenticated User",
    "_postman_id": "e1cd23e1-d8a9-47d5-a36e-c161a5d717fb",
    "description": "Returns information about the authenticated user.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Authenticated",
      "item": [
        {
          "id": "0b9a2fda-f8d7-4b21-842b-2db7185bf9c7",
          "name": "content.accounts.authinfo",
          "request": {
            "url": "http://www.googleapis.com/content/v2/accounts/authinfo",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns information about the authenticated user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "83aa45fe-673c-40c5-9f26-abb981210d7b"
            }
          ]
        }
      ]
    }
  ]
}