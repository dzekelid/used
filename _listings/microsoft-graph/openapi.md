swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 1
info:
  title: Microsoft Graph API
  description: microsoft-graph-exposes-multiple-apis-from-office-365-and-other-microsoft-cloud-services-through-a-single-endpoint-httpsgraph-microsoft-com--microsoft-graph-simplifies-queries-that-would-otherwise-be-more-complex-
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
  /workbook/worksheets(&lt;id|name&gt;)/UsedRange:
    post:
      summary: Worksheet Used Range
      description: 'Worksheet: UsedRange The used range is the smallest range that
        encompasses any cells that have a value or formatting assigned to them. If
        the worksheet is blank, this function will return the top left cell.'
      operationId: Worksheet:UsedRange
      x-api-path-slug: workbookworksheetsltidnamegtusedrange-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Worksheet
      - Used
      - Range