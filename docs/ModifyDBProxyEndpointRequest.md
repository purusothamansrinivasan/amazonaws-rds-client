

# ModifyDBProxyEndpointRequest


## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**dbProxyEndpointName** | **String** | The name of the DB proxy sociated with the DB proxy endpoint that you want to modify. |  |
|**newDBProxyEndpointName** | **String** | The new identifier for the &lt;code&gt;DBProxyEndpoint&lt;/code&gt;. An identifier must begin with a letter and must contain only ASCII letters, digits, and hyphens; it can&#39;t end with a hyphen or contain two consecutive hyphens. |  [optional] |
|**vpcSecurityGroupIds** | **List&lt;String&gt;** | The VPC security group IDs for the DB proxy endpoint. When the DB proxy endpoint uses a different VPC than the original proxy, you also specify a different set of security group IDs than for the original proxy. |  [optional] |



