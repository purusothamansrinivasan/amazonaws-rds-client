

# OptionSetting

Option settings are the actual settings being applied or configured for that option. It is used when you modify an option group or describe option groups. For example, the NATIVE_NETWORK_ENCRYPTION option has a setting called SQLNET.ENCRYPTION_SERVER that can have several different values.

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**name** | **String** | The name of the option that has settings that you can set. |  [optional] |
|**value** | **String** | The current value of the option setting. |  [optional] |
|**defaultValue** | **String** | The default value of the option setting. |  [optional] |
|**description** | **String** | The description of the option setting. |  [optional] |
|**applyType** | **String** | The DB engine specific parameter type. |  [optional] |
|**dataType** | **String** | The data type of the option setting. |  [optional] |
|**allowedValues** | **String** | The allowed values of the option setting. |  [optional] |
|**isModifiable** | **Boolean** | A Boolean value that, when true, indicates the option setting can be modified from the default. |  [optional] |
|**isCollection** | **Boolean** | Indicates if the option setting is part of a collection. |  [optional] |



