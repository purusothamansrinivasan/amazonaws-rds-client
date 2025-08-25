

# DescribeDBParametersMessage


## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**dbParameterGroupName** | **String** | &lt;p&gt;The name of a specific DB parameter group to return details for.&lt;/p&gt; &lt;p&gt;Constraints:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt;If supplied, must match the name of an existing DBParameterGroup.&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; |  |
|**source** | **String** | &lt;p&gt;The parameter types to return.&lt;/p&gt; &lt;p&gt;Default: All parameter types returned&lt;/p&gt; &lt;p&gt;Valid Values: &lt;code&gt;user | system | engine-default&lt;/code&gt; &lt;/p&gt; |  [optional] |
|**filters** | [**List&lt;Filter&gt;**](Filter.md) | This parameter isn&#39;t currently supported. |  [optional] |
|**maxRecords** | **Integer** | &lt;p&gt;The maximum number of records to include in the response. If more records exist than the specified &lt;code&gt;MaxRecords&lt;/code&gt; value, a pagination token called a marker is included in the response so that you can retrieve the remaining results.&lt;/p&gt; &lt;p&gt;Default: 100&lt;/p&gt; &lt;p&gt;Constraints: Minimum 20, maximum 100.&lt;/p&gt; |  [optional] |
|**marker** | **String** | An optional pagination token provided by a previous &lt;code&gt;DescribeDBParameters&lt;/code&gt; request. If this parameter is specified, the response includes only records beyond the marker, up to the value specified by &lt;code&gt;MaxRecords&lt;/code&gt;. |  [optional] |



