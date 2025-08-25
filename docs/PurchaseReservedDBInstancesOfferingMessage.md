

# PurchaseReservedDBInstancesOfferingMessage

<p/>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**reservedDBInstancesOfferingId** | **String** | &lt;p&gt;The ID of the Reserved DB instance offering to purchase.&lt;/p&gt; &lt;p&gt;Example: 438012d3-4052-4cc7-b2e3-8d3372e0e706&lt;/p&gt; |  |
|**reservedDBInstanceId** | **String** | &lt;p&gt;Customer-specified identifier to track this reservation.&lt;/p&gt; &lt;p&gt;Example: myreservationID&lt;/p&gt; |  [optional] |
|**dbInstanceCount** | **Integer** | &lt;p&gt;The number of instances to reserve.&lt;/p&gt; &lt;p&gt;Default: &lt;code&gt;1&lt;/code&gt; &lt;/p&gt; |  [optional] |
|**tags** | [**List&lt;Tag&gt;**](Tag.md) | A list of tags. For more information, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/USER_Tagging.html\&quot;&gt;Tagging Amazon RDS Resources&lt;/a&gt; in the &lt;i&gt;Amazon RDS User Guide.&lt;/i&gt;  |  [optional] |



