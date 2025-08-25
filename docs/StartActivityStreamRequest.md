

# StartActivityStreamRequest


## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**resourceArn** | **String** | The Amazon Resource Name (ARN) of the DB cluster, for example, &lt;code&gt;arn:aws:rds:us-east-1:12345667890:cluster:das-cluster&lt;/code&gt;. |  |
|**mode** | **ActivityStreamMode** | Specifies the mode of the database activity stream. Database events such as a change or access generate an activity stream event. The database session can handle these events either synchronously or asynchronously. |  |
|**kmsKeyId** | **String** | The Amazon Web Services KMS key identifier for encrypting messages in the database activity stream. The Amazon Web Services KMS key identifier is the key ARN, key ID, alias ARN, or alias name for the KMS key. |  |
|**applyImmediately** | **Boolean** | Specifies whether or not the database activity stream is to start as soon as possible, regardless of the maintenance window for the database. |  [optional] |
|**engineNativeAuditFieldsIncluded** | **Boolean** | Specifies whether the database activity stream includes engine-native audit fields. This option applies to an Oracle or Microsoft SQL Server DB instance. By default, no engine-native audit fields are included. |  [optional] |



