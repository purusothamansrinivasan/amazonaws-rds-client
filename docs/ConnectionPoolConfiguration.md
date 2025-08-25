

# ConnectionPoolConfiguration

Specifies the settings that control the size and behavior of the connection pool associated with a <code>DBProxyTargetGroup</code>.

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**maxConnectionsPercent** | **Integer** | &lt;p&gt;The maximum size of the connection pool for each target in a target group. The value is expressed as a percentage of the &lt;code&gt;max_connections&lt;/code&gt; setting for the RDS DB instance or Aurora DB cluster used by the target group.&lt;/p&gt; &lt;p&gt;If you specify &lt;code&gt;MaxIdleConnectionsPercent&lt;/code&gt;, then you must also include a value for this parameter.&lt;/p&gt; &lt;p&gt;Default: 10 for RDS for Microsoft SQL Server, and 100 for all other engines&lt;/p&gt; &lt;p&gt;Constraints: Must be between 1 and 100.&lt;/p&gt; |  [optional] |
|**maxIdleConnectionsPercent** | **Integer** | &lt;p&gt;Controls how actively the proxy closes idle database connections in the connection pool. The value is expressed as a percentage of the &lt;code&gt;max_connections&lt;/code&gt; setting for the RDS DB instance or Aurora DB cluster used by the target group. With a high value, the proxy leaves a high percentage of idle database connections open. A low value causes the proxy to close more idle connections and return them to the database.&lt;/p&gt; &lt;p&gt;If you specify this parameter, then you must also include a value for &lt;code&gt;MaxConnectionsPercent&lt;/code&gt;.&lt;/p&gt; &lt;p&gt;Default: The default value is half of the value of &lt;code&gt;MaxConnectionsPercent&lt;/code&gt;. For example, if &lt;code&gt;MaxConnectionsPercent&lt;/code&gt; is 80, then the default value of &lt;code&gt;MaxIdleConnectionsPercent&lt;/code&gt; is 40. If the value of &lt;code&gt;MaxConnectionsPercent&lt;/code&gt; isn&#39;t specified, then for SQL Server, &lt;code&gt;MaxIdleConnectionsPercent&lt;/code&gt; is 5, and for all other engines, the default is 50.&lt;/p&gt; &lt;p&gt;Constraints: Must be between 0 and the value of &lt;code&gt;MaxConnectionsPercent&lt;/code&gt;.&lt;/p&gt; |  [optional] |
|**connectionBorrowTimeout** | **Integer** | &lt;p&gt;The number of seconds for a proxy to wait for a connection to become available in the connection pool. Only applies when the proxy has opened its maximum number of connections and all connections are busy with client sessions.&lt;/p&gt; &lt;p&gt;Default: 120&lt;/p&gt; &lt;p&gt;Constraints: between 1 and 3600, or 0 representing unlimited&lt;/p&gt; |  [optional] |
|**sessionPinningFilters** | **List&lt;String&gt;** | &lt;p&gt;Each item in the list represents a class of SQL operations that normally cause all later statements in a session using a proxy to be pinned to the same underlying database connection. Including an item in the list exempts that class of SQL operations from the pinning behavior.&lt;/p&gt; &lt;p&gt;Default: no session pinning filters&lt;/p&gt; |  [optional] |
|**initQuery** | **String** | &lt;p&gt;One or more SQL statements for the proxy to run when opening each new database connection. Typically used with &lt;code&gt;SET&lt;/code&gt; statements to make sure that each connection has identical settings such as time zone and character set. For multiple statements, use semicolons as the separator. You can also include multiple variables in a single &lt;code&gt;SET&lt;/code&gt; statement, such as &lt;code&gt;SET x&#x3D;1, y&#x3D;2&lt;/code&gt;.&lt;/p&gt; &lt;p&gt;Default: no initialization query&lt;/p&gt; |  [optional] |



