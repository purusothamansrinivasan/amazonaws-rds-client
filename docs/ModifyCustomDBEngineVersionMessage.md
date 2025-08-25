

# ModifyCustomDBEngineVersionMessage


## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**engine** | **String** | The DB engine. The only supported values are &lt;code&gt;custom-oracle-ee&lt;/code&gt; and &lt;code&gt;custom-oracle-ee-cdb&lt;/code&gt;. |  |
|**engineVersion** | **String** | The custom engine version (CEV) that you want to modify. This option is required for RDS Custom for Oracle, but optional for Amazon RDS. The combination of &lt;code&gt;Engine&lt;/code&gt; and &lt;code&gt;EngineVersion&lt;/code&gt; is unique per customer per Amazon Web Services Region. |  |
|**description** | **String** | An optional description of your CEV. |  [optional] |
|**status** | **CustomEngineVersionStatus** | &lt;p&gt;The availability status to be assigned to the CEV. Valid values are as follows:&lt;/p&gt; &lt;dl&gt; &lt;dt&gt;available&lt;/dt&gt; &lt;dd&gt; &lt;p&gt;You can use this CEV to create a new RDS Custom DB instance.&lt;/p&gt; &lt;/dd&gt; &lt;dt&gt;inactive&lt;/dt&gt; &lt;dd&gt; &lt;p&gt;You can create a new RDS Custom instance by restoring a DB snapshot with this CEV. You can&#39;t patch or create new instances with this CEV.&lt;/p&gt; &lt;/dd&gt; &lt;/dl&gt; &lt;p&gt;You can change any status to any status. A typical reason to change status is to prevent the accidental use of a CEV, or to make a deprecated CEV eligible for use again. For example, you might change the status of your CEV from &lt;code&gt;available&lt;/code&gt; to &lt;code&gt;inactive&lt;/code&gt;, and from &lt;code&gt;inactive&lt;/code&gt; back to &lt;code&gt;available&lt;/code&gt;. To change the availability status of the CEV, it must not currently be in use by an RDS Custom instance, snapshot, or automated backup.&lt;/p&gt; |  [optional] |



