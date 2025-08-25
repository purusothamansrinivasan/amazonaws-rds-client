

# DescribeDBClusterAutomatedBackupsMessage


## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**dbClusterResourceId** | **String** | The resource ID of the DB cluster that is the source of the automated backup. This parameter isn&#39;t case-sensitive. |  [optional] |
|**dbClusterIdentifier** | **String** | (Optional) The user-supplied DB cluster identifier. If this parameter is specified, it must match the identifier of an existing DB cluster. It returns information from the specific DB cluster&#39;s automated backup. This parameter isn&#39;t case-sensitive. |  [optional] |
|**filters** | [**List&lt;Filter&gt;**](Filter.md) | &lt;p&gt;A filter that specifies which resources to return based on status.&lt;/p&gt; &lt;p&gt;Supported filters are the following:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;status&lt;/code&gt; &lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;retained&lt;/code&gt; - Automated backups for deleted clusters and after backup replication is stopped.&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;db-cluster-id&lt;/code&gt; - Accepts DB cluster identifiers and Amazon Resource Names (ARNs). The results list includes only information about the DB cluster automated backups identified by these ARNs.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;db-cluster-resource-id&lt;/code&gt; - Accepts DB resource identifiers and Amazon Resource Names (ARNs). The results list includes only information about the DB cluster resources identified by these ARNs.&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; &lt;p&gt;Returns all resources by default. The status for each resource is specified in the response.&lt;/p&gt; |  [optional] |
|**maxRecords** | **Integer** | The maximum number of records to include in the response. If more records exist than the specified &lt;code&gt;MaxRecords&lt;/code&gt; value, a pagination token called a marker is included in the response so that you can retrieve the remaining results. |  [optional] |
|**marker** | **String** | The pagination token provided in the previous request. If this parameter is specified the response includes only records beyond the marker, up to &lt;code&gt;MaxRecords&lt;/code&gt;. |  [optional] |



