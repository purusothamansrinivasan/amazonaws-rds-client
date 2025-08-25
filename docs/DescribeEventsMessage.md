

# DescribeEventsMessage

<p/>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**sourceIdentifier** | **String** | &lt;p&gt;The identifier of the event source for which events are returned. If not specified, then all sources are included in the response.&lt;/p&gt; &lt;p&gt;Constraints:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt;If &lt;code&gt;SourceIdentifier&lt;/code&gt; is supplied, &lt;code&gt;SourceType&lt;/code&gt; must also be provided.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt;If the source type is a DB instance, a &lt;code&gt;DBInstanceIdentifier&lt;/code&gt; value must be supplied.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt;If the source type is a DB cluster, a &lt;code&gt;DBClusterIdentifier&lt;/code&gt; value must be supplied.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt;If the source type is a DB parameter group, a &lt;code&gt;DBParameterGroupName&lt;/code&gt; value must be supplied.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt;If the source type is a DB security group, a &lt;code&gt;DBSecurityGroupName&lt;/code&gt; value must be supplied.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt;If the source type is a DB snapshot, a &lt;code&gt;DBSnapshotIdentifier&lt;/code&gt; value must be supplied.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt;If the source type is a DB cluster snapshot, a &lt;code&gt;DBClusterSnapshotIdentifier&lt;/code&gt; value must be supplied.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt;If the source type is an RDS Proxy, a &lt;code&gt;DBProxyName&lt;/code&gt; value must be supplied.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt;Can&#39;t end with a hyphen or contain two consecutive hyphens.&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; |  [optional] |
|**sourceType** | **SourceType** | The event source to retrieve events for. If no value is specified, all events are returned. |  [optional] |
|**startTime** | **OffsetDateTime** | &lt;p&gt;The beginning of the time interval to retrieve events for, specified in ISO 8601 format. For more information about ISO 8601, go to the &lt;a href&#x3D;\&quot;http://en.wikipedia.org/wiki/ISO_8601\&quot;&gt;ISO8601 Wikipedia page.&lt;/a&gt; &lt;/p&gt; &lt;p&gt;Example: 2009-07-08T18:00Z&lt;/p&gt; |  [optional] |
|**endTime** | **OffsetDateTime** | &lt;p&gt;The end of the time interval for which to retrieve events, specified in ISO 8601 format. For more information about ISO 8601, go to the &lt;a href&#x3D;\&quot;http://en.wikipedia.org/wiki/ISO_8601\&quot;&gt;ISO8601 Wikipedia page.&lt;/a&gt; &lt;/p&gt; &lt;p&gt;Example: 2009-07-08T18:00Z&lt;/p&gt; |  [optional] |
|**duration** | **Integer** | &lt;p&gt;The number of minutes to retrieve events for.&lt;/p&gt; &lt;p&gt;Default: 60&lt;/p&gt; |  [optional] |
|**eventCategories** | **List&lt;String&gt;** | A list of event categories that trigger notifications for a event notification subscription. |  [optional] |
|**filters** | [**List&lt;Filter&gt;**](Filter.md) | This parameter isn&#39;t currently supported. |  [optional] |
|**maxRecords** | **Integer** | &lt;p&gt;The maximum number of records to include in the response. If more records exist than the specified &lt;code&gt;MaxRecords&lt;/code&gt; value, a pagination token called a marker is included in the response so that you can retrieve the remaining results.&lt;/p&gt; &lt;p&gt;Default: 100&lt;/p&gt; &lt;p&gt;Constraints: Minimum 20, maximum 100.&lt;/p&gt; |  [optional] |
|**marker** | **String** | An optional pagination token provided by a previous DescribeEvents request. If this parameter is specified, the response includes only records beyond the marker, up to the value specified by &lt;code&gt;MaxRecords&lt;/code&gt;. |  [optional] |



