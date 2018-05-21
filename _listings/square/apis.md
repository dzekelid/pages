---
name: Square
x-slug: square
description: Starting with a free credit card reader for the iPhone, iPad, and Android
  devices, Square Reader allows anyone to accept credit cards anywhere, anytime, for
  a low transaction rate of 2.75 percent per swipe, with no hidden fees. Square Register
  serves as a full point-of-sale system for businesses to accept payments, manage
  items, and share menu and location information. Square Wallet, available in the
  US, is the most seamless way to pay, enabling individuals to pay at their favorite
  local businesses, discover new ones nearby, explore menu listings, and store receipts.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/square-logo.png
x-kinRank: "9"
x-alexaRank: ""
tags: Pages
created: "2018-05-20"
modified: "2018-05-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/square/apis.md
specificationVersion: "0.14"
apis:
- name: Square Connect API Post Location Pages
  x-api-slug: square-connect-api
  description: Creates a Favorites page in Square Register.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/square-logo.png
  humanURL: https://squareup.com
  baseURL: https://connect.squareup.com/v1///{location_id}/pages
  tags: Location,Pages
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/square/location-idpages-post-openapi.md
- name: Square Connect API Get Location Pages
  x-api-slug: square-connect-api
  description: Lists all of a location's Favorites pages in Square Register.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/square-logo.png
  humanURL: https://squareup.com
  baseURL: https://connect.squareup.com/v1///{location_id}/pages
  tags: Location,Pages
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/square/location-idpages-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/square/location-idpages-get-openapi.md
- name: Square Connect API Put Location Pages Page
  x-api-slug: square-connect-api
  description: Modifies the details of a Favorites page in Square Register.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/square-logo.png
  humanURL: https://squareup.com
  baseURL: https://connect.squareup.com/v1///{location_id}/pages/{page_id}
  tags: Location,Pages,Page
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/square/location-idpagespage-id-put-openapi.md
- name: Square Connect API Delete Location Pages Page
  x-api-slug: square-connect-api
  description: Deletes an existing Favorites page and all of its cells.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/square-logo.png
  humanURL: https://squareup.com
  baseURL: https://connect.squareup.com/v1///{location_id}/pages/{page_id}
  tags: Location,Pages,Page
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/square/location-idpagespage-id-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/square/location-idpagespage-id-delete-openapi.md
- name: Square Connect API Put Location Pages Page Cells
  x-api-slug: square-connect-api
  description: Modifies a cell of a Favorites page in Square Register.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/square-logo.png
  humanURL: https://squareup.com
  baseURL: https://connect.squareup.com/v1///{location_id}/pages/{page_id}/cells
  tags: Location,Pages,Page,Cells
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/square/location-idpagespage-idcells-put-openapi.md
- name: Square Connect API Delete Location Pages Page Cells
  x-api-slug: square-connect-api
  description: Deletes a cell from a Favorites page in Square Register.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/square-logo.png
  humanURL: https://squareup.com
  baseURL: https://connect.squareup.com/v1///{location_id}/pages/{page_id}/cells
  tags: Location,Pages,Page,Cells
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/square/location-idpagespage-idcells-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/square/location-idpagespage-idcells-delete-openapi.md
- name: Square Connect API
  x-api-slug: square-connect-api
  description: Starting with a free credit card reader for the iPhone, iPad, and Android
    devices, Square Reader allows anyone to accept credit cards anywhere, anytime,
    for a low transaction rate of 2.75 percent per swipe, with no hidden fees. Square
    Register serves as a full point-of-sale system for businesses to accept payments,
    manage items, and share menu and location information. Square Wallet, available
    in the US, is the most seamless way to pay, enabling individuals to pay at their
    favorite local businesses, discover new ones nearby, explore menu listings, and
    store receipts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/square-logo.png
  humanURL: https://squareup.com
  baseURL: https://connect.squareup.com/v1/
  tags: Pages
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/square/openapi.md
x-common:
- type: x-base
  url: https://connect.squareup.com
- type: x-crunchbase
  url: http://www.crunchbase.com/company/square
- type: x-developer
  url: https://connect.squareup.com/
- type: x-github
  url: https://github.com/square
- type: x-twitter
  url: https://twitter.com/Square
- type: x-website
  url: https://squareup.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---