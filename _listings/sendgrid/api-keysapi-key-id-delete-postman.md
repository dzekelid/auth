{
  "info": {
    "name": "SendGrid Delete Api Keys Api Key",
    "_postman_id": "456c357d-6339-4900-b107-fe9a307a3bc4",
    "description": "**This endpoint allows you to revoke an existing API Key**\n\nAuthentications using this API Key will fail after this request is made, with some small propogation delay.If the API Key ID does not exist an HTTP 404 will be returned.\n\nThe API Keys feature allows customers to be able to generate an API Key credential which can be used for authentication with the SendGrid v3 Web API or the [Mail API Endpoint](https://sendgrid.com/docs/API_Reference/Web_API/mail.html).\n\n## URI Parameters\n\n| URI Parameter   | Type  | Required?  | Description  |\n|---|---|---|---|\n|api_key_id |string | required | The ID of the API Key you are deleting.|",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "email",
      "item": [
        {
          "id": "723bc2cc-40c8-4174-9f8a-fd4a8fa67cd3",
          "name": "api_keys.api_key_id.delete",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.sendgrid.com",
              "path": [
                "v3",
                "api_keys/:api_key_id"
              ],
              "query": [
                {
                  "key": "No Name",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "api_key_id",
                  "value": "api_key_id",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "**This endpoint allows you to revoke an existing API Key**\n\nAuthentications using this API Key will fail after this request is made, with some small propogation delay"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f59b33c6-e9fb-4a30-ab7d-e453456869e1"
            }
          ]
        }
      ]
    }
  ]
}