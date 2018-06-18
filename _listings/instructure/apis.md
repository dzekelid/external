---
name: Instructure
x-slug: instructure
description: Instructure makes software that makes smarter people. Products include
  Canvas LMS, Bridge and Canvas Network.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
x-kinRank: "8"
x-alexaRank: "367"
tags: External
created: "2018-06-18"
modified: "2018-06-18"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/external/master/_listings/instructure/apis.md
specificationVersion: "0.14"
apis:
- name: Instructure Canvas Courses API List external feeds
  x-api-slug: instructure-canvas-courses-api
  description: List external feeds.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/external_feeds
  tags: Courses,Course,Id,External,Feeds
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/external/master/_listings/instructure/coursescourse-idexternal-feeds-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/external/master/_listings/instructure/coursescourse-idexternal-feeds-get-openapi.md
- name: Instructure Canvas Courses API Create an external feed
  x-api-slug: instructure-canvas-courses-api
  description: Create an external feed.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/external_feeds
  tags: Courses,Course,Id,External,Feeds
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/external/master/_listings/instructure/coursescourse-idexternal-feeds-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/external/master/_listings/instructure/coursescourse-idexternal-feeds-post-openapi.md
- name: Instructure Canvas Courses API Delete an external feed
  x-api-slug: instructure-canvas-courses-api
  description: Delete an external feed.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/external_feeds/external_feed_id
  tags: Courses,Course,Id,External,Feeds,External,Feed,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/external/master/_listings/instructure/coursescourse-idexternal-feedsexternal-feed-id-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/external/master/_listings/instructure/coursescourse-idexternal-feedsexternal-feed-id-delete-openapi.md
- name: Instructure Canvas Courses API List external tools
  x-api-slug: instructure-canvas-courses-api
  description: List external tools.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/external_tools
  tags: Courses,Course,Id,External,Tools
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/external/master/_listings/instructure/coursescourse-idexternal-tools-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/external/master/_listings/instructure/coursescourse-idexternal-tools-get-openapi.md
- name: Instructure Canvas Courses API Create an external tool
  x-api-slug: instructure-canvas-courses-api
  description: Create an external tool.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/external_tools
  tags: Courses,Course,Id,External,Tools
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/external/master/_listings/instructure/coursescourse-idexternal-tools-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/external/master/_listings/instructure/coursescourse-idexternal-tools-post-openapi.md
- name: Instructure Canvas Courses API Delete an external tool
  x-api-slug: instructure-canvas-courses-api
  description: Delete an external tool.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/external_tools/external_tool_id
  tags: Courses,Course,Id,External,Tools,External,Tool,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/external/master/_listings/instructure/coursescourse-idexternal-toolsexternal-tool-id-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/external/master/_listings/instructure/coursescourse-idexternal-toolsexternal-tool-id-delete-openapi.md
- name: Instructure Canvas Courses API Get a single external tool
  x-api-slug: instructure-canvas-courses-api
  description: Get a single external tool.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/external_tools/external_tool_id
  tags: Courses,Course,Id,External,Tools,External,Tool,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/external/master/_listings/instructure/coursescourse-idexternal-toolsexternal-tool-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/external/master/_listings/instructure/coursescourse-idexternal-toolsexternal-tool-id-get-openapi.md
- name: Instructure Canvas Courses API Edit an external tool
  x-api-slug: instructure-canvas-courses-api
  description: Edit an external tool.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/external_tools/external_tool_id
  tags: Courses,Course,Id,External,Tools,External,Tool,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/external/master/_listings/instructure/coursescourse-idexternal-toolsexternal-tool-id-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/external/master/_listings/instructure/coursescourse-idexternal-toolsexternal-tool-id-put-openapi.md
- name: Instructure Canvas Courses API Get a sessionless launch url for an external
    tool.
  x-api-slug: instructure-canvas-courses-api
  description: Get a sessionless launch url for an external tool..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/external_tools/sessionless_launch
  tags: Courses,Course,Id,External,Tools,Sessionless,Launch
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/external/master/_listings/instructure/coursescourse-idexternal-toolssessionless-launch-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/external/master/_listings/instructure/coursescourse-idexternal-toolssessionless-launch-get-openapi.md
- name: Instructure Canvas Courses API
  x-api-slug: instructure-canvas-courses-api
  description: Instructure makes software that makes smarter people. Products include
    Canvas LMS, Bridge and Canvas Network.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1
  tags: External
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/external/master/_listings/instructure/openapi.md
- name: Instructure Canvas Groups API List external feeds
  x-api-slug: instructure-canvas-groups-api
  description: List external feeds.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//groups/{group_id}/external_feeds
  tags: Groups,Group,Id,External,Feeds
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/external/master/_listings/instructure/groupsgroup-idexternal-feeds-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/external/master/_listings/instructure/groupsgroup-idexternal-feeds-get-openapi.md
- name: Instructure Canvas Groups API Create an external feed
  x-api-slug: instructure-canvas-groups-api
  description: Create an external feed.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//groups/{group_id}/external_feeds
  tags: Groups,Group,Id,External,Feeds
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/external/master/_listings/instructure/groupsgroup-idexternal-feeds-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/external/master/_listings/instructure/groupsgroup-idexternal-feeds-post-openapi.md
- name: Instructure Canvas Groups API Delete an external feed
  x-api-slug: instructure-canvas-groups-api
  description: Delete an external feed.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//groups/{group_id}/external_feeds/external_feed_id
  tags: Groups,Group,Id,External,Feeds,External,Feed,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/external/master/_listings/instructure/groupsgroup-idexternal-feedsexternal-feed-id-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/external/master/_listings/instructure/groupsgroup-idexternal-feedsexternal-feed-id-delete-openapi.md
- name: Instructure Canvas Groups API
  x-api-slug: instructure-canvas-groups-api
  description: Instructure makes software that makes smarter people. Products include
    Canvas LMS, Bridge and Canvas Network.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1
  tags: External
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/external/master/_listings/instructure/openapi.md
x-common:
- type: x-blog
  url: http://blog.instructure.com
- type: x-blog-rss
  url: http://voice.instructure.com/CMS/UI/Modules/BizBlogger/rss.aspx?tabid=772438&moduleid=1638884&maxcount=25&t=415c2e5d197a4d6f7cdcc81385b677f1
- type: x-crunchbase
  url: https://crunchbase.com/organization/instructure
- type: x-crunchbase
  url: http://www.crunchbase.com/company/instructure
- type: x-email
  url: info@instructure.com
- type: x-email
  url: jobs@instructure.com
- type: x-email
  url: privacy@instructure.com
- type: x-email
  url: legal@instructure.com
- type: x-github
  url: https://github.com/instructure
- type: x-twitter
  url: https://twitter.com/instructure
- type: x-website
  url: http://instructure.com
- type: x-website
  url: https://canvas.instructure.com/doc/api/index.html
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---