---
name: AWS X-Ray
x-slug: aws-xray
description: AWS X-Ray helps developers analyze and debug production, distributed
  applications, such as those built using a microservices architecture. With X-Ray,
  you can understand how your application and its underlying services are performing
  to identify and troubleshoot the root cause of performance issues and errors. X-Ray
  provides an end-to-end view of requests as they travel through your application,
  and shows a map of your applications underlying components. You can use X-Ray to
  analyze both applications in development and in production, from simple three-tier
  applications to complex microservices applications consisting of thousands of services.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-xray.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Graph
created: "2018-08-25"
modified: "2018-08-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/graph/master/_listings/aws-xray/apis.md
specificationVersion: "0.14"
apis:
- name: AWS X-Ray API - Get Service Graph
  x-api-slug: actiongetservicegraph-get
  description: |-
    Retrieves a document that describes services that process incoming requests, and
          downstream services that they call as a result.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-xray.png
  humanURL: https://aws.amazon.com/xray/
  baseURL: :///
  tags: Amazon Web Services, Monitoring, Testing, Orchestration, Stack Network, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/graph/master/_listings/aws-xray/actiongetservicegraph-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/graph/master/_listings/aws-xray/actiongetservicegraph-get-openapi.md
- name: AWS X-Ray API - Get Trace Graph
  x-api-slug: actiongettracegraph-get
  description: Retrieves a service graph for one or more specific trace IDs.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-xray.png
  humanURL: https://aws.amazon.com/xray/
  baseURL: :///
  tags: Amazon Web Services, Monitoring, Testing, Orchestration, Stack Network, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/graph/master/_listings/aws-xray/actiongettracegraph-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/graph/master/_listings/aws-xray/actiongettracegraph-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://aws.workspaces.api.gallery.streamdata.io
- type: x-api-stack
  url: http://aws.xray.stack.network
- type: x-documentation
  url: http://docs.aws.amazon.com/xray/latest/api/Welcome.html
- type: x-faq
  url: https://aws.amazon.com/xray/faqs/
- type: x-getting-started
  url: https://aws.amazon.com/xray/getting-started/
- type: x-pricing
  url: https://aws.amazon.com/xray/pricing/
- type: x-website
  url: https://aws.amazon.com/xray/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---