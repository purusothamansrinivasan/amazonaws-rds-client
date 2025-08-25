

# DBSubnetGroup

<p>Contains the details of an Amazon RDS DB subnet group.</p> <p>This data type is used as a response element in the <code>DescribeDBSubnetGroups</code> action.</p>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**dbSubnetGroupName** | **String** | The name of the DB subnet group. |  [optional] |
|**dbSubnetGroupDescription** | **String** | Provides the description of the DB subnet group. |  [optional] |
|**vpcId** | **String** | Provides the VpcId of the DB subnet group. |  [optional] |
|**subnetGroupStatus** | **String** | Provides the status of the DB subnet group. |  [optional] |
|**subnets** | [**List&lt;Subnet&gt;**](Subnet.md) | Contains a list of &lt;code&gt;Subnet&lt;/code&gt; elements. |  [optional] |
|**dbSubnetGroupArn** | **String** | The Amazon Resource Name (ARN) for the DB subnet group. |  [optional] |
|**supportedNetworkTypes** | **List&lt;String&gt;** | &lt;p&gt;The network type of the DB subnet group.&lt;/p&gt; &lt;p&gt;Valid values:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;IPV4&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;DUAL&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; &lt;p&gt;A &lt;code&gt;DBSubnetGroup&lt;/code&gt; can support only the IPv4 protocol or the IPv4 and the IPv6 protocols (&lt;code&gt;DUAL&lt;/code&gt;).&lt;/p&gt; &lt;p&gt;For more information, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/USER_VPC.WorkingWithRDSInstanceinaVPC.html\&quot;&gt; Working with a DB instance in a VPC&lt;/a&gt; in the &lt;i&gt;Amazon RDS User Guide.&lt;/i&gt; &lt;/p&gt; |  [optional] |



