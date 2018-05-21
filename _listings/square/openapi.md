---
swagger: "2.0"
x-collection-name: Square
x-complete: 1
info:
  title: Square Connect API
  description: client-library-for-accessing-the-square-connect-apis
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
  /{location_id}/pages/{page_id}/cells:
    put:
      summary: Put Location Pages Page Cells
      description: Modifies a cell of a Favorites page in Square Register.
      operationId: putLocationPagesPageCells
      x-api-path-slug: location-idpagespage-idcells-put
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
        description: The ID of the page the cell belongs to
      responses:
        200:
          description: OK
      tags:
      - Location
      - Pages
      - Page
      - Cells
    delete:
      summary: Delete Location Pages Page Cells
      description: Deletes a cell from a Favorites page in Square Register.
      operationId: deleteLocationPagesPageCells
      x-api-path-slug: location-idpagespage-idcells-delete
      parameters:
      - in: query
        name: column
        description: The column of the cell to clear
      - in: path
        name: location_id
        description: The ID of the Favorites pages associated location
      - in: path
        name: page_id
        description: The ID of the page to delete
      - in: query
        name: row
        description: The row of the cell to clear
      responses:
        200:
          description: OK
      tags:
      - Location
      - Pages
      - Page
      - Cells
---