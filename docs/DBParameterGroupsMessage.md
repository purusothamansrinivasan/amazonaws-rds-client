

# DBParameterGroupsMessage

Contains the result of a successful invocation of the <code>DescribeDBParameterGroups</code> action.

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**marker** | **String** | An optional pagination token provided by a previous request. If this parameter is specified, the response includes only records beyond the marker, up to the value specified by &lt;code&gt;MaxRecords&lt;/code&gt;. |  [optional] |
|**dbParameterGroups** | [**List&lt;DBParameterGroup&gt;**](DBParameterGroup.md) | A list of &lt;code&gt;DBParameterGroup&lt;/code&gt; instances. |  [optional] |



