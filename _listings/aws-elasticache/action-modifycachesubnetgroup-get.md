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
  /?Action=ModifyCacheSubnetGroup:
    get:
      summary: ' Modify Cache Subnet Group '
      description: Modifies an existing cache subnet group
      operationId: modifyCacheSubnetGroup
      parameters:
      - in: query
        name: CacheSubnetGroupDescription
        description: A description of the cache subnet group
        type: string
      - in: query
        name: CacheSubnetGroupName
        description: The name for the cache subnet group
        type: string
      - in: query
        name: SubnetIds.SubnetIdentifier.N
        description: The EC2 subnet IDs for the cache subnet group
        type: string
      responses:
        200:
          description: OK
      tags:
      - cache subnet groups
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