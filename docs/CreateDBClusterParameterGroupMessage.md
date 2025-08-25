

# CreateDBClusterParameterGroupMessage

<p/>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**dbClusterParameterGroupName** | **String** | &lt;p&gt;The name of the DB cluster parameter group.&lt;/p&gt; &lt;p&gt;Constraints:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt;Must not match the name of an existing DB cluster parameter group.&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; &lt;note&gt; &lt;p&gt;This value is stored as a lowercase string.&lt;/p&gt; &lt;/note&gt; |  |
|**dbParameterGroupFamily** | **String** | &lt;p&gt;The DB cluster parameter group family name. A DB cluster parameter group can be associated with one and only one DB cluster parameter group family, and can be applied only to a DB cluster running a database engine and engine version compatible with that DB cluster parameter group family.&lt;/p&gt; &lt;p&gt; &lt;b&gt;Aurora MySQL&lt;/b&gt; &lt;/p&gt; &lt;p&gt;Example: &lt;code&gt;aurora-mysql5.7&lt;/code&gt;, &lt;code&gt;aurora-mysql8.0&lt;/code&gt; &lt;/p&gt; &lt;p&gt; &lt;b&gt;Aurora PostgreSQL&lt;/b&gt; &lt;/p&gt; &lt;p&gt;Example: &lt;code&gt;aurora-postgresql14&lt;/code&gt; &lt;/p&gt; &lt;p&gt; &lt;b&gt;RDS for MySQL&lt;/b&gt; &lt;/p&gt; &lt;p&gt;Example: &lt;code&gt;mysql8.0&lt;/code&gt; &lt;/p&gt; &lt;p&gt; &lt;b&gt;RDS for PostgreSQL&lt;/b&gt; &lt;/p&gt; &lt;p&gt;Example: &lt;code&gt;postgres12&lt;/code&gt; &lt;/p&gt; &lt;p&gt;To list all of the available parameter group families for a DB engine, use the following command:&lt;/p&gt; &lt;p&gt; &lt;code&gt;aws rds describe-db-engine-versions --query \&quot;DBEngineVersions[].DBParameterGroupFamily\&quot; --engine &amp;lt;engine&amp;gt;&lt;/code&gt; &lt;/p&gt; &lt;p&gt;For example, to list all of the available parameter group families for the Aurora PostgreSQL DB engine, use the following command:&lt;/p&gt; &lt;p&gt; &lt;code&gt;aws rds describe-db-engine-versions --query \&quot;DBEngineVersions[].DBParameterGroupFamily\&quot; --engine aurora-postgresql&lt;/code&gt; &lt;/p&gt; &lt;note&gt; &lt;p&gt;The output contains duplicates.&lt;/p&gt; &lt;/note&gt; &lt;p&gt;The following are the valid DB engine values:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;aurora-mysql&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;aurora-postgresql&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;mysql&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;postgres&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; |  |
|**description** | **String** | The description for the DB cluster parameter group. |  |
|**tags** | [**List&lt;Tag&gt;**](Tag.md) | Tags to assign to the DB cluster parameter group. |  [optional] |



