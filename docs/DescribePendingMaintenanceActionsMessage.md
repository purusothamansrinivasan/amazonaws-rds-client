

# DescribePendingMaintenanceActionsMessage

<p/>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**resourceIdentifier** | **String** | The ARN of a resource to return pending maintenance actions for. |  [optional] |
|**filters** | [**List&lt;Filter&gt;**](Filter.md) | &lt;p&gt;A filter that specifies one or more resources to return pending maintenance actions for.&lt;/p&gt; &lt;p&gt;Supported filters:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;db-cluster-id&lt;/code&gt; - Accepts DB cluster identifiers and DB cluster Amazon Resource Names (ARNs). The results list only includes pending maintenance actions for the DB clusters identified by these ARNs.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;db-instance-id&lt;/code&gt; - Accepts DB instance identifiers and DB instance ARNs. The results list only includes pending maintenance actions for the DB instances identified by these ARNs.&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; |  [optional] |
|**marker** | **String** | An optional pagination token provided by a previous &lt;code&gt;DescribePendingMaintenanceActions&lt;/code&gt; request. If this parameter is specified, the response includes only records beyond the marker, up to a number of records specified by &lt;code&gt;MaxRecords&lt;/code&gt;. |  [optional] |
|**maxRecords** | **Integer** | &lt;p&gt;The maximum number of records to include in the response. If more records exist than the specified &lt;code&gt;MaxRecords&lt;/code&gt; value, a pagination token called a marker is included in the response so that you can retrieve the remaining results.&lt;/p&gt; &lt;p&gt;Default: 100&lt;/p&gt; &lt;p&gt;Constraints: Minimum 20, maximum 100.&lt;/p&gt; |  [optional] |



