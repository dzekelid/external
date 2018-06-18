---
swagger: "2.0"
x-collection-name: Instructure
x-complete: 0
info:
  title: Instructure Canvas Courses API List external tools
  description: List external tools.
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