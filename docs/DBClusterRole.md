

# DBClusterRole

Describes an Amazon Web Services Identity and Access Management (IAM) role that is associated with a DB cluster.

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**roleArn** | **String** | The Amazon Resource Name (ARN) of the IAM role that is associated with the DB cluster. |  [optional] |
|**status** | **String** | &lt;p&gt;Describes the state of association between the IAM role and the DB cluster. The Status property returns one of the following values:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;ACTIVE&lt;/code&gt; - the IAM role ARN is associated with the DB cluster and can be used to access other Amazon Web Services on your behalf.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;PENDING&lt;/code&gt; - the IAM role ARN is being associated with the DB cluster.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;INVALID&lt;/code&gt; - the IAM role ARN is associated with the DB cluster, but the DB cluster is unable to assume the IAM role in order to access other Amazon Web Services on your behalf.&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; |  [optional] |
|**featureName** | **String** | The name of the feature associated with the Amazon Web Services Identity and Access Management (IAM) role. For information about supported feature names, see &lt;a&gt;DBEngineVersion&lt;/a&gt;. |  [optional] |



