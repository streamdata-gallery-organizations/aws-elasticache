---
swagger: "2.0"
info:
  title: AWS ElastiCache API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeReplicationGroups:
    get:
      summary: ' Describe Replication Groups '
      description: |-
        Returns information about a particular
                    replication group
      operationId: describeReplicationGroups
      parameters:
      - in: query
        name: Marker
        description: An optional marker returned from a prior request
        type: string
      - in: query
        name: MaxRecords
        description: The maximum number of records to include in the response
        type: string
      - in: query
        name: ReplicationGroupId
        description: The identifier for the replication group to be described
        type: string
      responses:
        200:
          description: OK
      tags:
      - replication groups
definitions: []
x-collection-name: AWS ElastiCache
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