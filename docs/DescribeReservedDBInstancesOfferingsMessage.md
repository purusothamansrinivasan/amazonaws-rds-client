

# DescribeReservedDBInstancesOfferingsMessage

<p/>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**reservedDBInstancesOfferingId** | **String** | &lt;p&gt;The offering identifier filter value. Specify this parameter to show only the available offering that matches the specified reservation identifier.&lt;/p&gt; &lt;p&gt;Example: &lt;code&gt;438012d3-4052-4cc7-b2e3-8d3372e0e706&lt;/code&gt; &lt;/p&gt; |  [optional] |
|**dbInstanceClass** | **String** | The DB instance class filter value. Specify this parameter to show only the available offerings matching the specified DB instance class. |  [optional] |
|**duration** | **String** | &lt;p&gt;Duration filter value, specified in years or seconds. Specify this parameter to show only reservations for this duration.&lt;/p&gt; &lt;p&gt;Valid Values: &lt;code&gt;1 | 3 | 31536000 | 94608000&lt;/code&gt; &lt;/p&gt; |  [optional] |
|**productDescription** | **String** | &lt;p&gt;Product description filter value. Specify this parameter to show only the available offerings that contain the specified product description.&lt;/p&gt; &lt;note&gt; &lt;p&gt;The results show offerings that partially match the filter value.&lt;/p&gt; &lt;/note&gt; |  [optional] |
|**offeringType** | **String** | &lt;p&gt;The offering type filter value. Specify this parameter to show only the available offerings matching the specified offering type.&lt;/p&gt; &lt;p&gt;Valid Values: &lt;code&gt;\&quot;Partial Upfront\&quot; | \&quot;All Upfront\&quot; | \&quot;No Upfront\&quot; &lt;/code&gt; &lt;/p&gt; |  [optional] |
|**multiAZ** | **Boolean** | A value that indicates whether to show only those reservations that support Multi-AZ. |  [optional] |
|**filters** | [**List&lt;Filter&gt;**](Filter.md) | This parameter isn&#39;t currently supported. |  [optional] |
|**maxRecords** | **Integer** | &lt;p&gt;The maximum number of records to include in the response. If more than the &lt;code&gt;MaxRecords&lt;/code&gt; value is available, a pagination token called a marker is included in the response so you can retrieve the remaining results.&lt;/p&gt; &lt;p&gt;Default: 100&lt;/p&gt; &lt;p&gt;Constraints: Minimum 20, maximum 100.&lt;/p&gt; |  [optional] |
|**marker** | **String** | An optional pagination token provided by a previous request. If this parameter is specified, the response includes only records beyond the marker, up to the value specified by &lt;code&gt;MaxRecords&lt;/code&gt;. |  [optional] |



