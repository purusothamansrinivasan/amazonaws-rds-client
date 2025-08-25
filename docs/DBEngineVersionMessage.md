

# DBEngineVersionMessage

Contains the result of a successful invocation of the <code>DescribeDBEngineVersions</code> action.

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**marker** | **String** | An optional pagination token provided by a previous request. If this parameter is specified, the response includes only records beyond the marker, up to the value specified by &lt;code&gt;MaxRecords&lt;/code&gt;. |  [optional] |
|**dbEngineVersions** | [**List&lt;DBEngineVersion&gt;**](DBEngineVersion.md) | A list of &lt;code&gt;DBEngineVersion&lt;/code&gt; elements. |  [optional] |



