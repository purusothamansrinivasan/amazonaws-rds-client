

# DescribeDBProxyEndpointsRequest


## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**dbProxyName** | **String** | The name of the DB proxy whose endpoints you want to describe. If you omit this parameter, the output includes information about all DB proxy endpoints associated with all your DB proxies. |  [optional] |
|**dbProxyEndpointName** | **String** | The name of a DB proxy endpoint to describe. If you omit this parameter, the output includes information about all DB proxy endpoints associated with the specified proxy. |  [optional] |
|**filters** | [**List&lt;Filter&gt;**](Filter.md) | This parameter is not currently supported. |  [optional] |
|**marker** | **String** | An optional pagination token provided by a previous request. If this parameter is specified, the response includes only records beyond the marker, up to the value specified by &lt;code&gt;MaxRecords&lt;/code&gt;. |  [optional] |
|**maxRecords** | **Integer** | &lt;p&gt;The maximum number of records to include in the response. If more records exist than the specified &lt;code&gt;MaxRecords&lt;/code&gt; value, a pagination token called a marker is included in the response so that the remaining results can be retrieved.&lt;/p&gt; &lt;p&gt;Default: 100&lt;/p&gt; &lt;p&gt;Constraints: Minimum 20, maximum 100.&lt;/p&gt; |  [optional] |



