---
swagger: "2.0"
x-collection-name: OneNote
x-complete: 0
info:
  title: One Note Post Sections Sectionid Pages
  description: Creates a new page in a specific section.
  version: 1.0.0
host: www.onenote.com
basePath: /api/v1.0/me/notes/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /pages/{pageId}/content:
    get:
      summary: Get Pages Pageid Content
      description: Returns HTML content of the specified page.
      operationId: getPagesPageContent
      x-api-path-slug: pagespageidcontent-get
      parameters:
      - in: header
        name: Accept
        description: 'Required: indicates type of content returned in the response'
      - in: query
        name: Accept
        description: 'Required: indicates type of content returned in the response'
      - in: query
        name: includeIDs
        description: 'Optional: set to true to get generated IDs to use for PATCH
          operations'
      - in: path
        name: pageId
        description: Specifies the page whose content you want to retrieve
      responses:
        200:
          description: OK
      tags:
      - Pages
      - PageId
      - Content
    parameters:
      summary: Parameters Pages Pageid Content
      description: Parameters pages pageid content.
      operationId: parametersPagesPageContent
      x-api-path-slug: pagespageidcontent-parameters
      responses:
        200:
          description: OK
      tags:
      - Pages
      - PageId
      - Content
  /pages/{pageId}:
    delete:
      summary: Delete Pages Pageid
      description: Deletes the specified page.
      operationId: deletePagesPage
      x-api-path-slug: pagespageid-delete
      parameters:
      - in: path
        name: pageId
        description: Specifies the page to delete
      responses:
        200:
          description: OK
      tags:
      - Pages
      - PageId
    get:
      summary: Get Pages Pageid
      description: Returns the specified page.
      operationId: getPagesPage
      x-api-path-slug: pagespageid-get
      parameters:
      - in: query
        name: expand
        description: The navigation properties (parentNotebook or parentSection) to
          return inline in the response
      - in: path
        name: pageId
        description: Specifies the page to get
      - in: query
        name: pagelevel
        description: true, to return the level and order properties
      - in: query
        name: select
        description: The properties to return
      responses:
        200:
          description: OK
      tags:
      - Pages
      - PageId
    parameters:
      summary: Parameters Pages Pageid
      description: Parameters pages pageid.
      operationId: parametersPagesPage
      x-api-path-slug: pagespageid-parameters
      responses:
        200:
          description: OK
      tags:
      - Pages
      - PageId
  /sections/{sectionId}/pages:
    get:
      summary: Get Sections Sectionid Pages
      description: Get the pages (metadata) in the specified section.
      operationId: getSectionsSectionPages
      x-api-path-slug: sectionssectionidpages-get
      parameters:
      - in: query
        name: count
        description: true, to return the number of entities in the collection
      - in: query
        name: expand
        description: The navigation properties (parentNotebook or parentSection) to
          return inline in the response
      - in: query
        name: filter
        description: The filter for the query
      - in: query
        name: orderby
        description: The property to order by
      - in: query
        name: pagelevel
        description: true, to return the level and order properties for pages
      - in: query
        name: search
        description: The term or phrase to search for
      - in: path
        name: sectionId
        description: Specifies the section that contains the pages
      - in: query
        name: select
        description: The properties to return
      - in: query
        name: skip
        description: The number of entities to skip in the result set
      - in: query
        name: top
        description: The number of entities to return from the result set
      responses:
        200:
          description: OK
      tags:
      - Sections
      - SectionId
      - Pages
    post:
      summary: Post Sections Sectionid Pages
      description: Creates a new page in a specific section.
      operationId: postSectionsSectionPages
      x-api-path-slug: sectionssectionidpages-post
      parameters:
      - in: header
        name: Content-Type
        description: 'Required: indicates type of content sent'
      - in: query
        name: Content-Type
        description: 'Required: indicates type of content sent'
      - in: path
        name: sectionId
        description: Specifies the section to create the page in
      responses:
        200:
          description: OK
      tags:
      - Sections
      - SectionId
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