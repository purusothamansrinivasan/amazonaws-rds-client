

# ValidDBInstanceModificationsMessage

Information about valid modifications that you can make to your DB instance. Contains the result of a successful call to the <code>DescribeValidDBInstanceModifications</code> action. You can use this information when you call <code>ModifyDBInstance</code>.

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**storage** | [**List&lt;ValidStorageOptions&gt;**](ValidStorageOptions.md) | Valid storage options for your DB instance. |  [optional] |
|**validProcessorFeatures** | [**List&lt;AvailableProcessorFeature&gt;**](AvailableProcessorFeature.md) | Valid processor features for your DB instance. |  [optional] |



