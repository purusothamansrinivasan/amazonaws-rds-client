

# SwitchoverDetail

<p>Contains the details about a blue/green deployment.</p> <p>For more information, see <a href=\"https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/blue-green-deployments.html\">Using Amazon RDS Blue/Green Deployments for database updates</a> in the <i>Amazon RDS User Guide</i> and <a href=\"https://docs.aws.amazon.com/AmazonRDS/latest/AuroraUserGuide/blue-green-deployments.html\">Using Amazon RDS Blue/Green Deployments for database updates</a> in the <i>Amazon Aurora User Guide</i>.</p>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**sourceMember** | **String** | The Amazon Resource Name (ARN) of a resource in the blue environment. |  [optional] |
|**targetMember** | **String** | The Amazon Resource Name (ARN) of a resource in the green environment. |  [optional] |
|**status** | **String** | &lt;p&gt;The switchover status of a resource in a blue/green deployment.&lt;/p&gt; &lt;p&gt;Values:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;PROVISIONING&lt;/code&gt; - The resource is being prepared to switch over.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;AVAILABLE&lt;/code&gt; - The resource is ready to switch over.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;SWITCHOVER_IN_PROGRESS&lt;/code&gt; - The resource is being switched over.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;SWITCHOVER_COMPLETED&lt;/code&gt; - The resource has been switched over.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;SWITCHOVER_FAILED&lt;/code&gt; - The resource attempted to switch over but failed.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;MISSING_SOURCE&lt;/code&gt; - The source resource has been deleted.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;MISSING_TARGET&lt;/code&gt; - The target resource has been deleted.&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; |  [optional] |



