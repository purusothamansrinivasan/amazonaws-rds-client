

# ModifyDBClusterEndpointMessage


## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**dbClusterEndpointIdentifier** | **String** | The identifier of the endpoint to modify. This parameter is stored as a lowercase string. |  |
|**endpointType** | **String** | The type of the endpoint. One of: &lt;code&gt;READER&lt;/code&gt;, &lt;code&gt;WRITER&lt;/code&gt;, &lt;code&gt;ANY&lt;/code&gt;. |  [optional] |
|**staticMembers** | **List&lt;String&gt;** | List of DB instance identifiers that are part of the custom endpoint group. |  [optional] |
|**excludedMembers** | **List&lt;String&gt;** | List of DB instance identifiers that aren&#39;t part of the custom endpoint group. All other eligible instances are reachable through the custom endpoint. Only relevant if the list of static members is empty. |  [optional] |



