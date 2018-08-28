---
swagger: "2.0"
x-collection-name: Datadog
x-complete: 0
info:
  title: DataDog API Add Graph Embed
  version: 1.0.0
  description: Creates a new embeddable graph.
basePath: api/v1/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  graph/snapshot:
    get:
      summary: Get Graph Snapshot
      description: GET graph snapshot
      operationId: getGraphSnapshot
      x-api-path-slug: graphsnapshot-get
      parameters:
      - in: query
        name: graph_def
        description: can be used instead of metric_query
        type: string
      responses:
        200:
          description: OK
      tags:
      - Monitoring
      - Graph
      - Snapshot
  graph/embed:
    get:
      summary: Get Graph Embed
      description: Gets a list of previously created embeddable graphs.
      operationId: getGraphEmbed
      x-api-path-slug: graphembed-get
      responses:
        200:
          description: OK
      tags:
      - Monitoring
      - Graph
      - Embed
    post:
      summary: Add Graph Embed
      description: Creates a new embeddable graph.
      operationId: postGraphEmbed
      x-api-path-slug: graphembed-post
      responses:
        200:
          description: OK
      tags:
      - Monitoring
      - Graph
      - Embed
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