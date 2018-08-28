---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: "Dezrez Saves or Updates a General ToDo \r\nThis is currently used to save
    quick reminders"
  version: 1.0.0
  description: "Saves or updates a general todo \r\nthis is currently used to save
    quick reminders."
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/branding/websitesetup/{brandId}:
    get:
      summary: Get files and details that can be used to customize a website
      description: Get files and details that can be used to customize a website.
      operationId: Branding_WebsiteSetupBybrandId
      x-api-path-slug: apibrandingwebsitesetupbrandid-get
      parameters:
      - in: path
        name: brandId
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Files
      - Details
      - That
      - Can
      - Be
      - Used
      - To
      - Customize
      - Website
  /api/coreplatformstate/reportMigration/{migrationId}:
    post:
      summary: Reports that a data migration has been shedueled - used by workflow
      description: Reports that a data migration has been shedueled - used by workflow.
      operationId: CorePlatformState_ReportMigrationStateBymigrationId
      x-api-path-slug: apicoreplatformstatereportmigrationmigrationid-post
      parameters:
      - in: path
        name: migrationId
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Reports
      - That
      - Data
      - Migration
      - Has
      - Been
      - Shedueled
      - '-'
      - Used
      - By
      - Workflow
  /api/document/setprivacy:
    put:
      summary: Sets the document privacy for an existing document.  This is used to
        change a document from being publicly accessible to being private, and vice
        versa.
      description: Sets the document privacy for an existing document.  this is used
        to change a document from being publicly accessible to being private, and
        vice versa..
      operationId: Document_SetDocumentPrivacyBysetDocumentPrivacyCommand
      x-api-path-slug: apidocumentsetprivacy-put
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: body
        name: setDocumentPrivacyCommand
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Sets
      - Document
      - Privacyan
      - Existing
      - Document
      - ""
      - ""
      - This
      - Is
      - Used
      - To
      - Change
      - Document
      - From
      - Being
      - Publicly
      - Accessible
      - To
      - Being
      - Private
      - ""
      - Vice
      - Versa
  /api/documentgeneration/unusedmergetemplates:
    get:
      summary: Returns a list of lettertemplates associated to this agency that are
        not currently used in any envelope templates
      description: Returns a list of lettertemplates associated to this agency that
        are not currently used in any envelope templates.
      operationId: DocumentGeneration_GetUnusedMergeTemplates
      x-api-path-slug: apidocumentgenerationunusedmergetemplates-get
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Returns
      - List
      - Of
      - Lettertemplates
      - Associated
      - To
      - This
      - Agency
      - That
      - Are
      - Not
      - Currently
      - Used
      - In
      - Any
      - Envelope
      - Templates
  /api/todo/general/savetodo:
    post:
      summary: "Saves or Updates a General ToDo \r\nThis is currently used to save
        quick reminders"
      description: "Saves or updates a general todo \r\nthis is currently used to
        save quick reminders."
      operationId: GeneralToDo_SaveToDoBytoDoSave
      x-api-path-slug: apitodogeneralsavetodo-post
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: body
        name: toDoSave
        description: A wrapper for the todo save data and the various data contracts
          needed
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Saves
      - S
      - General
      - ToDo
      - This
      - Is
      - Currently
      - Used
      - To
      - Save
      - Quick
      - Reminders
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