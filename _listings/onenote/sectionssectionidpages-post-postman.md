{
  "info": {
    "name": "One Note Post Sections Sectionid Pages",
    "_postman_id": "103b388b-c093-43c5-9a5e-32ea6a993f66",
    "description": "Creates a new page in a specific section.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Sections",
      "item": [
        {
          "id": "0bf5cced-2204-43c4-91e3-f5074136c832",
          "name": "getSectionsSectionPages",
          "request": {
            "url": {
              "protocol": "http",
              "host": "www.onenote.com",
              "path": [
                "api",
                "v1.0",
                "me",
                "notes",
                "sections/:sectionId/pages"
              ],
              "query": [
                {
                  "key": "count",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "expand",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "filter",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "orderby",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "pagelevel",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "search",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "select",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "skip",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "top",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "sectionId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get the pages (metadata) in the specified section."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "09fec157-03ae-4f83-abe0-74158c2bd76b"
            }
          ]
        },
        {
          "id": "3607b9e1-3133-4517-a635-e2e6909d7ed1",
          "name": "postSectionsSectionPages",
          "request": {
            "url": {
              "protocol": "http",
              "host": "www.onenote.com",
              "path": [
                "api",
                "v1.0",
                "me",
                "notes",
                "sections/:sectionId/pages"
              ],
              "variable": [
                {
                  "id": "sectionId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "header": [
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "Required: indicates type of content sent",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new page in a specific section."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "41c71034-278c-4e3e-918b-d561017207f8"
            }
          ]
        }
      ]
    }
  ]
}