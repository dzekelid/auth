{
  "info": {
    "name": "Flickr Auth Oauth Get Access Token",
    "_postman_id": "35ab82e5-882f-4a5b-8dd2-74874f92a43e",
    "description": "Exchange an auth token from the old Authentication API, to an OAuth access token. Calling this method will delete the auth token used to make the request. The request must be signed.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Auth",
      "item": [
        {
          "id": "159fab64-ec18-407a-a3a0-6d3439e37528",
          "name": "getRestMethodFlickr.auth.oauth.getaccesstoken",
          "request": {
            "url": "http://api.flickr.com/services/rest/?method=flickr.auth.oauth.getAccessToken?api_key=%7B%7D&format=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Exchange an auth token from the old Authentication API, to an OAuth access token. Calling this method will delete the auth token used to make the request. The request must be signed."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5a0e5325-6fc4-43b2-98cc-90119f12f314"
            }
          ]
        }
      ]
    }
  ]
}