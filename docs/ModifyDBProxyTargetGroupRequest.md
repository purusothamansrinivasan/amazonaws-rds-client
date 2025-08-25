

# ModifyDBProxyTargetGroupRequest


## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**targetGroupName** | **String** | The name of the target group to modify. |  |
|**dbProxyName** | **String** | The name of the proxy. |  |
|**connectionPoolConfig** | [**ConnectionPoolConfiguration**](ConnectionPoolConfiguration.md) | The settings that determine the size and behavior of the connection pool for the target group. |  [optional] |
|**newName** | **String** | The new name for the modified &lt;code&gt;DBProxyTarget&lt;/code&gt;. An identifier must begin with a letter and must contain only ASCII letters, digits, and hyphens; it can&#39;t end with a hyphen or contain two consecutive hyphens. |  [optional] |



