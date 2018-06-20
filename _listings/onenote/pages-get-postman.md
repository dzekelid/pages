{
  "info": {
    "name": "One Note Get Pages",
    "_postman_id": "a9398f0a-b5e6-4c1c-988e-438873ce3d29",
    "description": "Get the pages (metadata) from all notebooks in OneDrive that are owned by the user.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Pages",
      "item": [
        {
          "id": "c5723633-2ed2-4987-8cc9-5fe74b97f548",
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
              "id": "38f3b236-7ccd-4e2d-83be-5fd8008e40ed"
            }
          ]
        }
      ]
    }
  ]
}