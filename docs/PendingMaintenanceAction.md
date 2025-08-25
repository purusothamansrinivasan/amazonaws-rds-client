

# PendingMaintenanceAction

Provides information about a pending maintenance action for a resource.

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**action** | **String** | The type of pending maintenance action that is available for the resource. Valid actions are &lt;code&gt;system-update&lt;/code&gt;, &lt;code&gt;db-upgrade&lt;/code&gt;, &lt;code&gt;hardware-maintenance&lt;/code&gt;, and &lt;code&gt;ca-certificate-rotation&lt;/code&gt;. |  [optional] |
|**autoAppliedAfterDate** | **OffsetDateTime** | The date of the maintenance window when the action is applied. The maintenance action is applied to the resource during its first maintenance window after this date. |  [optional] |
|**forcedApplyDate** | **OffsetDateTime** | &lt;p&gt;The date when the maintenance action is automatically applied.&lt;/p&gt; &lt;p&gt;On this date, the maintenance action is applied to the resource as soon as possible, regardless of the maintenance window for the resource. There might be a delay of one or more days from this date before the maintenance action is applied.&lt;/p&gt; |  [optional] |
|**optInStatus** | **String** | Indicates the type of opt-in request that has been received for the resource. |  [optional] |
|**currentApplyDate** | **OffsetDateTime** | The effective date when the pending maintenance action is applied to the resource. This date takes into account opt-in requests received from the &lt;code&gt;ApplyPendingMaintenanceAction&lt;/code&gt; API, the &lt;code&gt;AutoAppliedAfterDate&lt;/code&gt;, and the &lt;code&gt;ForcedApplyDate&lt;/code&gt;. This value is blank if an opt-in request has not been received and nothing has been specified as &lt;code&gt;AutoAppliedAfterDate&lt;/code&gt; or &lt;code&gt;ForcedApplyDate&lt;/code&gt;. |  [optional] |
|**description** | **String** | A description providing more detail about the maintenance action. |  [optional] |



