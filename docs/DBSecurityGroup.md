

# DBSecurityGroup

<p>Contains the details for an Amazon RDS DB security group.</p> <p>This data type is used as a response element in the <code>DescribeDBSecurityGroups</code> action.</p>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**ownerId** | **String** | Provides the Amazon Web Services ID of the owner of a specific DB security group. |  [optional] |
|**dbSecurityGroupName** | **String** | Specifies the name of the DB security group. |  [optional] |
|**dbSecurityGroupDescription** | **String** | Provides the description of the DB security group. |  [optional] |
|**vpcId** | **String** | Provides the VpcId of the DB security group. |  [optional] |
|**ec2SecurityGroups** | [**List&lt;EC2SecurityGroup&gt;**](EC2SecurityGroup.md) | Contains a list of &lt;code&gt;EC2SecurityGroup&lt;/code&gt; elements. |  [optional] |
|**ipRanges** | [**List&lt;IPRange&gt;**](IPRange.md) | Contains a list of &lt;code&gt;IPRange&lt;/code&gt; elements. |  [optional] |
|**dbSecurityGroupArn** | **String** | The Amazon Resource Name (ARN) for the DB security group. |  [optional] |



