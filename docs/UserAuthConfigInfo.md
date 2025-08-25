

# UserAuthConfigInfo

Returns the details of authentication used by a proxy to log in as a specific database user.

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**description** | **String** | A user-specified description about the authentication used by a proxy to log in as a specific database user. |  [optional] |
|**userName** | **String** | The name of the database user to which the proxy connects. |  [optional] |
|**authScheme** | **AuthScheme** | The type of authentication that the proxy uses for connections from the proxy to the underlying database. |  [optional] |
|**secretArn** | **String** | The Amazon Resource Name (ARN) representing the secret that the proxy uses to authenticate to the RDS DB instance or Aurora DB cluster. These secrets are stored within Amazon Secrets Manager. |  [optional] |
|**iaMAuth** | **IAMAuthMode** | Whether to require or disallow Amazon Web Services Identity and Access Management (IAM) authentication for connections to the proxy. The &lt;code&gt;ENABLED&lt;/code&gt; value is valid only for proxies with RDS for Microsoft SQL Server. |  [optional] |
|**clientPasswordAuthType** | **ClientPasswordAuthType** | The type of authentication the proxy uses for connections from clients. |  [optional] |



