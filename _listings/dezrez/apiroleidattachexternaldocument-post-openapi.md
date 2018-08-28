---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: Dezrez Attaches an externally hosted document to a role
  version: 1.0.0
  description: Attaches an externally hosted document to a role.
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/branding/{id}/attachexternaldocument:
    put:
      summary: Attaches an external document to brand.
      description: Attaches an external document to brand..
      operationId: Branding_AttachExternalDocumentByidByexternalDocument
      x-api-path-slug: apibrandingidattachexternaldocument-put
      parameters:
      - in: body
        name: externalDocument
        description: Details of the external document
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: The BrandId
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Attaches
      - External
      - Document
      - To
      - Brand
  /api/ExternalProvider:
    get:
      summary: Returns a URL that will start the process of authorisation with the
        external provider - normally using the OAuth1/2 protocol suite.
      description: Returns a url that will start the process of authorisation with
        the external provider - normally using the oauth1/2 protocol suite..
      operationId: ExternalProvider_GetAuthoriseAgencyUrlByexternalProviderId
      x-api-path-slug: apiexternalprovider-get
      parameters:
      - in: query
        name: externalProviderId
        description: The external provider identifier
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Returns
      - URL
      - That
      - Will
      - Start
      - Process
      - Of
      - Authorisation
      - External
      - Provider
      - '-'
      - Normally
      - Using
      - OAuth1
      - "2"
      - Protocol
      - Suite
  /api/group/{id}/attachexternaldocument:
    post:
      summary: Attaches the external document.
      description: Attaches the external document..
      operationId: Group_AttachExternalDocumentByidBydocumentDetails
      x-api-path-slug: apigroupidattachexternaldocument-post
      parameters:
      - in: body
        name: documentDetails
        description: The document details
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: The identifier
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Attaches
      - External
      - Document
  /api/role/{id}/boardrequest:
    post:
      summary: To send an board request email to a external provider
      description: To send an board request email to a external provider.
      operationId: Role_BoardRequestByidByupdateBoardRequestDataContract
      x-api-path-slug: apiroleidboardrequest-post
      parameters:
      - in: path
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: body
        name: updateBoardRequestDataContract
        description: Details of the sms to send
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - To
      - Send
      - Board
      - Request
      - Email
      - To
      - External
      - Provider
  /api/property/{id}/attachexternaldocument:
    post:
      summary: Attaches an externally hosted document to a property
      description: Attaches an externally hosted document to a property.
      operationId: Property_AttachExternalDocumentByidBydocumentDetails
      x-api-path-slug: apipropertyidattachexternaldocument-post
      parameters:
      - in: body
        name: documentDetails
        description: Details of the document to associate
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: The property Id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Attaches
      - Externally
      - Hosted
      - Document
      - To
      - Property
  /api/role/{id}/attachexternaldocument:
    post:
      summary: Attaches an externally hosted document to a role
      description: Attaches an externally hosted document to a role.
      operationId: Role_AttachExternalDocumentByidBydocumentDetails
      x-api-path-slug: apiroleidattachexternaldocument-post
      parameters:
      - in: body
        name: documentDetails
        description: Details of the document to associate
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: The role Id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Attaches
      - Externally
      - Hosted
      - Document
      - To
      - Role
  /api/roomdescription/{id}/attachexternaldocumenttoroom:
    put:
      summary: Attaches an externally hosted document to a room within a room description.
      description: Attaches an externally hosted document to a room within a room
        description..
      operationId: RoomDescription_AttachExternalDocumentToRoomByidByexternalDocumentByroomId
      x-api-path-slug: apiroomdescriptionidattachexternaldocumenttoroom-put
      parameters:
      - in: body
        name: externalDocument
        description: Details of the external document
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: The RoomDescriptionId
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: query
        name: roomId
        description: The room identifier
      responses:
        200:
          description: OK
      tags:
      - Attaches
      - Externally
      - Hosted
      - Document
      - To
      - Room
      - Within
      - Room
      - Description
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