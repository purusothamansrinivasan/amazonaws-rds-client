

# CreateOptionGroupMessage

<p/>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**optionGroupName** | **String** | &lt;p&gt;Specifies the name of the option group to be created.&lt;/p&gt; &lt;p&gt;Constraints:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt;Must be 1 to 255 letters, numbers, or hyphens&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt;First character must be a letter&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt;Can&#39;t end with a hyphen or contain two consecutive hyphens&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; &lt;p&gt;Example: &lt;code&gt;myoptiongroup&lt;/code&gt; &lt;/p&gt; |  |
|**engineName** | **String** | &lt;p&gt;Specifies the name of the engine that this option group should be associated with.&lt;/p&gt; &lt;p&gt;Valid Values:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;mariadb&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;mysql&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;oracle-ee&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;oracle-ee-cdb&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;oracle-se2&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;oracle-se2-cdb&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;postgres&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;sqlserver-ee&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;sqlserver-se&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;sqlserver-ex&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;sqlserver-web&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; |  |
|**majorEngineVersion** | **String** | Specifies the major version of the engine that this option group should be associated with. |  |
|**optionGroupDescription** | **String** | The description of the option group. |  |
|**tags** | [**List&lt;Tag&gt;**](Tag.md) | Tags to assign to the option group. |  [optional] |



