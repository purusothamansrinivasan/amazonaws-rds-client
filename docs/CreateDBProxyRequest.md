

# CreateDBProxyRequest


## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**dbProxyName** | **String** | The identifier for the proxy. This name must be unique for all proxies owned by your Amazon Web Services account in the specified Amazon Web Services Region. An identifier must begin with a letter and must contain only ASCII letters, digits, and hyphens; it can&#39;t end with a hyphen or contain two consecutive hyphens. |  |
|**engineFamily** | **EngineFamily** | The kinds of databases that the proxy can connect to. This value determines which database network protocol the proxy recognizes when it interprets network traffic to and from the database. For Aurora MySQL, RDS for MariaDB, and RDS for MySQL databases, specify &lt;code&gt;MYSQL&lt;/code&gt;. For Aurora PostgreSQL and RDS for PostgreSQL databases, specify &lt;code&gt;POSTGRESQL&lt;/code&gt;. For RDS for Microsoft SQL Server, specify &lt;code&gt;SQLSERVER&lt;/code&gt;. |  |
|**auth** | [**List&lt;UserAuthConfig&gt;**](UserAuthConfig.md) | The authorization mechanism that the proxy uses. |  |
|**roleArn** | **String** | The Amazon Resource Name (ARN) of the IAM role that the proxy uses to access secrets in Amazon Web Services Secrets Manager. |  |
|**vpcSubnetIds** | **List&lt;String&gt;** | One or more VPC subnet IDs to associate with the new proxy. |  |
|**vpcSecurityGroupIds** | **List&lt;String&gt;** | One or more VPC security group IDs to associate with the new proxy. |  [optional] |
|**requireTLS** | **Boolean** | A Boolean parameter that specifies whether Transport Layer Security (TLS) encryption is required for connections to the proxy. By enabling this setting, you can enforce encrypted TLS connections to the proxy. |  [optional] |
|**idleClientTimeout** | **Integer** | The number of seconds that a connection to the proxy can be inactive before the proxy disconnects it. You can set this value higher or lower than the connection timeout limit for the associated database. |  [optional] |
|**debugLogging** | **Boolean** | Whether the proxy includes detailed information about SQL statements in its logs. This information helps you to debug issues involving SQL behavior or the performance and scalability of the proxy connections. The debug information includes the text of SQL statements that you submit through the proxy. Thus, only enable this setting when needed for debugging, and only when you have security measures in place to safeguard any sensitive information that appears in the logs. |  [optional] |
|**tags** | [**List&lt;Tag&gt;**](Tag.md) | An optional set of key-value pairs to associate arbitrary data of your choosing with the proxy. |  [optional] |



