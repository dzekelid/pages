swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 1
info:
  title: plentymarkets REST-API
  description: the-plentymarkets-rest-api-expands-the-functionality-of-the-plentymarkets-cms-and-allows-access-to-resources-i-e--data-records-via-unique-uri-paths
  contact:
    name: plentymarkets
    url: https://forum.plentymarkets.com/c/rest-api
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/shop_builder/pages:
    get:
      summary: List content pages from all plugins in a given plugin set.
      description: List content pages from all plugins in a given plugin set..
      operationId: getRestShopBuilderPages
      x-api-path-slug: restshop-builderpages-get
      responses:
        200:
          description: OK
      tags:
      - List
      - Content
      - Pages
      - From
      - ""
      - Plugins
      - In
      - Given
      - Plugin
      - Set