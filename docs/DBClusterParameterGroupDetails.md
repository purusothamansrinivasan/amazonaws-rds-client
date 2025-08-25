

# DBClusterParameterGroupDetails

Provides details about a DB cluster parameter group including the parameters in the DB cluster parameter group.

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**parameters** | [**List&lt;Parameter&gt;**](Parameter.md) | Provides a list of parameters for the DB cluster parameter group. |  [optional] |
|**marker** | **String** | An optional pagination token provided by a previous &lt;code&gt;DescribeDBClusterParameters&lt;/code&gt; request. If this parameter is specified, the response includes only records beyond the marker, up to the value specified by &lt;code&gt;MaxRecords&lt;/code&gt;. |  [optional] |



