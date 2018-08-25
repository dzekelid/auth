---
name: Flickr
x-slug: flickr
description: Flickr (pronounced flicker) is an image hosting and video hosting website,
  and web services suite that was created by Ludicorp in 2004 and acquired by Yahoo
  in 2005. In addition to being a popular website for users to share and embed personal
  photographs, and effectively an online community, the service is widely used by
  photo researchers and by bloggers to host images that they embed in blogs and social
  media.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flickr-logo.jpg
x-kinRank: "9"
x-alexaRank: "0"
tags: Auth
created: "2018-08-25"
modified: "2018-08-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/auth/master/_listings/flickr/apis.md
specificationVersion: "0.14"
apis:
- name: Flickr - Auth Check Token
  x-api-slug: restmethodflickr-auth-checktoken-get
  description: Returns the credentials attached to an authentication token. This call
    must be signed as specified in the authentication API spec.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flickr-logo.jpg
  humanURL: http://www.flickr.com/
  baseURL: https://api.flickr.com//services/
  tags: Images, My API Stack, Imports, Stack Network, Stack, Media, Photos, Getting
    Started Example, API Provider, Photos, Photos, Profiles, General Data, Relative
    Data, Pedestal, Historical Data API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/auth/master/_listings/flickr/restmethodflickr-auth-checktoken-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/auth/master/_listings/flickr/restmethodflickr-auth-checktoken-get-openapi.md
- name: Flickr - Auth Get Frob
  x-api-slug: restmethodflickr-auth-getfrob-get
  description: Returns a frob to be used during authentication. This method call must
    be signed, and is deprecated in favour of OAuth.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flickr-logo.jpg
  humanURL: http://www.flickr.com/
  baseURL: https://api.flickr.com//services/
  tags: Images, My API Stack, Imports, Stack Network, Stack, Media, Photos, Getting
    Started Example, API Provider, Photos, Photos, Profiles, General Data, Relative
    Data, Pedestal, Historical Data API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/auth/master/_listings/flickr/restmethodflickr-auth-getfrob-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/auth/master/_listings/flickr/restmethodflickr-auth-getfrob-get-openapi.md
- name: Flickr - Auth Get Full Token
  x-api-slug: restmethodflickr-auth-getfulltoken-get
  description: Get the full authentication token for a mini-token. This method call
    must be signed.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flickr-logo.jpg
  humanURL: http://www.flickr.com/
  baseURL: https://api.flickr.com//services/
  tags: Images, My API Stack, Imports, Stack Network, Stack, Media, Photos, Getting
    Started Example, API Provider, Photos, Photos, Profiles, General Data, Relative
    Data, Pedestal, Historical Data API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/auth/master/_listings/flickr/restmethodflickr-auth-getfulltoken-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/auth/master/_listings/flickr/restmethodflickr-auth-getfulltoken-get-openapi.md
- name: Flickr - Auth Get Token
  x-api-slug: restmethodflickr-auth-gettoken-get
  description: Returns the auth token for the given frob, if one has been attached.
    This method call must be signed, and is deprecated in favour of OAuth.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flickr-logo.jpg
  humanURL: http://www.flickr.com/
  baseURL: https://api.flickr.com//services/
  tags: Images, My API Stack, Imports, Stack Network, Stack, Media, Photos, Getting
    Started Example, API Provider, Photos, Photos, Profiles, General Data, Relative
    Data, Pedestal, Historical Data API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/auth/master/_listings/flickr/restmethodflickr-auth-gettoken-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/auth/master/_listings/flickr/restmethodflickr-auth-gettoken-get-openapi.md
- name: Flickr - Auth Oauth Get Access Token
  x-api-slug: restmethodflickr-auth-oauth-getaccesstoken-get
  description: Exchange an auth token from the old Authentication API, to an OAuth
    access token. Calling this method will delete the auth token used to make the
    request. The request must be signed.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flickr-logo.jpg
  humanURL: http://www.flickr.com/
  baseURL: https://api.flickr.com//services/
  tags: Images, My API Stack, Imports, Stack Network, Stack, Media, Photos, Getting
    Started Example, API Provider, Photos, Photos, Profiles, General Data, Relative
    Data, Pedestal, Historical Data API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/auth/master/_listings/flickr/restmethodflickr-auth-oauth-getaccesstoken-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/auth/master/_listings/flickr/restmethodflickr-auth-oauth-getaccesstoken-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://flat.api.gallery.streamdata.io
- type: x-api-stack
  url: http://flickr.stack.network
- type: x-authentication
  url: https://www.flickr.com/services/api/auth.oauth.html
- type: x-base
  url: https://api.flickr.com/services/
- type: x-developer
  url: https://www.flickr.com/services/api/
- type: x-getting-started
  url: https://www.flickr.com/services/developer/
- type: x-privacy
  url: https://info.yahoo.com/privacy/us/yahoo/flickr/details.html
- type: x-support
  url: https://help.yahoo.com/kb/flickr-for-desktop
- type: x-terms-of-service
  url: https://www.flickr.com/services/api/tos/
- type: x-twitter
  url: https://twitter.com/flickr
- type: x-website
  url: http://www.flickr.com/
- type: x-website
  url: http://flickr.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---