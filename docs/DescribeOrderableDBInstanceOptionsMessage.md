

# DescribeOrderableDBInstanceOptionsMessage

<p/>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**engine** | **String** | &lt;p&gt;The name of the engine to retrieve DB instance options for.&lt;/p&gt; &lt;p&gt;Valid Values:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;aurora-mysql&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;aurora-postgresql&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;custom-oracle-ee&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;mariadb&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;mysql&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;oracle-ee&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;oracle-ee-cdb&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;oracle-se2&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;oracle-se2-cdb&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;postgres&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;sqlserver-ee&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;sqlserver-se&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;sqlserver-ex&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;sqlserver-web&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; |  |
|**engineVersion** | **String** | The engine version filter value. Specify this parameter to show only the available offerings matching the specified engine version. |  [optional] |
|**dbInstanceClass** | **String** | The DB instance class filter value. Specify this parameter to show only the available offerings matching the specified DB instance class. |  [optional] |
|**licenseModel** | **String** | &lt;p&gt;The license model filter value. Specify this parameter to show only the available offerings matching the specified license model.&lt;/p&gt; &lt;p&gt;RDS Custom supports only the BYOL licensing model.&lt;/p&gt; |  [optional] |
|**availabilityZoneGroup** | **String** | &lt;p&gt;The Availability Zone group associated with a Local Zone. Specify this parameter to retrieve available offerings for the Local Zones in the group.&lt;/p&gt; &lt;p&gt;Omit this parameter to show the available offerings in the specified Amazon Web Services Region.&lt;/p&gt; &lt;p&gt;This setting doesn&#39;t apply to RDS Custom.&lt;/p&gt; |  [optional] |
|**vpc** | **Boolean** | &lt;p&gt;A value that indicates whether to show only VPC or non-VPC offerings. RDS Custom supports only VPC offerings.&lt;/p&gt; &lt;p&gt;RDS Custom supports only VPC offerings. If you describe non-VPC offerings for RDS Custom, the output shows VPC offerings.&lt;/p&gt; |  [optional] |
|**filters** | [**List&lt;Filter&gt;**](Filter.md) | This parameter isn&#39;t currently supported. |  [optional] |
|**maxRecords** | **Integer** | &lt;p&gt;The maximum number of records to include in the response. If more records exist than the specified &lt;code&gt;MaxRecords&lt;/code&gt; value, a pagination token called a marker is included in the response so that you can retrieve the remaining results.&lt;/p&gt; &lt;p&gt;Default: 100&lt;/p&gt; &lt;p&gt;Constraints: Minimum 20, maximum 10000.&lt;/p&gt; |  [optional] |
|**marker** | **String** | An optional pagination token provided by a previous DescribeOrderableDBInstanceOptions request. If this parameter is specified, the response includes only records beyond the marker, up to the value specified by &lt;code&gt;MaxRecords&lt;/code&gt;. |  [optional] |



