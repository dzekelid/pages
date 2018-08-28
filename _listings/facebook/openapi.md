---
swagger: "2.0"
x-collection-name: Facebook
x-complete: 1
info:
  title: Facebook Graph (Achievement Type) API
  description: api-for-managing-facebook-achievement-types
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
  /&#123;user-id&#125;/ids_for_pages:
    get:
      summary: Get User S For Pages
      description: User Ids For Pages
      operationId: getUserSForPages
      x-api-path-slug: 123userid125ids-for-pages-get
      parameters:
      - in: query
        name: "100"
        description: Invalid parameter
        type: string
      responses:
        200:
          description: OK
      tags:
      - User
      - S
      - Pages
---