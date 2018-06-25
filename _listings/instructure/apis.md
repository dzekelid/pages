---
name: Instructure
x-slug: instructure
description: Instructure makes software that makes smarter people. Products include
  Canvas LMS, Bridge and Canvas Network.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
x-kinRank: "8"
x-alexaRank: "367"
tags: Pages
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/instructure/apis.md
specificationVersion: "0.14"
apis:
- name: Instructure Canvas Courses API List pages
  x-api-slug: instructure-canvas-courses-api
  description: List pages.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/pages
  tags: Courses,Course,Id,Pages
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/instructure/coursescourse-idpages-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/instructure/coursescourse-idpages-get-openapi.md
- name: Instructure Canvas Courses API Create page
  x-api-slug: instructure-canvas-courses-api
  description: Create page.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/pages
  tags: Courses,Course,Id,Pages
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/instructure/coursescourse-idpages-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/instructure/coursescourse-idpages-post-openapi.md
- name: Instructure Canvas Courses API Delete page
  x-api-slug: instructure-canvas-courses-api
  description: Delete page.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/pages/url
  tags: Courses,Course,Id,Pages,Url
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/instructure/coursescourse-idpagesurl-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/instructure/coursescourse-idpagesurl-delete-openapi.md
- name: Instructure Canvas Courses API Show page
  x-api-slug: instructure-canvas-courses-api
  description: Show page.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/pages/url
  tags: Courses,Course,Id,Pages,Url
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/instructure/coursescourse-idpagesurl-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/instructure/coursescourse-idpagesurl-get-openapi.md
- name: Instructure Canvas Courses API Update/create page
  x-api-slug: instructure-canvas-courses-api
  description: Update/create page.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/pages/url
  tags: Courses,Course,Id,Pages,Url
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/instructure/coursescourse-idpagesurl-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/instructure/coursescourse-idpagesurl-put-openapi.md
- name: Instructure Canvas Courses API List revisions
  x-api-slug: instructure-canvas-courses-api
  description: List revisions.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/pages/url/revisions
  tags: Courses,Course,Id,Pages,Url,Revisions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/instructure/coursescourse-idpagesurlrevisions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/instructure/coursescourse-idpagesurlrevisions-get-openapi.md
- name: Instructure Canvas Courses API Show revision
  x-api-slug: instructure-canvas-courses-api
  description: Show revision.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/pages/url/revisions/latest
  tags: Courses,Course,Id,Pages,Url,Revisions,Latest
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/instructure/coursescourse-idpagesurlrevisionslatest-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/instructure/coursescourse-idpagesurlrevisionslatest-get-openapi.md
- name: Instructure Canvas Courses API Show revision
  x-api-slug: instructure-canvas-courses-api
  description: Show revision.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/pages/url/revisions/{revision_id}
  tags: Courses,Course,Id,Pages,Url,Revisions,Revision,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/instructure/coursescourse-idpagesurlrevisionsrevision-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/instructure/coursescourse-idpagesurlrevisionsrevision-id-get-openapi.md
- name: Instructure Canvas Courses API Revert to revision
  x-api-slug: instructure-canvas-courses-api
  description: Revert to revision.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/pages/url/revisions/{revision_id}
  tags: Courses,Course,Id,Pages,Url,Revisions,Revision,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/instructure/coursescourse-idpagesurlrevisionsrevision-id-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/instructure/coursescourse-idpagesurlrevisionsrevision-id-post-openapi.md
- name: Instructure Canvas Courses API
  x-api-slug: instructure-canvas-courses-api
  description: Instructure makes software that makes smarter people. Products include
    Canvas LMS, Bridge and Canvas Network.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1
  tags: Pages
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/instructure/openapi.md
- name: Instructure Canvas Groups API List pages
  x-api-slug: instructure-canvas-groups-api
  description: List pages.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//groups/{group_id}/pages
  tags: Groups,Group,Id,Pages
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/instructure/groupsgroup-idpages-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/instructure/groupsgroup-idpages-get-openapi.md
- name: Instructure Canvas Groups API Create page
  x-api-slug: instructure-canvas-groups-api
  description: Create page.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//groups/{group_id}/pages
  tags: Groups,Group,Id,Pages
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/instructure/groupsgroup-idpages-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/instructure/groupsgroup-idpages-post-openapi.md
- name: Instructure Canvas Groups API Delete page
  x-api-slug: instructure-canvas-groups-api
  description: Delete page.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//groups/{group_id}/pages/url
  tags: Groups,Group,Id,Pages,Url
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/instructure/groupsgroup-idpagesurl-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/instructure/groupsgroup-idpagesurl-delete-openapi.md
- name: Instructure Canvas Groups API Show page
  x-api-slug: instructure-canvas-groups-api
  description: Show page.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//groups/{group_id}/pages/url
  tags: Groups,Group,Id,Pages,Url
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/instructure/groupsgroup-idpagesurl-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/instructure/groupsgroup-idpagesurl-get-openapi.md
- name: Instructure Canvas Groups API Update/create page
  x-api-slug: instructure-canvas-groups-api
  description: Update/create page.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//groups/{group_id}/pages/url
  tags: Groups,Group,Id,Pages,Url
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/instructure/groupsgroup-idpagesurl-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/instructure/groupsgroup-idpagesurl-put-openapi.md
- name: Instructure Canvas Groups API List revisions
  x-api-slug: instructure-canvas-groups-api
  description: List revisions.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//groups/{group_id}/pages/url/revisions
  tags: Groups,Group,Id,Pages,Url,Revisions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/instructure/groupsgroup-idpagesurlrevisions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/instructure/groupsgroup-idpagesurlrevisions-get-openapi.md
- name: Instructure Canvas Groups API Show revision
  x-api-slug: instructure-canvas-groups-api
  description: Show revision.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//groups/{group_id}/pages/url/revisions/latest
  tags: Groups,Group,Id,Pages,Url,Revisions,Latest
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/instructure/groupsgroup-idpagesurlrevisionslatest-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/instructure/groupsgroup-idpagesurlrevisionslatest-get-openapi.md
- name: Instructure Canvas Groups API Show revision
  x-api-slug: instructure-canvas-groups-api
  description: Show revision.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//groups/{group_id}/pages/url/revisions/{revision_id}
  tags: Groups,Group,Id,Pages,Url,Revisions,Revision,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/instructure/groupsgroup-idpagesurlrevisionsrevision-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/instructure/groupsgroup-idpagesurlrevisionsrevision-id-get-openapi.md
- name: Instructure Canvas Groups API Revert to revision
  x-api-slug: instructure-canvas-groups-api
  description: Revert to revision.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//groups/{group_id}/pages/url/revisions/{revision_id}
  tags: Groups,Group,Id,Pages,Url,Revisions,Revision,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/instructure/groupsgroup-idpagesurlrevisionsrevision-id-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/instructure/groupsgroup-idpagesurlrevisionsrevision-id-post-openapi.md
- name: Instructure Canvas Groups API
  x-api-slug: instructure-canvas-groups-api
  description: Instructure makes software that makes smarter people. Products include
    Canvas LMS, Bridge and Canvas Network.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1
  tags: Pages
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/instructure/openapi.md
x-common:
- type: x-blog
  url: http://blog.instructure.com
- type: x-blog-rss
  url: http://voice.instructure.com/CMS/UI/Modules/BizBlogger/rss.aspx?tabid=772438&moduleid=1638884&maxcount=25&t=415c2e5d197a4d6f7cdcc81385b677f1
- type: x-crunchbase
  url: https://crunchbase.com/organization/instructure
- type: x-crunchbase
  url: http://www.crunchbase.com/company/instructure
- type: x-email
  url: info@instructure.com
- type: x-email
  url: jobs@instructure.com
- type: x-email
  url: privacy@instructure.com
- type: x-email
  url: legal@instructure.com
- type: x-github
  url: https://github.com/instructure
- type: x-twitter
  url: https://twitter.com/instructure
- type: x-website
  url: http://instructure.com
- type: x-website
  url: https://canvas.instructure.com/doc/api/index.html
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---