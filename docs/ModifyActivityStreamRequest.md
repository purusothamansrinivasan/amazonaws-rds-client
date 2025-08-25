

# ModifyActivityStreamRequest


## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**resourceArn** | **String** | The Amazon Resource Name (ARN) of the RDS for Oracle or Microsoft SQL Server DB instance. For example, &lt;code&gt;arn:aws:rds:us-east-1:12345667890:instance:my-orcl-db&lt;/code&gt;. |  [optional] |
|**auditPolicyState** | **AuditPolicyState** | The audit policy state. When a policy is unlocked, it is read/write. When it is locked, it is read-only. You can edit your audit policy only when the activity stream is unlocked or stopped. |  [optional] |



