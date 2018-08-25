{
  "info": {
    "name": "Instagram Instagram User Authorized Adaccounts",
    "_postman_id": "ebff79a7-b2c8-4a26-984c-778e9d45937a",
    "description": "Instagram User Authorized Adaccounts",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Instagram",
      "item": [
        {
          "id": "5b904ad5-e0d1-4b42-810e-9967e61622d2",
          "name": "getInstagramMediaComments",
          "request": {
            "url": "http://graph.facebook.com/v3.0/&#123;instagram-media-id&#125;/comments?100=100",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Instagram Media Comments"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "49fe215c-5e6c-4599-a3b2-4f8ddf47cd46"
            }
          ]
        },
        {
          "id": "5bfb9394-2bc3-44e4-88e5-35c2edbf016e",
          "name": "getInstagramUser",
          "request": {
            "url": "http://graph.facebook.com/v3.0/&#123;instagram-user-id&#125;?followed_by_countint32=followed_by_countint32&follow_countint32=follow_countint32&has_profile_picturebool=has_profile_picturebool&idnumeric string=idnumeric%20string&is_privatebool=is_privatebool&is_publishedbool=is_publishedbool&media_countint32=media_countint32&profile_picstring=profile_picstring&usernamestring=usernamestring",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Instagram User"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5de94029-5003-4462-9116-1cfa5b38a4f0"
            }
          ]
        },
        {
          "id": "96b08377-cd2f-4bfc-992a-246139029554",
          "name": "getInstagramUserAgencies",
          "request": {
            "url": "http://graph.facebook.com/v3.0/&#123;instagram-user-id&#125;/agencies?294=294",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Instagram User Agencies"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c1bee0ca-ff40-436e-aa4f-ba251d0b583c"
            }
          ]
        },
        {
          "id": "ee9877e8-329d-4805-856e-4c527503f0d7",
          "name": "getInstagramUserAuthorizedAdaccounts",
          "request": {
            "url": "http://graph.facebook.com/v3.0/&#123;instagram-user-id&#125;/authorized_adaccounts?100=100",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Instagram User Authorized Adaccounts"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3de622e2-fe5d-4bdd-87a3-ce9212ec7020"
            }
          ]
        }
      ]
    }
  ]
}