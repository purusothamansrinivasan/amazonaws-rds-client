

# AddRoleToDBClusterMessage


## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**dbClusterIdentifier** | **String** | The name of the DB cluster to associate the IAM role with. |  |
|**roleArn** | **String** | The Amazon Resource Name (ARN) of the IAM role to associate with the Aurora DB cluster, for example &lt;code&gt;arn:aws:iam::123456789012:role/AuroraAccessRole&lt;/code&gt;. |  |
|**featureName** | **String** | The name of the feature for the DB cluster that the IAM role is to be associated with. For information about supported feature names, see &lt;a&gt;DBEngineVersion&lt;/a&gt;. |  [optional] |



