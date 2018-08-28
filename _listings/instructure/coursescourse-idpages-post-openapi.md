---
swagger: "2.0"
x-collection-name: Instructure
x-complete: 0
info:
  title: Instructure Canvas Courses API Create page
  description: Create page.
  termsOfService: https://www.canvaslms.com/policies/api-policy
  version: v1
host: canvas.instructure.com
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /courses/{course_id}/pages:
    get:
      summary: List pages
      description: List pages.
      operationId: list-pages
      x-api-path-slug: coursescourse-idpages-get
      parameters:
      - in: query
        name: order
        description: The sorting order
      - in: query
        name: published
        description: If true, include only published paqes
      - in: query
        name: search_term
        description: The partial title of the pages to match and return
      - in: query
        name: sort
        description: Sort results by this field
      responses:
        200:
          description: OK
      tags:
      - Courses
      - Course
      - Id
      - Pages
    post:
      summary: Create page
      description: Create page.
      operationId: create-page
      x-api-path-slug: coursescourse-idpages-post
      parameters:
      - in: query
        name: wiki_page[body]
        description: The content for the new page
      - in: query
        name: wiki_page[editing_roles]
        description: Which user roles are allowed to edit this page
      - in: query
        name: wiki_page[front_page]
        description: Set an unhidden page as the front page (if true)
      - in: query
        name: wiki_page[notify_of_update]
        description: Whether participants should be notified when this page changes
      - in: query
        name: wiki_page[published]
        description: Whether the page is published (true) or draft state (false)
      - in: query
        name: wiki_page[title]
        description: The title for the new page
      responses:
        200:
          description: OK
      tags:
      - Courses
      - Course
      - Id
      - Pages
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