

# ModifyActivityStreamResponse


## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**kmsKeyId** | **String** | The Amazon Web Services KMS key identifier for encryption of messages in the database activity stream. |  [optional] |
|**kinesisStreamName** | **String** | The name of the Amazon Kinesis data stream to be used for the database activity stream. |  [optional] |
|**status** | **ActivityStreamStatus** | The status of the modification to the database activity stream. |  [optional] |
|**mode** | **ActivityStreamMode** | The mode of the database activity stream. |  [optional] |
|**engineNativeAuditFieldsIncluded** | **Boolean** | Indicates whether engine-native audit fields are included in the database activity stream. |  [optional] |
|**policyStatus** | **ActivityStreamPolicyStatus** | The status of the modification to the policy state of the database activity stream. |  [optional] |



