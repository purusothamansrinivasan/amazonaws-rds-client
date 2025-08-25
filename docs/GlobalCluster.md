

# GlobalCluster

A data type representing an Aurora global database.

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**globalClusterIdentifier** | **String** | Contains a user-supplied global database cluster identifier. This identifier is the unique key that identifies a global database cluster. |  [optional] |
|**globalClusterResourceId** | **String** | The Amazon Web Services Region-unique, immutable identifier for the global database cluster. This identifier is found in Amazon Web Services CloudTrail log entries whenever the Amazon Web Services KMS key for the DB cluster is accessed. |  [optional] |
|**globalClusterArn** | **String** | The Amazon Resource Name (ARN) for the global database cluster. |  [optional] |
|**status** | **String** | Specifies the current state of this global database cluster. |  [optional] |
|**engine** | **String** | The Aurora database engine used by the global database cluster. |  [optional] |
|**engineVersion** | **String** | Indicates the database engine version. |  [optional] |
|**databaseName** | **String** | The default database name within the new global database cluster. |  [optional] |
|**storageEncrypted** | **Boolean** | The storage encryption setting for the global database cluster. |  [optional] |
|**deletionProtection** | **Boolean** | The deletion protection setting for the new global database cluster. |  [optional] |
|**globalClusterMembers** | [**List&lt;GlobalClusterMember&gt;**](GlobalClusterMember.md) | The list of primary and secondary clusters within the global database cluster. |  [optional] |
|**failoverState** | [**FailoverState**](FailoverState.md) | A data object containing all properties for the current state of an in-process or pending failover process for this Aurora global database. This object is empty unless the &lt;a&gt;FailoverGlobalCluster&lt;/a&gt; API operation has been called on this Aurora global database (&lt;a&gt;GlobalCluster&lt;/a&gt;). |  [optional] |



