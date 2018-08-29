---
swagger: "2.0"
x-collection-name: AWS ElastiCache
x-complete: 0
info:
  title: Amazon ElastiCache API Describe Cache Security Groups
  version: 1.0.0
  description: |-
    Returns a list of cache security group
                descriptions.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=AddTagsToResource:
    get:
      summary: Add Tags To Resource
      description: Adds up to 10 cost allocation tags to the named resource.
      operationId: addTagsToResource
      x-api-path-slug: actionaddtagstoresource-get
      parameters:
      - in: query
        name: ResourceName
        description: The Amazon Resource Name (ARN) of the resource to which the tags
          are to be added,             for example arn:aws:elasticache:us-west-2:0123456789:cluster:myCluster             or
          arn:aws:elasticache:us-west-2:0123456789:snapshot:mySnapshot
        type: string
      - in: query
        name: Tags.Tag.N
        description: A list of cost allocation tags to be added to this resource
        type: string
      responses:
        200:
          description: OK
      tags:
      - Resource Tags
  /?Action=AuthorizeCacheSecurityGroupIngress:
    get:
      summary: Authorize Cache Security Group Ingress
      description: |-
        Allows network ingress to a cache
                    security group.
      operationId: authorizeCacheSecurityGroupIngress
      x-api-path-slug: actionauthorizecachesecuritygroupingress-get
      parameters:
      - in: query
        name: CacheSecurityGroupName
        description: The cache security group that allows network ingress
        type: string
      - in: query
        name: EC2SecurityGroupName
        description: The Amazon EC2 security group to be authorized for ingress to
          the cache security group
        type: string
      - in: query
        name: EC2SecurityGroupOwnerId
        description: The AWS account number of the Amazon EC2 security group owner
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cache Security Groups
  /?Action=CopySnapshot:
    get:
      summary: Copy Snapshot
      description: Makes a copy of an existing snapshot.
      operationId: copySnapshot
      x-api-path-slug: actioncopysnapshot-get
      parameters:
      - in: query
        name: SourceSnapshotName
        description: The name of an existing snapshot from which to make a copy
        type: string
      - in: query
        name: TargetBucket
        description: The Amazon S3 bucket to which the snapshot is exported
        type: string
      - in: query
        name: TargetSnapshotName
        description: A name for the snapshot copy
        type: string
      responses:
        200:
          description: OK
      tags:
      - Snapshots
  /?Action=CreateCacheCluster:
    get:
      summary: Create Cache Cluster
      description: Creates a cache cluster.
      operationId: createCacheCluster
      x-api-path-slug: actioncreatecachecluster-get
      parameters:
      - in: query
        name: AuthToken
        description: Reserved parameter
        type: string
      - in: query
        name: AutoMinorVersionUpgrade
        description: This parameter is currently disabled
        type: string
      - in: query
        name: AZMode
        description: Specifies whether the nodes in this Memcached cluster are created
          in a single Availability Zone or             created across multiple Availability
          Zones in the clusters region
        type: string
      - in: query
        name: CacheClusterId
        description: The node group (shard) identifier
        type: string
      - in: query
        name: CacheNodeType
        description: The compute and memory capacity of the nodes in the node group
          (shard)
        type: string
      - in: query
        name: CacheParameterGroupName
        description: The name of the parameter group to associate with this cache
          cluster
        type: string
      - in: query
        name: CacheSecurityGroupNames.CacheSecurityGroupName.N
        description: A list of security group names to associate with this cache cluster
        type: string
      - in: query
        name: CacheSubnetGroupName
        description: The name of the subnet group to be used for the cache cluster
        type: string
      - in: query
        name: Engine
        description: The name of the cache engine to be used for this cache cluster
        type: string
      - in: query
        name: EngineVersion
        description: The version number of the cache engine to be used for this cache
          cluster
        type: string
      - in: query
        name: NotificationTopicArn
        description: The Amazon Resource Name (ARN) of the Amazon Simple Notification
          Service (SNS) topic           to which notifications are sent
        type: string
      - in: query
        name: NumCacheNodes
        description: The initial number of cache nodes that the cache cluster has
        type: string
      - in: query
        name: Port
        description: The port number on which each of the cache nodes  accepts connections
        type: string
      - in: query
        name: PreferredAvailabilityZone
        description: The EC2 Availability Zone in which the cache cluster is created
        type: string
      - in: query
        name: PreferredAvailabilityZones.PreferredAvailabilityZone.N
        description: A list of the Availability Zones in which cache nodes are created
        type: string
      - in: query
        name: PreferredMaintenanceWindow
        description: Specifies the weekly time range during which maintenance            on
          the cache cluster is performed
        type: string
      - in: query
        name: ReplicationGroupId
        description: Important
        type: string
      - in: query
        name: SecurityGroupIds.SecurityGroupId.N
        description: One or more VPC security groups associated with the cache cluster
        type: string
      - in: query
        name: SnapshotArns.SnapshotArn.N
        description: A single-element string list containing an Amazon Resource Name
          (ARN) that uniquely identifies a Redis RDB snapshot file stored in Amazon
          S3
        type: string
      - in: query
        name: SnapshotName
        description: The name of a Redis snapshot from which to restore data into
          the new node group (shard)
        type: string
      - in: query
        name: SnapshotRetentionLimit
        description: The number of days for which ElastiCache retains automatic snapshots
          before deleting them
        type: string
      - in: query
        name: SnapshotWindow
        description: The daily time range (in UTC) during which ElastiCache begins
          taking a daily snapshot of your node group (shard)
        type: string
      - in: query
        name: Tags.Tag.N
        description: A list of cost allocation tags to be added to this resource
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cache Clusters
  /?Action=CreateCacheParameterGroup:
    get:
      summary: Create Cache Parameter Group
      description: Creates a new cache parameter group.
      operationId: createCacheParameterGroup
      x-api-path-slug: actioncreatecacheparametergroup-get
      parameters:
      - in: query
        name: CacheParameterGroupFamily
        description: The name of the cache parameter group family that the cache parameter
          group can be used with
        type: string
      - in: query
        name: CacheParameterGroupName
        description: A user-specified name for the cache parameter group
        type: string
      - in: query
        name: Description
        description: A user-specified description for the cache parameter group
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cache Parameter Groups
  /?Action=CreateCacheSecurityGroup:
    get:
      summary: Create Cache Security Group
      description: Creates a new cache security group.
      operationId: createCacheSecurityGroup
      x-api-path-slug: actioncreatecachesecuritygroup-get
      parameters:
      - in: query
        name: CacheSecurityGroupName
        description: A name for the cache security group
        type: string
      - in: query
        name: Description
        description: A description for the cache security group
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cache Security Groups
  /?Action=CreateCacheSubnetGroup:
    get:
      summary: Create Cache Subnet Group
      description: Creates a new cache subnet group.
      operationId: createCacheSubnetGroup
      x-api-path-slug: actioncreatecachesubnetgroup-get
      parameters:
      - in: query
        name: CacheSubnetGroupDescription
        description: A description for the cache subnet group
        type: string
      - in: query
        name: CacheSubnetGroupName
        description: A name for the cache subnet group
        type: string
      - in: query
        name: SubnetIds.SubnetIdentifier.N
        description: A list of VPC subnet IDs for the cache subnet group
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cache Subnet Groups
  /?Action=CreateReplicationGroup:
    get:
      summary: Create Replication Group
      description: Creates a Redis (cluster mode disabled) or a Redis (cluster mode
        enabled) replication group.
      operationId: createReplicationGroup
      x-api-path-slug: actioncreatereplicationgroup-get
      parameters:
      - in: query
        name: AuthToken
        description: Reserved parameter
        type: string
      - in: query
        name: AutomaticFailoverEnabled
        description: Specifies whether a read-only replica is automatically promoted
          to read/write primary if the existing primary fails
        type: string
      - in: query
        name: AutoMinorVersionUpgrade
        description: This parameter is currently disabled
        type: string
      - in: query
        name: CacheNodeType
        description: The compute and memory capacity of the nodes in the node group
          (shard)
        type: string
      - in: query
        name: CacheParameterGroupName
        description: The name of the parameter group to associate with this replication
          group
        type: string
      - in: query
        name: CacheSecurityGroupNames.CacheSecurityGroupName.N
        description: A list of cache security group names to associate with this replication
          group
        type: string
      - in: query
        name: CacheSubnetGroupName
        description: The name of the cache subnet group to be used for the replication
          group
        type: string
      - in: query
        name: Engine
        description: The name of the cache engine to be used for the cache clusters
          in this replication group
        type: string
      - in: query
        name: EngineVersion
        description: The version number of the cache engine to be used for the cache
          clusters in this replication group
        type: string
      - in: query
        name: NodeGroupConfiguration.NodeGroupConfiguration.N
        description: A list of node group (shard) configuration options
        type: string
      - in: query
        name: NotificationTopicArn
        description: The Amazon Resource Name (ARN) of the Amazon Simple Notification
          Service (SNS) topic to which notifications are sent
        type: string
      - in: query
        name: NumCacheClusters
        description: The number of clusters this replication group initially has
        type: string
      - in: query
        name: NumNodeGroups
        description: An optional parameter that specifies the number of node groups
          (shards) for this Redis (cluster mode enabled) replication group
        type: string
      - in: query
        name: Port
        description: The port number on which each member of the replication group
          accepts connections
        type: string
      - in: query
        name: PreferredCacheClusterAZs.AvailabilityZone.N
        description: A list of EC2 Availability Zones in which the replication groups
          cache clusters are created
        type: string
      - in: query
        name: PreferredMaintenanceWindow
        description: Specifies the weekly time range during which maintenance    on
          the cache cluster is performed
        type: string
      - in: query
        name: PrimaryClusterId
        description: The identifier of the cache cluster that serves as the primary
          for this replication            group
        type: string
      - in: query
        name: ReplicasPerNodeGroup
        description: An optional parameter that specifies the number of replica nodes
          in each node group (shard)
        type: string
      - in: query
        name: ReplicationGroupDescription
        description: A user-created description for the replication group
        type: string
      - in: query
        name: ReplicationGroupId
        description: The replication group identifier
        type: string
      - in: query
        name: SecurityGroupIds.SecurityGroupId.N
        description: One or more Amazon VPC security groups associated with this replication
          group
        type: string
      - in: query
        name: SnapshotArns.SnapshotArn.N
        description: A list of Amazon Resource Names (ARN) that uniquely identify           the
          Redis RDB snapshot files stored in Amazon S3
        type: string
      - in: query
        name: SnapshotName
        description: The name of a snapshot from which to restore data into the new
          replication group
        type: string
      - in: query
        name: SnapshotRetentionLimit
        description: The number of days for which ElastiCache retains automatic snapshots
          before deleting them
        type: string
      - in: query
        name: SnapshotWindow
        description: The daily time range (in UTC) during which ElastiCache begins
          taking a daily snapshot of your node group (shard)
        type: string
      - in: query
        name: Tags.Tag.N
        description: A list of cost allocation tags to be added to this resource
        type: string
      responses:
        200:
          description: OK
      tags:
      - Replication Groups
  /?Action=CreateSnapshot:
    get:
      summary: Create Snapshot
      description: |-
        Creates a copy of an entire cache cluster or replication group at a
                    specific moment in time.
      operationId: createSnapshot
      x-api-path-slug: actioncreatesnapshot-get
      parameters:
      - in: query
        name: CacheClusterId
        description: The identifier of an existing cache cluster
        type: string
      - in: query
        name: ReplicationGroupId
        description: The identifier of an existing replication group
        type: string
      - in: query
        name: SnapshotName
        description: A name for the snapshot being created
        type: string
      responses:
        200:
          description: OK
      tags:
      - Snapshots
  /?Action=DeleteCacheCluster:
    get:
      summary: Delete Cache Cluster
      description: Deletes a previously provisioned cache cluster.
      operationId: deleteCacheCluster
      x-api-path-slug: actiondeletecachecluster-get
      parameters:
      - in: query
        name: CacheClusterId
        description: The cache cluster identifier for the cluster to be deleted
        type: string
      - in: query
        name: FinalSnapshotIdentifier
        description: The user-supplied name of a final cache cluster snapshot
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cache Clusters
  /?Action=DeleteCacheParameterGroup:
    get:
      summary: Delete Cache Parameter Group
      description: |-
        Deletes the specified cache parameter
                    group.
      operationId: deleteCacheParameterGroup
      x-api-path-slug: actiondeletecacheparametergroup-get
      parameters:
      - in: query
        name: CacheParameterGroupName
        description: The name of the cache parameter group to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cache Parameter Groups
  /?Action=DeleteCacheSecurityGroup:
    get:
      summary: Delete Cache Security Group
      description: Deletes a cache security group.
      operationId: deleteCacheSecurityGroup
      x-api-path-slug: actiondeletecachesecuritygroup-get
      parameters:
      - in: query
        name: CacheSecurityGroupName
        description: The name of the cache security group to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cache Security Groups
  /?Action=DeleteCacheSubnetGroup:
    get:
      summary: Delete Cache Subnet Group
      description: Deletes a cache subnet group.
      operationId: deleteCacheSubnetGroup
      x-api-path-slug: actiondeletecachesubnetgroup-get
      parameters:
      - in: query
        name: CacheSubnetGroupName
        description: The name of the cache subnet group to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cache Subnet Groups
  /?Action=DeleteReplicationGroup:
    get:
      summary: Delete Replication Group
      description: Deletes an existing replication group.
      operationId: deleteReplicationGroup
      x-api-path-slug: actiondeletereplicationgroup-get
      parameters:
      - in: query
        name: FinalSnapshotIdentifier
        description: The name of a final node group (shard) snapshot
        type: string
      - in: query
        name: ReplicationGroupId
        description: The identifier for the cluster to be deleted
        type: string
      - in: query
        name: RetainPrimaryCluster
        description: If set to true, all of the read replicas are deleted,             but
          the primary node is retained
        type: string
      responses:
        200:
          description: OK
      tags:
      - Replication Groups
  /?Action=DeleteSnapshot:
    get:
      summary: Delete Snapshot
      description: Deletes an existing snapshot.
      operationId: deleteSnapshot
      x-api-path-slug: actiondeletesnapshot-get
      parameters:
      - in: query
        name: SnapshotName
        description: The name of the snapshot to be deleted
        type: string
      responses:
        200:
          description: OK
      tags:
      - Snapshots
  /?Action=DescribeCacheClusters:
    get:
      summary: Describe Cache Clusters
      description: |-
        Returns information about all provisioned
                    cache clusters if no cache cluster identifier is specified, or about a specific cache
                    cluster if a cache cluster identifier is supplied.
      operationId: describeCacheClusters
      x-api-path-slug: actiondescribecacheclusters-get
      parameters:
      - in: query
        name: CacheClusterId
        description: The user-supplied cluster identifier
        type: string
      - in: query
        name: Marker
        description: An optional marker returned from a prior request
        type: string
      - in: query
        name: MaxRecords
        description: The maximum number of records to include in the response
        type: string
      - in: query
        name: ShowCacheNodeInfo
        description: An optional flag that can be included in the DescribeCacheCluster
          request             to retrieve information about the individual cache nodes
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cache Clusters
  /?Action=DescribeCacheEngineVersions:
    get:
      summary: Describe Cache Engine Versions
      description: |-
        Returns a list of the available cache
                    engines and their versions.
      operationId: describeCacheEngineVersions
      x-api-path-slug: actiondescribecacheengineversions-get
      parameters:
      - in: query
        name: CacheParameterGroupFamily
        description: The name of a specific cache parameter group family to return
          details for
        type: string
      - in: query
        name: DefaultOnly
        description: If true, specifies that only the default version of the specified
          engine or engine            and major version combination is to be returned
        type: string
      - in: query
        name: Engine
        description: The cache engine to return
        type: string
      - in: query
        name: EngineVersion
        description: The cache engine version to return
        type: string
      - in: query
        name: Marker
        description: An optional marker returned from a prior request
        type: string
      - in: query
        name: MaxRecords
        description: The maximum number of records to include in the response
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cache Engine Versions
  /?Action=DescribeCacheParameterGroups:
    get:
      summary: Describe Cache Parameter Groups
      description: |-
        Returns a list of cache parameter group
                    descriptions.
      operationId: describeCacheParameterGroups
      x-api-path-slug: actiondescribecacheparametergroups-get
      parameters:
      - in: query
        name: CacheParameterGroupName
        description: The name of a specific cache parameter group to return details
          for
        type: string
      - in: query
        name: Marker
        description: An optional marker returned from a prior request
        type: string
      - in: query
        name: MaxRecords
        description: The maximum number of records to include in the response
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cache Parameter Groups
  /?Action=DescribeCacheParameters:
    get:
      summary: Describe Cache Parameters
      description: |-
        Returns the detailed parameter list for a
                    particular cache parameter group.
      operationId: describeCacheParameters
      x-api-path-slug: actiondescribecacheparameters-get
      parameters:
      - in: query
        name: CacheParameterGroupName
        description: The name of a specific cache parameter group to return details
          for
        type: string
      - in: query
        name: Marker
        description: An optional marker returned from a prior request
        type: string
      - in: query
        name: MaxRecords
        description: The maximum number of records to include in the response
        type: string
      - in: query
        name: Source
        description: The parameter types to return
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cache Parameters
  /?Action=DescribeCacheSecurityGroups:
    get:
      summary: Describe Cache Security Groups
      description: |-
        Returns a list of cache security group
                    descriptions.
      operationId: describeCacheSecurityGroups
      x-api-path-slug: actiondescribecachesecuritygroups-get
      parameters:
      - in: query
        name: CacheSecurityGroupName
        description: The name of the cache security group to return details for
        type: string
      - in: query
        name: Marker
        description: An optional marker returned from a prior request
        type: string
      - in: query
        name: MaxRecords
        description: The maximum number of records to include in the response
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cache Security Groups
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