

# DescribeDBClusterParameterGroupsMessage

<p/>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**dbClusterParameterGroupName** | **String** | &lt;p&gt;The name of a specific DB cluster parameter group to return details for.&lt;/p&gt; &lt;p&gt;Constraints:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt;If supplied, must match the name of an existing DBClusterParameterGroup.&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; |  [optional] |
|**filters** | [**List&lt;Filter&gt;**](Filter.md) | This parameter isn&#39;t currently supported. |  [optional] |
|**maxRecords** | **Integer** | &lt;p&gt;The maximum number of records to include in the response. If more records exist than the specified &lt;code&gt;MaxRecords&lt;/code&gt; value, a pagination token called a marker is included in the response so you can retrieve the remaining results.&lt;/p&gt; &lt;p&gt;Default: 100&lt;/p&gt; &lt;p&gt;Constraints: Minimum 20, maximum 100.&lt;/p&gt; |  [optional] |
|**marker** | **String** | An optional pagination token provided by a previous &lt;code&gt;DescribeDBClusterParameterGroups&lt;/code&gt; request. If this parameter is specified, the response includes only records beyond the marker, up to the value specified by &lt;code&gt;MaxRecords&lt;/code&gt;. |  [optional] |



