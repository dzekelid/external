---
swagger: "2.0"
x-collection-name: Azure Data Lake Analytics
x-complete: 1
info:
  title: DataLakeAnalyticsJobManagementClient
  description: creates-an-azure-data-lake-analytics-job-client-
  version: 1.0.0
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /catalog/usql/databases/{databaseName}/externaldatasources/{externalDataSourceName}:
    get:
      summary: Catalog Get External Data Source
      description: Retrieves the specified external data source from the Data Lake
        Analytics catalog.
      operationId: Catalog_GetExternalDataSource
      x-api-path-slug: catalogusqldatabasesdatabasenameexternaldatasourcesexternaldatasourcename-get
      parameters:
      - in: path
        name: databaseName
        description: The name of the database containing the external data source
      - in: path
        name: externalDataSourceName
        description: The name of the external data source
      - in: query
        name: No Name
      responses:
        1:
          description: Photoset not found - The photoset id passed was not the id
            of avalid photoset owned by the calling user
        2:
          description: Photo not found - The photo id passed was not the id of a valid
            photo owned by the calling user
        95:
          description: SSL is required - SSL is required to access the Flickr API
        96:
          description: Invalid signature - The passed signature was invalid
        97:
          description: Missing signature - The call required signing but no signature
            was sent
        98:
          description: Login failed / Invalid auth token - The login details or auth
            token passed were invalid
        99:
          description: User not logged in / Insufficient permissions - The method
            requires user authentication but the user was not logged in, or the authenticated
            method call did not have the required permissions
        100:
          description: Invalid API Key - The API key passed was not valid or has expired
        105:
          description: Service currently unavailable - The requested service is temporarily
            unavailable
        106:
          description: Write operation failed - The requested operation failed due
            to a temporary issue
        111:
          description: Format "xxx" not found - The requested response format was
            not found
        112:
          description: Method "xxx" not found - The requested method was not found
        114:
          description: Invalid SOAP envelope - The SOAP envelope send in the request
            could not be parsed
        115:
          description: Invalid XML-RPC Method Call - The XML-RPC request document
            could not be parsed
        116:
          description: Bad URL found - One or more arguments contained a URL that
            has been used for abuse on Flickr
        200:
          description: OK
      tags:
      - Catalog External Data Source
  /catalog/usql/databases/{databaseName}/externaldatasources:
    get:
      summary: Catalog List External Data Sources
      description: Retrieves the list of external data sources from the Data Lake
        Analytics catalog.
      operationId: Catalog_ListExternalDataSources
      x-api-path-slug: catalogusqldatabasesdatabasenameexternaldatasources-get
      parameters:
      - in: query
        name: $count
        description: The Boolean value of true or false to request a count of the
          matching resources included with the resources in the response, e
      - in: query
        name: $filter
        description: OData filter
      - in: query
        name: $orderby
        description: OrderBy clause
      - in: query
        name: $select
        description: OData Select statement
      - in: query
        name: $skip
        description: The number of items to skip over before returning elements
      - in: query
        name: $top
        description: The number of items to return
      - in: path
        name: databaseName
        description: The name of the database containing the external data sources
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Catalog External Data Sources
---