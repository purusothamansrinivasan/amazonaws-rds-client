

# ModifyDBParameterGroupMessage

<p/>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**dbParameterGroupName** | **String** | &lt;p&gt;The name of the DB parameter group.&lt;/p&gt; &lt;p&gt;Constraints:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt;If supplied, must match the name of an existing &lt;code&gt;DBParameterGroup&lt;/code&gt;.&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; |  |
|**parameters** | [**List&lt;Parameter&gt;**](Parameter.md) | &lt;p&gt;An array of parameter names, values, and the application methods for the parameter update. At least one parameter name, value, and application method must be supplied; later arguments are optional. A maximum of 20 parameters can be modified in a single request.&lt;/p&gt; &lt;p&gt;Valid Values (for the application method): &lt;code&gt;immediate | pending-reboot&lt;/code&gt; &lt;/p&gt; &lt;p&gt;You can use the &lt;code&gt;immediate&lt;/code&gt; value with dynamic parameters only. You can use the &lt;code&gt;pending-reboot&lt;/code&gt; value for both dynamic and static parameters.&lt;/p&gt; &lt;p&gt;When the application method is &lt;code&gt;immediate&lt;/code&gt;, changes to dynamic parameters are applied immediately to the DB instances associated with the parameter group.&lt;/p&gt; &lt;p&gt;When the application method is &lt;code&gt;pending-reboot&lt;/code&gt;, changes to dynamic and static parameters are applied after a reboot without failover to the DB instances associated with the parameter group.&lt;/p&gt; &lt;note&gt; &lt;p&gt;You can&#39;t use &lt;code&gt;pending-reboot&lt;/code&gt; with dynamic parameters on RDS for SQL Server DB instances. Use &lt;code&gt;immediate&lt;/code&gt;.&lt;/p&gt; &lt;/note&gt; &lt;p&gt;For more information on modifying DB parameters, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/USER_WorkingWithParamGroups.html\&quot;&gt;Working with DB parameter groups&lt;/a&gt; in the &lt;i&gt;Amazon RDS User Guide&lt;/i&gt;.&lt;/p&gt; |  |



