---
name: AWS CloudTrail
description: AWS CloudTrail is a web service that records AWS API calls for your account
  and delivers log files to you. The recorded information includes the identity of
  the API caller, the time of the API call, the source IP address of the API caller,
  the request parameters, and the response elements returned by the AWS service.nWith
  CloudTrail, you can get a history of AWS API calls for your account, including API
  calls made via the AWS Management Console, AWS SDKs, command line tools, and higher-level
  AWS services (such as AWS CloudFormation). The AWS API call history produced by
  CloudTrail enables security analysis, resource change tracking, and compliance auditing.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSCloudTrail.png
x-kinRank: "10"
x-alexaRank: ""
tags:
- Stack Network
- Management
- Logging
- Analysis
- Amazon Web Services
created: "2018-03-23"
modified: "2018-03-23"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/aws-cloudtrail/apis.yaml
specificationVersion: "0.14"
apis:
- name: AWS CloudTrail API
  description: AWS CloudTrail is a web service that records AWS API calls for your
    account and delivers log files to you
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSCloudTrail.png
  humanURL: ""
  baseURL: :///
  tags: Logging
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/aws-cloudtrail/action-stoplogging-get.md
- name: AWS CloudTrail API Stop Logging
  description: Suspends the recording of AWS API calls and log file delivery for the
    specified trail.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSCloudTrail.png
  humanURL: https://aws.amazon.com/cloudtrail/
  baseURL: http:://{host}//
  tags: Logging
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/aws-cloudtrail/action-stoplogging-get.md
x-common:
- type: x-console
  url: https://console.aws.amazon.com/cloudtrail/home
- type: x-documentation
  url: http://docs.aws.amazon.com/awscloudtrail/latest/APIReference/Welcome.html
- type: x-faq
  url: https://aws.amazon.com/cloudtrail/faqs/
- type: x-forum
  url: https://forums.aws.amazon.com/forum.jspa?forumID=168
- type: x-getting-started
  url: https://aws.amazon.com/cloudtrail/getting-started/
- type: x-partners
  url: https://aws.amazon.com/cloudtrail/partners/
- type: x-pricing
  url: https://aws.amazon.com/cloudtrail/pricing/
- type: x-website
  url: https://aws.amazon.com/cloudtrail/
- type: x-console
  url: https://console.aws.amazon.com/cloudtrail/home
- type: x-documentation
  url: http://docs.aws.amazon.com/awscloudtrail/latest/APIReference/Welcome.html
- type: x-faq
  url: https://aws.amazon.com/cloudtrail/faqs/
- type: x-forum
  url: https://forums.aws.amazon.com/forum.jspa?forumID=168
- type: x-getting-started
  url: https://aws.amazon.com/cloudtrail/getting-started/
- type: x-partners
  url: https://aws.amazon.com/cloudtrail/partners/
- type: x-pricing
  url: https://aws.amazon.com/cloudtrail/pricing/
- type: x-website
  url: https://aws.amazon.com/cloudtrail/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---