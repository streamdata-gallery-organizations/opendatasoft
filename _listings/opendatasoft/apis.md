---
name: OpenDataSoft
x-slug: opendatasoft
description: OpenDataSoft is a cloud-based turnkey platform for data publishing and
  API management. Its interface is intuitively designed to empower anyone, regardless
  of technical skills, to upload easy-to-understand Open Data, or to even share data
  within an admi...
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2716-opendatasoft.jpg
x-kinRank: "7"
x-alexaRank: "323884"
tags: OpenDataSoft
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opendatasoft/master/_listings/opendatasoft/apis.md
specificationVersion: "0.14"
apis:
- name: OpenDataSoft Get
  x-api-slug: opendatasoft
  description: |-
    API entry point

    Provides links for:
    * catalog, your domain's list of datasets
    * opendatasoft, all datasets on the OpenDataSoft network
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2716-opendatasoft.jpg
  humanURL: http://opendatasoft.com
  baseURL: https://public.opendatasoft.com//api/v2//
  tags: ""
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opendatasoft/master/_listings/opendatasoft/get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opendatasoft/master/_listings/opendatasoft/get-openapi.md
- name: OpenDataSoft Get Pages
  x-api-slug: opendatasoft
  description: List of all pages from this portal.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2716-opendatasoft.jpg
  humanURL: http://opendatasoft.com
  baseURL: https://public.opendatasoft.com//api/v2//pages
  tags: Pages
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opendatasoft/master/_listings/opendatasoft/pages-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opendatasoft/master/_listings/opendatasoft/pages-get-openapi.md
- name: OpenDataSoft Get Pages Slug
  x-api-slug: opendatasoft
  description: A single page's metadata from this portal
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2716-opendatasoft.jpg
  humanURL: http://opendatasoft.com
  baseURL: https://public.opendatasoft.com//api/v2//pages/{slug}
  tags: Pages,Slug
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opendatasoft/master/_listings/opendatasoft/pagesslug-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opendatasoft/master/_listings/opendatasoft/pagesslug-get-openapi.md
- name: OpenDataSoft Get Source
  x-api-slug: opendatasoft
  description: |-
    Source entry points

    Provides links for the source's datasets and metadata.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2716-opendatasoft.jpg
  humanURL: http://opendatasoft.com
  baseURL: https://public.opendatasoft.com//api/v2//{source}
  tags: Source
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opendatasoft/master/_listings/opendatasoft/source-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opendatasoft/master/_listings/opendatasoft/source-get-openapi.md
- name: OpenDataSoft Get Source Aggregates
  x-api-slug: opendatasoft
  description: Compute aggregations from catalog and return a list of each aggregate
    indexed by their names.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2716-opendatasoft.jpg
  humanURL: http://opendatasoft.com
  baseURL: https://public.opendatasoft.com//api/v2//{source}/aggregates
  tags: Source,Aggregates
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opendatasoft/master/_listings/opendatasoft/sourceaggregates-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opendatasoft/master/_listings/opendatasoft/sourceaggregates-get-openapi.md
- name: OpenDataSoft Get Source Datasets
  x-api-slug: opendatasoft
  description: |-
    List of available datasets, each with their endpoints, paginated.

    Links provided:
    * previous page
    * next page
    * last page
    * first page
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2716-opendatasoft.jpg
  humanURL: http://opendatasoft.com
  baseURL: https://public.opendatasoft.com//api/v2//{source}/datasets
  tags: Source,Datasets
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opendatasoft/master/_listings/opendatasoft/sourcedatasets-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opendatasoft/master/_listings/opendatasoft/sourcedatasets-get-openapi.md
- name: OpenDataSoft Get Source Datasets Dataset
  x-api-slug: opendatasoft
  description: |-
    List of available endpoints for the specified dataset, with metadata and endpoints.

    Will provide links for:
    * the attachments endpoint
    * the files endpoint
    * the records endpoint
    * the catalog endpoint
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2716-opendatasoft.jpg
  humanURL: http://opendatasoft.com
  baseURL: https://public.opendatasoft.com//api/v2//{source}/datasets/{dataset_id}
  tags: Source,Datasets,Dataset,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opendatasoft/master/_listings/opendatasoft/sourcedatasetsdataset-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opendatasoft/master/_listings/opendatasoft/sourcedatasetsdataset-id-get-openapi.md
- name: OpenDataSoft Get Source Datasets Dataset Aggregates
  x-api-slug: opendatasoft
  description: Compute aggregations from dataset records and return a list of each
    aggregate indexed by their names.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2716-opendatasoft.jpg
  humanURL: http://opendatasoft.com
  baseURL: https://public.opendatasoft.com//api/v2//{source}/datasets/{dataset_id}/aggregates
  tags: Source,Datasets,Dataset,Id,Aggregates
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opendatasoft/master/_listings/opendatasoft/sourcedatasetsdataset-idaggregates-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opendatasoft/master/_listings/opendatasoft/sourcedatasetsdataset-idaggregates-get-openapi.md
- name: OpenDataSoft Get Source Datasets Dataset Attachments
  x-api-slug: opendatasoft
  description: Get list of all available attachments
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2716-opendatasoft.jpg
  humanURL: http://opendatasoft.com
  baseURL: https://public.opendatasoft.com//api/v2//{source}/datasets/{dataset_id}/attachments
  tags: Source,Datasets,Dataset,Id,Attachments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opendatasoft/master/_listings/opendatasoft/sourcedatasetsdataset-idattachments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opendatasoft/master/_listings/opendatasoft/sourcedatasetsdataset-idattachments-get-openapi.md
- name: OpenDataSoft Get Source Datasets Dataset Attachments Attachment
  x-api-slug: opendatasoft
  description: Download attachment
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2716-opendatasoft.jpg
  humanURL: http://opendatasoft.com
  baseURL: https://public.opendatasoft.com//api/v2//{source}/datasets/{dataset_id}/attachments/{attachment_id}
  tags: Source,Datasets,Dataset,Id,Attachments,Attachment,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opendatasoft/master/_listings/opendatasoft/sourcedatasetsdataset-idattachmentsattachment-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opendatasoft/master/_listings/opendatasoft/sourcedatasetsdataset-idattachmentsattachment-id-get-openapi.md
- name: OpenDataSoft Get Source Datasets Dataset Exports Csv
  x-api-slug: opendatasoft
  description: Export dataset in CSV format
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2716-opendatasoft.jpg
  humanURL: http://opendatasoft.com
  baseURL: https://public.opendatasoft.com//api/v2//{source}/datasets/{dataset_id}/exports/csv
  tags: Source,Datasets,Dataset,Id,Exports,Csv
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opendatasoft/master/_listings/opendatasoft/sourcedatasetsdataset-idexportscsv-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opendatasoft/master/_listings/opendatasoft/sourcedatasetsdataset-idexportscsv-get-openapi.md
- name: OpenDataSoft Get Source Datasets Dataset Exports Geojson
  x-api-slug: opendatasoft
  description: Export dataset in GEOJSON format
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2716-opendatasoft.jpg
  humanURL: http://opendatasoft.com
  baseURL: https://public.opendatasoft.com//api/v2//{source}/datasets/{dataset_id}/exports/geojson
  tags: Source,Datasets,Dataset,Id,Exports,Geojson
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opendatasoft/master/_listings/opendatasoft/sourcedatasetsdataset-idexportsgeojson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opendatasoft/master/_listings/opendatasoft/sourcedatasetsdataset-idexportsgeojson-get-openapi.md
- name: OpenDataSoft Get Source Datasets Dataset Exports Ical
  x-api-slug: opendatasoft
  description: Export dataset in ICAL format
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2716-opendatasoft.jpg
  humanURL: http://opendatasoft.com
  baseURL: https://public.opendatasoft.com//api/v2//{source}/datasets/{dataset_id}/exports/ical
  tags: Source,Datasets,Dataset,Id,Exports,Ical
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opendatasoft/master/_listings/opendatasoft/sourcedatasetsdataset-idexportsical-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opendatasoft/master/_listings/opendatasoft/sourcedatasetsdataset-idexportsical-get-openapi.md
- name: OpenDataSoft Get Source Datasets Dataset Exports Json
  x-api-slug: opendatasoft
  description: Export dataset in JSON format
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2716-opendatasoft.jpg
  humanURL: http://opendatasoft.com
  baseURL: https://public.opendatasoft.com//api/v2//{source}/datasets/{dataset_id}/exports/json
  tags: Source,Datasets,Dataset,Id,Exports,Json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opendatasoft/master/_listings/opendatasoft/sourcedatasetsdataset-idexportsjson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opendatasoft/master/_listings/opendatasoft/sourcedatasetsdataset-idexportsjson-get-openapi.md
- name: OpenDataSoft Get Source Datasets Dataset Exports Ov2
  x-api-slug: opendatasoft
  description: Export dataset in OV2 format
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2716-opendatasoft.jpg
  humanURL: http://opendatasoft.com
  baseURL: https://public.opendatasoft.com//api/v2//{source}/datasets/{dataset_id}/exports/ov2
  tags: Source,Datasets,Dataset,Id,Exports,Ov2
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opendatasoft/master/_listings/opendatasoft/sourcedatasetsdataset-idexportsov2-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opendatasoft/master/_listings/opendatasoft/sourcedatasetsdataset-idexportsov2-get-openapi.md
- name: OpenDataSoft Get Source Datasets Dataset Exports Shp
  x-api-slug: opendatasoft
  description: Export dataset in Esri shapefile (shp) format
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2716-opendatasoft.jpg
  humanURL: http://opendatasoft.com
  baseURL: https://public.opendatasoft.com//api/v2//{source}/datasets/{dataset_id}/exports/shp
  tags: Source,Datasets,Dataset,Id,Exports,Shp
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opendatasoft/master/_listings/opendatasoft/sourcedatasetsdataset-idexportsshp-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opendatasoft/master/_listings/opendatasoft/sourcedatasetsdataset-idexportsshp-get-openapi.md
- name: OpenDataSoft Get Source Datasets Dataset Exports Xls
  x-api-slug: opendatasoft
  description: Export dataset in XLS (Excel) format
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2716-opendatasoft.jpg
  humanURL: http://opendatasoft.com
  baseURL: https://public.opendatasoft.com//api/v2//{source}/datasets/{dataset_id}/exports/xls
  tags: Source,Datasets,Dataset,Id,Exports,Xls
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opendatasoft/master/_listings/opendatasoft/sourcedatasetsdataset-idexportsxls-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opendatasoft/master/_listings/opendatasoft/sourcedatasetsdataset-idexportsxls-get-openapi.md
- name: OpenDataSoft Put Source Datasets Dataset Feedback
  x-api-slug: opendatasoft
  description: Create new feedback entry.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2716-opendatasoft.jpg
  humanURL: http://opendatasoft.com
  baseURL: https://public.opendatasoft.com//api/v2//{source}/datasets/{dataset_id}/feedback
  tags: Source,Datasets,Dataset,Id,Feedback
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opendatasoft/master/_listings/opendatasoft/sourcedatasetsdataset-idfeedback-put-openapi.md
- name: OpenDataSoft Get Source Datasets Dataset Files File
  x-api-slug: opendatasoft
  description: Download file
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2716-opendatasoft.jpg
  humanURL: http://opendatasoft.com
  baseURL: https://public.opendatasoft.com//api/v2//{source}/datasets/{dataset_id}/files/{file_id}
  tags: Source,Datasets,Dataset,Id,Files,File,Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opendatasoft/master/_listings/opendatasoft/sourcedatasetsdataset-idfilesfile-id-get-openapi.md
- name: OpenDataSoft Get Source Datasets Dataset Records
  x-api-slug: opendatasoft
  description: Search dataset's records.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2716-opendatasoft.jpg
  humanURL: http://opendatasoft.com
  baseURL: https://public.opendatasoft.com//api/v2//{source}/datasets/{dataset_id}/records
  tags: Source,Datasets,Dataset,Id,Records
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opendatasoft/master/_listings/opendatasoft/sourcedatasetsdataset-idrecords-get-openapi.md
- name: OpenDataSoft Get Source Datasets Dataset Records Record
  x-api-slug: opendatasoft
  description: Retrieve a single record based on its ID.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2716-opendatasoft.jpg
  humanURL: http://opendatasoft.com
  baseURL: https://public.opendatasoft.com//api/v2//{source}/datasets/{dataset_id}/records/{record_id}
  tags: Source,Datasets,Dataset,Id,Records,Record,Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opendatasoft/master/_listings/opendatasoft/sourcedatasetsdataset-idrecordsrecord-id-get-openapi.md
- name: OpenDataSoft Get Source Datasets Dataset Reuses
  x-api-slug: opendatasoft
  description: Get list of reuses
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2716-opendatasoft.jpg
  humanURL: http://opendatasoft.com
  baseURL: https://public.opendatasoft.com//api/v2//{source}/datasets/{dataset_id}/reuses
  tags: Source,Datasets,Dataset,Id,Reuses
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opendatasoft/master/_listings/opendatasoft/sourcedatasetsdataset-idreuses-get-openapi.md
- name: OpenDataSoft Get Source Datasets Dataset Reuses Reuse
  x-api-slug: opendatasoft
  description: Retrieve a single reuse based on its ID.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2716-opendatasoft.jpg
  humanURL: http://opendatasoft.com
  baseURL: https://public.opendatasoft.com//api/v2//{source}/datasets/{dataset_id}/reuses/{reuse_id}
  tags: Source,Datasets,Dataset,Id,Reuses,Reuse,Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opendatasoft/master/_listings/opendatasoft/sourcedatasetsdataset-idreusesreuse-id-get-openapi.md
- name: OpenDataSoft Get Source Datasets Dataset Snapshots
  x-api-slug: opendatasoft
  description: List of all snapshots for this dataset.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2716-opendatasoft.jpg
  humanURL: http://opendatasoft.com
  baseURL: https://public.opendatasoft.com//api/v2//{source}/datasets/{dataset_id}/snapshots
  tags: Source,Datasets,Dataset,Id,Snapshots
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opendatasoft/master/_listings/opendatasoft/sourcedatasetsdataset-idsnapshots-get-openapi.md
- name: OpenDataSoft Get Source Datasets Dataset Snapshots Snapshot
  x-api-slug: opendatasoft
  description: List of all snapshots for this dataset.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2716-opendatasoft.jpg
  humanURL: http://opendatasoft.com
  baseURL: https://public.opendatasoft.com//api/v2//{source}/datasets/{dataset_id}/snapshots/{snapshot_id}
  tags: Source,Datasets,Dataset,Id,Snapshots,Snapshot,Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opendatasoft/master/_listings/opendatasoft/sourcedatasetsdataset-idsnapshotssnapshot-id-get-openapi.md
- name: OpenDataSoft Get Source Exports Csv
  x-api-slug: opendatasoft
  description: Export catalog (source) in CSV format
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2716-opendatasoft.jpg
  humanURL: http://opendatasoft.com
  baseURL: https://public.opendatasoft.com//api/v2//{source}/exports/csv
  tags: Source,Exports,Csv
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opendatasoft/master/_listings/opendatasoft/sourceexportscsv-get-openapi.md
- name: OpenDataSoft Get Source Exports Json
  x-api-slug: opendatasoft
  description: Export catalog (source) in JSON format
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2716-opendatasoft.jpg
  humanURL: http://opendatasoft.com
  baseURL: https://public.opendatasoft.com//api/v2//{source}/exports/json
  tags: Source,Exports,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opendatasoft/master/_listings/opendatasoft/sourceexportsjson-get-openapi.md
- name: OpenDataSoft Get Source Exports Rdf
  x-api-slug: opendatasoft
  description: Export catalog (source) in RDF/XML format
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2716-opendatasoft.jpg
  humanURL: http://opendatasoft.com
  baseURL: https://public.opendatasoft.com//api/v2//{source}/exports/rdf
  tags: Source,Exports,Rdf
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opendatasoft/master/_listings/opendatasoft/sourceexportsrdf-get-openapi.md
- name: OpenDataSoft Get Source Exports Rss
  x-api-slug: opendatasoft
  description: Export catalog (source) in RSS format
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2716-opendatasoft.jpg
  humanURL: http://opendatasoft.com
  baseURL: https://public.opendatasoft.com//api/v2//{source}/exports/rss
  tags: Source,Exports,Rss
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opendatasoft/master/_listings/opendatasoft/sourceexportsrss-get-openapi.md
- name: OpenDataSoft Get Source Exports Ttl
  x-api-slug: opendatasoft
  description: Export catalog (source) in TTL (turtle/rdf) format
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2716-opendatasoft.jpg
  humanURL: http://opendatasoft.com
  baseURL: https://public.opendatasoft.com//api/v2//{source}/exports/ttl
  tags: Source,Exports,Ttl
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opendatasoft/master/_listings/opendatasoft/sourceexportsttl-get-openapi.md
- name: OpenDataSoft Get Source Exports Xls
  x-api-slug: opendatasoft
  description: Export catalog (source) in XLS (Excel) format
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2716-opendatasoft.jpg
  humanURL: http://opendatasoft.com
  baseURL: https://public.opendatasoft.com//api/v2//{source}/exports/xls
  tags: Source,Exports,Xls
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opendatasoft/master/_listings/opendatasoft/sourceexportsxls-get-openapi.md
- name: OpenDataSoft Get Source Metadata Templates
  x-api-slug: opendatasoft
  description: List of available metadata templates types, each with their endpoints.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2716-opendatasoft.jpg
  humanURL: http://opendatasoft.com
  baseURL: https://public.opendatasoft.com//api/v2//{source}/metadata_templates
  tags: Source,Metadata,Templates
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opendatasoft/master/_listings/opendatasoft/sourcemetadata-templates-get-openapi.md
- name: OpenDataSoft Get Source Metadata Templates Metadata Template Type
  x-api-slug: opendatasoft
  description: List of metadata templates available for this type.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2716-opendatasoft.jpg
  humanURL: http://opendatasoft.com
  baseURL: https://public.opendatasoft.com//api/v2//{source}/metadata_templates/{metadata_template_type}
  tags: Source,Metadata,Templates,Metadata,Template,Type
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opendatasoft/master/_listings/opendatasoft/sourcemetadata-templatesmetadata-template-type-get-openapi.md
- name: OpenDataSoft Get Source Metadata Templates Metadata Template Type Metadata
    Template Name
  x-api-slug: opendatasoft
  description: A single metadata_template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2716-opendatasoft.jpg
  humanURL: http://opendatasoft.com
  baseURL: https://public.opendatasoft.com//api/v2//{source}/metadata_templates/{metadata_template_type}/{metadata_template_name}
  tags: Source,Metadata,Templates,Metadata,Template,Type,Metadata,Template,Name
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opendatasoft/master/_listings/opendatasoft/sourcemetadata-templatesmetadata-template-typemetadata-template-name-get-openapi.md
- name: OpenDataSoft
  x-api-slug: opendatasoft
  description: OpenDataSoft is a cloud-based turnkey platform for data publishing
    and API management. Its interface is intuitively designed to empower anyone, regardless
    of technical skills, to upload easy-to-understand Open Data, or to even share
    data within an admi...
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2716-opendatasoft.jpg
  humanURL: http://opendatasoft.com
  baseURL: https://public.opendatasoft.com//api/v2
  tags: OpenDataSoft
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opendatasoft/master/_listings/opendatasoft/openapi.md
x-common:
- type: x-blog
  url: http://www.opendatasoft.com/category/news/
- type: x-crunchbase
  url: https://crunchbase.com/organization/opendatasoft
- type: x-crunchbase
  url: http://www.crunchbase.com/company/opendatasoft
- type: x-email
  url: contact@opendatasoft.com
- type: x-email
  url: cil@opendatasoft.com
- type: x-twitter
  url: https://twitter.com/opendatasoft
- type: x-website
  url: http://opendatasoft.com
- type: x-website
  url: https://www.opendatasoft.com
- type: x-website
  url: http://www.opendatasoft.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---