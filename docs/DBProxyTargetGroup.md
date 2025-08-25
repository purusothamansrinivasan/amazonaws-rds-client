

# DBProxyTargetGroup

<p>Represents a set of RDS DB instances, Aurora DB clusters, or both that a proxy can connect to. Currently, each target group is associated with exactly one RDS DB instance or Aurora DB cluster.</p> <p>This data type is used as a response element in the <code>DescribeDBProxyTargetGroups</code> action.</p>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**dbProxyName** | **String** | The identifier for the RDS proxy associated with this target group. |  [optional] |
|**targetGroupName** | **String** | The identifier for the target group. This name must be unique for all target groups owned by your Amazon Web Services account in the specified Amazon Web Services Region. |  [optional] |
|**targetGroupArn** | **String** | The Amazon Resource Name (ARN) representing the target group. |  [optional] |
|**isDefault** | **Boolean** | Whether this target group is the first one used for connection requests by the associated proxy. Because each proxy is currently associated with a single target group, currently this setting is always &lt;code&gt;true&lt;/code&gt;. |  [optional] |
|**status** | **String** | The current status of this target group. A status of &lt;code&gt;available&lt;/code&gt; means the target group is correctly associated with a database. Other values indicate that you must wait for the target group to be ready, or take some action to resolve an issue. |  [optional] |
|**connectionPoolConfig** | [**ConnectionPoolConfigurationInfo**](ConnectionPoolConfigurationInfo.md) | The settings that determine the size and behavior of the connection pool for the target group. |  [optional] |
|**createdDate** | **OffsetDateTime** | The date and time when the target group was first created. |  [optional] |
|**updatedDate** | **OffsetDateTime** | The date and time when the target group was last updated. |  [optional] |



