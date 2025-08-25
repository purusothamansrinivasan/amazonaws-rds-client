

# BlueGreenDeployment

<p>Details about a blue/green deployment.</p> <p>For more information, see <a href=\"https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/blue-green-deployments.html\">Using Amazon RDS Blue/Green Deployments for database updates</a> in the <i>Amazon RDS User Guide</i> and <a href=\"https://docs.aws.amazon.com/AmazonRDS/latest/AuroraUserGuide/blue-green-deployments.html\">Using Amazon RDS Blue/Green Deployments for database updates</a> in the <i>Amazon Aurora User Guide</i>.</p>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**blueGreenDeploymentIdentifier** | **String** | The unique identifier of the blue/green deployment. |  [optional] |
|**blueGreenDeploymentName** | **String** | The user-supplied name of the blue/green deployment. |  [optional] |
|**source** | **String** | &lt;p&gt;The source database for the blue/green deployment.&lt;/p&gt; &lt;p&gt;Before switchover, the source database is the production database in the blue environment.&lt;/p&gt; |  [optional] |
|**target** | **String** | &lt;p&gt;The target database for the blue/green deployment.&lt;/p&gt; &lt;p&gt;Before switchover, the target database is the clone database in the green environment.&lt;/p&gt; |  [optional] |
|**switchoverDetails** | [**List&lt;SwitchoverDetail&gt;**](SwitchoverDetail.md) | The details about each source and target resource in the blue/green deployment. |  [optional] |
|**tasks** | [**List&lt;BlueGreenDeploymentTask&gt;**](BlueGreenDeploymentTask.md) | Either tasks to be performed or tasks that have been completed on the target database before switchover. |  [optional] |
|**status** | **String** | &lt;p&gt;The status of the blue/green deployment.&lt;/p&gt; &lt;p&gt;Valid Values:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;PROVISIONING&lt;/code&gt; - Resources are being created in the green environment.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;AVAILABLE&lt;/code&gt; - Resources are available in the green environment.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;SWITCHOVER_IN_PROGRESS&lt;/code&gt; - The deployment is being switched from the blue environment to the green environment.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;SWITCHOVER_COMPLETED&lt;/code&gt; - Switchover from the blue environment to the green environment is complete.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;INVALID_CONFIGURATION&lt;/code&gt; - Resources in the green environment are invalid, so switchover isn&#39;t possible.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;SWITCHOVER_FAILED&lt;/code&gt; - Switchover was attempted but failed.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;DELETING&lt;/code&gt; - The blue/green deployment is being deleted.&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; |  [optional] |
|**statusDetails** | **String** | Additional information about the status of the blue/green deployment. |  [optional] |
|**createTime** | **OffsetDateTime** | The time when the blue/green deployment was created, in Universal Coordinated Time (UTC). |  [optional] |
|**deleteTime** | **OffsetDateTime** | The time when the blue/green deployment was deleted, in Universal Coordinated Time (UTC). |  [optional] |
|**tagList** | [**List&lt;Tag&gt;**](Tag.md) | A list of tags. For more information, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/USER_Tagging.html\&quot;&gt;Tagging Amazon RDS Resources&lt;/a&gt; in the &lt;i&gt;Amazon RDS User Guide.&lt;/i&gt;  |  [optional] |



