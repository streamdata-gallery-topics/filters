---
swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 0
info:
  title: Microsoft Graph API Table Clear Filters
  description: 'Table: clearFilters Clears all the filters currently applied on the
    table.'
  version: 1.0.0
host: graph.microsoft.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /workbook/tables(&lt;id|name&gt;)/clearFilters:
    post:
      summary: Table Clear Filters
      description: 'Table: clearFilters Clears all the filters currently applied on
        the table.'
      operationId: Table:ClearFilters
      x-api-path-slug: workbooktablesltidnamegtclearfilters-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      responses:
        200:
          description: OK
      tags:
      - Table
      - Clear
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