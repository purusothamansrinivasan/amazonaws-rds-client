

# RemoveRoleFromDBInstanceMessage


## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**dbInstanceIdentifier** | **String** | The name of the DB instance to disassociate the IAM role from. |  |
|**roleArn** | **String** | The Amazon Resource Name (ARN) of the IAM role to disassociate from the DB instance, for example, &lt;code&gt;arn:aws:iam::123456789012:role/AccessRole&lt;/code&gt;. |  |
|**featureName** | **String** | The name of the feature for the DB instance that the IAM role is to be disassociated from. For information about supported feature names, see &lt;code&gt;DBEngineVersion&lt;/code&gt;. |  |



