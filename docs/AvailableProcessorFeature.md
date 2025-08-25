

# AvailableProcessorFeature

<p>Contains the available processor feature information for the DB instance class of a DB instance.</p> <p>For more information, see <a href=\"https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/Concepts.DBInstanceClass.html#USER_ConfigureProcessor\">Configuring the Processor of the DB Instance Class</a> in the <i>Amazon RDS User Guide. </i> </p>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**name** | **String** | The name of the processor feature. Valid names are &lt;code&gt;coreCount&lt;/code&gt; and &lt;code&gt;threadsPerCore&lt;/code&gt;. |  [optional] |
|**defaultValue** | **String** | The default value for the processor feature of the DB instance class. |  [optional] |
|**allowedValues** | **String** | The allowed values for the processor feature of the DB instance class. |  [optional] |



