

# ReservedDBInstance

This data type is used as a response element in the <code>DescribeReservedDBInstances</code> and <code>PurchaseReservedDBInstancesOffering</code> actions.

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**reservedDBInstanceId** | **String** | The unique identifier for the reservation. |  [optional] |
|**reservedDBInstancesOfferingId** | **String** | The offering identifier. |  [optional] |
|**dbInstanceClass** | **String** | The DB instance class for the reserved DB instance. |  [optional] |
|**startTime** | **OffsetDateTime** | The time the reservation started. |  [optional] |
|**duration** | **Integer** | The duration of the reservation in seconds. |  [optional] |
|**fixedPrice** | **Double** | The fixed price charged for this reserved DB instance. |  [optional] |
|**usagePrice** | **Double** | The hourly price charged for this reserved DB instance. |  [optional] |
|**currencyCode** | **String** | The currency code for the reserved DB instance. |  [optional] |
|**dbInstanceCount** | **Integer** | The number of reserved DB instances. |  [optional] |
|**productDescription** | **String** | The description of the reserved DB instance. |  [optional] |
|**offeringType** | **String** | The offering type of this reserved DB instance. |  [optional] |
|**multiAZ** | **Boolean** | Indicates if the reservation applies to Multi-AZ deployments. |  [optional] |
|**state** | **String** | The state of the reserved DB instance. |  [optional] |
|**recurringCharges** | [**List&lt;RecurringCharge&gt;**](RecurringCharge.md) | The recurring price charged to run this reserved DB instance. |  [optional] |
|**reservedDBInstanceArn** | **String** | The Amazon Resource Name (ARN) for the reserved DB instance. |  [optional] |
|**leaseId** | **String** | &lt;p&gt;The unique identifier for the lease associated with the reserved DB instance.&lt;/p&gt; &lt;note&gt; &lt;p&gt;Amazon Web Services Support might request the lease ID for an issue related to a reserved DB instance.&lt;/p&gt; &lt;/note&gt; |  [optional] |



