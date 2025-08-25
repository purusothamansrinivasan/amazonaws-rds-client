

# ResetDBClusterParameterGroupMessage

<p/>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**dbClusterParameterGroupName** | **String** | The name of the DB cluster parameter group to reset. |  |
|**resetAllParameters** | **Boolean** | A value that indicates whether to reset all parameters in the DB cluster parameter group to their default values. You can&#39;t use this parameter if there is a list of parameter names specified for the &lt;code&gt;Parameters&lt;/code&gt; parameter. |  [optional] |
|**parameters** | [**List&lt;Parameter&gt;**](Parameter.md) | A list of parameter names in the DB cluster parameter group to reset to the default values. You can&#39;t use this parameter if the &lt;code&gt;ResetAllParameters&lt;/code&gt; parameter is enabled. |  [optional] |



