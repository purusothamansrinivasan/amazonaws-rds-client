

# ModifyDBProxyRequest


## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**dbProxyName** | **String** | The identifier for the &lt;code&gt;DBProxy&lt;/code&gt; to modify. |  |
|**newDBProxyName** | **String** | The new identifier for the &lt;code&gt;DBProxy&lt;/code&gt;. An identifier must begin with a letter and must contain only ASCII letters, digits, and hyphens; it can&#39;t end with a hyphen or contain two consecutive hyphens. |  [optional] |
|**auth** | [**List&lt;UserAuthConfig&gt;**](UserAuthConfig.md) | The new authentication settings for the &lt;code&gt;DBProxy&lt;/code&gt;. |  [optional] |
|**requireTLS** | **Boolean** | Whether Transport Layer Security (TLS) encryption is required for connections to the proxy. By enabling this setting, you can enforce encrypted TLS connections to the proxy, even if the associated database doesn&#39;t use TLS. |  [optional] |
|**idleClientTimeout** | **Integer** | The number of seconds that a connection to the proxy can be inactive before the proxy disconnects it. You can set this value higher or lower than the connection timeout limit for the associated database. |  [optional] |
|**debugLogging** | **Boolean** | Whether the proxy includes detailed information about SQL statements in its logs. This information helps you to debug issues involving SQL behavior or the performance and scalability of the proxy connections. The debug information includes the text of SQL statements that you submit through the proxy. Thus, only enable this setting when needed for debugging, and only when you have security measures in place to safeguard any sensitive information that appears in the logs. |  [optional] |
|**roleArn** | **String** | The Amazon Resource Name (ARN) of the IAM role that the proxy uses to access secrets in Amazon Web Services Secrets Manager. |  [optional] |
|**securityGroups** | **List&lt;String&gt;** | The new list of security groups for the &lt;code&gt;DBProxy&lt;/code&gt;. |  [optional] |



