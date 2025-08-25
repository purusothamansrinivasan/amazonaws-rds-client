

# EventSubscriptionsMessage

Data returned by the <b>DescribeEventSubscriptions</b> action.

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**marker** | **String** | An optional pagination token provided by a previous DescribeOrderableDBInstanceOptions request. If this parameter is specified, the response includes only records beyond the marker, up to the value specified by &lt;code&gt;MaxRecords&lt;/code&gt;. |  [optional] |
|**eventSubscriptionsList** | [**List&lt;EventSubscription&gt;**](EventSubscription.md) | A list of EventSubscriptions data types. |  [optional] |



