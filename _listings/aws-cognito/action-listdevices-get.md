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
  /?Action=ListDevices:
    get:
      summary: ' List Devices '
      description: Lists the devices
      operationId: listDevices
      parameters:
      - in: query
        name: AccessToken
        description: The access tokens for the request to list devices
        type: string
      - in: query
        name: Limit
        description: The limit of the device request
        type: string
      - in: query
        name: PaginationToken
        description: The pagination token for the list request
        type: string
      responses:
        200:
          description: OK
      tags:
      - devices
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