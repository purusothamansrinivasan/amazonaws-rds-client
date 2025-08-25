

# CopyDBClusterParameterGroupMessage


## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**sourceDBClusterParameterGroupIdentifier** | **String** | &lt;p&gt;The identifier or Amazon Resource Name (ARN) for the source DB cluster parameter group. For information about creating an ARN, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/AmazonRDS/latest/AuroraUserGuide/USER_Tagging.ARN.html#USER_Tagging.ARN.Constructing\&quot;&gt; Constructing an ARN for Amazon RDS&lt;/a&gt; in the &lt;i&gt;Amazon Aurora User Guide&lt;/i&gt;.&lt;/p&gt; &lt;p&gt;Constraints:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt;Must specify a valid DB cluster parameter group.&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; |  |
|**targetDBClusterParameterGroupIdentifier** | **String** | &lt;p&gt;The identifier for the copied DB cluster parameter group.&lt;/p&gt; &lt;p&gt;Constraints:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt;Can&#39;t be null, empty, or blank&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt;Must contain from 1 to 255 letters, numbers, or hyphens&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt;First character must be a letter&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt;Can&#39;t end with a hyphen or contain two consecutive hyphens&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; &lt;p&gt;Example: &lt;code&gt;my-cluster-param-group1&lt;/code&gt; &lt;/p&gt; |  |
|**targetDBClusterParameterGroupDescription** | **String** | A description for the copied DB cluster parameter group. |  |
|**tags** | [**List&lt;Tag&gt;**](Tag.md) | A list of tags. For more information, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/USER_Tagging.html\&quot;&gt;Tagging Amazon RDS Resources&lt;/a&gt; in the &lt;i&gt;Amazon RDS User Guide.&lt;/i&gt;  |  [optional] |



