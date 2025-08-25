

# SwitchoverBlueGreenDeploymentRequest


## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**blueGreenDeploymentIdentifier** | **String** | &lt;p&gt;The unique identifier of the blue/green deployment.&lt;/p&gt; &lt;p&gt;Constraints:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt;Must match an existing blue/green deployment identifier.&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; |  |
|**switchoverTimeout** | **Integer** | &lt;p&gt;The amount of time, in seconds, for the switchover to complete.&lt;/p&gt; &lt;p&gt;Default: 300&lt;/p&gt; &lt;p&gt;If the switchover takes longer than the specified duration, then any changes are rolled back, and no changes are made to the environments.&lt;/p&gt; |  [optional] |



