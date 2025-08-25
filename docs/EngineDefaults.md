

# EngineDefaults

Contains the result of a successful invocation of the <code>DescribeEngineDefaultParameters</code> action.

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**dbParameterGroupFamily** | **String** | Specifies the name of the DB parameter group family that the engine default parameters apply to. |  [optional] |
|**marker** | **String** | An optional pagination token provided by a previous EngineDefaults request. If this parameter is specified, the response includes only records beyond the marker, up to the value specified by &lt;code&gt;MaxRecords&lt;/code&gt; . |  [optional] |
|**parameters** | [**List&lt;Parameter&gt;**](Parameter.md) | Contains a list of engine default parameters. |  [optional] |



