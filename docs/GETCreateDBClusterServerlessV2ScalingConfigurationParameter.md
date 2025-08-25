

# GETCreateDBClusterServerlessV2ScalingConfigurationParameter

<p>Contains the scaling configuration of an Aurora Serverless v2 DB cluster.</p> <p>For more information, see <a href=\"https://docs.aws.amazon.com/AmazonRDS/latest/AuroraUserGuide/aurora-serverless-v2.html\">Using Amazon Aurora Serverless v2</a> in the <i>Amazon Aurora User Guide</i>.</p>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**minCapacity** | **Double** | The minimum number of Aurora capacity units (ACUs) for a DB instance in an Aurora Serverless v2 cluster. You can specify ACU values in half-step increments, such as 8, 8.5, 9, and so on. The smallest value that you can use is 0.5. |  [optional] |
|**maxCapacity** | **Double** | The maximum number of Aurora capacity units (ACUs) for a DB instance in an Aurora Serverless v2 cluster. You can specify ACU values in half-step increments, such as 40, 40.5, 41, and so on. The largest value that you can use is 128. |  [optional] |



