

# DescribeReservedDBInstancesMessage

<p/>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**reservedDBInstanceId** | **String** | The reserved DB instance identifier filter value. Specify this parameter to show only the reservation that matches the specified reservation ID. |  [optional] |
|**reservedDBInstancesOfferingId** | **String** | The offering identifier filter value. Specify this parameter to show only purchased reservations matching the specified offering identifier. |  [optional] |
|**dbInstanceClass** | **String** | The DB instance class filter value. Specify this parameter to show only those reservations matching the specified DB instances class. |  [optional] |
|**duration** | **String** | &lt;p&gt;The duration filter value, specified in years or seconds. Specify this parameter to show only reservations for this duration.&lt;/p&gt; &lt;p&gt;Valid Values: &lt;code&gt;1 | 3 | 31536000 | 94608000&lt;/code&gt; &lt;/p&gt; |  [optional] |
|**productDescription** | **String** | The product description filter value. Specify this parameter to show only those reservations matching the specified product description. |  [optional] |
|**offeringType** | **String** | &lt;p&gt;The offering type filter value. Specify this parameter to show only the available offerings matching the specified offering type.&lt;/p&gt; &lt;p&gt;Valid Values: &lt;code&gt;\&quot;Partial Upfront\&quot; | \&quot;All Upfront\&quot; | \&quot;No Upfront\&quot; &lt;/code&gt; &lt;/p&gt; |  [optional] |
|**multiAZ** | **Boolean** | A value that indicates whether to show only those reservations that support Multi-AZ. |  [optional] |
|**leaseId** | **String** | &lt;p&gt;The lease identifier filter value. Specify this parameter to show only the reservation that matches the specified lease ID.&lt;/p&gt; &lt;note&gt; &lt;p&gt;Amazon Web Services Support might request the lease ID for an issue related to a reserved DB instance.&lt;/p&gt; &lt;/note&gt; |  [optional] |
|**filters** | [**List&lt;Filter&gt;**](Filter.md) | This parameter isn&#39;t currently supported. |  [optional] |
|**maxRecords** | **Integer** | &lt;p&gt;The maximum number of records to include in the response. If more than the &lt;code&gt;MaxRecords&lt;/code&gt; value is available, a pagination token called a marker is included in the response so you can retrieve the remaining results.&lt;/p&gt; &lt;p&gt;Default: 100&lt;/p&gt; &lt;p&gt;Constraints: Minimum 20, maximum 100.&lt;/p&gt; |  [optional] |
|**marker** | **String** | An optional pagination token provided by a previous request. If this parameter is specified, the response includes only records beyond the marker, up to the value specified by &lt;code&gt;MaxRecords&lt;/code&gt;. |  [optional] |



