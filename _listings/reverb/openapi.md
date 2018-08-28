swagger: "2.0"
x-collection-name: Reverb
x-complete: 1
info:
  title: reverb
  description: reverb
  termsOfService: https://reverb.com/page/terms
  contact:
    name: Reverb API
    url: https://dev.reverb.com
    email: integrations@reverb.com
  version: "3.0"
host: api.reverb.com
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /comparison_shopping_pages:
    get:
      summary: Get Comparison Shopping Pages
      description: Returns a set of comparison shopping pages based on the current
        params
      operationId: getComparisonShoppingPages
      x-api-path-slug: comparison-shopping-pages-get
      responses:
        200:
          description: OK
      tags:
      - Comparison
      - Shopping
      - Pages
  /comparison_shopping_pages/find:
    get:
      summary: Get Comparison Shopping Pages Find
      description: Get comparison shopping pages find.
      operationId: getComparisonShoppingPagesFind
      x-api-path-slug: comparison-shopping-pagesfind-get
      parameters:
      - in: query
        name: id
        description: ID of the comparison shopping page
      - in: query
        name: slug
        description: Slug of the comparison shopping page
      responses:
        200:
          description: OK
      tags:
      - Comparison
      - Shopping
      - Pages
      - Find
  /comparison_shopping_pages/{id}:
    get:
      summary: Get Comparison Shopping Pages
      description: Get comparison shopping pages.
      operationId: getComparisonShoppingPages
      x-api-path-slug: comparison-shopping-pagesid-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Comparison
      - Shopping
      - Pages
      - Id
  /comparison_shopping_pages/{id}/listings:
    get:
      summary: Get Comparison Shopping Pages Listings
      description: Return new or used listings for a comparison shopping page
      operationId: getComparisonShoppingPagesListings
      x-api-path-slug: comparison-shopping-pagesidlistings-get
      parameters:
      - in: query
        name: condition
        description: Condition of the listing
      - in: path
        name: id
      - in: query
        name: offset
      - in: query
        name: page
      - in: query
        name: per_page
      responses:
        200:
          description: OK
      tags:
      - Comparison
      - Shopping
      - Pages
      - Id
      - Listings
  /comparison_shopping_pages/{id}/reviews:
    get:
      summary: Get Comparison Shopping Pages Reviews
      description: View reviews of a comparison shopping page
      operationId: getComparisonShoppingPagesReviews
      x-api-path-slug: comparison-shopping-pagesidreviews-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Comparison
      - Shopping
      - Pages
      - Id
      - Reviews