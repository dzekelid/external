---
name: New Relic
x-slug: new-relic
description: New Relic offers SaaS Software Analytics Platform that offers Application
  Performance Management and Real User Monitoring for Cloud and Data Center deployed
  web applications implemented in Ruby, Java, .NET, Python, PHP, Node.js. New Relic
  also offers mobile monitoring solutions for iOS and Android applications.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/newrelic-logo-square.png
x-kinRank: "8"
x-alexaRank: ""
tags: External
created: "2018-05-20"
modified: "2018-05-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/external/master/_listings/new-relic/apis.md
specificationVersion: "0.14"
apis:
- name: New Relic Add Alerts External Service Conditions Policies Policy  . Format
  x-api-slug: new-relic
  description: "This API endpoint allows you to create external service conditions
    for your alert policies.\n\nNote: Admin User\u2019s API Key is required.\n\nSee
    our documentation for a discussion on creating conditions for external services.\n\nAll
    fields are required except for \u201Crunbook_url\u201D, \u201Cenabled\u201D (defaults
    to false).\n\ntype: apm_external_service, mobile_external_service.\n\nname: A
    title for your condition.\n\nenabled: The status of your condition (optional).\n\nentities:
    An array of instance IDs associated with your condition.\n\nexternal_service_url:
    The URL of the external service. Must not include protocol (\u201Cexample.com\u201D,
    not \u201Chttps://example.com\u201D)\n\nmetric: The metric field accepts parameters
    based on the condition type selected as follows:\n\n\_\_When apm_external_service:
    response_time_average, response_time_minimum, response_time_maximum, throughput.\n\n\_\_When
    mobile_external_service: response_time_average, response_time_minimum, response_time_maximum,
    throughput, network_failure_percentage, http_status_error_percentage.\n\nrunbook_url:
    Runbook URL to display in notifications (optional).\n\nterms[duration] (in minutes):
    5, 10, 15, 30, 60, 120.\n\nterms[operator]: above, below, equal.\n\nterms[priority]:
    critical, warning.\n\nterms[threshold]: Must be 0 or greater.\n\nterms[time_function]:
    all, any."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/newrelic-logo-square.png
  humanURL: https://newrelic.com/
  baseURL: https:///v2///alerts_external_service_conditions/policies/{policy_id}.{format}
  tags: Alerts, External, Service, Conditions, Policies, Policy, , ., Format
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/external/master/_listings/new-relic/alerts-external-service-conditionspoliciespolicy-idformat-post-openapi.md
- name: New Relic Put Alerts External Service Conditions  . Format
  x-api-slug: new-relic
  description: "This API endpoint allows you to update external service conditions
    for your alert policies.\n\nNote: Admin User\u2019s API Key is required.\n\nSee
    Alerts External Service Conditions &gt; Create for an explanation of the field
    values used in this command or the online documentation on\nupdating conditions
    for external services."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/newrelic-logo-square.png
  humanURL: https://newrelic.com/
  baseURL: https:///v2///alerts_external_service_conditions/{id}.{format}
  tags: Alerts, External, Service, Conditions, , ., Format
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/external/master/_listings/new-relic/alerts-external-service-conditionsidformat-put-openapi.md
- name: New Relic Delete Alerts External Service Conditions Condition  . Format
  x-api-slug: new-relic
  description: "This API endpoint allows you to delete external service conditions
    associated with your alert policy.\n\nNote: Admin User\u2019s API Key is required.\n\nSee
    our documentation for a discussion on deleting External services conditions."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/newrelic-logo-square.png
  humanURL: https://newrelic.com/
  baseURL: https:///v2///alerts_external_service_conditions/{condition_id}.{format}
  tags: Alerts, External, Service, Conditions, Condition, , ., Format
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/external/master/_listings/new-relic/alerts-external-service-conditionscondition-idformat-delete-openapi.md
- name: New Relic Get Alerts External Service Conditions. Format
  x-api-slug: new-relic
  description: "This API endpoint allows you to list the external service conditions
    for your alert policy.\n\nSee our documentation for a discussion on \n output
    pagination."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/newrelic-logo-square.png
  humanURL: https://newrelic.com/
  baseURL: https:///v2///alerts_external_service_conditions.{format}
  tags: Alerts, External, Service, Conditions., Format
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/external/master/_listings/new-relic/alerts-external-service-conditionsformat-get-openapi.md
- name: New Relic
  x-api-slug: new-relic
  description: New Relic offers SaaS Software Analytics Platform that offers Application
    Performance Management and Real User Monitoring for Cloud and Data Center deployed
    web applications implemented in Ruby, Java, .NET, Python, PHP, Node.js. New Relic
    also offers mobile monitoring solutions for iOS and Android applications.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/newrelic-logo-square.png
  humanURL: https://newrelic.com/
  baseURL: https:///v2/
  tags: External
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/external/master/_listings/new-relic/openapi.md
x-common:
- type: x-blog
  url: https://blog.newrelic.com/
- type: x-blog-rss
  url: https://blog.newrelic.com/feed/
- type: x-developer
  url: https://rpm.newrelic.com/api/explore/
- type: x-github
  url: https://github.com/newrelic
- type: x-twitter
  url: https://twitter.com/NewRelic
- type: x-website
  url: https://newrelic.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---