

# CreateDBClusterSnapshotMessage

<p/>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**dbClusterSnapshotIdentifier** | **String** | &lt;p&gt;The identifier of the DB cluster snapshot. This parameter is stored as a lowercase string.&lt;/p&gt; &lt;p&gt;Constraints:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt;Must contain from 1 to 63 letters, numbers, or hyphens.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt;First character must be a letter.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt;Can&#39;t end with a hyphen or contain two consecutive hyphens.&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; &lt;p&gt;Example: &lt;code&gt;my-cluster1-snapshot1&lt;/code&gt; &lt;/p&gt; |  |
|**dbClusterIdentifier** | **String** | &lt;p&gt;The identifier of the DB cluster to create a snapshot for. This parameter isn&#39;t case-sensitive.&lt;/p&gt; &lt;p&gt;Constraints:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt;Must match the identifier of an existing DBCluster.&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; &lt;p&gt;Example: &lt;code&gt;my-cluster1&lt;/code&gt; &lt;/p&gt; |  |
|**tags** | [**List&lt;Tag&gt;**](Tag.md) | The tags to be assigned to the DB cluster snapshot. |  [optional] |



