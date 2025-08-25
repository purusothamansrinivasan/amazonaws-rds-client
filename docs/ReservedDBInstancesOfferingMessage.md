

# ReservedDBInstancesOfferingMessage

Contains the result of a successful invocation of the <code>DescribeReservedDBInstancesOfferings</code> action.

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**marker** | **String** | An optional pagination token provided by a previous request. If this parameter is specified, the response includes only records beyond the marker, up to the value specified by &lt;code&gt;MaxRecords&lt;/code&gt;. |  [optional] |
|**reservedDBInstancesOfferings** | [**List&lt;ReservedDBInstancesOffering&gt;**](ReservedDBInstancesOffering.md) | A list of reserved DB instance offerings. |  [optional] |



