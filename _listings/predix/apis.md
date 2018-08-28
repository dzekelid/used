---
name: Predix
x-slug: predix
description: Predix (IoT PaaS) helps you develop apps that connect people with industrial
  machines through analytics and data for better business outcomes.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
x-kinRank: "7"
x-alexaRank: "264121"
tags: Used
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/used/master/_listings/predix/apis.md
specificationVersion: "0.14"
apis:
- name: Analytics Framework - Validate the specified orchestration and the health
    of all the analytics used in the orchestration.
  x-api-slug: apiv2executionvalidation-post
  description: To successfully validate the orchestration, the BPMN XML file must
    reference analytics that are running. The validation will call a 'healthCheck'
    entry on each analytic.  Analytics in the platform automatically have this entry,
    analytics outside the platform must implement this APIfor their validation to
    pass.  The results contain the http status for each for the healthCheck call to
    each analytic.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/used/master/_listings/predix/apiv2executionvalidation-post-openapi.md
- name: Analytics Runtime - Validate the specified orchestration and the health of
    all the analytics used in the orchestration.
  x-api-slug: apiv2executionvalidation-post
  description: To successfully validate the orchestration, the BPMN XML file must
    reference analytics that are running. The validation will call a 'healthCheck'
    entry on each analytic.  Analytics in the platform automatically have this entry,
    analytics outside the platform must implement this APIfor their validation to
    pass.  The results contain the http status for each for the healthCheck call to
    each analytic.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/used/master/_listings/predix/apiv2executionvalidation-post-openapi.md
x-common:
- type: x-api-gallery
  url: http://predicthq.api.gallery.streamdata.io
- type: x-api-stack
  url: http://predix.stack.network
- type: x-crunchbase
  url: https://crunchbase.com/organization/predix
- type: x-documentation
  url: https://docs.predix.io/en-US/platform
- type: x-twitter
  url: https://twitter.com/Predix
- type: x-website
  url: https://www.predix.io
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---