{
  "info": {
    "name": "AWS X-Ray API Get Service Graph",
    "_postman_id": "194ac7d5-6b20-420e-a7c6-9739a6979ed3",
    "description": "Retrieves a document that describes services that process incoming requests, and\n      downstream services that they call as a result.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Traces",
      "item": [
        {
          "id": "2ee8830b-3ace-4806-9a20-ef5e958a30ae",
          "name": "batchGetTraces",
          "request": {
            "url": "http://example.com/api/?Action=BatchGetTraces?NextToken=NextToken&TraceIds=TraceIds",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves a list of traces specified by ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1dfc2561-173d-4052-8555-d17a40448df8"
            }
          ]
        }
      ]
    },
    {
      "name": "Service Graph",
      "item": [
        {
          "id": "e04384de-46e7-41f7-aaf7-2633cf19dc1e",
          "name": "getServiceGraph",
          "request": {
            "url": "http://example.com/api/?Action=GetServiceGraph?EndTime=EndTime&NextToken=NextToken&StartTime=StartTime",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves a document that describes services that process incoming requests, and\n      downstream services that they call as a result."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0f1b7210-f40e-49d7-8232-f5be8f7c5f2c"
            }
          ]
        }
      ]
    }
  ]
}