

# FailoverState

Contains the state of scheduled or in-process failover operations on an Aurora global database (<a>GlobalCluster</a>). This Data type is empty unless a failover operation is scheduled or is currently underway on the Aurora global database.

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**status** | **FailoverStatus** | &lt;p&gt;The current status of the Aurora global database (&lt;a&gt;GlobalCluster&lt;/a&gt;). Possible values are as follows:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt;pending &amp;#x96; A request to fail over the Aurora global database (&lt;a&gt;GlobalCluster&lt;/a&gt;) has been received by the service. The &lt;code&gt;GlobalCluster&lt;/code&gt;&#39;s primary DB cluster and the specified secondary DB cluster are being verified before the failover process can start.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt;failing-over &amp;#x96; This status covers the range of Aurora internal operations that take place during the failover process, such as demoting the primary Aurora DB cluster, promoting the secondary Aurora DB, and synchronizing replicas.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt;cancelling &amp;#x96; The request to fail over the Aurora global database (&lt;a&gt;GlobalCluster&lt;/a&gt;) was cancelled and the primary Aurora DB cluster and the selected secondary Aurora DB cluster are returning to their previous states.&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; |  [optional] |
|**fromDbClusterArn** | **String** | The Amazon Resource Name (ARN) of the Aurora DB cluster that is currently being demoted, and which is associated with this state. |  [optional] |
|**toDbClusterArn** | **String** | The Amazon Resource Name (ARN) of the Aurora DB cluster that is currently being promoted, and which is associated with this state. |  [optional] |



