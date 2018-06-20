---
name: AWS ElastiCache
x-slug: aws-elasticache
description: Amazon ElastiCache is a web service that makes it easy to deploy, operate,
  and scale an in-memory data store or cache in the cloud. The service improves the
  performance of web applications by allowing you to retrieve information from fast,
  managed, in-memory data stores, instead of relying entirely on slower disk-based
  databases. Amazon ElastiCache automatically detects and replaces failed nodes, reducing
  the overhead associated with self-managed infrastructures and provides a resilient
  system that mitigates the risk of overloaded databases, which slow website and application
  load times. Through integration with Amazon CloudWatch, Amazon ElastiCache provides
  enhanced visibility into key performance metrics associated with your Redis or Memcached
  nodes.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
x-kinRank: "10"
x-alexaRank: "0"
tags: AWS ElastiCache
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elasticache/master/_listings/aws-elasticache/apis.md
specificationVersion: "0.14"
apis:
- name: Amazon ElastiCache API Add Tags To Resource
  x-api-slug: amazon-elasticache-api
  description: Adds up to 10 cost allocation tags to the named resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: ://///?Action=AddTagsToResource
  tags: Resource Tags
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elasticache/master/_listings/aws-elasticache/actionaddtagstoresource-get-openapi.md
- name: Amazon ElastiCache API Authorize Cache Security Group Ingress
  x-api-slug: amazon-elasticache-api
  description: |-
    Allows network ingress to a cache
                security group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: ://///?Action=AuthorizeCacheSecurityGroupIngress
  tags: Cache Security Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elasticache/master/_listings/aws-elasticache/actionauthorizecachesecuritygroupingress-get-openapi.md
- name: Amazon ElastiCache API Copy Snapshot
  x-api-slug: amazon-elasticache-api
  description: Makes a copy of an existing snapshot.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: ://///?Action=CopySnapshot
  tags: Snapshots
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elasticache/master/_listings/aws-elasticache/actioncopysnapshot-get-openapi.md
- name: Amazon ElastiCache API Create Cache Cluster
  x-api-slug: amazon-elasticache-api
  description: Creates a cache cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: ://///?Action=CreateCacheCluster
  tags: Cache Clusters
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elasticache/master/_listings/aws-elasticache/actioncreatecachecluster-get-openapi.md
- name: Amazon ElastiCache API Create Cache Parameter Group
  x-api-slug: amazon-elasticache-api
  description: Creates a new cache parameter group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: ://///?Action=CreateCacheParameterGroup
  tags: Cache Parameter Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elasticache/master/_listings/aws-elasticache/actioncreatecacheparametergroup-get-openapi.md
- name: Amazon ElastiCache API Create Cache Security Group
  x-api-slug: amazon-elasticache-api
  description: Creates a new cache security group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: ://///?Action=CreateCacheSecurityGroup
  tags: Cache Security Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elasticache/master/_listings/aws-elasticache/actioncreatecachesecuritygroup-get-openapi.md
- name: Amazon ElastiCache API Create Cache Subnet Group
  x-api-slug: amazon-elasticache-api
  description: Creates a new cache subnet group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: ://///?Action=CreateCacheSubnetGroup
  tags: Cache Subnet Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elasticache/master/_listings/aws-elasticache/actioncreatecachesubnetgroup-get-openapi.md
- name: Amazon ElastiCache API Create Replication Group
  x-api-slug: amazon-elasticache-api
  description: Creates a Redis (cluster mode disabled) or a Redis (cluster mode enabled)
    replication group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: ://///?Action=CreateReplicationGroup
  tags: Replication Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elasticache/master/_listings/aws-elasticache/actioncreatereplicationgroup-get-openapi.md
- name: Amazon ElastiCache API Create Snapshot
  x-api-slug: amazon-elasticache-api
  description: |-
    Creates a copy of an entire cache cluster or replication group at a
                specific moment in time.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: ://///?Action=CreateSnapshot
  tags: Snapshots
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elasticache/master/_listings/aws-elasticache/actioncreatesnapshot-get-openapi.md
- name: Amazon ElastiCache API Delete Cache Cluster
  x-api-slug: amazon-elasticache-api
  description: Deletes a previously provisioned cache cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: ://///?Action=DeleteCacheCluster
  tags: Cache Clusters
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elasticache/master/_listings/aws-elasticache/actiondeletecachecluster-get-openapi.md
- name: Amazon ElastiCache API Delete Cache Parameter Group
  x-api-slug: amazon-elasticache-api
  description: |-
    Deletes the specified cache parameter
                group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: ://///?Action=DeleteCacheParameterGroup
  tags: Cache Parameter Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elasticache/master/_listings/aws-elasticache/actiondeletecacheparametergroup-get-openapi.md
- name: Amazon ElastiCache API Delete Cache Security Group
  x-api-slug: amazon-elasticache-api
  description: Deletes a cache security group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: ://///?Action=DeleteCacheSecurityGroup
  tags: Cache Security Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elasticache/master/_listings/aws-elasticache/actiondeletecachesecuritygroup-get-openapi.md
- name: Amazon ElastiCache API Delete Cache Subnet Group
  x-api-slug: amazon-elasticache-api
  description: Deletes a cache subnet group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: ://///?Action=DeleteCacheSubnetGroup
  tags: Cache Subnet Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elasticache/master/_listings/aws-elasticache/actiondeletecachesubnetgroup-get-openapi.md
- name: Amazon ElastiCache API Delete Replication Group
  x-api-slug: amazon-elasticache-api
  description: Deletes an existing replication group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: ://///?Action=DeleteReplicationGroup
  tags: Replication Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elasticache/master/_listings/aws-elasticache/actiondeletereplicationgroup-get-openapi.md
- name: Amazon ElastiCache API Delete Snapshot
  x-api-slug: amazon-elasticache-api
  description: Deletes an existing snapshot.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: ://///?Action=DeleteSnapshot
  tags: Snapshots
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elasticache/master/_listings/aws-elasticache/actiondeletesnapshot-get-openapi.md
- name: Amazon ElastiCache API Describe Cache Clusters
  x-api-slug: amazon-elasticache-api
  description: |-
    Returns information about all provisioned
                cache clusters if no cache cluster identifier is specified, or about a specific cache
                cluster if a cache cluster identifier is supplied.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: ://///?Action=DescribeCacheClusters
  tags: Cache Clusters
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elasticache/master/_listings/aws-elasticache/actiondescribecacheclusters-get-openapi.md
- name: Amazon ElastiCache API Describe Cache Engine Versions
  x-api-slug: amazon-elasticache-api
  description: |-
    Returns a list of the available cache
                engines and their versions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: ://///?Action=DescribeCacheEngineVersions
  tags: Cache Engine Versions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elasticache/master/_listings/aws-elasticache/actiondescribecacheengineversions-get-openapi.md
- name: Amazon ElastiCache API Describe Cache Parameter Groups
  x-api-slug: amazon-elasticache-api
  description: |-
    Returns a list of cache parameter group
                descriptions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: ://///?Action=DescribeCacheParameterGroups
  tags: Cache Parameter Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elasticache/master/_listings/aws-elasticache/actiondescribecacheparametergroups-get-openapi.md
- name: Amazon ElastiCache API Describe Cache Parameters
  x-api-slug: amazon-elasticache-api
  description: |-
    Returns the detailed parameter list for a
                particular cache parameter group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: ://///?Action=DescribeCacheParameters
  tags: Cache Parameters
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elasticache/master/_listings/aws-elasticache/actiondescribecacheparameters-get-openapi.md
- name: Amazon ElastiCache API Describe Cache Security Groups
  x-api-slug: amazon-elasticache-api
  description: |-
    Returns a list of cache security group
                descriptions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: ://///?Action=DescribeCacheSecurityGroups
  tags: Cache Security Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elasticache/master/_listings/aws-elasticache/actiondescribecachesecuritygroups-get-openapi.md
- name: Amazon ElastiCache API Describe Cache Subnet Groups
  x-api-slug: amazon-elasticache-api
  description: |-
    Returns a list of cache subnet group
                descriptions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: ://///?Action=DescribeCacheSubnetGroups
  tags: Cache Subnet Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elasticache/master/_listings/aws-elasticache/actiondescribecachesubnetgroups-get-openapi.md
- name: Amazon ElastiCache API Describe Engine Default Parameters
  x-api-slug: amazon-elasticache-api
  description: |-
    Returns the default engine and
                system parameter information for the specified cache engine.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: ://///?Action=DescribeEngineDefaultParameters
  tags: Engine Default Parameters
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elasticache/master/_listings/aws-elasticache/actiondescribeenginedefaultparameters-get-openapi.md
- name: Amazon ElastiCache API Describe Events
  x-api-slug: amazon-elasticache-api
  description: |-
    Returns events related to cache clusters, cache
                security groups, and cache parameter groups.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: ://///?Action=DescribeEvents
  tags: Events
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elasticache/master/_listings/aws-elasticache/actiondescribeevents-get-openapi.md
- name: Amazon ElastiCache API Describe Replication Groups
  x-api-slug: amazon-elasticache-api
  description: |-
    Returns information about a particular
                replication group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: ://///?Action=DescribeReplicationGroups
  tags: Replication Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elasticache/master/_listings/aws-elasticache/actiondescribereplicationgroups-get-openapi.md
- name: Amazon ElastiCache API Describe Reserved Cache Nodes
  x-api-slug: amazon-elasticache-api
  description: |-
    Returns information about reserved cache
                nodes for this account, or about a specified reserved cache node.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: ://///?Action=DescribeReservedCacheNodes
  tags: Reserved Cache Nodes
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elasticache/master/_listings/aws-elasticache/actiondescribereservedcachenodes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elasticache/master/_listings/aws-elasticache/actiondescribereservedcachenodes-get-openapi.md
- name: Amazon ElastiCache API Describe Reserved Cache Nodes Offerings
  x-api-slug: amazon-elasticache-api
  description: |-
    Lists available reserved cache
                node offerings.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: ://///?Action=DescribeReservedCacheNodesOfferings
  tags: Reserved Cache Nodes
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elasticache/master/_listings/aws-elasticache/actiondescribereservedcachenodesofferings-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elasticache/master/_listings/aws-elasticache/actiondescribereservedcachenodesofferings-get-openapi.md
- name: Amazon ElastiCache API Describe Snapshots
  x-api-slug: amazon-elasticache-api
  description: Returns information about cache cluster or replication group snapshots.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: ://///?Action=DescribeSnapshots
  tags: Snapshots
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elasticache/master/_listings/aws-elasticache/actiondescribesnapshots-get-openapi.md
- name: Amazon ElastiCache API List Allowed Node Type Modifications
  x-api-slug: amazon-elasticache-api
  description: |-
    Lists all available node types that you
                can scale your Redis cluster's or replication group's current node type up to.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: ://///?Action=ListAllowedNodeTypeModifications
  tags: Node Type Modifications
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elasticache/master/_listings/aws-elasticache/actionlistallowednodetypemodifications-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elasticache/master/_listings/aws-elasticache/actionlistallowednodetypemodifications-get-openapi.md
- name: Amazon ElastiCache API List Available Node Types
  x-api-slug: amazon-elasticache-api
  description: .
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: ://///?Action=ListAvailableNodeTypes
  tags: Node Types
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elasticache/master/_listings/aws-elasticache/actionlistavailablenodetypes-get-openapi.md
- name: Amazon ElastiCache API List Tags For Resource
  x-api-slug: amazon-elasticache-api
  description: Lists all cost allocation tags currently on the named resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: ://///?Action=ListTagsForResource
  tags: Resource Tags
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elasticache/master/_listings/aws-elasticache/actionlisttagsforresource-get-openapi.md
- name: Amazon ElastiCache API Modify Cache Cluster
  x-api-slug: amazon-elasticache-api
  description: Modifies the settings for a cache cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: ://///?Action=ModifyCacheCluster
  tags: Cache Clusters
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elasticache/master/_listings/aws-elasticache/actionmodifycachecluster-get-openapi.md
- name: Amazon ElastiCache API Modify Cache Parameter Group
  x-api-slug: amazon-elasticache-api
  description: |-
    Modifies the parameters of a cache
                parameter group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: ://///?Action=ModifyCacheParameterGroup
  tags: Cache Parameter Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elasticache/master/_listings/aws-elasticache/actionmodifycacheparametergroup-get-openapi.md
- name: Amazon ElastiCache API Modify Cache Subnet Group
  x-api-slug: amazon-elasticache-api
  description: Modifies an existing cache subnet group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: ://///?Action=ModifyCacheSubnetGroup
  tags: Cache Subnet Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elasticache/master/_listings/aws-elasticache/actionmodifycachesubnetgroup-get-openapi.md
- name: Amazon ElastiCache API Modify Replication Group
  x-api-slug: amazon-elasticache-api
  description: Modifies the settings for a replication group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: ://///?Action=ModifyReplicationGroup
  tags: Replication Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elasticache/master/_listings/aws-elasticache/actionmodifyreplicationgroup-get-openapi.md
- name: Amazon ElastiCache API Purchase Reserved Cache Nodes Offering
  x-api-slug: amazon-elasticache-api
  description: |-
    Allows you to purchase a reserved
                cache node offering.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: ://///?Action=PurchaseReservedCacheNodesOffering
  tags: Reserved Cache Nodes
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elasticache/master/_listings/aws-elasticache/actionpurchasereservedcachenodesoffering-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elasticache/master/_listings/aws-elasticache/actionpurchasereservedcachenodesoffering-get-openapi.md
- name: Amazon ElastiCache API Reboot Cache Cluster
  x-api-slug: amazon-elasticache-api
  description: |-
    Reboots some, or all, of the cache nodes
                within a provisioned cache cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: ://///?Action=RebootCacheCluster
  tags: Cache Clusters
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elasticache/master/_listings/aws-elasticache/actionrebootcachecluster-get-openapi.md
- name: Amazon ElastiCache API Remove Tags From Resource
  x-api-slug: amazon-elasticache-api
  description: "Removes the tags identified by the TagKeys \n            list from
    the named resource."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: ://///?Action=RemoveTagsFromResource
  tags: Resource Tags
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elasticache/master/_listings/aws-elasticache/actionremovetagsfromresource-get-openapi.md
- name: Amazon ElastiCache API Reset Cache Parameter Group
  x-api-slug: amazon-elasticache-api
  description: |-
    Modifies the parameters of a cache
                parameter group to the engine or system default value.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: ://///?Action=ResetCacheParameterGroup
  tags: Cache Parameter Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elasticache/master/_listings/aws-elasticache/actionresetcacheparametergroup-get-openapi.md
- name: Amazon ElastiCache API Revoke Cache Security Group Ingress
  x-api-slug: amazon-elasticache-api
  description: |-
    Revokes ingress from a cache
                security group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: ://///?Action=RevokeCacheSecurityGroupIngress
  tags: Cache Security Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elasticache/master/_listings/aws-elasticache/actionrevokecachesecuritygroupingress-get-openapi.md
- name: Amazon ElastiCache API
  x-api-slug: amazon-elasticache-api
  description: Amazon ElastiCache is a web service that makes it easy to deploy, operate,
    and scale an in-memory data store or cache in the cloud. The service improves
    the performance of web applications by allowing you to retrieve information from
    fast, managed, in-memory data stores, instead of relying entirely on slower disk-based
    databases. Amazon ElastiCache automatically detects and replaces failed nodes,
    reducing the overhead associated with self-managed infrastructures and provides
    a resilient system that mitigates the risk of overloaded databases, which slow
    website and application load times. Through integration with Amazon CloudWatch,
    Amazon ElastiCache provides enhanced visibility into key performance metrics associated
    with your Redis or Memcached nodes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: AWS ElastiCache
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elasticache/master/_listings/aws-elasticache/openapi.md
x-common:
- type: x-documentation
  url: http://docs.aws.amazon.com/AmazonElastiCache/latest/APIReference/Welcome.html
- type: x-faq
  url: https://aws.amazon.com/elasticache/faqs/
- type: x-getting-started
  url: https://aws.amazon.com/elasticache/getting-started/
- type: x-pricing
  url: https://aws.amazon.com/elasticache/pricing/
- type: x-resources
  url: https://aws.amazon.com/elasticache/developer-resources/
- type: x-testimonials
  url: https://aws.amazon.com/elasticache/testimonials/
- type: x-website
  url: https://aws.amazon.com/elasticache/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---