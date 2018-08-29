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
  /?Action=ConfirmSignUp:
    get:
      summary: ' Confirm Sign Up '
      description: |-
        Confirms registration of a user and handles the existing alias from a previous
                    user
      operationId: confirmSignUp
      parameters:
      - in: query
        name: ClientId
        description: The ID of the client associated with the user pool
        type: string
      - in: query
        name: ConfirmationCode
        description: The confirmation code sent by a user's request to confirm registration
        type: string
      - in: query
        name: ForceAliasCreation
        description: Boolean to be specified to force user confirmation irrespective
          of existing alias
        type: string
      - in: query
        name: SecretHash
        description: A keyed-hash message authentication code (HMAC) calculated using
          the secret key of            a user pool client and username plus the client
          ID in the message
        type: string
      - in: query
        name: Username
        description: The user name of the user whose registration you wish to confirm
        type: string
      responses:
        200:
          description: OK
      tags:
      - sign ups
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