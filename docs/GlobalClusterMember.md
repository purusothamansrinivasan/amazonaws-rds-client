

# GlobalClusterMember

A data structure with information about any primary and secondary clusters associated with an Aurora global database.

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**dbClusterArn** | **String** | The Amazon Resource Name (ARN) for each Aurora cluster. |  [optional] |
|**readers** | **List&lt;String&gt;** | The Amazon Resource Name (ARN) for each read-only secondary cluster associated with the Aurora global database. |  [optional] |
|**isWriter** | **Boolean** | Specifies whether the Aurora cluster is the primary cluster (that is, has read-write capability) for the Aurora global database with which it is associated. |  [optional] |
|**globalWriteForwardingStatus** | **WriteForwardingStatus** | Specifies whether a secondary cluster in an Aurora global database has write forwarding enabled, not enabled, or is in the process of enabling it. |  [optional] |



