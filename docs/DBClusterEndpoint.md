

# DBClusterEndpoint

<p>This data type represents the information you need to connect to an Amazon Aurora DB cluster. This data type is used as a response element in the following actions:</p> <ul> <li> <p> <code>CreateDBClusterEndpoint</code> </p> </li> <li> <p> <code>DescribeDBClusterEndpoints</code> </p> </li> <li> <p> <code>ModifyDBClusterEndpoint</code> </p> </li> <li> <p> <code>DeleteDBClusterEndpoint</code> </p> </li> </ul> <p>For the data structure that represents Amazon RDS DB instance endpoints, see <code>Endpoint</code>.</p>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**dbClusterEndpointIdentifier** | **String** | The identifier associated with the endpoint. This parameter is stored as a lowercase string. |  [optional] |
|**dbClusterIdentifier** | **String** | The DB cluster identifier of the DB cluster associated with the endpoint. This parameter is stored as a lowercase string. |  [optional] |
|**dbClusterEndpointResourceIdentifier** | **String** | A unique system-generated identifier for an endpoint. It remains the same for the whole life of the endpoint. |  [optional] |
|**endpoint** | **String** | The DNS address of the endpoint. |  [optional] |
|**status** | **String** | The current status of the endpoint. One of: &lt;code&gt;creating&lt;/code&gt;, &lt;code&gt;available&lt;/code&gt;, &lt;code&gt;deleting&lt;/code&gt;, &lt;code&gt;inactive&lt;/code&gt;, &lt;code&gt;modifying&lt;/code&gt;. The &lt;code&gt;inactive&lt;/code&gt; state applies to an endpoint that can&#39;t be used for a certain kind of cluster, such as a &lt;code&gt;writer&lt;/code&gt; endpoint for a read-only secondary cluster in a global database. |  [optional] |
|**endpointType** | **String** | The type of the endpoint. One of: &lt;code&gt;READER&lt;/code&gt;, &lt;code&gt;WRITER&lt;/code&gt;, &lt;code&gt;CUSTOM&lt;/code&gt;. |  [optional] |
|**customEndpointType** | **String** | The type associated with a custom endpoint. One of: &lt;code&gt;READER&lt;/code&gt;, &lt;code&gt;WRITER&lt;/code&gt;, &lt;code&gt;ANY&lt;/code&gt;. |  [optional] |
|**staticMembers** | **List&lt;String&gt;** | List of DB instance identifiers that are part of the custom endpoint group. |  [optional] |
|**excludedMembers** | **List&lt;String&gt;** | List of DB instance identifiers that aren&#39;t part of the custom endpoint group. All other eligible instances are reachable through the custom endpoint. Only relevant if the list of static members is empty. |  [optional] |
|**dbClusterEndpointArn** | **String** | The Amazon Resource Name (ARN) for the endpoint. |  [optional] |



