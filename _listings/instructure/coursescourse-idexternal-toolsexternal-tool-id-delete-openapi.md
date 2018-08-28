---
swagger: "2.0"
x-collection-name: Instructure
x-complete: 0
info:
  title: Instructure Canvas Courses API Delete an external tool
  description: Delete an external tool.
  termsOfService: https://www.canvaslms.com/policies/api-policy
  version: v1
host: canvas.instructure.com
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /courses/{course_id}/external_feeds:
    get:
      summary: List external feeds
      description: List external feeds.
      operationId: list-external-feeds
      x-api-path-slug: coursescourse-idexternal-feeds-get
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
      - Courses
      - Course
      - Id
      - External
      - Feeds
    post:
      summary: Create an external feed
      description: Create an external feed.
      operationId: create-an-external-feed
      x-api-path-slug: coursescourse-idexternal-feeds-post
      parameters:
      - in: query
        name: header_match
        description: If given, only feed entries that contain this string in their
          title will benimported
      - in: query
        name: url
        description: The url to the external rss or atom feed
      - in: query
        name: verbosity
        description: 'Defaults to u201cfullu201dnn        n        n          Allowed
          values: full, truncate, link_only'
      responses:
        200:
          description: OK
      tags:
      - Courses
      - Course
      - Id
      - External
      - Feeds
  /courses/{course_id}/external_feeds/external_feed_id:
    delete:
      summary: Delete an external feed
      description: Delete an external feed.
      operationId: delete-an-external-feed
      x-api-path-slug: coursescourse-idexternal-feedsexternal-feed-id-delete
      responses:
        200:
          description: OK
      tags:
      - Courses
      - Course
      - Id
      - External
      - Feeds
      - External
      - Feed
      - Id
  /courses/{course_id}/external_tools:
    get:
      summary: List external tools
      description: List external tools.
      operationId: list-external-tools
      x-api-path-slug: coursescourse-idexternal-tools-get
      parameters:
      - in: query
        name: search_term
        description: The partial name of the tools to match and return
      - in: query
        name: selectable
        description: If true, then only tools that are meant to be selectable are
          returned
      responses:
        200:
          description: OK
      tags:
      - Courses
      - Course
      - Id
      - External
      - Tools
    post:
      summary: Create an external tool
      description: Create an external tool.
      operationId: create-an-external-tool
      x-api-path-slug: coursescourse-idexternal-tools-post
      parameters:
      - in: query
        name: account_navigation[enabled]
        description: Set this to enable this feature
      - in: query
        name: account_navigation[text]
        description: The text that will show on the left-tab in the account navigation
      - in: query
        name: account_navigation[url]
        description: The url of the external tool for account navigation
      - in: query
        name: config_type
        description: Configuration can be passed in as CC xml instead of using query
          parameters
      - in: query
        name: config_url
        description: URL where the server can retrieve an XML tool configuration,
          as specifiednin the CC xml specification
      - in: query
        name: config_xml
        description: XML tool configuration, as specified in the CC xml specification
      - in: query
        name: consumer_key
        description: The consumer key for the external tool
      - in: query
        name: course_navigation[default]
        description: Whether the navigation option will show in the course by default
          or whethernthe teacher will have to explicitly enable it
      - in: query
        name: course_navigation[enabled]
        description: Set this to enable this feature
      - in: query
        name: course_navigation[text]
        description: The text that will show on the left-tab in the course navigation
      - in: query
        name: course_navigation[url]
        description: The url of the external tool for course navigation
      - in: query
        name: course_navigation[visibility]
        description: Who will see the navigation tab
      - in: query
        name: custom_fields
        description: Custom fields that will be sent to the tool consumer, specified
          as custom_fields
      - in: query
        name: description
        description: A description of the tool
      - in: query
        name: domain
        description: The domain to match links against
      - in: query
        name: editor_button[enabled]
        description: Set this to enable this feature
      - in: query
        name: editor_button[icon_url]
        description: The url of the icon to show in the WYSIWYG editor
      - in: query
        name: editor_button[selection_height]
        description: The height of the dialog the tool is launched in
      - in: query
        name: editor_button[selection_width]
        description: The width of the dialog the tool is launched in
      - in: query
        name: editor_button[url]
        description: The url of the external tool
      - in: query
        name: icon_url
        description: The url of the icon to show for this tool
      - in: query
        name: name
        description: The name of the tool
      - in: query
        name: not_selectable
        description: 'Default: false, if set to true the tool won&#39;t show up in
          the externalntool selection UI in modules and assignments'
      - in: query
        name: privacy_level
        description: What information to send to the external tool
      - in: query
        name: resource_selection[enabled]
        description: Set this to enable this feature
      - in: query
        name: resource_selection[icon_url]
        description: The url of the icon to show in the module external tool list
      - in: query
        name: resource_selection[selection_height]
        description: The height of the dialog the tool is launched in
      - in: query
        name: resource_selection[selection_width]
        description: The width of the dialog the tool is launched in
      - in: query
        name: resource_selection[url]
        description: The url of the external tool
      - in: query
        name: shared_secret
        description: The shared secret with the external tool
      - in: query
        name: text
        description: The default text to show for this tool
      - in: query
        name: url
        description: The url to match links against
      - in: query
        name: user_navigation[enabled]
        description: Set this to enable this feature
      - in: query
        name: user_navigation[text]
        description: The text that will show on the left-tab in the user navigation
      - in: query
        name: user_navigation[url]
        description: The url of the external tool for user navigation
      responses:
        200:
          description: OK
      tags:
      - Courses
      - Course
      - Id
      - External
      - Tools
  /courses/{course_id}/external_tools/external_tool_id:
    delete:
      summary: Delete an external tool
      description: Delete an external tool.
      operationId: delete-an-external-tool
      x-api-path-slug: coursescourse-idexternal-toolsexternal-tool-id-delete
      responses:
        200:
          description: OK
      tags:
      - Courses
      - Course
      - Id
      - External
      - Tools
      - External
      - Tool
      - Id
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