

# EC2SecurityGroup

<p>This data type is used as a response element in the following actions:</p> <ul> <li> <p> <code>AuthorizeDBSecurityGroupIngress</code> </p> </li> <li> <p> <code>DescribeDBSecurityGroups</code> </p> </li> <li> <p> <code>RevokeDBSecurityGroupIngress</code> </p> </li> </ul>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**status** | **String** | Provides the status of the EC2 security group. Status can be \&quot;authorizing\&quot;, \&quot;authorized\&quot;, \&quot;revoking\&quot;, and \&quot;revoked\&quot;. |  [optional] |
|**ec2SecurityGroupName** | **String** | Specifies the name of the EC2 security group. |  [optional] |
|**ec2SecurityGroupId** | **String** | Specifies the id of the EC2 security group. |  [optional] |
|**ec2SecurityGroupOwnerId** | **String** | Specifies the Amazon Web Services ID of the owner of the EC2 security group specified in the &lt;code&gt;EC2SecurityGroupName&lt;/code&gt; field. |  [optional] |



