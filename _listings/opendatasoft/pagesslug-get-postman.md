{
  "info": {
    "name": "OpenDataSoft Get Pages Slug",
    "_postman_id": "ad1174ec-3c4f-46c2-b28e-0dda6334d698",
    "description": "A single page's metadata from this portal",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Pages",
      "item": [
        {
          "id": "e0519a02-0dac-4c08-9195-f4b5ef6a39a0",
          "name": "getPages",
          "request": {
            "url": "http://public.opendatasoft.com/api/v2/pages",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List of all pages from this portal."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "13d63a9e-9535-48b2-90e6-46a85ce1179f"
            }
          ]
        },
        {
          "id": "052dc602-8a50-4f0a-8558-0286599f8785",
          "name": "getPage",
          "request": {
            "url": {
              "protocol": "http",
              "host": "public.opendatasoft.com",
              "path": [
                "api",
                "v2",
                "pages/:slug"
              ],
              "query": [
                {
                  "key": "No Name",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "slug",
                  "value": "slug",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "A single page's metadata from this portal"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "aa305462-091d-4ad1-b3a0-274d168615c6"
            }
          ]
        }
      ]
    }
  ]
}