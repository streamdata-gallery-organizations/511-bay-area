---
swagger: "2.0"
x-collection-name: 511 Bay Area
x-complete: 0
info:
  title: Bay Area 511 Transit API Transit Patterns API
  description: San francisco 511 transit transit patterns api.
  version: 1.0.0
host: api.511.org
basePath: /transit
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /operators:
    get:
      summary: Operatorators API
      description: San francisco 511 transit operatorators api.
      operationId: OperatorsGet
      x-api-path-slug: operators-get
      parameters:
      - in: query
        name: api_key
      responses:
        200:
          description: OK
      tags:
      - "511"
      - Operatorators
      - API
  /VehicleMonitoring:
    get:
      summary: San Francisco 511 Vehicle Monitoring API
      description: San francisco 511 vehicle monitoring api.
      operationId: VehicleMonitoringGet
      x-api-path-slug: vehiclemonitoring-get
      parameters:
      - in: query
        name: agency
      - in: query
        name: api_key
      - in: query
        name: stopCode
      responses:
        200:
          description: OK
      tags:
      - "511"
      - San
      - Francisco
      - "511"
      - Vehicle
      - Monitoring
      - API
  /stopPlaces:
    get:
      summary: Stop Places API
      description: San francisco 511 transit stop places api.
      operationId: StopPlacesGet
      x-api-path-slug: stopplaces-get
      parameters:
      - in: query
        name: api_key
      - in: query
        name: operator_id
      responses:
        200:
          description: OK
      tags:
      - "511"
      - Stop
      - Places
      - API
  /GeneralAnnouncements:
    get:
      summary: San Francisco 511 General Announcements API
      description: San francisco 511 general announcements api.
      operationId: GeneralAnnouncementsGet
      x-api-path-slug: generalannouncements-get
      parameters:
      - in: query
        name: api_key
      responses:
        200:
          description: OK
      tags:
      - "511"
      - San
      - Francisco
      - "511"
      - General
      - Announcements
      - API
  /stoptimetable:
    get:
      summary: Stop Timetable API
      description: San francisco 511 transit stop timetable api.
      operationId: StoptimetableGet
      x-api-path-slug: stoptimetable-get
      parameters:
      - in: query
        name: api_key
      - in: query
        name: MonitoringRef
      - in: query
        name: OperatorRef
      responses:
        200:
          description: OK
      tags:
      - "511"
      - Stop
      - Timetable
      - API
  /StopMonitoring:
    get:
      summary: Stop Monitoring API
      description: San francisco 511 transit stop monitoring api.
      operationId: StopMonitoringGet
      x-api-path-slug: stopmonitoring-get
      parameters:
      - in: query
        name: agency
      - in: query
        name: api_key
      - in: query
        name: stopCode
      responses:
        200:
          description: OK
      tags:
      - "511"
      - Stop
      - Monitoring
      - API
  /stops:
    get:
      summary: Stops API
      description: San francisco 511 transit stops api.
      operationId: StopsGet
      x-api-path-slug: stops-get
      parameters:
      - in: query
        name: api_key
      - in: query
        name: operator_id
      responses:
        200:
          description: OK
      tags:
      - "511"
      - Stops
      - API
  /patterns:
    get:
      summary: Transit Patterns API
      description: San francisco 511 transit transit patterns api.
      operationId: PatternsGet
      x-api-path-slug: patterns-get
      parameters:
      - in: query
        name: api_key
      - in: query
        name: operator_id
      - in: query
        name: pattern_id
      responses:
        200:
          description: OK
      tags:
      - "511"
      - Transit
      - Patterns
      - API
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