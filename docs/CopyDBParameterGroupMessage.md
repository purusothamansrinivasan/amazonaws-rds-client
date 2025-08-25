

# CopyDBParameterGroupMessage

<p/>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**sourceDBParameterGroupIdentifier** | **String** | &lt;p&gt;The identifier or ARN for the source DB parameter group. For information about creating an ARN, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/USER_Tagging.ARN.html#USER_Tagging.ARN.Constructing\&quot;&gt; Constructing an ARN for Amazon RDS&lt;/a&gt; in the &lt;i&gt;Amazon RDS User Guide&lt;/i&gt;.&lt;/p&gt; &lt;p&gt;Constraints:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt;Must specify a valid DB parameter group.&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; |  |
|**targetDBParameterGroupIdentifier** | **String** | &lt;p&gt;The identifier for the copied DB parameter group.&lt;/p&gt; &lt;p&gt;Constraints:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt;Can&#39;t be null, empty, or blank&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt;Must contain from 1 to 255 letters, numbers, or hyphens&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt;First character must be a letter&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt;Can&#39;t end with a hyphen or contain two consecutive hyphens&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; &lt;p&gt;Example: &lt;code&gt;my-db-parameter-group&lt;/code&gt; &lt;/p&gt; |  |
|**targetDBParameterGroupDescription** | **String** | A description for the copied DB parameter group. |  |
|**tags** | [**List&lt;Tag&gt;**](Tag.md) | A list of tags. For more information, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/USER_Tagging.html\&quot;&gt;Tagging Amazon RDS Resources&lt;/a&gt; in the &lt;i&gt;Amazon RDS User Guide.&lt;/i&gt;  |  [optional] |



