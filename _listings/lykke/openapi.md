---
swagger: "2.0"
x-collection-name: Lykke
x-complete: 1
info:
  title: Wallet_Api
  version: 1.0.0
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/GraphPeriods:
    get:
      summary: Get API Graphperiods
      description: Get api graphperiods.
      operationId: ApiGraphPeriodsGet
      x-api-path-slug: apigraphperiods-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - Graphperiods
---