

# DescribeDBClustersMessage

<p/>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**dbClusterIdentifier** | **String** | &lt;p&gt;The user-supplied DB cluster identifier or the Amazon Resource Name (ARN) of the DB cluster. If this parameter is specified, information for only the specific DB cluster is returned. This parameter isn&#39;t case-sensitive.&lt;/p&gt; &lt;p&gt;Constraints:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt;If supplied, must match an existing DB cluster identifier.&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; |  [optional] |
|**filters** | [**List&lt;Filter&gt;**](Filter.md) | &lt;p&gt;A filter that specifies one or more DB clusters to describe.&lt;/p&gt; &lt;p&gt;Supported Filters:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;clone-group-id&lt;/code&gt; - Accepts clone group identifiers. The results list only includes information about the DB clusters associated with these clone groups.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;db-cluster-id&lt;/code&gt; - Accepts DB cluster identifiers and DB cluster Amazon Resource Names (ARNs). The results list only includes information about the DB clusters identified by these ARNs.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;db-cluster-resource-id&lt;/code&gt; - Accepts DB cluster resource identifiers. The results list will only include information about the DB clusters identified by these DB cluster resource identifiers.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;domain&lt;/code&gt; - Accepts Active Directory directory IDs. The results list only includes information about the DB clusters associated with these domains.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;engine&lt;/code&gt; - Accepts engine names. The results list only includes information about the DB clusters for these engines.&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; |  [optional] |
|**maxRecords** | **Integer** | &lt;p&gt;The maximum number of records to include in the response. If more records exist than the specified &lt;code&gt;MaxRecords&lt;/code&gt; value, a pagination token called a marker is included in the response so you can retrieve the remaining results.&lt;/p&gt; &lt;p&gt;Default: 100&lt;/p&gt; &lt;p&gt;Constraints: Minimum 20, maximum 100.&lt;/p&gt; |  [optional] |
|**marker** | **String** | An optional pagination token provided by a previous &lt;code&gt;DescribeDBClusters&lt;/code&gt; request. If this parameter is specified, the response includes only records beyond the marker, up to the value specified by &lt;code&gt;MaxRecords&lt;/code&gt;. |  [optional] |
|**includeShared** | **Boolean** | Specifies whether the output includes information about clusters shared from other Amazon Web Services accounts. |  [optional] |



