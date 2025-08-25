

# Subnet

This data type is used as a response element for the <code>DescribeDBSubnetGroups</code> operation.

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**subnetIdentifier** | **String** | The identifier of the subnet. |  [optional] |
|**subnetAvailabilityZone** | [**AvailabilityZone**](AvailabilityZone.md) |  |  [optional] |
|**subnetOutpost** | [**Outpost**](Outpost.md) | &lt;p&gt;If the subnet is associated with an Outpost, this value specifies the Outpost.&lt;/p&gt; &lt;p&gt;For more information about RDS on Outposts, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/rds-on-outposts.html\&quot;&gt;Amazon RDS on Amazon Web Services Outposts&lt;/a&gt; in the &lt;i&gt;Amazon RDS User Guide.&lt;/i&gt; &lt;/p&gt; |  [optional] |
|**subnetStatus** | **String** | The status of the subnet. |  [optional] |



