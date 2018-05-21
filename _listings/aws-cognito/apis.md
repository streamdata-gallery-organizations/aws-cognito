---
name: AWS Cognito
x-slug: aws-cognito
description: Amazon Cognito lets you easily add user sign-up and sign-in to your mobile
  and web apps. With Amazon Cognito, you also have the options to authenticate users
  through social identity providers such as Facebook, Twitter, or Amazon, with SAML
  identity solutions, or by using your own identity system. In addition, Amazon Cognito
  enables you to save data locally on users devices, allowing your applications to
  work even when the devices are offline. You can then synchronize data across users
  devices so that their app experience remains consistent regardless of the device
  they use. With Amazon Cognito, you can focus on creating great app experiences instead
  of worrying about building, securing, and scaling a solution to handle user management,
  authentication, and sync across devices.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
x-kinRank: "10"
x-alexaRank: ""
tags: AWS Cognito
created: "2018-05-20"
modified: "2018-05-20"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Cognito API Add Custom Attributes
  x-api-slug: aws-cognito-api
  description: Adds additional user attributes to the user pool schema.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=AddCustomAttributes
  tags: Attributes
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionaddcustomattributes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionaddcustomattributes-get-openapi.md
- name: AWS Cognito API Admin Add User To Group
  x-api-slug: aws-cognito-api
  description: Adds the specified user to the specified group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=AdminAddUserToGroup
  tags: Users,Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionadminaddusertogroup-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionadminaddusertogroup-get-openapi.md
- name: AWS Cognito API Admin Confirm Sign Up
  x-api-slug: aws-cognito-api
  description: Confirms user registration as an admin without using a confirmation
    code.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=AdminConfirmSignUp
  tags: Sign Up
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionadminconfirmsignup-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionadminconfirmsignup-get-openapi.md
- name: AWS Cognito API Admin Create User
  x-api-slug: aws-cognito-api
  description: |-
    Creates a new user in the specified user pool and sends a welcome message via email
                or phone (SMS).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=AdminCreateUser
  tags: Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionadmincreateuser-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionadmincreateuser-get-openapi.md
- name: AWS Cognito API Admin Delete User
  x-api-slug: aws-cognito-api
  description: Deletes a user as an administrator.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=AdminDeleteUser
  tags: Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionadmindeleteuser-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionadmindeleteuser-get-openapi.md
- name: AWS Cognito API Admin Delete User Attributes
  x-api-slug: aws-cognito-api
  description: Deletes the user attributes in a user pool as an administrator.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=AdminDeleteUserAttributes
  tags: Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionadmindeleteuserattributes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionadmindeleteuserattributes-get-openapi.md
- name: AWS Cognito API Admin Disable User
  x-api-slug: aws-cognito-api
  description: Disables the specified user as an administrator.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=AdminDisableUser
  tags: Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionadmindisableuser-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionadmindisableuser-get-openapi.md
- name: AWS Cognito API Admin Enable User
  x-api-slug: aws-cognito-api
  description: Enables the specified user as an administrator.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=AdminEnableUser
  tags: Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionadminenableuser-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionadminenableuser-get-openapi.md
- name: AWS Cognito API Admin Forget Device
  x-api-slug: aws-cognito-api
  description: Forgets the device, as an administrator.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=AdminForgetDevice
  tags: Devices
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionadminforgetdevice-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionadminforgetdevice-get-openapi.md
- name: AWS Cognito API Admin Get Device
  x-api-slug: aws-cognito-api
  description: Gets the device, as an administrator.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=AdminGetDevice
  tags: http://laneworks.net/api-stack/pull/pull-amazon-cognito-sync.php
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionadmingetdevice-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionadmingetdevice-get-openapi.md
- name: AWS Cognito API Admin Get User
  x-api-slug: aws-cognito-api
  description: Gets the specified user by user name in a user pool as an administrator.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=AdminGetUser
  tags: Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionadmingetuser-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionadmingetuser-get-openapi.md
- name: AWS Cognito API Admin Initiate Auth
  x-api-slug: aws-cognito-api
  description: Initiates the authentication flow, as an administrator.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=AdminInitiateAuth
  tags: Authnetication
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionadmininitiateauth-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionadmininitiateauth-get-openapi.md
- name: AWS Cognito API Admin List Devices
  x-api-slug: aws-cognito-api
  description: Lists devices, as an administrator.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=AdminListDevices
  tags: http://laneworks.net/api-stack/pull/pull-amazon-cognito-sync.php
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionadminlistdevices-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionadminlistdevices-get-openapi.md
- name: AWS Cognito API Admin List Groups For User
  x-api-slug: aws-cognito-api
  description: Lists the groups that the user belongs to.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=AdminListGroupsForUser
  tags: Users,Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionadminlistgroupsforuser-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionadminlistgroupsforuser-get-openapi.md
- name: AWS Cognito API Admin Remove User From Group
  x-api-slug: aws-cognito-api
  description: Removes the specified user from the specified group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=AdminRemoveUserFromGroup
  tags: Users,Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionadminremoveuserfromgroup-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionadminremoveuserfromgroup-get-openapi.md
- name: AWS Cognito API Admin Reset User Password
  x-api-slug: aws-cognito-api
  description: Resets the specified user's password in a user pool as an administrator.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=AdminResetUserPassword
  tags: Users,Passwords
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionadminresetuserpassword-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionadminresetuserpassword-get-openapi.md
- name: AWS Cognito API Admin Respond To Auth Challenge
  x-api-slug: aws-cognito-api
  description: Responds to an authentication challenge, as an administrator.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=AdminRespondToAuthChallenge
  tags: Authentication Challenge
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionadminrespondtoauthchallenge-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionadminrespondtoauthchallenge-get-openapi.md
- name: AWS Cognito API Admin Set User Settings
  x-api-slug: aws-cognito-api
  description: Sets all the user settings for a specified user name.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=AdminSetUserSettings
  tags: Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionadminsetusersettings-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionadminsetusersettings-get-openapi.md
- name: AWS Cognito API Admin Update Device Status
  x-api-slug: aws-cognito-api
  description: Updates the device status as an administrator.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=AdminUpdateDeviceStatus
  tags: Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionadminupdatedevicestatus-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionadminupdatedevicestatus-get-openapi.md
- name: AWS Cognito API Admin Update User Attributes
  x-api-slug: aws-cognito-api
  description: |-
    Updates the specified user's attributes, including developer attributes, as an
                administrator.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=AdminUpdateUserAttributes
  tags: Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionadminupdateuserattributes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionadminupdateuserattributes-get-openapi.md
- name: AWS Cognito API Admin User Global Sign Out
  x-api-slug: aws-cognito-api
  description: Signs out users from all devices, as an administrator.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=AdminUserGlobalSignOut
  tags: Users,Global Sign Out
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionadminuserglobalsignout-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionadminuserglobalsignout-get-openapi.md
- name: AWS Cognito API Change Password
  x-api-slug: aws-cognito-api
  description: Changes the password for a specified user in a user pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=ChangePassword
  tags: Password
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionchangepassword-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionchangepassword-get-openapi.md
- name: AWS Cognito API Confirm Device
  x-api-slug: aws-cognito-api
  description: Confirms tracking of the device.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=ConfirmDevice
  tags: Devices
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionconfirmdevice-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionconfirmdevice-get-openapi.md
- name: AWS Cognito API Confirm Forgot Password
  x-api-slug: aws-cognito-api
  description: |-
    Allows a user to enter a code provided when they reset their password to update
                their password.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=ConfirmForgotPassword
  tags: Passwords
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionconfirmforgotpassword-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionconfirmforgotpassword-get-openapi.md
- name: AWS Cognito API Confirm Sign Up
  x-api-slug: aws-cognito-api
  description: |-
    Confirms registration of a user and handles the existing alias from a previous
                user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=ConfirmSignUp
  tags: Sign Ups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionconfirmsignup-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionconfirmsignup-get-openapi.md
- name: AWS Cognito API Create Group
  x-api-slug: aws-cognito-api
  description: Creates a new group in the specified user pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=CreateGroup
  tags: Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actioncreategroup-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actioncreategroup-get-openapi.md
- name: AWS Cognito API Create User Import Job
  x-api-slug: aws-cognito-api
  description: Creates the user import job.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=CreateUserImportJob
  tags: Users,Imports
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actioncreateuserimportjob-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actioncreateuserimportjob-get-openapi.md
- name: AWS Cognito API Create User Pool
  x-api-slug: aws-cognito-api
  description: |-
    Creates a new Amazon Cognito user pool and sets the password policy for the
                pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=CreateUserPool
  tags: Users,Pools
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actioncreateuserpool-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actioncreateuserpool-get-openapi.md
- name: AWS Cognito API Create User Pool Client
  x-api-slug: aws-cognito-api
  description: Creates the user pool client.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=CreateUserPoolClient
  tags: Users,Pool Clients
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actioncreateuserpoolclient-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actioncreateuserpoolclient-get-openapi.md
- name: AWS Cognito API Delete Group
  x-api-slug: aws-cognito-api
  description: Deletes a group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=DeleteGroup
  tags: Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actiondeletegroup-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actiondeletegroup-get-openapi.md
- name: AWS Cognito API Delete User
  x-api-slug: aws-cognito-api
  description: Allows a user to delete one's self.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=DeleteUser
  tags: Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actiondeleteuser-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actiondeleteuser-get-openapi.md
- name: AWS Cognito API Delete User Attributes
  x-api-slug: aws-cognito-api
  description: Deletes the attributes for a user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=DeleteUserAttributes
  tags: Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actiondeleteuserattributes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actiondeleteuserattributes-get-openapi.md
- name: AWS Cognito API Delete User Pool
  x-api-slug: aws-cognito-api
  description: Deletes the specified Amazon Cognito user pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=DeleteUserPool
  tags: Users,Pools
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actiondeleteuserpool-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actiondeleteuserpool-get-openapi.md
- name: AWS Cognito API Delete User Pool Client
  x-api-slug: aws-cognito-api
  description: Allows the developer to delete the user pool client.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=DeleteUserPoolClient
  tags: Users,Pools
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actiondeleteuserpoolclient-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actiondeleteuserpoolclient-get-openapi.md
- name: AWS Cognito API Describe User Import Job
  x-api-slug: aws-cognito-api
  description: Describes the user import job.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=DescribeUserImportJob
  tags: Users,Imports
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actiondescribeuserimportjob-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actiondescribeuserimportjob-get-openapi.md
- name: AWS Cognito API Describe User Pool
  x-api-slug: aws-cognito-api
  description: |-
    Returns the configuration information and metadata of the specified user
                pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=DescribeUserPool
  tags: Users,Pools
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actiondescribeuserpool-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actiondescribeuserpool-get-openapi.md
- name: AWS Cognito API Describe User Pool Client
  x-api-slug: aws-cognito-api
  description: |-
    Client method for returning the configuration information and metadata of the
                specified user pool client.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=DescribeUserPoolClient
  tags: Users,Pool Clients
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actiondescribeuserpoolclient-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actiondescribeuserpoolclient-get-openapi.md
- name: AWS Cognito API Forget Device
  x-api-slug: aws-cognito-api
  description: Forgets the specified device.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=ForgetDevice
  tags: Devices
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionforgetdevice-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionforgetdevice-get-openapi.md
- name: AWS Cognito API Forgot Password
  x-api-slug: aws-cognito-api
  description: Retrieves the password for the specified client ID or username.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=ForgotPassword
  tags: Passwords
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionforgotpassword-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionforgotpassword-get-openapi.md
- name: AWS Cognito API Get C S V Header
  x-api-slug: aws-cognito-api
  description: Gets the header information for the.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=GetCSVHeader
  tags: CSV Header
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actiongetcsvheader-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actiongetcsvheader-get-openapi.md
- name: AWS Cognito API Get Device
  x-api-slug: aws-cognito-api
  description: Gets the device.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=GetDevice
  tags: Users,Pools
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actiongetdevice-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actiongetdevice-get-openapi.md
- name: AWS Cognito API Get Group
  x-api-slug: aws-cognito-api
  description: Gets a group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=GetGroup
  tags: Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actiongetgroup-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actiongetgroup-get-openapi.md
- name: AWS Cognito API Get User
  x-api-slug: aws-cognito-api
  description: Gets the user attributes and metadata for a user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=GetUser
  tags: Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actiongetuser-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actiongetuser-get-openapi.md
- name: AWS Cognito API Get User Attribute Verification Code
  x-api-slug: aws-cognito-api
  description: |-
    Gets the user attribute verification code for the specified attribute
                name.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=GetUserAttributeVerificationCode
  tags: Verification Codes
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actiongetuserattributeverificationcode-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actiongetuserattributeverificationcode-get-openapi.md
- name: AWS Cognito API Global Sign Out
  x-api-slug: aws-cognito-api
  description: Signs out users from all devices.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=GlobalSignOut
  tags: Sign Out
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionglobalsignout-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionglobalsignout-get-openapi.md
- name: AWS Cognito API Initiate Auth
  x-api-slug: aws-cognito-api
  description: Initiates the authentication flow.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=InitiateAuth
  tags: Authentication
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actioninitiateauth-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actioninitiateauth-get-openapi.md
- name: AWS Cognito API List Devices
  x-api-slug: aws-cognito-api
  description: Lists the devices.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=ListDevices
  tags: Devices
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionlistdevices-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionlistdevices-get-openapi.md
- name: AWS Cognito API List Groups
  x-api-slug: aws-cognito-api
  description: Lists the groups associated with a user pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=ListGroups
  tags: Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionlistgroups-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionlistgroups-get-openapi.md
- name: AWS Cognito API List User Import Jobs
  x-api-slug: aws-cognito-api
  description: Lists the user import jobs.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=ListUserImportJobs
  tags: Users,Imports
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionlistuserimportjobs-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionlistuserimportjobs-get-openapi.md
- name: AWS Cognito API List User Pool Clients
  x-api-slug: aws-cognito-api
  description: Lists the clients that have been created for the specified user pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=ListUserPoolClients
  tags: user Pool Clients
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionlistuserpoolclients-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionlistuserpoolclients-get-openapi.md
- name: AWS Cognito API List User Pools
  x-api-slug: aws-cognito-api
  description: Lists the user pools associated with an AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=ListUserPools
  tags: user Pools
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionlistuserpools-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionlistuserpools-get-openapi.md
- name: AWS Cognito API List Users
  x-api-slug: aws-cognito-api
  description: Lists the users in the Amazon Cognito user pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=ListUsers
  tags: Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionlistusers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionlistusers-get-openapi.md
- name: AWS Cognito API List Users In Group
  x-api-slug: aws-cognito-api
  description: Lists the users in the specified group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=ListUsersInGroup
  tags: Users,Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionlistusersingroup-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionlistusersingroup-get-openapi.md
- name: AWS Cognito API Resend Confirmation Code
  x-api-slug: aws-cognito-api
  description: |-
    Resends the confirmation (for confirmation of registration) to a specific user in
                the user pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=ResendConfirmationCode
  tags: Confirmation Code
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionresendconfirmationcode-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionresendconfirmationcode-get-openapi.md
- name: AWS Cognito API Respond To Auth Challenge
  x-api-slug: aws-cognito-api
  description: Responds to the authentication challenge.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=RespondToAuthChallenge
  tags: Authentication Challenges
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionrespondtoauthchallenge-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionrespondtoauthchallenge-get-openapi.md
- name: AWS Cognito API Set User Settings
  x-api-slug: aws-cognito-api
  description: Sets the user settings like multi-factor authentication (MFA).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=SetUserSettings
  tags: Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionsetusersettings-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionsetusersettings-get-openapi.md
- name: AWS Cognito API Sign Up
  x-api-slug: aws-cognito-api
  description: |-
    Registers the user in the specified user pool and creates a user name, password,
                and user attributes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=SignUp
  tags: Sign Up
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionsignup-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionsignup-get-openapi.md
- name: AWS Cognito API Start User Import Job
  x-api-slug: aws-cognito-api
  description: Starts the user import.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=StartUserImportJob
  tags: Users,Imports
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionstartuserimportjob-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionstartuserimportjob-get-openapi.md
- name: AWS Cognito API Stop User Import Job
  x-api-slug: aws-cognito-api
  description: Stops the user import job.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=StopUserImportJob
  tags: Users,Iimport
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionstopuserimportjob-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionstopuserimportjob-get-openapi.md
- name: AWS Cognito API Update Device Status
  x-api-slug: aws-cognito-api
  description: Updates the device status.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=UpdateDeviceStatus
  tags: Devices
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionupdatedevicestatus-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionupdatedevicestatus-get-openapi.md
- name: AWS Cognito API Update Group
  x-api-slug: aws-cognito-api
  description: Updates the specified group with the specified attributes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=UpdateGroup
  tags: Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionupdategroup-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionupdategroup-get-openapi.md
- name: AWS Cognito API Update User Attributes
  x-api-slug: aws-cognito-api
  description: Allows a user to update a specific attribute (one at a time).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=UpdateUserAttributes
  tags: Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionupdateuserattributes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionupdateuserattributes-get-openapi.md
- name: AWS Cognito API Update User Pool
  x-api-slug: aws-cognito-api
  description: Updates the specified user pool with the specified attributes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=UpdateUserPool
  tags: Users,Pools
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionupdateuserpool-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionupdateuserpool-get-openapi.md
- name: AWS Cognito API Update User Pool Client
  x-api-slug: aws-cognito-api
  description: |-
    Allows the developer to update the specified user pool client and password
                policy.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=UpdateUserPoolClient
  tags: Users,Pool Clients
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionupdateuserpoolclient-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionupdateuserpoolclient-get-openapi.md
- name: AWS Cognito API Verify User Attribute
  x-api-slug: aws-cognito-api
  description: Verifies the specified user attributes in the user pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=VerifyUserAttribute
  tags: Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionverifyuserattribute-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionverifyuserattribute-get-openapi.md
- name: AWS Cognito API Create Identity Pool
  x-api-slug: aws-cognito-api
  description: Creates a new identity pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=CreateIdentityPool
  tags: Identity Pool
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actioncreateidentitypool-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actioncreateidentitypool-get-openapi.md
- name: AWS Cognito API Delete Identities
  x-api-slug: aws-cognito-api
  description: Deletes identities from an identity pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=DeleteIdentities
  tags: Identities
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actiondeleteidentities-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actiondeleteidentities-get-openapi.md
- name: AWS Cognito API Delete Identity Pool
  x-api-slug: aws-cognito-api
  description: Deletes a user pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=DeleteIdentityPool
  tags: Identity Pool
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actiondeleteidentitypool-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actiondeleteidentitypool-get-openapi.md
- name: AWS Cognito API Describe Identity
  x-api-slug: aws-cognito-api
  description: |-
    Returns metadata related to the given identity, including when the identity was
             created and any associated linked logins.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=DescribeIdentity
  tags: Identities
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actiondescribeidentity-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actiondescribeidentity-get-openapi.md
- name: AWS Cognito API Describe Identity Pool
  x-api-slug: aws-cognito-api
  description: |-
    Gets details about a particular identity pool, including the pool name, ID
             description, creation date, and current number of users.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=DescribeIdentityPool
  tags: Identity Pool
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actiondescribeidentitypool-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actiondescribeidentitypool-get-openapi.md
- name: AWS Cognito API Get Credentials For Identity
  x-api-slug: aws-cognito-api
  description: Returns credentials for the provided identity ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=GetCredentialsForIdentity
  tags: Identities
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actiongetcredentialsforidentity-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actiongetcredentialsforidentity-get-openapi.md
- name: AWS Cognito API Get Id
  x-api-slug: aws-cognito-api
  description: Generates (or retrieves) a Cognito ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=GetId
  tags: Identities
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actiongetid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actiongetid-get-openapi.md
- name: AWS Cognito API Get Identity Pool Roles
  x-api-slug: aws-cognito-api
  description: Gets the roles for an identity pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=GetIdentityPoolRoles
  tags: Identity Pool Roles
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actiongetidentitypoolroles-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actiongetidentitypoolroles-get-openapi.md
- name: AWS Cognito API Get Open Id Token
  x-api-slug: aws-cognito-api
  description: Gets an OpenID token, using a known Cognito ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=GetOpenIdToken
  tags: Open ID Token
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actiongetopenidtoken-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actiongetopenidtoken-get-openapi.md
- name: AWS Cognito API Get Open Id Token For Developer Identity
  x-api-slug: aws-cognito-api
  description: |-
    Registers (or retrieves) a Cognito IdentityId and an OpenID Connect
             token for a user authenticated by your backend authentication process.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=GetOpenIdTokenForDeveloperIdentity
  tags: Open ID Token for Developer Identities
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actiongetopenidtokenfordeveloperidentity-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actiongetopenidtokenfordeveloperidentity-get-openapi.md
- name: AWS Cognito API List Identities
  x-api-slug: aws-cognito-api
  description: Lists the identities in a pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=ListIdentities
  tags: Identities
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionlistidentities-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionlistidentities-get-openapi.md
- name: AWS Cognito API List Identity Pools
  x-api-slug: aws-cognito-api
  description: Lists all of the Cognito identity pools registered for your account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=ListIdentityPools
  tags: Identity Pool
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionlistidentitypools-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionlistidentitypools-get-openapi.md
- name: AWS Cognito API Lookup Developer Identity
  x-api-slug: aws-cognito-api
  description: |-
    Retrieves the IdentityID associated with a
                DeveloperUserIdentifier or the list of
             DeveloperUserIdentifiers associated with an IdentityId for an
             existing identity.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=LookupDeveloperIdentity
  tags: Developer Identities
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionlookupdeveloperidentity-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionlookupdeveloperidentity-get-openapi.md
- name: AWS Cognito API Merge Developer Identities
  x-api-slug: aws-cognito-api
  description: |-
    Merges two users having different IdentityIds, existing in the same
             identity pool, and identified by the same developer provider.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=MergeDeveloperIdentities
  tags: Developer Identities
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionmergedeveloperidentities-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionmergedeveloperidentities-get-openapi.md
- name: AWS Cognito API Set Identity Pool Roles
  x-api-slug: aws-cognito-api
  description: Sets the roles for an identity pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=SetIdentityPoolRoles
  tags: Identity Pool
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionsetidentitypoolroles-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionsetidentitypoolroles-get-openapi.md
- name: AWS Cognito API Unlink Developer Identity
  x-api-slug: aws-cognito-api
  description: Unlinks a DeveloperUserIdentifier from an existing identity.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=UnlinkDeveloperIdentity
  tags: Developer Identities
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionunlinkdeveloperidentity-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionunlinkdeveloperidentity-get-openapi.md
- name: AWS Cognito API Unlink Identity
  x-api-slug: aws-cognito-api
  description: Unlinks a federated identity from an existing account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=UnlinkIdentity
  tags: Identities
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionunlinkidentity-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionunlinkidentity-get-openapi.md
- name: AWS Cognito API Update Identity Pool
  x-api-slug: aws-cognito-api
  description: Updates a user pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=UpdateIdentityPool
  tags: Identity Pool
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionupdateidentitypool-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionupdateidentitypool-get-openapi.md
- name: AWS Cognito API Bulk Publish
  x-api-slug: aws-cognito-api
  description: Initiates a bulk publish of all existing datasets for an Identity Pool
    to the configured stream.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=BulkPublish
  tags: Publish
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionbulkpublish-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionbulkpublish-get-openapi.md
- name: AWS Cognito API Delete Dataset
  x-api-slug: aws-cognito-api
  description: Deletes the specific dataset.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=DeleteDataset
  tags: Dataset
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actiondeletedataset-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actiondeletedataset-get-openapi.md
- name: AWS Cognito API Describe Dataset
  x-api-slug: aws-cognito-api
  description: Gets meta data about a dataset by identity and dataset name.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=DescribeDataset
  tags: Dataset
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actiondescribedataset-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actiondescribedataset-get-openapi.md
- name: AWS Cognito API Describe Identity Pool Usage
  x-api-slug: aws-cognito-api
  description: Gets usage details (for example, data storage) about a particular identity
    pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=DescribeIdentityPoolUsage
  tags: Identity Pool Usage
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actiondescribeidentitypoolusage-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actiondescribeidentitypoolusage-get-openapi.md
- name: AWS Cognito API Describe Identity Usage
  x-api-slug: aws-cognito-api
  description: Gets usage information for an identity, including number of datasets
    and data usage.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=DescribeIdentityUsage
  tags: Identity Pool Usage
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actiondescribeidentityusage-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actiondescribeidentityusage-get-openapi.md
- name: AWS Cognito API Get Bulk Publish Details
  x-api-slug: aws-cognito-api
  description: Get the status of the last BulkPublish operation for an identity pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=GetBulkPublishDetails
  tags: Publish
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actiongetbulkpublishdetails-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actiongetbulkpublishdetails-get-openapi.md
- name: AWS Cognito API Get Cognito Events
  x-api-slug: aws-cognito-api
  description: Gets the events and the corresponding Lambda functions associated with
    an identity pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=GetCognitoEvents
  tags: Events
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actiongetcognitoevents-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actiongetcognitoevents-get-openapi.md
- name: AWS Cognito API Get Identity Pool Configuration
  x-api-slug: aws-cognito-api
  description: Gets the configuration settings of an identity pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=GetIdentityPoolConfiguration
  tags: Identity Pools
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actiongetidentitypoolconfiguration-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actiongetidentitypoolconfiguration-get-openapi.md
- name: AWS Cognito API List Datasets
  x-api-slug: aws-cognito-api
  description: Lists datasets for an identity.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=ListDatasets
  tags: Dataset
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionlistdatasets-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionlistdatasets-get-openapi.md
- name: AWS Cognito API List Identity Pool Usage
  x-api-slug: aws-cognito-api
  description: Gets a list of identity pools registered with Cognito.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=ListIdentityPoolUsage
  tags: Identity Pools
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionlistidentitypoolusage-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionlistidentitypoolusage-get-openapi.md
- name: AWS Cognito API List Records
  x-api-slug: aws-cognito-api
  description: Gets paginated records, optionally changed after a particular sync
    count for a dataset and identity.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=ListRecords
  tags: Records
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionlistrecords-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionlistrecords-get-openapi.md
- name: AWS Cognito API Register Device
  x-api-slug: aws-cognito-api
  description: Registers a device to receive push sync notifications.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=RegisterDevice
  tags: Devices
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionregisterdevice-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionregisterdevice-get-openapi.md
- name: AWS Cognito API Set Cognito Events
  x-api-slug: aws-cognito-api
  description: Sets the AWS Lambda function for a given event type for an identity
    pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=SetCognitoEvents
  tags: Events
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionsetcognitoevents-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionsetcognitoevents-get-openapi.md
- name: AWS Cognito API Set Identity Pool Configuration
  x-api-slug: aws-cognito-api
  description: Sets the necessary configuration for push sync.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=SetIdentityPoolConfiguration
  tags: Identity Pools
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionsetidentitypoolconfiguration-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionsetidentitypoolconfiguration-get-openapi.md
- name: AWS Cognito API Subscribe To Dataset
  x-api-slug: aws-cognito-api
  description: Subscribes to receive notifications when a dataset is modified by another
    device.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=SubscribeToDataset
  tags: Dataset
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionsubscribetodataset-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionsubscribetodataset-get-openapi.md
- name: AWS Cognito API Unsubscribe From Dataset
  x-api-slug: aws-cognito-api
  description: Unsubscribes from receiving notifications when a dataset is modified
    by another device.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=UnsubscribeFromDataset
  tags: Dataset
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionunsubscribefromdataset-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionunsubscribefromdataset-get-openapi.md
- name: AWS Cognito API Update Records
  x-api-slug: aws-cognito-api
  description: Posts updates to records and adds and deletes records for a dataset
    and user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=UpdateRecords
  tags: Records
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionupdaterecords-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/actionupdaterecords-get-openapi.md
- name: AWS Cognito API
  x-api-slug: aws-cognito-api
  description: Amazon Cognito lets you easily add user sign-up and sign-in to your
    mobile and web apps. With Amazon Cognito, you also have the options to authenticate
    users through social identity providers such as Facebook, Twitter, or Amazon,
    with SAML identity solutions, or by using your own identity system. In addition,
    Amazon Cognito enables you to save data locally on users devices, allowing your
    applications to work even when the devices are offline. You can then synchronize
    data across users devices so that their app experience remains consistent regardless
    of the device they use. With Amazon Cognito, you can focus on creating great app
    experiences instead of worrying about building, securing, and scaling a solution
    to handle user management, authentication, and sync across devices.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: AWS Cognito
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cognito/master/_listings/aws-cognito/openapi.md
x-common:
- type: x-blog
  url: https://aws.amazon.com/cognito/dev-resources/#blogposts
- type: x-documentation
  url: http://docs.aws.amazon.com/cognito-user-identity-pools/latest/APIReference/Welcome.html
- type: x-documentation
  url: http://docs.aws.amazon.com/cognitoidentity/latest/APIReference/Welcome.html
- type: x-documentation
  url: http://docs.aws.amazon.com/cognitosync/latest/APIReference/Welcome.html
- type: x-faq
  url: http://aws.amazon.com/cognito/faqs
- type: x-forum
  url: https://forums.aws.amazon.com/forum.jspa?forumID=173
- type: x-pricing
  url: http://aws.amazon.com/cognito/pricing
- type: x-sdk
  url: https://aws.amazon.com/cognito/dev-resources/#documentation
- type: x-slides
  url: https://aws.amazon.com/cognito/dev-resources/#slides
- type: x-videos
  url: https://aws.amazon.com/cognito/dev-resources/#videos
- type: x-website
  url: https://aws.amazon.com/cognito/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---