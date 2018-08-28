---
swagger: "2.0"
x-collection-name: AWS Step Functions
x-complete: 0
info:
  title: AWS Step Functions API Get Activity Task
  version: 1.0.0
  description: "Used by workers to retrieve a task (with the specified activity ARN)
    which has been scheduled \n    for execution by a running state machine."
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=GetActivityTask:
    get:
      summary: Get Activity Task
      description: "Used by workers to retrieve a task (with the specified activity
        ARN) which has been scheduled \n    for execution by a running state machine."
      operationId: getActivityTask
      x-api-path-slug: actiongetactivitytask-get
      parameters:
      - in: query
        name: activityArn
        description: The Amazon Resource Name (ARN) of the activity to retrieve tasks
          from (assigned when you create the task      using CreateActivity
        type: string
      - in: query
        name: workerName
        description: You can provide an arbitrary name in order to identify the worker
          that the task is assigned to
        type: string
      responses:
        200:
          description: OK
      tags:
      - Activity Task
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