

# DescribeOptionGroupsMessage

<p/>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**optionGroupName** | **String** | The name of the option group to describe. Can&#39;t be supplied together with EngineName or MajorEngineVersion. |  [optional] |
|**filters** | [**List&lt;Filter&gt;**](Filter.md) | This parameter isn&#39;t currently supported. |  [optional] |
|**marker** | **String** | An optional pagination token provided by a previous DescribeOptionGroups request. If this parameter is specified, the response includes only records beyond the marker, up to the value specified by &lt;code&gt;MaxRecords&lt;/code&gt;. |  [optional] |
|**maxRecords** | **Integer** | &lt;p&gt;The maximum number of records to include in the response. If more records exist than the specified &lt;code&gt;MaxRecords&lt;/code&gt; value, a pagination token called a marker is included in the response so that you can retrieve the remaining results.&lt;/p&gt; &lt;p&gt;Default: 100&lt;/p&gt; &lt;p&gt;Constraints: Minimum 20, maximum 100.&lt;/p&gt; |  [optional] |
|**engineName** | **String** | &lt;p&gt;Filters the list of option groups to only include groups associated with a specific database engine.&lt;/p&gt; &lt;p&gt;Valid Values:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;mariadb&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;mysql&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;oracle-ee&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;oracle-ee-cdb&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;oracle-se2&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;oracle-se2-cdb&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;postgres&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;sqlserver-ee&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;sqlserver-se&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;sqlserver-ex&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;sqlserver-web&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; |  [optional] |
|**majorEngineVersion** | **String** | Filters the list of option groups to only include groups associated with a specific database engine version. If specified, then EngineName must also be specified. |  [optional] |



