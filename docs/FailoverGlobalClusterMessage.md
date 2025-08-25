

# FailoverGlobalClusterMessage


## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**globalClusterIdentifier** | **String** | &lt;p&gt;Identifier of the Aurora global database (&lt;a&gt;GlobalCluster&lt;/a&gt;) that should be failed over. The identifier is the unique key assigned by the user when the Aurora global database was created. In other words, it&#39;s the name of the Aurora global database that you want to fail over.&lt;/p&gt; &lt;p&gt;Constraints:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt;Must match the identifier of an existing &lt;a&gt;GlobalCluster&lt;/a&gt; (Aurora global database).&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; |  |
|**targetDbClusterIdentifier** | **String** | Identifier of the secondary Aurora DB cluster that you want to promote to primary for the Aurora global database (&lt;a&gt;GlobalCluster&lt;/a&gt;.) Use the Amazon Resource Name (ARN) for the identifier so that Aurora can locate the cluster in its Amazon Web Services Region. |  |



