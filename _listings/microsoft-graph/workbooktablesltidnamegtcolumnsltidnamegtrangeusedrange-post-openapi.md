---
swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 0
info:
  title: Microsoft Graph Range Used Range
  description: 'Range: UsedRange Returns the used range of the given range object.'
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
  /workbook/names(&lt;name&gt;)/range/UsedRange:
    post:
      summary: Range Used Range
      description: 'Range: UsedRange Returns the used range of the given range object.'
      operationId: Range:UsedRange
      x-api-path-slug: workbooknamesltnamegtrangeusedrange-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Used
      - Range
  /workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/UsedRange:
    post:
      summary: Range Used Range
      description: 'Range: UsedRange Returns the used range of the given range object.'
      operationId: Range:UsedRange
      x-api-path-slug: workbookworksheetsltidnamegtrangeltaddressgtusedrange-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Used
      - Range
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/UsedRange:
    post:
      summary: Range Used Range
      description: 'Range: UsedRange Returns the used range of the given range object.'
      operationId: Range:UsedRange
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtrangeusedrange-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Used
      - Range
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