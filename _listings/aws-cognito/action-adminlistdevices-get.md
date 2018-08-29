---
swagger: "2.0"
info:
  title: AWS Cognito Merged API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=AdminListDevices:
    get:
      summary: ' Admin List Devices '
      description: Lists devices, as an administrator
      operationId: adminListDevices
      parameters:
      - in: query
        name: Limit
        description: The limit of the devices request
        type: string
      - in: query
        name: PaginationToken
        description: The pagination token
        type: string
      - in: query
        name: Username
        description: The user name
        type: string
      - in: query
        name: UserPoolId
        description: The user pool ID
        type: string
      responses:
        200:
          description: OK
      tags:
      - http://laneworks.net/api-stack/pull/pull-amazon-cognito-sync.php
definitions: []
x-collection-name: AWS Cognito
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