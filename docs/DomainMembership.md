

# DomainMembership

An Active Directory Domain membership record associated with the DB instance or cluster.

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**domain** | **String** | The identifier of the Active Directory Domain. |  [optional] |
|**status** | **String** | The status of the Active Directory Domain membership for the DB instance or cluster. Values include &lt;code&gt;joined&lt;/code&gt;, &lt;code&gt;pending-join&lt;/code&gt;, &lt;code&gt;failed&lt;/code&gt;, and so on. |  [optional] |
|**FQDN** | **String** | The fully qualified domain name (FQDN) of the Active Directory Domain. |  [optional] |
|**iaMRoleName** | **String** | The name of the IAM role used when making API calls to the Directory Service. |  [optional] |
|**OU** | **String** | The Active Directory organizational unit for the DB instance or cluster. |  [optional] |
|**authSecretArn** | **String** | The ARN for the Secrets Manager secret with the credentials for the user that&#39;s a member of the domain. |  [optional] |
|**dnsIps** | **List&lt;String&gt;** | The IPv4 DNS IP addresses of the primary and secondary Active Directory domain controllers. |  [optional] |



