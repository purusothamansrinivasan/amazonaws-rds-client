

# CertificateDetails

<p>Returns the details of the DB instance’s server certificate.</p> <p>For more information, see <a href=\"https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/UsingWithRDS.SSL.html\">Using SSL/TLS to encrypt a connection to a DB instance</a> in the <i>Amazon RDS User Guide</i> and <a href=\"https://docs.aws.amazon.com/AmazonRDS/latest/AuroraUserGuide/UsingWithRDS.SSL.html\"> Using SSL/TLS to encrypt a connection to a DB cluster</a> in the <i>Amazon Aurora User Guide</i>.</p>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**caIdentifier** | **String** | The CA identifier of the CA certificate used for the DB instance&#39;s server certificate. |  [optional] |
|**validTill** | **OffsetDateTime** | The expiration date of the DB instance’s server certificate. |  [optional] |



