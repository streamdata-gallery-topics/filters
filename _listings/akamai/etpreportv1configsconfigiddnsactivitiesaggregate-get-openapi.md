---
swagger: "2.0"
x-collection-name: Akamai
x-complete: 0
info:
  title: Akamai API Report DNS Activities Totals
  description: Report DNS Activities Totals
  version: 1.0.0
host: developer.akamai.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /etp-report/v1/configs/{configId}/threat-events/aggregate:
    get:
      summary: Report Security Event Aggregation
      description: Report Security Event Aggregation
      operationId: etpreportv1configsconfigidthreateventsaggregatestarttimesecendtimesecdimensionfilters
      x-api-path-slug: etpreportv1configsconfigidthreateventsaggregate-get
      parameters:
      - in: query
        name: configId
        description: ETP Configuration identifier assigned to the customer
        type: string
      - in: query
        name: dimension
        description: Flag to group the data
        type: string
      - in: query
        name: endTimeSec
        description: Timestamp for the end of the data window, in UTC seconds format
        type: string
      - in: query
        name: filters
        description: filter parameters to filter the data
        type: string
      - in: query
        name: startTimeSec
        description: Timestamp for the start of the data window, in UTC seconds format
        type: string
      responses:
        200:
          description: OK
      tags:
      - Etp
      - Report
      - Configurationss
      - Configurations
      - Threat
      - Events
      - Aggregation
      - Starttimesec
      - endtimesec
      - dimension
      - filters
      - Aggregation
  /etp-report/v1/configs/{configId}/threat-events/details:
    get:
      summary: Report Security Event Details
      description: Report Security Event Details
      operationId: etpreportv1configsconfigidthreateventsdetailsstarttimesecendtimesecdimensionfilters
      x-api-path-slug: etpreportv1configsconfigidthreateventsdetails-get
      parameters:
      - in: query
        name: configId
        description: ETP Configuration identifier assigned to the customer
        type: string
      - in: query
        name: dimension
        description: Flag to group the data
        type: string
      - in: query
        name: endTimeSec
        description: Timestamp for the end of the data window, in UTC seconds format
        type: string
      - in: query
        name: filters
        description: filter parameters to filter the data
        type: string
      - in: query
        name: startTimeSec
        description: Timestamp for the start of the data window, in UTC seconds format
        type: string
      responses:
        200:
          description: OK
      tags:
      - Etp
      - Report
      - Configurationss
      - Configurations
      - Threat
      - Events
      - Details
      - Starttimesec
      - endtimesec
      - dimension
      - filters
  /etp-report/v1/configs/{configId}/threat-events/time-series:
    get:
      summary: Report Security Event Time Series
      description: Report Security Event Time Series
      operationId: etpreportv1configsconfigidthreateventstimeseriesstarttimesecendtimesecdimensionfilters
      x-api-path-slug: etpreportv1configsconfigidthreateventstimeseries-get
      parameters:
      - in: query
        name: configId
        description: ETP Configuration identifier assigned to the customer
        type: string
      - in: query
        name: dimension
        description: Flag to group the data
        type: string
      - in: query
        name: endTimeSec
        description: Timestamp for the end of the data window, in UTC seconds format
        type: string
      - in: query
        name: filters
        description: filter parameters to filter the data
        type: string
      - in: query
        name: startTimeSec
        description: Timestamp for the start of the data window, in UTC seconds format
        type: string
      responses:
        200:
          description: OK
      tags:
      - Etp
      - Report
      - Configurationss
      - Configurations
      - Threat
      - Events
      - Time
      - Series
      - Starttimesec
      - endtimesec
      - dimension
      - filters
  /etp-report/v1/configs/{configId}/aup-events/details:
    get:
      summary: Report AUP Event Details
      description: Report AUP Event Details
      operationId: etpreportv1configsconfigidaupeventsdetailsstarttimesecendtimesecdimensionfilters
      x-api-path-slug: etpreportv1configsconfigidaupeventsdetails-get
      parameters:
      - in: query
        name: configId
        description: ETP Configuration identifier assigned to the customer
        type: string
      - in: query
        name: dimension
        description: Flag to group the data
        type: string
      - in: query
        name: endTimeSec
        description: Timestamp for the end of the data window, in UTC seconds format
        type: string
      - in: query
        name: filters
        description: filter parameters to filter the data
        type: string
      - in: query
        name: startTimeSec
        description: Timestamp for the start of the data window, in UTC seconds format
        type: string
      responses:
        200:
          description: OK
      tags:
      - Etp
      - Report
      - Configurationss
      - Configurations
      - Aup
      - Events
      - Details
      - Starttimesec
      - endtimesec
      - dimension
      - filters
  /etp-report/v1/configs/{configId}/aup-events/time-series:
    get:
      summary: Report AUP Event Time Series
      description: Report AUP Event Time Series
      operationId: etpreportv1configsconfigidaupeventstimeseriesstarttimesecendtimesecdimensionfilters
      x-api-path-slug: etpreportv1configsconfigidaupeventstimeseries-get
      parameters:
      - in: query
        name: configId
        description: ETP Configuration identifier assigned to the customer
        type: string
      - in: query
        name: dimension
        description: Flag to group the data
        type: string
      - in: query
        name: endTimeSec
        description: Timestamp for the end of the data window, in UTC seconds format
        type: string
      - in: query
        name: filters
        description: filter parameters to filter the data
        type: string
      - in: query
        name: startTimeSec
        description: Timestamp for the start of the data window, in UTC seconds format
        type: string
      responses:
        200:
          description: OK
      tags:
      - Etp
      - Report
      - Configurationss
      - Configurations
      - Aup
      - Events
      - Time
      - Series
      - Starttimesec
      - endtimesec
      - dimension
      - filters
  /etp-report/v1/configs/{configId}/dns-activities/time-series:
    get:
      summary: Report DNS Activity Time Series
      description: Report DNS Activity Time Series
      operationId: etpreportv1configsconfigiddnsactivitiestimeseriesstarttimesecendtimesecdimensionfilters
      x-api-path-slug: etpreportv1configsconfigiddnsactivitiestimeseries-get
      parameters:
      - in: query
        name: configId
        description: ETP Configuration identifier assigned to the customer
        type: string
      - in: query
        name: dimension
        description: Flag to group the data
        type: string
      - in: query
        name: endTimeSec
        description: Timestamp for the end of the data window, in UTC seconds format
        type: string
      - in: query
        name: filters
        description: filter parameters to filter the data
        type: string
      - in: query
        name: startTimeSec
        description: Timestamp for the start of the data window, in UTC seconds format
        type: string
      responses:
        200:
          description: OK
      tags:
      - Etp
      - Report
      - Configurationss
      - Configurations
      - DNS
      - Activities
      - Time
      - Series
      - Starttimesec
      - endtimesec
      - dimension
      - filters
  /etp-report/v1/configs/{configId}/dns-activities/aggregate:
    get:
      summary: Report DNS Activities Totals
      description: Report DNS Activities Totals
      operationId: etpreportv1configsconfigiddnsactivitiesaggregatestarttimesecendtimesecdimensionfilters
      x-api-path-slug: etpreportv1configsconfigiddnsactivitiesaggregate-get
      parameters:
      - in: query
        name: configId
        description: ETP Configuration identifier assigned to the customer
        type: string
      - in: query
        name: dimension
        description: Flag to group the data
        type: string
      - in: query
        name: endTimeSec
        description: Timestamp for the end of the data window, in UTC seconds format
        type: string
      - in: query
        name: filters
        description: filter parameters to filter the data
        type: string
      - in: query
        name: startTimeSec
        description: Timestamp for the start of the data window, in UTC seconds format
        type: string
      responses:
        200:
          description: OK
      tags:
      - Etp
      - Report
      - Configurationss
      - Configurations
      - DNS
      - Activities
      - Aggregation
      - Starttimesec
      - endtimesec
      - dimension
      - filters
      - Aggregation
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