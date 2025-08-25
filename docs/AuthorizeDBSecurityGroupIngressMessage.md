

# AuthorizeDBSecurityGroupIngressMessage

<p/>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**dbSecurityGroupName** | **String** | The name of the DB security group to add authorization to. |  |
|**CIDRIP** | **String** | The IP range to authorize. |  [optional] |
|**ec2SecurityGroupName** | **String** | Name of the EC2 security group to authorize. For VPC DB security groups, &lt;code&gt;EC2SecurityGroupId&lt;/code&gt; must be provided. Otherwise, &lt;code&gt;EC2SecurityGroupOwnerId&lt;/code&gt; and either &lt;code&gt;EC2SecurityGroupName&lt;/code&gt; or &lt;code&gt;EC2SecurityGroupId&lt;/code&gt; must be provided. |  [optional] |
|**ec2SecurityGroupId** | **String** | Id of the EC2 security group to authorize. For VPC DB security groups, &lt;code&gt;EC2SecurityGroupId&lt;/code&gt; must be provided. Otherwise, &lt;code&gt;EC2SecurityGroupOwnerId&lt;/code&gt; and either &lt;code&gt;EC2SecurityGroupName&lt;/code&gt; or &lt;code&gt;EC2SecurityGroupId&lt;/code&gt; must be provided. |  [optional] |
|**ec2SecurityGroupOwnerId** | **String** | Amazon Web Services account number of the owner of the EC2 security group specified in the &lt;code&gt;EC2SecurityGroupName&lt;/code&gt; parameter. The Amazon Web Services access key ID isn&#39;t an acceptable value. For VPC DB security groups, &lt;code&gt;EC2SecurityGroupId&lt;/code&gt; must be provided. Otherwise, &lt;code&gt;EC2SecurityGroupOwnerId&lt;/code&gt; and either &lt;code&gt;EC2SecurityGroupName&lt;/code&gt; or &lt;code&gt;EC2SecurityGroupId&lt;/code&gt; must be provided. |  [optional] |



