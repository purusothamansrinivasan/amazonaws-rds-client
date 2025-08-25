

# PendingCloudwatchLogsExports

A list of the log types whose configuration is still pending. In other words, these log types are in the process of being activated or deactivated.

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**logTypesToEnable** | **List&lt;String&gt;** | Log types that are in the process of being deactivated. After they are deactivated, these log types aren&#39;t exported to CloudWatch Logs. |  [optional] |
|**logTypesToDisable** | **List&lt;String&gt;** | Log types that are in the process of being enabled. After they are enabled, these log types are exported to CloudWatch Logs. |  [optional] |



