

# CreateDBClusterEndpointMessage


## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**dbClusterIdentifier** | **String** | The DB cluster identifier of the DB cluster associated with the endpoint. This parameter is stored as a lowercase string. |  |
|**dbClusterEndpointIdentifier** | **String** | The identifier to use for the new endpoint. This parameter is stored as a lowercase string. |  |
|**endpointType** | **String** | The type of the endpoint, one of: &lt;code&gt;READER&lt;/code&gt;, &lt;code&gt;WRITER&lt;/code&gt;, &lt;code&gt;ANY&lt;/code&gt;. |  |
|**staticMembers** | **List&lt;String&gt;** | List of DB instance identifiers that are part of the custom endpoint group. |  [optional] |
|**excludedMembers** | **List&lt;String&gt;** | List of DB instance identifiers that aren&#39;t part of the custom endpoint group. All other eligible instances are reachable through the custom endpoint. This parameter is relevant only if the list of static members is empty. |  [optional] |
|**tags** | [**List&lt;Tag&gt;**](Tag.md) | The tags to be assigned to the Amazon RDS resource. |  [optional] |



