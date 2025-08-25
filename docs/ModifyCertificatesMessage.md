

# ModifyCertificatesMessage


## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**certificateIdentifier** | **String** | &lt;p&gt;The new default certificate identifier to override the current one with.&lt;/p&gt; &lt;p&gt;To determine the valid values, use the &lt;code&gt;describe-certificates&lt;/code&gt; CLI command or the &lt;code&gt;DescribeCertificates&lt;/code&gt; API operation.&lt;/p&gt; |  [optional] |
|**removeCustomerOverride** | **Boolean** | A value that indicates whether to remove the override for the default certificate. If the override is removed, the default certificate is the system default. |  [optional] |



