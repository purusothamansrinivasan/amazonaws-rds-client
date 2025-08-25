

# EventSubscription

Contains the results of a successful invocation of the <code>DescribeEventSubscriptions</code> action.

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**customerAwsId** | **String** | The Amazon Web Services customer account associated with the RDS event notification subscription. |  [optional] |
|**custSubscriptionId** | **String** | The RDS event notification subscription Id. |  [optional] |
|**snsTopicArn** | **String** | The topic ARN of the RDS event notification subscription. |  [optional] |
|**status** | **String** | &lt;p&gt;The status of the RDS event notification subscription.&lt;/p&gt; &lt;p&gt;Constraints:&lt;/p&gt; &lt;p&gt;Can be one of the following: creating | modifying | deleting | active | no-permission | topic-not-exist&lt;/p&gt; &lt;p&gt;The status \&quot;no-permission\&quot; indicates that RDS no longer has permission to post to the SNS topic. The status \&quot;topic-not-exist\&quot; indicates that the topic was deleted after the subscription was created.&lt;/p&gt; |  [optional] |
|**subscriptionCreationTime** | **String** | The time the RDS event notification subscription was created. |  [optional] |
|**sourceType** | **String** | The source type for the RDS event notification subscription. |  [optional] |
|**sourceIdsList** | **List&lt;String&gt;** | A list of source IDs for the RDS event notification subscription. |  [optional] |
|**eventCategoriesList** | **List&lt;String&gt;** | A list of event categories for the RDS event notification subscription. |  [optional] |
|**enabled** | **Boolean** | A Boolean value indicating if the subscription is enabled. True indicates the subscription is enabled. |  [optional] |
|**eventSubscriptionArn** | **String** | The Amazon Resource Name (ARN) for the event subscription. |  [optional] |



