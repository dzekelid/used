swagger: "2.0"
x-collection-name: AWS Config
x-complete: 1
info:
  title: AWS Config API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=PutEvaluations:
    get:
      summary: Put Evaluations
      description: Used by an AWS Lambda function to deliver evaluation results to
        AWS Config.
      operationId: putEvaluations
      x-api-path-slug: actionputevaluations-get
      parameters:
      - in: query
        name: Evaluations
        description: The assessments that the AWS Lambda function performs
        type: string
      - in: query
        name: ResultToken
        description: An encrypted token that associates an evaluation with an AWS
          Config rule
        type: string
      responses:
        200:
          description: OK
      tags:
      - Evaluations