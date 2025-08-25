

# DBInstanceStatusInfo

Provides a list of status information for a DB instance.

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**statusType** | **String** | This value is currently \&quot;read replication.\&quot; |  [optional] |
|**normal** | **Boolean** | Boolean value that is true if the instance is operating normally, or false if the instance is in an error state. |  [optional] |
|**status** | **String** | Status of the DB instance. For a StatusType of read replica, the values can be replicating, replication stop point set, replication stop point reached, error, stopped, or terminated. |  [optional] |
|**message** | **String** | Details of the error if there is an error for the instance. If the instance isn&#39;t in an error state, this value is blank. |  [optional] |



