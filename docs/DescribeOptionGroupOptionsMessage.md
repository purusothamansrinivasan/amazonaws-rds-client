

# DescribeOptionGroupOptionsMessage

<p/>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**engineName** | **String** | &lt;p&gt;A required parameter. Options available for the given engine name are described.&lt;/p&gt; &lt;p&gt;Valid Values:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;mariadb&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;mysql&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;oracle-ee&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;oracle-ee-cdb&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;oracle-se2&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;oracle-se2-cdb&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;postgres&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;sqlserver-ee&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;sqlserver-se&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;sqlserver-ex&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;sqlserver-web&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; |  |
|**majorEngineVersion** | **String** | If specified, filters the results to include only options for the specified major engine version. |  [optional] |
|**filters** | [**List&lt;Filter&gt;**](Filter.md) | This parameter isn&#39;t currently supported. |  [optional] |
|**maxRecords** | **Integer** | &lt;p&gt;The maximum number of records to include in the response. If more records exist than the specified &lt;code&gt;MaxRecords&lt;/code&gt; value, a pagination token called a marker is included in the response so that you can retrieve the remaining results.&lt;/p&gt; &lt;p&gt;Default: 100&lt;/p&gt; &lt;p&gt;Constraints: Minimum 20, maximum 100.&lt;/p&gt; |  [optional] |
|**marker** | **String** | An optional pagination token provided by a previous request. If this parameter is specified, the response includes only records beyond the marker, up to the value specified by &lt;code&gt;MaxRecords&lt;/code&gt;. |  [optional] |



