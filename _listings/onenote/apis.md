---
name: OneNote
x-slug: onenote
description: Microsoft OneNote (formerly called Microsoft Office OneNote) is a computer
  program for free-form information gathering and multi-user collaboration. It gathers
  users notes (handwritten or typed), drawings, screen clippings and audio commentaries.
  Notes can be shared with other OneNote users over the Internet or a network. OneNote
  is available as a part of the Microsoft Office suite. It is also available as a
  free stand-alone application for Windows, Mac, Windows RT, Windows Phone, iOS, Android
  and Symbian.[4] A web-based version of OneNote is provided as part of OneDrive or
  Office Online and enables users to edit notes via a web browser.
image: https://s3.amazonaws.com/kinlane-productions/api-evangelist/api-butterfly.png
x-kinRank: "7"
x-alexaRank: "5531"
tags: Pages
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/onenote/apis.md
specificationVersion: "0.14"
apis:
- name: One Note Get Pages Pageid Content
  x-api-slug: one-note
  description: Returns HTML content of the specified page.
  image: https://s3.amazonaws.com/kinlane-productions/api-evangelist/api-butterfly.png
  humanURL: http://onenote.com
  baseURL: https://www.onenote.com//api/v1.0/me/notes///pages/{pageId}/content
  tags: Pages,PageId,Content
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/onenote/pagespageidcontent-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/onenote/pagespageidcontent-get-openapi.md
- name: One Note Parameters Pages Pageid Content
  x-api-slug: one-note
  description: Parameters pages pageid content.
  image: https://s3.amazonaws.com/kinlane-productions/api-evangelist/api-butterfly.png
  humanURL: http://onenote.com
  baseURL: https://www.onenote.com//api/v1.0/me/notes///pages/{pageId}/content
  tags: Pages,PageId,Content
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/onenote/pagespageidcontent-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/onenote/pagespageidcontent-parameters-openapi.md
- name: One Note Delete Pages Pageid
  x-api-slug: one-note
  description: Deletes the specified page.
  image: https://s3.amazonaws.com/kinlane-productions/api-evangelist/api-butterfly.png
  humanURL: http://onenote.com
  baseURL: https://www.onenote.com//api/v1.0/me/notes///pages/{pageId}
  tags: Pages,PageId
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/onenote/pagespageid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/onenote/pagespageid-delete-openapi.md
- name: One Note Get Pages Pageid
  x-api-slug: one-note
  description: Returns the specified page.
  image: https://s3.amazonaws.com/kinlane-productions/api-evangelist/api-butterfly.png
  humanURL: http://onenote.com
  baseURL: https://www.onenote.com//api/v1.0/me/notes///pages/{pageId}
  tags: Pages,PageId
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/onenote/pagespageid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/onenote/pagespageid-get-openapi.md
- name: One Note Parameters Pages Pageid
  x-api-slug: one-note
  description: Parameters pages pageid.
  image: https://s3.amazonaws.com/kinlane-productions/api-evangelist/api-butterfly.png
  humanURL: http://onenote.com
  baseURL: https://www.onenote.com//api/v1.0/me/notes///pages/{pageId}
  tags: Pages,PageId
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/onenote/pagespageid-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/onenote/pagespageid-parameters-openapi.md
- name: One Note Get Sections Sectionid Pages
  x-api-slug: one-note
  description: Get the pages (metadata) in the specified section.
  image: https://s3.amazonaws.com/kinlane-productions/api-evangelist/api-butterfly.png
  humanURL: http://onenote.com
  baseURL: https://www.onenote.com//api/v1.0/me/notes///sections/{sectionId}/pages
  tags: Sections,SectionId,Pages
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/onenote/sectionssectionidpages-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/onenote/sectionssectionidpages-get-openapi.md
- name: One Note Post Sections Sectionid Pages
  x-api-slug: one-note
  description: Creates a new page in a specific section.
  image: https://s3.amazonaws.com/kinlane-productions/api-evangelist/api-butterfly.png
  humanURL: http://onenote.com
  baseURL: https://www.onenote.com//api/v1.0/me/notes///sections/{sectionId}/pages
  tags: Sections,SectionId,Pages
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/onenote/sectionssectionidpages-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/onenote/sectionssectionidpages-post-openapi.md
- name: One Note Parameters Sections Sectionid Pages
  x-api-slug: one-note
  description: Parameters sections sectionid pages.
  image: https://s3.amazonaws.com/kinlane-productions/api-evangelist/api-butterfly.png
  humanURL: http://onenote.com
  baseURL: https://www.onenote.com//api/v1.0/me/notes///sections/{sectionId}/pages
  tags: Sections,SectionId,Pages
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/onenote/sectionssectionidpages-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/onenote/sectionssectionidpages-parameters-openapi.md
- name: One Note Get Pages
  x-api-slug: one-note
  description: Get the pages (metadata) from all notebooks in OneDrive that are owned
    by the user.
  image: https://s3.amazonaws.com/kinlane-productions/api-evangelist/api-butterfly.png
  humanURL: http://onenote.com
  baseURL: https://www.onenote.com//api/v1.0/me/notes///pages
  tags: Pages
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/onenote/pages-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/onenote/pages-get-openapi.md
- name: One Note Post Pages
  x-api-slug: one-note
  description: Creates a new page in the default notebook and section.
  image: https://s3.amazonaws.com/kinlane-productions/api-evangelist/api-butterfly.png
  humanURL: http://onenote.com
  baseURL: https://www.onenote.com//api/v1.0/me/notes///pages
  tags: Pages
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/onenote/pages-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/onenote/pages-post-openapi.md
- name: One Note Parameters Pages
  x-api-slug: one-note
  description: Parameters pages.
  image: https://s3.amazonaws.com/kinlane-productions/api-evangelist/api-butterfly.png
  humanURL: http://onenote.com
  baseURL: https://www.onenote.com//api/v1.0/me/notes///pages
  tags: Pages
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/onenote/pages-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/onenote/pages-parameters-openapi.md
- name: One Note Get Pages Pageid Preview
  x-api-slug: one-note
  description: Returns preview text and (if there is one) a preview image for the
    specified page.
  image: https://s3.amazonaws.com/kinlane-productions/api-evangelist/api-butterfly.png
  humanURL: http://onenote.com
  baseURL: https://www.onenote.com//api/v1.0/me/notes///pages/{pageId}/preview
  tags: Pages,PageId,Preview
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/onenote/pagespageidpreview-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/onenote/pagespageidpreview-get-openapi.md
- name: One Note
  x-api-slug: one-note
  description: Microsoft OneNote (formerly called Microsoft Office OneNote) is a computer
    program for free-form information gathering and multi-user collaboration. It gathers
    users notes (handwritten or typed), drawings, screen clippings and audio commentaries.
    Notes can be shared with other OneNote users over the Internet or a network. OneNote
    is available as a part of the Microsoft Office suite. It is also available as
    a free stand-alone application for Windows, Mac, Windows RT, Windows Phone, iOS,
    Android and Symbian.[4] A web-based version of OneNote is provided as part of
    OneDrive or Office Online and enables users to edit notes via a web browser.
  image: https://s3.amazonaws.com/kinlane-productions/api-evangelist/api-butterfly.png
  humanURL: http://onenote.com
  baseURL: https://www.onenote.com//api/v1.0/me/notes/
  tags: Pages
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pages/master/_listings/onenote/openapi.md
x-common:
- type: x-application-gallery
  url: http://dev.office.com/showcase
- type: x-blog
  url: http://blogs.msdn.com/b/onenotedev/
- type: x-blog-rss
  url: http://blogs.msdn.com/b/onenotedev/rss.aspx
- type: x-console
  url: https://apigee.com/onenote/embed/console/onenote
- type: x-developer
  url: http://dev.onenote.com/
- type: x-getting-started
  url: http://msdn.microsoft.com/en-us/library/office/dn575425.aspx
- type: x-github
  url: https://github.com/OneNoteDev
- type: x-twitter
  url: https://twitter.com/OneNoteDev
- type: x-privacy
  url: http://go.microsoft.com/fwlink/?LinkId=391953&clcid=0x409
- type: x-stack-overflow
  url: http://stackoverflow.com/questions/tagged/onenote
- type: x-terms-of-service
  url: http://go.microsoft.com/fwlink/?LinkId=391954&clcid=0x409
- type: x-trademarks
  url: http://go.microsoft.com/fwlink/p/?LinkId=316970
- type: x-website
  url: http://onenote.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---