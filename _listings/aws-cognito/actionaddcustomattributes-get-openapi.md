---
swagger: "2.0"
x-collection-name: AWS Cognito
x-complete: 0
info:
  title: AWS Cognito API Add Custom Attributes
  version: 1.0.0
  description: Adds additional user attributes to the user pool schema.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=AddCustomAttributes:
    get:
      summary: Add Custom Attributes
      description: Adds additional user attributes to the user pool schema.
      operationId: addCustomAttributes
      x-api-path-slug: actionaddcustomattributes-get
      parameters:
      - in: query
        name: CustomAttributes
        description: An array of custom attributes, such as Mutable and Name
        type: string
      - in: query
        name: UserPoolId
        description: The user pool ID for the user pool where you want to add custom            attributes
        type: string
      responses:
        200:
          description: OK
      tags:
      - Attributes
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