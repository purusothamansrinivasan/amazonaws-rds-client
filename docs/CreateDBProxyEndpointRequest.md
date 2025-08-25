

# CreateDBProxyEndpointRequest


## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**dbProxyName** | **String** | The name of the DB proxy associated with the DB proxy endpoint that you create. |  |
|**dbProxyEndpointName** | **String** | The name of the DB proxy endpoint to create. |  |
|**vpcSubnetIds** | **List&lt;String&gt;** | The VPC subnet IDs for the DB proxy endpoint that you create. You can specify a different set of subnet IDs than for the original DB proxy. |  |
|**vpcSecurityGroupIds** | **List&lt;String&gt;** | The VPC security group IDs for the DB proxy endpoint that you create. You can specify a different set of security group IDs than for the original DB proxy. The default is the default security group for the VPC. |  [optional] |
|**targetRole** | **DBProxyEndpointTargetRole** | A value that indicates whether the DB proxy endpoint can be used for read/write or read-only operations. The default is &lt;code&gt;READ_WRITE&lt;/code&gt;. The only role that proxies for RDS for Microsoft SQL Server support is &lt;code&gt;READ_WRITE&lt;/code&gt;. |  [optional] |
|**tags** | [**List&lt;Tag&gt;**](Tag.md) | A list of tags. For more information, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/USER_Tagging.html\&quot;&gt;Tagging Amazon RDS Resources&lt;/a&gt; in the &lt;i&gt;Amazon RDS User Guide.&lt;/i&gt;  |  [optional] |



