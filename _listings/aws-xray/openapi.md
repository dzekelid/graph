---
swagger: "2.0"
x-collection-name: AWS X-Ray
x-complete: 1
info:
  title: AWS X-Ray API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=GetServiceGraph:
    get:
      summary: Get Service Graph
      description: |-
        Retrieves a document that describes services that process incoming requests, and
              downstream services that they call as a result.
      operationId: getServiceGraph
      x-api-path-slug: actiongetservicegraph-get
      parameters:
      - in: query
        name: EndTime
        description: The end of the time frame for which to generate a graph
        type: string
      - in: query
        name: NextToken
        description: Pagination token
        type: string
      - in: query
        name: StartTime
        description: The start of the time frame for which to generate a graph
        type: string
      responses:
        200:
          description: OK
      tags:
      - Service Graph
  /?Action=GetTraceGraph:
    get:
      summary: Get Trace Graph
      description: Retrieves a service graph for one or more specific trace IDs.
      operationId: getTraceGraph
      x-api-path-slug: actiongettracegraph-get
      parameters:
      - in: query
        name: NextToken
        description: Pagination token
        type: string
      - in: query
        name: TraceIds
        description: Trace IDs of requests for which to generate a service graph
        type: string
      responses:
        200:
          description: OK
      tags:
      - Trace Graph
---