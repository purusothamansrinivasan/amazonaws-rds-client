

# ModifyOptionGroupMessage

<p/>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**optionGroupName** | **String** | &lt;p&gt;The name of the option group to be modified.&lt;/p&gt; &lt;p&gt;Permanent options, such as the TDE option for Oracle Advanced Security TDE, can&#39;t be removed from an option group, and that option group can&#39;t be removed from a DB instance once it is associated with a DB instance&lt;/p&gt; |  |
|**optionsToInclude** | [**List&lt;OptionConfiguration&gt;**](OptionConfiguration.md) | Options in this list are added to the option group or, if already present, the specified configuration is used to update the existing configuration. |  [optional] |
|**optionsToRemove** | **List&lt;String&gt;** | Options in this list are removed from the option group. |  [optional] |
|**applyImmediately** | **Boolean** | A value that indicates whether to apply the change immediately or during the next maintenance window for each instance associated with the option group. |  [optional] |



