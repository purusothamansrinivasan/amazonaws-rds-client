

# DescribeDBClusterEndpointsMessage


## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**dbClusterIdentifier** | **String** | The DB cluster identifier of the DB cluster associated with the endpoint. This parameter is stored as a lowercase string. |  [optional] |
|**dbClusterEndpointIdentifier** | **String** | The identifier of the endpoint to describe. This parameter is stored as a lowercase string. |  [optional] |
|**filters** | [**List&lt;Filter&gt;**](Filter.md) | A set of name-value pairs that define which endpoints to include in the output. The filters are specified as name-value pairs, in the format &lt;code&gt;Name&#x3D;&lt;i&gt;endpoint_type&lt;/i&gt;,Values&#x3D;&lt;i&gt;endpoint_type1&lt;/i&gt;,&lt;i&gt;endpoint_type2&lt;/i&gt;,...&lt;/code&gt;. &lt;code&gt;Name&lt;/code&gt; can be one of: &lt;code&gt;db-cluster-endpoint-type&lt;/code&gt;, &lt;code&gt;db-cluster-endpoint-custom-type&lt;/code&gt;, &lt;code&gt;db-cluster-endpoint-id&lt;/code&gt;, &lt;code&gt;db-cluster-endpoint-status&lt;/code&gt;. &lt;code&gt;Values&lt;/code&gt; for the &lt;code&gt; db-cluster-endpoint-type&lt;/code&gt; filter can be one or more of: &lt;code&gt;reader&lt;/code&gt;, &lt;code&gt;writer&lt;/code&gt;, &lt;code&gt;custom&lt;/code&gt;. &lt;code&gt;Values&lt;/code&gt; for the &lt;code&gt;db-cluster-endpoint-custom-type&lt;/code&gt; filter can be one or more of: &lt;code&gt;reader&lt;/code&gt;, &lt;code&gt;any&lt;/code&gt;. &lt;code&gt;Values&lt;/code&gt; for the &lt;code&gt;db-cluster-endpoint-status&lt;/code&gt; filter can be one or more of: &lt;code&gt;available&lt;/code&gt;, &lt;code&gt;creating&lt;/code&gt;, &lt;code&gt;deleting&lt;/code&gt;, &lt;code&gt;inactive&lt;/code&gt;, &lt;code&gt;modifying&lt;/code&gt;. |  [optional] |
|**maxRecords** | **Integer** | &lt;p&gt;The maximum number of records to include in the response. If more records exist than the specified &lt;code&gt;MaxRecords&lt;/code&gt; value, a pagination token called a marker is included in the response so you can retrieve the remaining results.&lt;/p&gt; &lt;p&gt;Default: 100&lt;/p&gt; &lt;p&gt;Constraints: Minimum 20, maximum 100.&lt;/p&gt; |  [optional] |
|**marker** | **String** | An optional pagination token provided by a previous &lt;code&gt;DescribeDBClusterEndpoints&lt;/code&gt; request. If this parameter is specified, the response includes only records beyond the marker, up to the value specified by &lt;code&gt;MaxRecords&lt;/code&gt;. |  [optional] |



