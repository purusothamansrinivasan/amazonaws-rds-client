

# OptionGroupOption

Available option.

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**name** | **String** | The name of the option. |  [optional] |
|**description** | **String** | The description of the option. |  [optional] |
|**engineName** | **String** | The name of the engine that this option can be applied to. |  [optional] |
|**majorEngineVersion** | **String** | Indicates the major engine version that the option is available for. |  [optional] |
|**minimumRequiredMinorEngineVersion** | **String** | The minimum required engine version for the option to be applied. |  [optional] |
|**portRequired** | **Boolean** | Specifies whether the option requires a port. |  [optional] |
|**defaultPort** | **Integer** | If the option requires a port, specifies the default port for the option. |  [optional] |
|**optionsDependedOn** | **List&lt;String&gt;** | The options that are prerequisites for this option. |  [optional] |
|**optionsConflictsWith** | **List&lt;String&gt;** | The options that conflict with this option. |  [optional] |
|**persistent** | **Boolean** | Persistent options can&#39;t be removed from an option group while DB instances are associated with the option group. If you disassociate all DB instances from the option group, your can remove the persistent option from the option group. |  [optional] |
|**permanent** | **Boolean** | Permanent options can never be removed from an option group. An option group containing a permanent option can&#39;t be removed from a DB instance. |  [optional] |
|**requiresAutoMinorEngineVersionUpgrade** | **Boolean** | If true, you must enable the Auto Minor Version Upgrade setting for your DB instance before you can use this option. You can enable Auto Minor Version Upgrade when you first create your DB instance, or by modifying your DB instance later. |  [optional] |
|**vpcOnly** | **Boolean** | If true, you can only use this option with a DB instance that is in a VPC. |  [optional] |
|**supportsOptionVersionDowngrade** | **Boolean** | If true, you can change the option to an earlier version of the option. This only applies to options that have different versions available. |  [optional] |
|**optionGroupOptionSettings** | [**List&lt;OptionGroupOptionSetting&gt;**](OptionGroupOptionSetting.md) | The option settings that are available (and the default value) for each option in an option group. |  [optional] |
|**optionGroupOptionVersions** | [**List&lt;OptionVersion&gt;**](OptionVersion.md) | The versions that are available for the option. |  [optional] |
|**copyableCrossAccount** | **Boolean** | Specifies whether the option can be copied across Amazon Web Services accounts. |  [optional] |



