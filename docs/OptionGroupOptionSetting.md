

# OptionGroupOptionSetting

Option group option settings are used to display settings available for each option with their default values and other information. These values are used with the DescribeOptionGroupOptions action.

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**settingName** | **String** | The name of the option group option. |  [optional] |
|**settingDescription** | **String** | The description of the option group option. |  [optional] |
|**defaultValue** | **String** | The default value for the option group option. |  [optional] |
|**applyType** | **String** | The DB engine specific parameter type for the option group option. |  [optional] |
|**allowedValues** | **String** | Indicates the acceptable values for the option group option. |  [optional] |
|**isModifiable** | **Boolean** | Boolean value where true indicates that this option group option can be changed from the default value. |  [optional] |
|**isRequired** | **Boolean** | Boolean value where true indicates that a value must be specified for this option setting of the option group option. |  [optional] |
|**minimumEngineVersionPerAllowedValue** | [**List&lt;MinimumEngineVersionPerAllowedValue&gt;**](MinimumEngineVersionPerAllowedValue.md) | The minimum DB engine version required for the corresponding allowed value for this option setting. |  [optional] |



