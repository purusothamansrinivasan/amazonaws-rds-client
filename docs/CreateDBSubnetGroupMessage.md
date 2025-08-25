

# CreateDBSubnetGroupMessage

<p/>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**dbSubnetGroupName** | **String** | &lt;p&gt;The name for the DB subnet group. This value is stored as a lowercase string.&lt;/p&gt; &lt;p&gt;Constraints:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt;Must contain no more than 255 letters, numbers, periods, underscores, spaces, or hyphens.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt;Must not be default.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt;First character must be a letter.&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; &lt;p&gt;Example: &lt;code&gt;mydbsubnetgroup&lt;/code&gt; &lt;/p&gt; |  |
|**dbSubnetGroupDescription** | **String** | The description for the DB subnet group. |  |
|**subnetIds** | **List&lt;String&gt;** | The EC2 Subnet IDs for the DB subnet group. |  |
|**tags** | [**List&lt;Tag&gt;**](Tag.md) | Tags to assign to the DB subnet group. |  [optional] |



