

# Parameter

<p>This data type is used as a request parameter in the <code>ModifyDBParameterGroup</code> and <code>ResetDBParameterGroup</code> actions.</p> <p>This data type is used as a response element in the <code>DescribeEngineDefaultParameters</code> and <code>DescribeDBParameters</code> actions.</p>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**parameterName** | **String** | Specifies the name of the parameter. |  [optional] |
|**parameterValue** | **String** | Specifies the value of the parameter. |  [optional] |
|**description** | **String** | Provides a description of the parameter. |  [optional] |
|**source** | **String** | Indicates the source of the parameter value. |  [optional] |
|**applyType** | **String** | Specifies the engine specific parameters type. |  [optional] |
|**dataType** | **String** | Specifies the valid data type for the parameter. |  [optional] |
|**allowedValues** | **String** | Specifies the valid range of values for the parameter. |  [optional] |
|**isModifiable** | **Boolean** | Indicates whether (&lt;code&gt;true&lt;/code&gt;) or not (&lt;code&gt;false&lt;/code&gt;) the parameter can be modified. Some parameters have security or operational implications that prevent them from being changed. |  [optional] |
|**minimumEngineVersion** | **String** | The earliest engine version to which the parameter can apply. |  [optional] |
|**applyMethod** | **ApplyMethod** | Indicates when to apply parameter updates. |  [optional] |
|**supportedEngineModes** | **List&lt;String&gt;** | The valid DB engine modes. |  [optional] |



