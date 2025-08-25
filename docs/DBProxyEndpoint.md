

# DBProxyEndpoint

<p>The data structure representing an endpoint associated with a DB proxy. RDS automatically creates one endpoint for each DB proxy. For Aurora DB clusters, you can associate additional endpoints with the same DB proxy. These endpoints can be read/write or read-only. They can also reside in different VPCs than the associated DB proxy.</p> <p>This data type is used as a response element in the <code>DescribeDBProxyEndpoints</code> operation.</p>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**dbProxyEndpointName** | **String** | The name for the DB proxy endpoint. An identifier must begin with a letter and must contain only ASCII letters, digits, and hyphens; it can&#39;t end with a hyphen or contain two consecutive hyphens. |  [optional] |
|**dbProxyEndpointArn** | **String** | The Amazon Resource Name (ARN) for the DB proxy endpoint. |  [optional] |
|**dbProxyName** | **String** | The identifier for the DB proxy that is associated with this DB proxy endpoint. |  [optional] |
|**status** | **DBProxyEndpointStatus** | The current status of this DB proxy endpoint. A status of &lt;code&gt;available&lt;/code&gt; means the endpoint is ready to handle requests. Other values indicate that you must wait for the endpoint to be ready, or take some action to resolve an issue. |  [optional] |
|**vpcId** | **String** | Provides the VPC ID of the DB proxy endpoint. |  [optional] |
|**vpcSecurityGroupIds** | **List&lt;String&gt;** | Provides a list of VPC security groups that the DB proxy endpoint belongs to. |  [optional] |
|**vpcSubnetIds** | **List&lt;String&gt;** | The EC2 subnet IDs for the DB proxy endpoint. |  [optional] |
|**endpoint** | **String** | The endpoint that you can use to connect to the DB proxy. You include the endpoint value in the connection string for a database client application. |  [optional] |
|**createdDate** | **OffsetDateTime** | The date and time when the DB proxy endpoint was first created. |  [optional] |
|**targetRole** | **DBProxyEndpointTargetRole** | A value that indicates whether the DB proxy endpoint can be used for read/write or read-only operations. |  [optional] |
|**isDefault** | **Boolean** | A value that indicates whether this endpoint is the default endpoint for the associated DB proxy. Default DB proxy endpoints always have read/write capability. Other endpoints that you associate with the DB proxy can be either read/write or read-only. |  [optional] |



