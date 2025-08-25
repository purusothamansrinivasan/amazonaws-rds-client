

# ReservedDBInstancesOffering

This data type is used as a response element in the <code>DescribeReservedDBInstancesOfferings</code> action.

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**reservedDBInstancesOfferingId** | **String** | The offering identifier. |  [optional] |
|**dbInstanceClass** | **String** | The DB instance class for the reserved DB instance. |  [optional] |
|**duration** | **Integer** | The duration of the offering in seconds. |  [optional] |
|**fixedPrice** | **Double** | The fixed price charged for this offering. |  [optional] |
|**usagePrice** | **Double** | The hourly price charged for this offering. |  [optional] |
|**currencyCode** | **String** | The currency code for the reserved DB instance offering. |  [optional] |
|**productDescription** | **String** | The database engine used by the offering. |  [optional] |
|**offeringType** | **String** | The offering type. |  [optional] |
|**multiAZ** | **Boolean** | Indicates if the offering applies to Multi-AZ deployments. |  [optional] |
|**recurringCharges** | [**List&lt;RecurringCharge&gt;**](RecurringCharge.md) | The recurring price charged to run this reserved DB instance. |  [optional] |



