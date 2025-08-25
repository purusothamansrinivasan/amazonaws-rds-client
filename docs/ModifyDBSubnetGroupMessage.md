

# ModifyDBSubnetGroupMessage

<p/>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**dbSubnetGroupName** | **String** | &lt;p&gt;The name for the DB subnet group. This value is stored as a lowercase string. You can&#39;t modify the default subnet group.&lt;/p&gt; &lt;p&gt;Constraints: Must match the name of an existing DBSubnetGroup. Must not be default.&lt;/p&gt; &lt;p&gt;Example: &lt;code&gt;mydbsubnetgroup&lt;/code&gt; &lt;/p&gt; |  |
|**dbSubnetGroupDescription** | **String** | The description for the DB subnet group. |  [optional] |
|**subnetIds** | **List&lt;String&gt;** | The EC2 subnet IDs for the DB subnet group. |  |



