

# Certificate

<p>A CA certificate for an Amazon Web Services account.</p> <p>For more information, see <a href=\"https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/UsingWithRDS.SSL.html\">Using SSL/TLS to encrypt a connection to a DB instance</a> in the <i>Amazon RDS User Guide</i> and <a href=\"https://docs.aws.amazon.com/AmazonRDS/latest/AuroraUserGuide/UsingWithRDS.SSL.html\"> Using SSL/TLS to encrypt a connection to a DB cluster</a> in the <i>Amazon Aurora User Guide</i>.</p>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**certificateIdentifier** | **String** | The unique key that identifies a certificate. |  [optional] |
|**certificateType** | **String** | The type of the certificate. |  [optional] |
|**thumbprint** | **String** | The thumbprint of the certificate. |  [optional] |
|**validFrom** | **OffsetDateTime** | The starting date from which the certificate is valid. |  [optional] |
|**validTill** | **OffsetDateTime** | The final date that the certificate continues to be valid. |  [optional] |
|**certificateArn** | **String** | The Amazon Resource Name (ARN) for the certificate. |  [optional] |
|**customerOverride** | **Boolean** | Whether there is an override for the default certificate identifier. |  [optional] |
|**customerOverrideValidTill** | **OffsetDateTime** | If there is an override for the default certificate identifier, when the override expires. |  [optional] |



