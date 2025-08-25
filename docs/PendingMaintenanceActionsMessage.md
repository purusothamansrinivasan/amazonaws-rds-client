

# PendingMaintenanceActionsMessage

Data returned from the <b>DescribePendingMaintenanceActions</b> action.

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**pendingMaintenanceActions** | [**List&lt;ResourcePendingMaintenanceActions&gt;**](ResourcePendingMaintenanceActions.md) | A list of the pending maintenance actions for the resource. |  [optional] |
|**marker** | **String** | An optional pagination token provided by a previous &lt;code&gt;DescribePendingMaintenanceActions&lt;/code&gt; request. If this parameter is specified, the response includes only records beyond the marker, up to a number of records specified by &lt;code&gt;MaxRecords&lt;/code&gt;. |  [optional] |



