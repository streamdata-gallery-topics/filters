---
swagger: "2.0"
x-collection-name: Logicbroker
x-complete: 0
info:
  title: Logic Broker CommerceAPI Get shipments for given filters
  version: 1.0.0
  description: Request rate limited to 10 requests per second with bursts up to 100
    requests.
host: stage.commerceapi.io
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1/Shipments:
    get:
      summary: Get shipments for given filters
      description: Request rate limited to 10 requests per second with bursts up to
        100 requests.
      operationId: Shipment_SearchShipment
      x-api-path-slug: apiv1shipments-get
      parameters:
      - in: query
        name: Filters.advanced
        description: Advanced query options
      - in: query
        name: Filters.from
        description: Beginning of time search window
      - in: query
        name: Filters.linkkey
        description: The linkkey identifies a group of related documents
      - in: query
        name: Filters.page
        description: Page number
      - in: query
        name: Filters.pageSize
        description: Page size
      - in: query
        name: Filters.partnerPO
        description: The partners purchase order number
      - in: query
        name: Filters.receiverCompanyId
        description: This Id is indicate who is received this document
      - in: query
        name: Filters.senderCompanyId
        description: This Id is indicate who is sent this document
      - in: query
        name: Filters.sourceKey
        description: Source key is usually the unique key the sender uses to find
          this document
      - in: query
        name: Filters.status
        description: The status of the document
      - in: query
        name: Filters.to
        description: End of time search window
      responses:
        200:
          description: OK
      tags:
      - Shipmentsgiven
      - Filters
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