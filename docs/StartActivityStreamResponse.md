

# StartActivityStreamResponse


## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**kmsKeyId** | **String** | The Amazon Web Services KMS key identifier for encryption of messages in the database activity stream. |  [optional] |
|**kinesisStreamName** | **String** | The name of the Amazon Kinesis data stream to be used for the database activity stream. |  [optional] |
|**status** | **ActivityStreamStatus** | The status of the database activity stream. |  [optional] |
|**mode** | **ActivityStreamMode** | The mode of the database activity stream. |  [optional] |
|**applyImmediately** | **Boolean** | Indicates whether or not the database activity stream will start as soon as possible, regardless of the maintenance window for the database. |  [optional] |
|**engineNativeAuditFieldsIncluded** | **Boolean** | Indicates whether engine-native audit fields are included in the database activity stream. |  [optional] |



