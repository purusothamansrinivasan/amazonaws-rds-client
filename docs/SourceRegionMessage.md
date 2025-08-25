

# SourceRegionMessage

Contains the result of a successful invocation of the <code>DescribeSourceRegions</code> action.

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**marker** | **String** | An optional pagination token provided by a previous request. If this parameter is specified, the response includes only records beyond the marker, up to the value specified by &lt;code&gt;MaxRecords&lt;/code&gt;. |  [optional] |
|**sourceRegions** | [**List&lt;SourceRegion&gt;**](SourceRegion.md) | A list of &lt;code&gt;SourceRegion&lt;/code&gt; instances that contains each source Amazon Web Services Region that the current Amazon Web Services Region can get a read replica or a DB snapshot from. |  [optional] |



