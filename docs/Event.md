

# Event

This data type is used as a response element in the <a href=\"https://docs.aws.amazon.com/AmazonRDS/latest/APIReference/API_DescribeEvents.html\">DescribeEvents</a> action.

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**sourceIdentifier** | **String** | Provides the identifier for the source of the event. |  [optional] |
|**sourceType** | **SourceType** | Specifies the source type for this event. |  [optional] |
|**message** | **String** | Provides the text of this event. |  [optional] |
|**eventCategories** | **List&lt;String&gt;** | Specifies the category for the event. |  [optional] |
|**date** | **OffsetDateTime** | Specifies the date and time of the event. |  [optional] |
|**sourceArn** | **String** | The Amazon Resource Name (ARN) for the event. |  [optional] |



