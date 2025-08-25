

# DescribeDBInstancesMessage

<p/>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**dbInstanceIdentifier** | **String** | &lt;p&gt;The user-supplied instance identifier or the Amazon Resource Name (ARN) of the DB instance. If this parameter is specified, information from only the specific DB instance is returned. This parameter isn&#39;t case-sensitive.&lt;/p&gt; &lt;p&gt;Constraints:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt;If supplied, must match the identifier of an existing DB instance.&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; |  [optional] |
|**filters** | [**List&lt;Filter&gt;**](Filter.md) | &lt;p&gt;A filter that specifies one or more DB instances to describe.&lt;/p&gt; &lt;p&gt;Supported Filters:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;db-cluster-id&lt;/code&gt; - Accepts DB cluster identifiers and DB cluster Amazon Resource Names (ARNs). The results list only includes information about the DB instances associated with the DB clusters identified by these ARNs.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;db-instance-id&lt;/code&gt; - Accepts DB instance identifiers and DB instance Amazon Resource Names (ARNs). The results list only includes information about the DB instances identified by these ARNs.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;dbi-resource-id&lt;/code&gt; - Accepts DB instance resource identifiers. The results list only includes information about the DB instances identified by these DB instance resource identifiers.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;domain&lt;/code&gt; - Accepts Active Directory directory IDs. The results list only includes information about the DB instances associated with these domains.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;engine&lt;/code&gt; - Accepts engine names. The results list only includes information about the DB instances for these engines.&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; |  [optional] |
|**maxRecords** | **Integer** | &lt;p&gt;The maximum number of records to include in the response. If more records exist than the specified &lt;code&gt;MaxRecords&lt;/code&gt; value, a pagination token called a marker is included in the response so that you can retrieve the remaining results.&lt;/p&gt; &lt;p&gt;Default: 100&lt;/p&gt; &lt;p&gt;Constraints: Minimum 20, maximum 100.&lt;/p&gt; |  [optional] |
|**marker** | **String** | An optional pagination token provided by a previous &lt;code&gt;DescribeDBInstances&lt;/code&gt; request. If this parameter is specified, the response includes only records beyond the marker, up to the value specified by &lt;code&gt;MaxRecords&lt;/code&gt;. |  [optional] |



