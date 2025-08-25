

# CreateDBSecurityGroupMessage

<p/>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**dbSecurityGroupName** | **String** | &lt;p&gt;The name for the DB security group. This value is stored as a lowercase string.&lt;/p&gt; &lt;p&gt;Constraints:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt;Must be 1 to 255 letters, numbers, or hyphens.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt;First character must be a letter&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt;Can&#39;t end with a hyphen or contain two consecutive hyphens&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt;Must not be \&quot;Default\&quot;&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; &lt;p&gt;Example: &lt;code&gt;mysecuritygroup&lt;/code&gt; &lt;/p&gt; |  |
|**dbSecurityGroupDescription** | **String** | The description for the DB security group. |  |
|**tags** | [**List&lt;Tag&gt;**](Tag.md) | Tags to assign to the DB security group. |  [optional] |



