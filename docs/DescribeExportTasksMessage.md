

# DescribeExportTasksMessage


## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**exportTaskIdentifier** | **String** | The identifier of the snapshot or cluster export task to be described. |  [optional] |
|**sourceArn** | **String** | The Amazon Resource Name (ARN) of the snapshot or cluster exported to Amazon S3. |  [optional] |
|**filters** | [**List&lt;Filter&gt;**](Filter.md) | &lt;p&gt;Filters specify one or more snapshot or cluster exports to describe. The filters are specified as name-value pairs that define what to include in the output. Filter names and values are case-sensitive.&lt;/p&gt; &lt;p&gt;Supported filters include the following:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;export-task-identifier&lt;/code&gt; - An identifier for the snapshot or cluster export task.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;s3-bucket&lt;/code&gt; - The Amazon S3 bucket the data is exported to.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;source-arn&lt;/code&gt; - The Amazon Resource Name (ARN) of the snapshot or cluster exported to Amazon S3.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;status&lt;/code&gt; - The status of the export task. Must be lowercase. Valid statuses are the following:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;canceled&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;canceling&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;complete&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;failed&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;in_progress&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;starting&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; &lt;/li&gt; &lt;/ul&gt; |  [optional] |
|**marker** | **String** | An optional pagination token provided by a previous &lt;code&gt;DescribeExportTasks&lt;/code&gt; request. If you specify this parameter, the response includes only records beyond the marker, up to the value specified by the &lt;code&gt;MaxRecords&lt;/code&gt; parameter. |  [optional] |
|**maxRecords** | **Integer** | &lt;p&gt;The maximum number of records to include in the response. If more records exist than the specified value, a pagination token called a marker is included in the response. You can use the marker in a later &lt;code&gt;DescribeExportTasks&lt;/code&gt; request to retrieve the remaining results.&lt;/p&gt; &lt;p&gt;Default: 100&lt;/p&gt; &lt;p&gt;Constraints: Minimum 20, maximum 100.&lt;/p&gt; |  [optional] |
|**sourceType** | **ExportSourceType** | The type of source for the export. |  [optional] |



