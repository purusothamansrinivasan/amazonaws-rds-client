

# BlueGreenDeploymentTask

<p>Details about a task for a blue/green deployment.</p> <p>For more information, see <a href=\"https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/blue-green-deployments.html\">Using Amazon RDS Blue/Green Deployments for database updates</a> in the <i>Amazon RDS User Guide</i> and <a href=\"https://docs.aws.amazon.com/AmazonRDS/latest/AuroraUserGuide/blue-green-deployments.html\">Using Amazon RDS Blue/Green Deployments for database updates</a> in the <i>Amazon Aurora User Guide</i>.</p>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**name** | **String** | The name of the blue/green deployment task. |  [optional] |
|**status** | **String** | &lt;p&gt;The status of the blue/green deployment task.&lt;/p&gt; &lt;p&gt;Valid Values:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;PENDING&lt;/code&gt; - The resource is being prepared for deployment.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;IN_PROGRESS&lt;/code&gt; - The resource is being deployed.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;COMPLETED&lt;/code&gt; - The resource has been deployed.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;FAILED&lt;/code&gt; - Deployment of the resource failed.&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; |  [optional] |



