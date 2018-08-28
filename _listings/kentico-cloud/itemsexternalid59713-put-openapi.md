---
swagger: "2.0"
x-collection-name: Kentico Cloud
x-complete: 0
info:
  title: Kentico Cloud Update a content item by external ID
  description: "Add a new content item or update an existing content item specified
    by its external ID.\r\n\r\n**Note:** If no content item with the specified external
    ID exists in the project, the system will try to create one. For existing content
    items, the API updates the content item's name and sitemap locations.\r\nYou can
    also specify the external ID when [adding content items](https://developer.kenticocloud.com/v1/reference#content-management-api-add-item)
    via the POST method."
  version: 1.0.0
host: deliver.kenticocloud.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /assets/external-id/which-brewing-fits-you:
    get:
      summary: View an asset by external ID
      description: Retrieve information about a single asset specified by its external
        ID.
      operationId: AssetsExternalIdWhichBrewingFitsYouGet
      x-api-path-slug: assetsexternalidwhichbrewingfitsyou-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - View
      - Asset
      - By
      - External
      - ID
    put:
      summary: Upsert an asset by external ID
      description: "Add a new asset or update an existing asset specified by its external
        ID.\r\n\r\n**Note:** If no asset with the specified external ID exists in
        the project, the system will try to create one. For existing assets, the API
        updates only the specified asset's descriptions and title."
      operationId: AssetsExternalIdWhichBrewingFitsYouPut
      x-api-path-slug: assetsexternalidwhichbrewingfitsyou-put
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Upsert
      - Asset
      - By
      - External
      - ID
  /items/external-id/59713:
    get:
      summary: View a content Item by external ID
      description: Retrieve metadata information about a content item specified by
        its external ID.
      operationId: ItemsExternalId59713Get
      x-api-path-slug: itemsexternalid59713-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - View
      - Content
      - Item
      - By
      - External
      - ID
    put:
      summary: Update a content item by external ID
      description: "Add a new content item or update an existing content item specified
        by its external ID.\r\n\r\n**Note:** If no content item with the specified
        external ID exists in the project, the system will try to create one. For
        existing content items, the API updates the content item's name and sitemap
        locations.\r\nYou can also specify the external ID when [adding content items](https://developer.kenticocloud.com/v1/reference#content-management-api-add-item)
        via the POST method."
      operationId: ItemsExternalId59713Put
      x-api-path-slug: itemsexternalid59713-put
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Content
      - Item
      - By
      - External
      - ID
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