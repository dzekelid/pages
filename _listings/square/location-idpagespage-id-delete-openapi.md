---
swagger: "2.0"
x-collection-name: Square
x-complete: 0
info:
  title: Square Connect API Delete Location Pages Page
  description: Deletes an existing Favorites page and all of its cells.
  termsOfService: https://connect.squareup.com/tos
  contact:
    name: Square Developer Platform
    url: https://squareup.com/developers
    email: developers@squareup.com
  version: 1.0.0
host: connect.squareup.com
basePath: v1/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{location_id}/pages:
    post:
      summary: Post Location Pages
      description: Creates a Favorites page in Square Register.
      operationId: postLocationPages
      x-api-path-slug: location-idpages-post
      parameters:
      - in: body
        name: body
        description: An object containing the fields to POST for the request
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: location_id
        description: The ID of the location to create an item for
      responses:
        200:
          description: OK
      tags:
      - Location
      - Pages
    get:
      summary: Get Location Pages
      description: Lists all of a location's Favorites pages in Square Register.
      operationId: getLocationPages
      x-api-path-slug: location-idpages-get
      parameters:
      - in: path
        name: location_id
        description: The ID of the location to list Favorites pages for
      responses:
        200:
          description: OK
      tags:
      - Location
      - Pages
  /{location_id}/pages/{page_id}:
    put:
      summary: Put Location Pages Page
      description: Modifies the details of a Favorites page in Square Register.
      operationId: putLocationPagesPage
      x-api-path-slug: location-idpagespage-id-put
      parameters:
      - in: body
        name: body
        description: An object containing the fields to POST for the request
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: location_id
        description: The ID of the Favorites pages associated location
      - in: path
        name: page_id
        description: The ID of the page to modify
      responses:
        200:
          description: OK
      tags:
      - Location
      - Pages
      - Page
    delete:
      summary: Delete Location Pages Page
      description: Deletes an existing Favorites page and all of its cells.
      operationId: deleteLocationPagesPage
      x-api-path-slug: location-idpagespage-id-delete
      parameters:
      - in: path
        name: location_id
        description: The ID of the Favorites pages associated location
      - in: path
        name: page_id
        description: The ID of the page to delete
      responses:
        200:
          description: OK
      tags:
      - Location
      - Pages
      - Page
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---