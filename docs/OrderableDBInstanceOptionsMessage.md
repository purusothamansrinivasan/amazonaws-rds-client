

# OrderableDBInstanceOptionsMessage

Contains the result of a successful invocation of the <code>DescribeOrderableDBInstanceOptions</code> action.

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**orderableDBInstanceOptions** | [**List&lt;OrderableDBInstanceOption&gt;**](OrderableDBInstanceOption.md) | An &lt;code&gt;OrderableDBInstanceOption&lt;/code&gt; structure containing information about orderable options for the DB instance. |  [optional] |
|**marker** | **String** | An optional pagination token provided by a previous OrderableDBInstanceOptions request. If this parameter is specified, the response includes only records beyond the marker, up to the value specified by &lt;code&gt;MaxRecords&lt;/code&gt;. |  [optional] |



