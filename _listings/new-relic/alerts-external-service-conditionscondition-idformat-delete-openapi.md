---
swagger: "2.0"
x-collection-name: New Relic
x-complete: 0
info:
  title: New Relic Delete Alerts External Service Conditions Condition  . Format
  version: 1.0.0
  description: "This API endpoint allows you to delete external service conditions
    associated with your alert policy.\n\nNote: Admin User\u2019s API Key is required.\n\nSee
    our documentation for a discussion on deleting External services conditions."
basePath: v2/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /alerts_external_service_conditions/policies/{policy_id}.{format}:
    post:
      summary: Add Alerts External Service Conditions Policies Policy  . Format
      description: "This API endpoint allows you to create external service conditions
        for your alert policies.\n\nNote: Admin User\u2019s API Key is required.\n\nSee
        our documentation for a discussion on creating conditions for external services.\n\nAll
        fields are required except for \u201Crunbook_url\u201D, \u201Cenabled\u201D
        (defaults to false).\n\ntype: apm_external_service, mobile_external_service.\n\nname:
        A title for your condition.\n\nenabled: The status of your condition (optional).\n\nentities:
        An array of instance IDs associated with your condition.\n\nexternal_service_url:
        The URL of the external service. Must not include protocol (\u201Cexample.com\u201D,
        not \u201Chttps://example.com\u201D)\n\nmetric: The metric field accepts parameters
        based on the condition type selected as follows:\n\n\_\_When apm_external_service:
        response_time_average, response_time_minimum, response_time_maximum, throughput.\n\n\_\_When
        mobile_external_service: response_time_average, response_time_minimum, response_time_maximum,
        throughput, network_failure_percentage, http_status_error_percentage.\n\nrunbook_url:
        Runbook URL to display in notifications (optional).\n\nterms[duration] (in
        minutes): 5, 10, 15, 30, 60, 120.\n\nterms[operator]: above, below, equal.\n\nterms[priority]:
        critical, warning.\n\nterms[threshold]: Must be 0 or greater.\n\nterms[time_function]:
        all, any."
      operationId: postAlertsExternalServiceConditionsPoliciesPolicy.Format
      x-api-path-slug: alerts-external-service-conditionspoliciespolicy-idformat-post
      parameters:
      - in: body
        name: external_service_condition
        description: Condition schema
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: policy_id
        description: Alerts policy ID
        type: integer
      responses:
        200:
          description: OK
      tags:
      - Alerts
      - External
      - Service
      - Conditions
      - Policies
      - Policy
      - ""
      - .
      - Format
  /alerts_external_service_conditions/{id}.{format}:
    put:
      summary: Put Alerts External Service Conditions  . Format
      description: "This API endpoint allows you to update external service conditions
        for your alert policies.\n\nNote: Admin User\u2019s API Key is required.\n\nSee
        Alerts External Service Conditions &gt; Create for an explanation of the field
        values used in this command or the online documentation on\nupdating conditions
        for external services."
      operationId: putAlertsExternalServiceConditions.Format
      x-api-path-slug: alerts-external-service-conditionsidformat-put
      parameters:
      - in: body
        name: external_service_condition
        description: Condition schema
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: Alerts condition ID to update
        type: integer
      responses:
        200:
          description: OK
      tags:
      - Alerts
      - External
      - Service
      - Conditions
      - ""
      - .
      - Format
  /alerts_external_service_conditions/{condition_id}.{format}:
    delete:
      summary: Delete Alerts External Service Conditions Condition  . Format
      description: "This API endpoint allows you to delete external service conditions
        associated with your alert policy.\n\nNote: Admin User\u2019s API Key is required.\n\nSee
        our documentation for a discussion on deleting External services conditions."
      operationId: deleteAlertsExternalServiceConditionsCondition.Format
      x-api-path-slug: alerts-external-service-conditionscondition-idformat-delete
      parameters:
      - in: path
        name: condition_id
        description: Alerts condition ID
        type: integer
      responses:
        200:
          description: OK
      tags:
      - Alerts
      - External
      - Service
      - Conditions
      - Condition
      - ""
      - .
      - Format
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