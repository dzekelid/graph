---
swagger: "2.0"
x-collection-name: Datadog
x-complete: 1
info:
  title: DataDog Merged API
  version: 1.0.0
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
  graph/embed/:embed_id:
    get:
      summary: Get Graph Embed Embed
      description: Get the HTML fragment for a previously generated embed with embed_id.
      operationId: getGraphEmbedEmbed
      x-api-path-slug: graphembedembed-id-get
      responses:
        200:
          description: OK
      tags:
      - Monitoring
      - Graph
      - Embed
      - Embed
  graph/embed/:embed_id/enable:
    get:
      summary: Get Graph Embed Embed  Enable
      description: Enable a specified embed.
      operationId: getGraphEmbedEmbedEnable
      x-api-path-slug: graphembedembed-idenable-get
      responses:
        200:
          description: OK
      tags:
      - Monitoring
      - Graph
      - Embed
      - Embed
      - ""
      - Enable
---