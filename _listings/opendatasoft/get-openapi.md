---
swagger: "2.0"
x-collection-name: OpenDataSoft
x-complete: 0
info:
  title: OpenDataSoft Get
  description: |-
    API entry point

    Provides links for:
    * catalog, your domain's list of datasets
    * opendatasoft, all datasets on the OpenDataSoft network
  version: 2.1.0
host: public.opendatasoft.com
basePath: /api/v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /:
    get:
      summary: Get
      description: |-
        API entry point

        Provides links for:
        * catalog, your domain's list of datasets
        * opendatasoft, all datasets on the OpenDataSoft network
      operationId: getRoot
      x-api-path-slug: get
      responses:
        200:
          description: OK
      tags:
      - ""
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