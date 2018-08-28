---
swagger: "2.0"
x-collection-name: Facebook
x-complete: 0
info:
  title: Facebook Get User Assigned Pages
  description: User Assigned Pages
  termsOfService: https://www.facebook.com/policies/
  version: 1.0.0
host: graph.facebook.com
basePath: /v3.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /&#123;pages-platform-component-flow-service-config-id&#125;:
    get:
      summary: Get Pages Platform Component Flow Service Config
      description: Pages Platform Component Flow Service Config
      operationId: getPagesPlatformComponentFlowServiceConfig
      x-api-path-slug: 123pagesplatformcomponentflowserviceconfigid125-get
      parameters:
      - in: query
        name: deeplinkstring
        description: The deeplink to open the flow
        type: string
      - in: query
        name: flow_categoryenum
        description: The category of the flow
        type: string
      - in: query
        name: idnumeric string
        description: Id
        type: string
      - in: query
        name: labelstring
        description: The label of the entry point that enters the flow
        type: string
      responses:
        200:
          description: OK
      tags:
      - Pages
      - Platform
      - Component
      - Flow
      - Service
      - Config
  /&#123;user-id&#125;/assigned_pages:
    get:
      summary: Get User Assigned Pages
      description: User Assigned Pages
      operationId: getUserAssignedPages
      x-api-path-slug: 123userid125assigned-pages-get
      parameters:
      - in: query
        name: permitted_rolesliststring
        description: Roles that are assignable on this object
        type: string
      - in: query
        name: rolestring
        description: Role of this particular user on this objectDefault
        type: string
      - in: query
        name: tasksliststring
        description: All unpacked roles/tasks of this particular user on this object
        type: string
      responses:
        200:
          description: OK
      tags:
      - User
      - Assigned
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