

# FailoverDBClusterMessage

<p/>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**dbClusterIdentifier** | **String** | &lt;p&gt;A DB cluster identifier to force a failover for. This parameter isn&#39;t case-sensitive.&lt;/p&gt; &lt;p&gt;Constraints:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt;Must match the identifier of an existing DBCluster.&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; |  |
|**targetDBInstanceIdentifier** | **String** | &lt;p&gt;The name of the DB instance to promote to the primary DB instance.&lt;/p&gt; &lt;p&gt;Specify the DB instance identifier for an Aurora Replica or a Multi-AZ readable standby in the DB cluster, for example &lt;code&gt;mydbcluster-replica1&lt;/code&gt;.&lt;/p&gt; &lt;p&gt;This setting isn&#39;t supported for RDS for MySQL Multi-AZ DB clusters.&lt;/p&gt; |  [optional] |



