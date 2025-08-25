

# RevokeDBSecurityGroupIngressMessage

<p/>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**dbSecurityGroupName** | **String** | The name of the DB security group to revoke ingress from. |  |
|**CIDRIP** | **String** | The IP range to revoke access from. Must be a valid CIDR range. If &lt;code&gt;CIDRIP&lt;/code&gt; is specified, &lt;code&gt;EC2SecurityGroupName&lt;/code&gt;, &lt;code&gt;EC2SecurityGroupId&lt;/code&gt; and &lt;code&gt;EC2SecurityGroupOwnerId&lt;/code&gt; can&#39;t be provided. |  [optional] |
|**ec2SecurityGroupName** | **String** | The name of the EC2 security group to revoke access from. For VPC DB security groups, &lt;code&gt;EC2SecurityGroupId&lt;/code&gt; must be provided. Otherwise, EC2SecurityGroupOwnerId and either &lt;code&gt;EC2SecurityGroupName&lt;/code&gt; or &lt;code&gt;EC2SecurityGroupId&lt;/code&gt; must be provided. |  [optional] |
|**ec2SecurityGroupId** | **String** | The id of the EC2 security group to revoke access from. For VPC DB security groups, &lt;code&gt;EC2SecurityGroupId&lt;/code&gt; must be provided. Otherwise, EC2SecurityGroupOwnerId and either &lt;code&gt;EC2SecurityGroupName&lt;/code&gt; or &lt;code&gt;EC2SecurityGroupId&lt;/code&gt; must be provided. |  [optional] |
|**ec2SecurityGroupOwnerId** | **String** | The Amazon Web Services account number of the owner of the EC2 security group specified in the &lt;code&gt;EC2SecurityGroupName&lt;/code&gt; parameter. The Amazon Web Services access key ID isn&#39;t an acceptable value. For VPC DB security groups, &lt;code&gt;EC2SecurityGroupId&lt;/code&gt; must be provided. Otherwise, EC2SecurityGroupOwnerId and either &lt;code&gt;EC2SecurityGroupName&lt;/code&gt; or &lt;code&gt;EC2SecurityGroupId&lt;/code&gt; must be provided. |  [optional] |



