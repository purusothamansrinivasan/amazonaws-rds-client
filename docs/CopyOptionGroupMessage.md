

# CopyOptionGroupMessage

<p/>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**sourceOptionGroupIdentifier** | **String** | &lt;p&gt;The identifier for the source option group.&lt;/p&gt; &lt;p&gt;Constraints:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt;Must specify a valid option group.&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; |  |
|**targetOptionGroupIdentifier** | **String** | &lt;p&gt;The identifier for the copied option group.&lt;/p&gt; &lt;p&gt;Constraints:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt;Can&#39;t be null, empty, or blank&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt;Must contain from 1 to 255 letters, numbers, or hyphens&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt;First character must be a letter&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt;Can&#39;t end with a hyphen or contain two consecutive hyphens&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; &lt;p&gt;Example: &lt;code&gt;my-option-group&lt;/code&gt; &lt;/p&gt; |  |
|**targetOptionGroupDescription** | **String** | The description for the copied option group. |  |
|**tags** | [**List&lt;Tag&gt;**](Tag.md) | A list of tags. For more information, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/USER_Tagging.html\&quot;&gt;Tagging Amazon RDS Resources&lt;/a&gt; in the &lt;i&gt;Amazon RDS User Guide.&lt;/i&gt;  |  [optional] |



