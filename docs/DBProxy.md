

# DBProxy

<p>The data structure representing a proxy managed by the RDS Proxy.</p> <p>This data type is used as a response element in the <code>DescribeDBProxies</code> action.</p>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**dbProxyName** | **String** | The identifier for the proxy. This name must be unique for all proxies owned by your Amazon Web Services account in the specified Amazon Web Services Region. |  [optional] |
|**dbProxyArn** | **String** | The Amazon Resource Name (ARN) for the proxy. |  [optional] |
|**status** | **DBProxyStatus** | The current status of this proxy. A status of &lt;code&gt;available&lt;/code&gt; means the proxy is ready to handle requests. Other values indicate that you must wait for the proxy to be ready, or take some action to resolve an issue. |  [optional] |
|**engineFamily** | **String** | The kinds of databases that the proxy can connect to. This value determines which database network protocol the proxy recognizes when it interprets network traffic to and from the database. &lt;code&gt;MYSQL&lt;/code&gt; supports Aurora MySQL, RDS for MariaDB, and RDS for MySQL databases. &lt;code&gt;POSTGRESQL&lt;/code&gt; supports Aurora PostgreSQL and RDS for PostgreSQL databases. &lt;code&gt;SQLSERVER&lt;/code&gt; supports RDS for Microsoft SQL Server databases. |  [optional] |
|**vpcId** | **String** | Provides the VPC ID of the DB proxy. |  [optional] |
|**vpcSecurityGroupIds** | **List&lt;String&gt;** | Provides a list of VPC security groups that the proxy belongs to. |  [optional] |
|**vpcSubnetIds** | **List&lt;String&gt;** | The EC2 subnet IDs for the proxy. |  [optional] |
|**auth** | [**List&lt;UserAuthConfigInfo&gt;**](UserAuthConfigInfo.md) | One or more data structures specifying the authorization mechanism to connect to the associated RDS DB instance or Aurora DB cluster. |  [optional] |
|**roleArn** | **String** | The Amazon Resource Name (ARN) for the IAM role that the proxy uses to access Amazon Secrets Manager. |  [optional] |
|**endpoint** | **String** | The endpoint that you can use to connect to the DB proxy. You include the endpoint value in the connection string for a database client application. |  [optional] |
|**requireTLS** | **Boolean** | Indicates whether Transport Layer Security (TLS) encryption is required for connections to the proxy. |  [optional] |
|**idleClientTimeout** | **Integer** | &lt;p&gt;The number of seconds a connection to the proxy can have no activity before the proxy drops the client connection. The proxy keeps the underlying database connection open and puts it back into the connection pool for reuse by later connection requests.&lt;/p&gt; &lt;p&gt;Default: 1800 (30 minutes)&lt;/p&gt; &lt;p&gt;Constraints: 1 to 28,800&lt;/p&gt; |  [optional] |
|**debugLogging** | **Boolean** | Whether the proxy includes detailed information about SQL statements in its logs. This information helps you to debug issues involving SQL behavior or the performance and scalability of the proxy connections. The debug information includes the text of SQL statements that you submit through the proxy. Thus, only enable this setting when needed for debugging, and only when you have security measures in place to safeguard any sensitive information that appears in the logs. |  [optional] |
|**createdDate** | **OffsetDateTime** | The date and time when the proxy was first created. |  [optional] |
|**updatedDate** | **OffsetDateTime** | The date and time when the proxy was last updated. |  [optional] |



