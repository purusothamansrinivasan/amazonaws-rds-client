

# AddSourceIdentifierToSubscriptionMessage

<p/>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**subscriptionName** | **String** | The name of the RDS event notification subscription you want to add a source identifier to. |  |
|**sourceIdentifier** | **String** | &lt;p&gt;The identifier of the event source to be added.&lt;/p&gt; &lt;p&gt;Constraints:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt;If the source type is a DB instance, a &lt;code&gt;DBInstanceIdentifier&lt;/code&gt; value must be supplied.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt;If the source type is a DB cluster, a &lt;code&gt;DBClusterIdentifier&lt;/code&gt; value must be supplied.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt;If the source type is a DB parameter group, a &lt;code&gt;DBParameterGroupName&lt;/code&gt; value must be supplied.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt;If the source type is a DB security group, a &lt;code&gt;DBSecurityGroupName&lt;/code&gt; value must be supplied.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt;If the source type is a DB snapshot, a &lt;code&gt;DBSnapshotIdentifier&lt;/code&gt; value must be supplied.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt;If the source type is a DB cluster snapshot, a &lt;code&gt;DBClusterSnapshotIdentifier&lt;/code&gt; value must be supplied.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt;If the source type is an RDS Proxy, a &lt;code&gt;DBProxyName&lt;/code&gt; value must be supplied.&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; |  |



