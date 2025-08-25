

# ClusterPendingModifiedValues

This data type is used as a response element in the <code>ModifyDBCluster</code> operation and contains changes that will be applied during the next maintenance window.

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**pendingCloudwatchLogsExports** | [**PendingCloudwatchLogsExports**](PendingCloudwatchLogsExports.md) |  |  [optional] |
|**dbClusterIdentifier** | **String** | The DBClusterIdentifier value for the DB cluster. |  [optional] |
|**masterUserPassword** | **String** | The master credentials for the DB cluster. |  [optional] |
|**iaMDatabaseAuthenticationEnabled** | **Boolean** | A value that indicates whether mapping of Amazon Web Services Identity and Access Management (IAM) accounts to database accounts is enabled. |  [optional] |
|**engineVersion** | **String** | The database engine version. |  [optional] |
|**backupRetentionPeriod** | **Integer** | The number of days for which automatic DB snapshots are retained. |  [optional] |
|**allocatedStorage** | **Integer** | The allocated storage size in gibibytes (GiB) for all database engines except Amazon Aurora. For Aurora, &lt;code&gt;AllocatedStorage&lt;/code&gt; always returns 1, because Aurora DB cluster storage size isn&#39;t fixed, but instead automatically adjusts as needed. |  [optional] |
|**iops** | **Integer** | The Provisioned IOPS (I/O operations per second) value. This setting is only for non-Aurora Multi-AZ DB clusters. |  [optional] |
|**storageType** | **String** | The storage type for the DB cluster. |  [optional] |



