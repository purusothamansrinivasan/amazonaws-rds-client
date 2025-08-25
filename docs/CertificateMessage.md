

# CertificateMessage

Data returned by the <b>DescribeCertificates</b> action.

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**certificates** | [**List&lt;Certificate&gt;**](Certificate.md) | The list of &lt;code&gt;Certificate&lt;/code&gt; objects for the Amazon Web Services account. |  [optional] |
|**marker** | **String** | An optional pagination token provided by a previous &lt;code&gt;DescribeCertificates&lt;/code&gt; request. If this parameter is specified, the response includes only records beyond the marker, up to the value specified by &lt;code&gt;MaxRecords&lt;/code&gt; . |  [optional] |



