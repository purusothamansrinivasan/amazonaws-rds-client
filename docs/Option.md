

# Option

Option details.

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**optionName** | **String** | The name of the option. |  [optional] |
|**optionDescription** | **String** | The description of the option. |  [optional] |
|**persistent** | **Boolean** | Indicate if this option is persistent. |  [optional] |
|**permanent** | **Boolean** | Indicate if this option is permanent. |  [optional] |
|**port** | **Integer** | If required, the port configured for this option to use. |  [optional] |
|**optionVersion** | **String** | The version of the option. |  [optional] |
|**optionSettings** | [**List&lt;OptionSetting&gt;**](OptionSetting.md) | The option settings for this option. |  [optional] |
|**dbSecurityGroupMemberships** | [**List&lt;DBSecurityGroupMembership&gt;**](DBSecurityGroupMembership.md) | If the option requires access to a port, then this DB security group allows access to the port. |  [optional] |
|**vpcSecurityGroupMemberships** | [**List&lt;VpcSecurityGroupMembership&gt;**](VpcSecurityGroupMembership.md) | If the option requires access to a port, then this VPC security group allows access to the port. |  [optional] |



