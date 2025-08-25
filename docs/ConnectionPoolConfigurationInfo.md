

# ConnectionPoolConfigurationInfo

Displays the settings that control the size and behavior of the connection pool associated with a <code>DBProxyTarget</code>.

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**maxConnectionsPercent** | **Integer** | The maximum size of the connection pool for each target in a target group. The value is expressed as a percentage of the &lt;code&gt;max_connections&lt;/code&gt; setting for the RDS DB instance or Aurora DB cluster used by the target group. |  [optional] |
|**maxIdleConnectionsPercent** | **Integer** | Controls how actively the proxy closes idle database connections in the connection pool. The value is expressed as a percentage of the &lt;code&gt;max_connections&lt;/code&gt; setting for the RDS DB instance or Aurora DB cluster used by the target group. With a high value, the proxy leaves a high percentage of idle database connections open. A low value causes the proxy to close more idle connections and return them to the database. |  [optional] |
|**connectionBorrowTimeout** | **Integer** | The number of seconds for a proxy to wait for a connection to become available in the connection pool. Only applies when the proxy has opened its maximum number of connections and all connections are busy with client sessions. |  [optional] |
|**sessionPinningFilters** | **List&lt;String&gt;** | Each item in the list represents a class of SQL operations that normally cause all later statements in a session using a proxy to be pinned to the same underlying database connection. Including an item in the list exempts that class of SQL operations from the pinning behavior. This setting is only supported for MySQL engine family databases. Currently, the only allowed value is &lt;code&gt;EXCLUDE_VARIABLE_SETS&lt;/code&gt;. |  [optional] |
|**initQuery** | **String** | One or more SQL statements for the proxy to run when opening each new database connection. Typically used with &lt;code&gt;SET&lt;/code&gt; statements to make sure that each connection has identical settings such as time zone and character set. This setting is empty by default. For multiple statements, use semicolons as the separator. You can also include multiple variables in a single &lt;code&gt;SET&lt;/code&gt; statement, such as &lt;code&gt;SET x&#x3D;1, y&#x3D;2&lt;/code&gt;. |  [optional] |



