

# DescribeDBLogFilesMessage

<p/>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**dbInstanceIdentifier** | **String** | &lt;p&gt;The customer-assigned name of the DB instance that contains the log files you want to list.&lt;/p&gt; &lt;p&gt;Constraints:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt;Must match the identifier of an existing DBInstance.&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; |  |
|**filenameContains** | **String** | Filters the available log files for log file names that contain the specified string. |  [optional] |
|**fileLastWritten** | **Integer** | Filters the available log files for files written since the specified date, in POSIX timestamp format with milliseconds. |  [optional] |
|**fileSize** | **Integer** | Filters the available log files for files larger than the specified size. |  [optional] |
|**filters** | [**List&lt;Filter&gt;**](Filter.md) | This parameter isn&#39;t currently supported. |  [optional] |
|**maxRecords** | **Integer** | The maximum number of records to include in the response. If more records exist than the specified MaxRecords value, a pagination token called a marker is included in the response so you can retrieve the remaining results. |  [optional] |
|**marker** | **String** | The pagination token provided in the previous request. If this parameter is specified the response includes only records beyond the marker, up to MaxRecords. |  [optional] |



