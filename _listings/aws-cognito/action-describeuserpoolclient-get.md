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
  /?Action=DescribeUserPoolClient:
    get:
      summary: ' Describe User Pool Client '
      description: |-
        Client method for returning the configuration information and metadata of the
                    specified user pool client
      operationId: describeUserPoolClient
      parameters:
      - in: query
        name: ClientId
        description: The ID of the client associated with the user pool
        type: string
      - in: query
        name: UserPoolId
        description: The user pool ID for the user pool you want to describe
        type: string
      responses:
        200:
          description: OK
      tags:
      - users
      - pool clients
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