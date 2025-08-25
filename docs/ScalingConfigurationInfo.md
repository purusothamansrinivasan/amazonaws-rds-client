

# ScalingConfigurationInfo

<p>The scaling configuration for an Aurora DB cluster in <code>serverless</code> DB engine mode.</p> <p>For more information, see <a href=\"https://docs.aws.amazon.com/AmazonRDS/latest/AuroraUserGuide/aurora-serverless.html\">Using Amazon Aurora Serverless v1</a> in the <i>Amazon Aurora User Guide</i>.</p>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**minCapacity** | **Integer** | The minimum capacity for an Aurora DB cluster in &lt;code&gt;serverless&lt;/code&gt; DB engine mode. |  [optional] |
|**maxCapacity** | **Integer** | The maximum capacity for an Aurora DB cluster in &lt;code&gt;serverless&lt;/code&gt; DB engine mode. |  [optional] |
|**autoPause** | **Boolean** | &lt;p&gt;A value that indicates whether automatic pause is allowed for the Aurora DB cluster in &lt;code&gt;serverless&lt;/code&gt; DB engine mode.&lt;/p&gt; &lt;p&gt;When the value is set to false for an Aurora Serverless v1 DB cluster, the DB cluster automatically resumes.&lt;/p&gt; |  [optional] |
|**secondsUntilAutoPause** | **Integer** | The remaining amount of time, in seconds, before the Aurora DB cluster in &lt;code&gt;serverless&lt;/code&gt; mode is paused. A DB cluster can be paused only when it&#39;s idle (it has no connections). |  [optional] |
|**timeoutAction** | **String** | &lt;p&gt;The action that occurs when Aurora times out while attempting to change the capacity of an Aurora Serverless v1 cluster. The value is either &lt;code&gt;ForceApplyCapacityChange&lt;/code&gt; or &lt;code&gt;RollbackCapacityChange&lt;/code&gt;.&lt;/p&gt; &lt;p&gt; &lt;code&gt;ForceApplyCapacityChange&lt;/code&gt;, the default, sets the capacity to the specified value as soon as possible.&lt;/p&gt; &lt;p&gt; &lt;code&gt;RollbackCapacityChange&lt;/code&gt; ignores the capacity change if a scaling point isn&#39;t found in the timeout period.&lt;/p&gt; |  [optional] |
|**secondsBeforeTimeout** | **Integer** | The number of seconds before scaling times out. What happens when an attempted scaling action times out is determined by the &lt;code&gt;TimeoutAction&lt;/code&gt; setting. |  [optional] |



