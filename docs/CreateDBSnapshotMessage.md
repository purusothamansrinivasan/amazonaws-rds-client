

# CreateDBSnapshotMessage

<p/>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**dbSnapshotIdentifier** | **String** | &lt;p&gt;The identifier for the DB snapshot.&lt;/p&gt; &lt;p&gt;Constraints:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt;Can&#39;t be null, empty, or blank&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt;Must contain from 1 to 255 letters, numbers, or hyphens&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt;First character must be a letter&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt;Can&#39;t end with a hyphen or contain two consecutive hyphens&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; &lt;p&gt;Example: &lt;code&gt;my-snapshot-id&lt;/code&gt; &lt;/p&gt; |  |
|**dbInstanceIdentifier** | **String** | &lt;p&gt;The identifier of the DB instance that you want to create the snapshot of.&lt;/p&gt; &lt;p&gt;Constraints:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt;Must match the identifier of an existing DBInstance.&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; |  |
|**tags** | [**List&lt;Tag&gt;**](Tag.md) | A list of tags. For more information, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/USER_Tagging.html\&quot;&gt;Tagging Amazon RDS Resources&lt;/a&gt; in the &lt;i&gt;Amazon RDS User Guide.&lt;/i&gt;  |  [optional] |



