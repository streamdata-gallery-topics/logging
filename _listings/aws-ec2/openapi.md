swagger: "2.0"
x-collection-name: AWS EC2
x-complete: 1
info:
  title: AWS EC2 API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=CreateFlowLogs:
    get:
      summary: Create Flow Logs
      description: Creates one or more flow logs to capture IP traffic for a specific
        network interface, subnet, or VPC.
      operationId: createflowlogs
      x-api-path-slug: actioncreateflowlogs-get
      parameters:
      - in: query
        name: FlowLogId.N
        description: One or more flow log IDs
        type: string
      responses:
        200:
          description: OK
      tags:
      - Flow Logs
  /?Action=DeleteFlowLogs:
    get:
      summary: Delete Flow Logs
      description: Deletes one or more flow logs.
      operationId: deleteflowlogs
      x-api-path-slug: actiondeleteflowlogs-get
      parameters:
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: FlowLogId.N
        description: One or more flow log IDs
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of results to return for the request in a
          single page
        type: string
      - in: query
        name: NextToken
        description: The token to retrieve the next page of results
        type: string
      responses:
        200:
          description: OK
      tags:
      - FLow Logs
  /?Action=DescribeFlowLogs:
    get:
      summary: Describe Flow Logs
      description: Describes one or more flow logs.
      operationId: describeflowlogs
      x-api-path-slug: actiondescribeflowlogs-get
      parameters:
      - in: query
        name: ClientToken
        description: Unique, case-sensitive identifier you provide to ensure the idempotency
          of the request
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,     and provides an error response
        type: string
      - in: query
        name: PolicyDocument
        description: A policy to attach to the endpoint that controls access to the
          service
        type: string
      - in: query
        name: RouteTableId.N
        description: One or more route table IDs
        type: string
      - in: query
        name: ServiceName
        description: The AWS service name, in the form com
        type: string
      - in: query
        name: VpcId
        description: The ID of the VPC in which the endpoint will be used
        type: string
      responses:
        200:
          description: OK
      tags:
      - Flow Logs
  /?Action=CreateSpotDatafeedSubscription:
    get:
      summary: Create Spot Datafeed Subscription
      description: Creates a data feed for Spot instances, enabling you to view Spot
        instance usage logs.
      operationId: createspotdatafeedsubscription
      x-api-path-slug: actioncreatespotdatafeedsubscription-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      responses:
        200:
          description: OK
      tags:
      - Subnet