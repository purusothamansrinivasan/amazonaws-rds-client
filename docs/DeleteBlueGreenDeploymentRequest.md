

# DeleteBlueGreenDeploymentRequest


## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**blueGreenDeploymentIdentifier** | **String** | &lt;p&gt;The unique identifier of the blue/green deployment to delete. This parameter isn&#39;t case-sensitive.&lt;/p&gt; &lt;p&gt;Constraints: &lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt;Must match an existing blue/green deployment identifier.&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; |  |
|**deleteTarget** | **Boolean** | Specifies whether to delete the resources in the green environment. You can&#39;t specify this option if the blue/green deployment &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/AmazonRDS/latest/APIReference/API_BlueGreenDeployment.html\&quot;&gt;status&lt;/a&gt; is &lt;code&gt;SWITCHOVER_COMPLETED&lt;/code&gt;. |  [optional] |



