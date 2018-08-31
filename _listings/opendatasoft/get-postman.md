{
  "info": {
    "name": "OpenDataSoft Get",
    "_postman_id": "33b81a4c-9cbc-4ae8-a9e9-d2b15b95c4d8",
    "description": "API entry point\n\nProvides links for:\n* catalog, your domain's list of datasets\n* opendatasoft, all datasets on the OpenDataSoft network",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "701c334a-11f4-4348-81ad-96b3250b31ce",
      "name": "getRoot",
      "request": {
        "url": "http://public.opendatasoft.com/api/v2/",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "API entry point\n\nProvides links for:\n* catalog, your domain's list of datasets\n* opendatasoft, all datasets on the OpenDataSoft network"
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "9464223b-9739-4291-9563-eff50f0bb6d6"
        }
      ]
    }
  ]
}