

# DBProxyTarget

<p>Contains the details for an RDS Proxy target. It represents an RDS DB instance or Aurora DB cluster that the proxy can connect to. One or more targets are associated with an RDS Proxy target group.</p> <p>This data type is used as a response element in the <code>DescribeDBProxyTargets</code> action.</p>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**targetArn** | **String** | The Amazon Resource Name (ARN) for the RDS DB instance or Aurora DB cluster. |  [optional] |
|**endpoint** | **String** | The writer endpoint for the RDS DB instance or Aurora DB cluster. |  [optional] |
|**trackedClusterId** | **String** | The DB cluster identifier when the target represents an Aurora DB cluster. This field is blank when the target represents an RDS DB instance. |  [optional] |
|**rdsResourceId** | **String** | The identifier representing the target. It can be the instance identifier for an RDS DB instance, or the cluster identifier for an Aurora DB cluster. |  [optional] |
|**port** | **Integer** | The port that the RDS Proxy uses to connect to the target RDS DB instance or Aurora DB cluster. |  [optional] |
|**type** | **TargetType** | Specifies the kind of database, such as an RDS DB instance or an Aurora DB cluster, that the target represents. |  [optional] |
|**role** | **TargetRole** | A value that indicates whether the target of the proxy can be used for read/write or read-only operations. |  [optional] |
|**targetHealth** | [**TargetHealth**](TargetHealth.md) | Information about the connection health of the RDS Proxy target. |  [optional] |



