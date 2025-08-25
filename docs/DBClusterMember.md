

# DBClusterMember

Contains information about an instance that is part of a DB cluster.

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**dbInstanceIdentifier** | **String** | Specifies the instance identifier for this member of the DB cluster. |  [optional] |
|**isClusterWriter** | **Boolean** | Value that is &lt;code&gt;true&lt;/code&gt; if the cluster member is the primary instance for the DB cluster and &lt;code&gt;false&lt;/code&gt; otherwise. |  [optional] |
|**dbClusterParameterGroupStatus** | **String** | Specifies the status of the DB cluster parameter group for this member of the DB cluster. |  [optional] |
|**promotionTier** | **Integer** | A value that specifies the order in which an Aurora Replica is promoted to the primary instance after a failure of the existing primary instance. For more information, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/AmazonRDS/latest/AuroraUserGuide/Aurora.Managing.Backups.html#Aurora.Managing.FaultTolerance\&quot;&gt; Fault Tolerance for an Aurora DB Cluster&lt;/a&gt; in the &lt;i&gt;Amazon Aurora User Guide&lt;/i&gt;. |  [optional] |



