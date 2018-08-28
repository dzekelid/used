swagger: "2.0"
x-collection-name: Predix
x-complete: 1
info:
  title: VIEWS
  version: 1.0.0
host: thetaray-anomaly-service.run.aws-usw02-pr.ice.predix.io
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v2/execution/validation:
    post:
      summary: Validate the specified orchestration and the health of all the analytics
        used in the orchestration.
      description: To successfully validate the orchestration, the BPMN XML file must
        reference analytics that are running. The validation will call a 'healthCheck'
        entry on each analytic.  Analytics in the platform automatically have this
        entry, analytics outside the platform must implement this APIfor their validation
        to pass.  The results contain the http status for each for the healthCheck
        call to each analytic.
      operationId: validate
      x-api-path-slug: apiv2executionvalidation-post
      parameters:
      - in: body
        name: file
        description: (Required) artifact file
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: Successful response
      tags:
      - Validate
      - Specified
      - Orchestration
      - Health
      - Of
      - ""
      - Analytics
      - Used
      - In
      - Orchestration