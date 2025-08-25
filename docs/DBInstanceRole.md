

# DBInstanceRole

Describes an Amazon Web Services Identity and Access Management (IAM) role that is associated with a DB instance.

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**roleArn** | **String** | The Amazon Resource Name (ARN) of the IAM role that is associated with the DB instance. |  [optional] |
|**featureName** | **String** | The name of the feature associated with the Amazon Web Services Identity and Access Management (IAM) role. For information about supported feature names, see &lt;code&gt;DBEngineVersion&lt;/code&gt;. |  [optional] |
|**status** | **String** | &lt;p&gt;Describes the state of association between the IAM role and the DB instance. The Status property returns one of the following values:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;ACTIVE&lt;/code&gt; - the IAM role ARN is associated with the DB instance and can be used to access other Amazon Web Services services on your behalf.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;PENDING&lt;/code&gt; - the IAM role ARN is being associated with the DB instance.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;INVALID&lt;/code&gt; - the IAM role ARN is associated with the DB instance, but the DB instance is unable to assume the IAM role in order to access other Amazon Web Services services on your behalf.&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; |  [optional] |



