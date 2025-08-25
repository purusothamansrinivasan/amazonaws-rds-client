

# ModifyDBClusterParameterGroupMessage

<p/>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**dbClusterParameterGroupName** | **String** | The name of the DB cluster parameter group to modify. |  |
|**parameters** | [**List&lt;Parameter&gt;**](Parameter.md) | &lt;p&gt;A list of parameters in the DB cluster parameter group to modify.&lt;/p&gt; &lt;p&gt;Valid Values (for the application method): &lt;code&gt;immediate | pending-reboot&lt;/code&gt; &lt;/p&gt; &lt;note&gt; &lt;p&gt;You can use the &lt;code&gt;immediate&lt;/code&gt; value with dynamic parameters only. You can use the &lt;code&gt;pending-reboot&lt;/code&gt; value for both dynamic and static parameters.&lt;/p&gt; &lt;p&gt;When the application method is &lt;code&gt;immediate&lt;/code&gt;, changes to dynamic parameters are applied immediately to the DB clusters associated with the parameter group. When the application method is &lt;code&gt;pending-reboot&lt;/code&gt;, changes to dynamic and static parameters are applied after a reboot without failover to the DB clusters associated with the parameter group.&lt;/p&gt; &lt;/note&gt; |  |



