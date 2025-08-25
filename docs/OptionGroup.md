

# OptionGroup

<p/>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**optionGroupName** | **String** | Specifies the name of the option group. |  [optional] |
|**optionGroupDescription** | **String** | Provides a description of the option group. |  [optional] |
|**engineName** | **String** | Indicates the name of the engine that this option group can be applied to. |  [optional] |
|**majorEngineVersion** | **String** | Indicates the major engine version associated with this option group. |  [optional] |
|**options** | [**List&lt;Option&gt;**](Option.md) | Indicates what options are available in the option group. |  [optional] |
|**allowsVpcAndNonVpcInstanceMemberships** | **Boolean** | Indicates whether this option group can be applied to both VPC and non-VPC instances. The value &lt;code&gt;true&lt;/code&gt; indicates the option group can be applied to both VPC and non-VPC instances. |  [optional] |
|**vpcId** | **String** | If &lt;b&gt;AllowsVpcAndNonVpcInstanceMemberships&lt;/b&gt; is &lt;code&gt;false&lt;/code&gt;, this field is blank. If &lt;b&gt;AllowsVpcAndNonVpcInstanceMemberships&lt;/b&gt; is &lt;code&gt;true&lt;/code&gt; and this field is blank, then this option group can be applied to both VPC and non-VPC instances. If this field contains a value, then this option group can only be applied to instances that are in the VPC indicated by this field. |  [optional] |
|**optionGroupArn** | **String** | Specifies the Amazon Resource Name (ARN) for the option group. |  [optional] |
|**sourceOptionGroup** | **String** | Specifies the name of the option group from which this option group is copied. |  [optional] |
|**sourceAccountId** | **String** | Specifies the Amazon Web Services account ID for the option group from which this option group is copied. |  [optional] |
|**copyTimestamp** | **OffsetDateTime** | Indicates when the option group was copied. |  [optional] |



