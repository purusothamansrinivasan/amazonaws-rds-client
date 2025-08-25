

# EventsMessage

Contains the result of a successful invocation of the <code>DescribeEvents</code> action.

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**marker** | **String** | An optional pagination token provided by a previous Events request. If this parameter is specified, the response includes only records beyond the marker, up to the value specified by &lt;code&gt;MaxRecords&lt;/code&gt;. |  [optional] |
|**events** | [**List&lt;Event&gt;**](Event.md) | A list of &lt;code&gt;Event&lt;/code&gt; instances. |  [optional] |



