

# ResetDBParameterGroupMessage

<p/>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**dbParameterGroupName** | **String** | &lt;p&gt;The name of the DB parameter group.&lt;/p&gt; &lt;p&gt;Constraints:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt;Must match the name of an existing &lt;code&gt;DBParameterGroup&lt;/code&gt;.&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; |  |
|**resetAllParameters** | **Boolean** | A value that indicates whether to reset all parameters in the DB parameter group to default values. By default, all parameters in the DB parameter group are reset to default values. |  [optional] |
|**parameters** | [**List&lt;Parameter&gt;**](Parameter.md) | &lt;p&gt;To reset the entire DB parameter group, specify the &lt;code&gt;DBParameterGroup&lt;/code&gt; name and &lt;code&gt;ResetAllParameters&lt;/code&gt; parameters. To reset specific parameters, provide a list of the following: &lt;code&gt;ParameterName&lt;/code&gt; and &lt;code&gt;ApplyMethod&lt;/code&gt;. A maximum of 20 parameters can be modified in a single request.&lt;/p&gt; &lt;p&gt; &lt;b&gt;MySQL&lt;/b&gt; &lt;/p&gt; &lt;p&gt;Valid Values (for Apply method): &lt;code&gt;immediate&lt;/code&gt; | &lt;code&gt;pending-reboot&lt;/code&gt; &lt;/p&gt; &lt;p&gt;You can use the immediate value with dynamic parameters only. You can use the &lt;code&gt;pending-reboot&lt;/code&gt; value for both dynamic and static parameters, and changes are applied when DB instance reboots.&lt;/p&gt; &lt;p&gt; &lt;b&gt;MariaDB&lt;/b&gt; &lt;/p&gt; &lt;p&gt;Valid Values (for Apply method): &lt;code&gt;immediate&lt;/code&gt; | &lt;code&gt;pending-reboot&lt;/code&gt; &lt;/p&gt; &lt;p&gt;You can use the immediate value with dynamic parameters only. You can use the &lt;code&gt;pending-reboot&lt;/code&gt; value for both dynamic and static parameters, and changes are applied when DB instance reboots.&lt;/p&gt; &lt;p&gt; &lt;b&gt;Oracle&lt;/b&gt; &lt;/p&gt; &lt;p&gt;Valid Values (for Apply method): &lt;code&gt;pending-reboot&lt;/code&gt; &lt;/p&gt; |  [optional] |



