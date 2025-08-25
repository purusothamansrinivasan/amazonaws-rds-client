

# CreateDBParameterGroupMessage

<p/>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**dbParameterGroupName** | **String** | &lt;p&gt;The name of the DB parameter group.&lt;/p&gt; &lt;p&gt;Constraints:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt;Must be 1 to 255 letters, numbers, or hyphens.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt;First character must be a letter&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt;Can&#39;t end with a hyphen or contain two consecutive hyphens&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; &lt;note&gt; &lt;p&gt;This value is stored as a lowercase string.&lt;/p&gt; &lt;/note&gt; |  |
|**dbParameterGroupFamily** | **String** | &lt;p&gt;The DB parameter group family name. A DB parameter group can be associated with one and only one DB parameter group family, and can be applied only to a DB instance running a database engine and engine version compatible with that DB parameter group family.&lt;/p&gt; &lt;p&gt;To list all of the available parameter group families for a DB engine, use the following command:&lt;/p&gt; &lt;p&gt; &lt;code&gt;aws rds describe-db-engine-versions --query \&quot;DBEngineVersions[].DBParameterGroupFamily\&quot; --engine &amp;lt;engine&amp;gt;&lt;/code&gt; &lt;/p&gt; &lt;p&gt;For example, to list all of the available parameter group families for the MySQL DB engine, use the following command:&lt;/p&gt; &lt;p&gt; &lt;code&gt;aws rds describe-db-engine-versions --query \&quot;DBEngineVersions[].DBParameterGroupFamily\&quot; --engine mysql&lt;/code&gt; &lt;/p&gt; &lt;note&gt; &lt;p&gt;The output contains duplicates.&lt;/p&gt; &lt;/note&gt; &lt;p&gt;The following are the valid DB engine values:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;aurora-mysql&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;aurora-postgresql&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;mariadb&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;mysql&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;oracle-ee&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;oracle-ee-cdb&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;oracle-se2&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;oracle-se2-cdb&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;postgres&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;sqlserver-ee&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;sqlserver-se&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;sqlserver-ex&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;sqlserver-web&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; |  |
|**description** | **String** | The description for the DB parameter group. |  |
|**tags** | [**List&lt;Tag&gt;**](Tag.md) | Tags to assign to the DB parameter group. |  [optional] |



