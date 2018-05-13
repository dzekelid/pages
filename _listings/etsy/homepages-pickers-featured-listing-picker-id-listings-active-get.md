---
swagger: "2.0"
info:
  title: Etsy Get Homepages Pickers Featured Listing Picker Listings Active
  description: Retrieves a set of Listing objects associated to a FeaturedListingPicker
    in scope active.
  version: 1.0.0
host: openapi.etsy.com
basePath: /v2/private
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /homepages/pickers/{featured_listing_picker_id}/listings/active:
    get:
      summary: Get Homepages Pickers Featured Listing Picker Listings Active
      description: Retrieves a set of Listing objects associated to a FeaturedListingPicker
        in scope active
      operationId: getHomepagesPickersFeaturedListingPickerListingsActive
      responses:
        200:
          description: OK
      tags:
      - home pages
      - pickers
      - featured
      - listing
      - picker
      - listings
      - active
definitions: []
x-collection-name: Etsy
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