---
swagger: "2.0"
x-collection-name: OpenDataSoft
x-complete: 0
info:
  title: OpenDataSoft Get Source Datasets Dataset Records Record
  description: Retrieve a single record based on its ID.
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
  /pages:
    get:
      summary: Get Pages
      description: List of all pages from this portal.
      operationId: getPages
      x-api-path-slug: pages-get
      responses:
        200:
          description: OK
      tags:
      - Pages
  /pages/{slug}:
    get:
      summary: Get Pages Slug
      description: A single page's metadata from this portal
      operationId: getPage
      x-api-path-slug: pagesslug-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Pages
      - Slug
  /{source}:
    get:
      summary: Get Source
      description: |-
        Source entry points

        Provides links for the source's datasets and metadata.
      operationId: getSource
      x-api-path-slug: source-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Source
  /{source}/aggregates:
    get:
      summary: Get Source Aggregates
      description: Compute aggregations from catalog and return a list of each aggregate
        indexed by their names.
      operationId: aggregateDatasets
      x-api-path-slug: sourceaggregates-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Source
      - Aggregates
  /{source}/datasets:
    get:
      summary: Get Source Datasets
      description: |-
        List of available datasets, each with their endpoints, paginated.

        Links provided:
        * previous page
        * next page
        * last page
        * first page
      operationId: getDatasets
      x-api-path-slug: sourcedatasets-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Source
      - Datasets
  /{source}/datasets/{dataset_id}:
    get:
      summary: Get Source Datasets Dataset
      description: |-
        List of available endpoints for the specified dataset, with metadata and endpoints.

        Will provide links for:
        * the attachments endpoint
        * the files endpoint
        * the records endpoint
        * the catalog endpoint
      operationId: getDataset
      x-api-path-slug: sourcedatasetsdataset-id-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Source
      - Datasets
      - Dataset
      - Id
  /{source}/datasets/{dataset_id}/aggregates:
    get:
      summary: Get Source Datasets Dataset Aggregates
      description: Compute aggregations from dataset records and return a list of
        each aggregate indexed by their names.
      operationId: aggregateRecords
      x-api-path-slug: sourcedatasetsdataset-idaggregates-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Source
      - Datasets
      - Dataset
      - Id
      - Aggregates
  /{source}/datasets/{dataset_id}/attachments:
    get:
      summary: Get Source Datasets Dataset Attachments
      description: Get list of all available attachments
      operationId: getDatasetAttachements
      x-api-path-slug: sourcedatasetsdataset-idattachments-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Source
      - Datasets
      - Dataset
      - Id
      - Attachments
  /{source}/datasets/{dataset_id}/attachments/{attachment_id}:
    get:
      summary: Get Source Datasets Dataset Attachments Attachment
      description: Download attachment
      operationId: downloadDatasetAttachement
      x-api-path-slug: sourcedatasetsdataset-idattachmentsattachment-id-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Source
      - Datasets
      - Dataset
      - Id
      - Attachments
      - Attachment
      - Id
  /{source}/datasets/{dataset_id}/exports/csv:
    get:
      summary: Get Source Datasets Dataset Exports Csv
      description: Export dataset in CSV format
      operationId: exportRecordsCSV
      x-api-path-slug: sourcedatasetsdataset-idexportscsv-get
      parameters:
      - in: query
        name: delimiter
        description: Provide a different delimiter (default ,)
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Source
      - Datasets
      - Dataset
      - Id
      - Exports
      - Csv
  /{source}/datasets/{dataset_id}/exports/geojson:
    get:
      summary: Get Source Datasets Dataset Exports Geojson
      description: Export dataset in GEOJSON format
      operationId: exportRecordsGEOJSON
      x-api-path-slug: sourcedatasetsdataset-idexportsgeojson-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Source
      - Datasets
      - Dataset
      - Id
      - Exports
      - Geojson
  /{source}/datasets/{dataset_id}/exports/ical:
    get:
      summary: Get Source Datasets Dataset Exports Ical
      description: Export dataset in ICAL format
      operationId: exportRecordsICAL
      x-api-path-slug: sourcedatasetsdataset-idexportsical-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Source
      - Datasets
      - Dataset
      - Id
      - Exports
      - Ical
  /{source}/datasets/{dataset_id}/exports/json:
    get:
      summary: Get Source Datasets Dataset Exports Json
      description: Export dataset in JSON format
      operationId: exportRecordsJSON
      x-api-path-slug: sourcedatasetsdataset-idexportsjson-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Source
      - Datasets
      - Dataset
      - Id
      - Exports
      - Json
  /{source}/datasets/{dataset_id}/exports/ov2:
    get:
      summary: Get Source Datasets Dataset Exports Ov2
      description: Export dataset in OV2 format
      operationId: exportRecordsOV2
      x-api-path-slug: sourcedatasetsdataset-idexportsov2-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Source
      - Datasets
      - Dataset
      - Id
      - Exports
      - Ov2
  /{source}/datasets/{dataset_id}/exports/shp:
    get:
      summary: Get Source Datasets Dataset Exports Shp
      description: Export dataset in Esri shapefile (shp) format
      operationId: exportRecordsSHP
      x-api-path-slug: sourcedatasetsdataset-idexportsshp-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Source
      - Datasets
      - Dataset
      - Id
      - Exports
      - Shp
  /{source}/datasets/{dataset_id}/exports/xls:
    get:
      summary: Get Source Datasets Dataset Exports Xls
      description: Export dataset in XLS (Excel) format
      operationId: exportRecordsXLS
      x-api-path-slug: sourcedatasetsdataset-idexportsxls-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Source
      - Datasets
      - Dataset
      - Id
      - Exports
      - Xls
  /{source}/datasets/{dataset_id}/feedback:
    put:
      summary: Put Source Datasets Dataset Feedback
      description: Create new feedback entry.
      operationId: sendDatasetFeedback
      x-api-path-slug: sourcedatasetsdataset-idfeedback-put
      parameters:
      - in: body
        name: feedback
        description: Feedback entry
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Source
      - Datasets
      - Dataset
      - Id
      - Feedback
  /{source}/datasets/{dataset_id}/files/{file_id}:
    get:
      summary: Get Source Datasets Dataset Files File
      description: Download file
      operationId: getDatasetFile
      x-api-path-slug: sourcedatasetsdataset-idfilesfile-id-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Source
      - Datasets
      - Dataset
      - Id
      - Files
      - File
      - Id
  /{source}/datasets/{dataset_id}/records:
    get:
      summary: Get Source Datasets Dataset Records
      description: Search dataset's records.
      operationId: getRecords
      x-api-path-slug: sourcedatasetsdataset-idrecords-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Source
      - Datasets
      - Dataset
      - Id
      - Records
  /{source}/datasets/{dataset_id}/records/{record_id}:
    get:
      summary: Get Source Datasets Dataset Records Record
      description: Retrieve a single record based on its ID.
      operationId: getRecord
      x-api-path-slug: sourcedatasetsdataset-idrecordsrecord-id-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Source
      - Datasets
      - Dataset
      - Id
      - Records
      - Record
      - Id
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