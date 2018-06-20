{
  "info": {
    "name": "One Note Post Pages",
    "_postman_id": "7321f57b-ad37-42ad-a9fa-0398bec5a858",
    "description": "Creates a new page in the default notebook and section.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Pages",
      "item": [
        {
          "id": "aeeb8cf2-a2b4-489f-9065-fb62e9d3d7e8",
          "name": "getPages",
          "request": {
            "url": "http://www.onenote.com/api/v1.0/me/notes/pages?count=%7B%7D&filter=%7B%7D&orderby=%7B%7D&search=%7B%7D&select=%7B%7D&skip=%7B%7D&top=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get the pages (metadata) from all notebooks in OneDrive that are owned by the user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "78a40e98-324f-4fec-9b41-56a6541e9f6e"
            }
          ]
        },
        {
          "id": "5d3c98e1-7d27-4470-8d00-b271641c0201",
          "name": "postPages",
          "request": {
            "url": "http://www.onenote.com/api/v1.0/me/notes/pages?sectionName=%7B%7D",
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
            "description": "Creates a new page in the default notebook and section."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "661dd154-37ca-4d0e-962d-fc2719522d93"
            }
          ]
        }
      ]
    }
  ]
}