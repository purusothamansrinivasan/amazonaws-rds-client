

# ApplyPendingMaintenanceActionMessage

<p/>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**resourceIdentifier** | **String** | The RDS Amazon Resource Name (ARN) of the resource that the pending maintenance action applies to. For information about creating an ARN, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/USER_Tagging.ARN.html#USER_Tagging.ARN.Constructing\&quot;&gt; Constructing an RDS Amazon Resource Name (ARN)&lt;/a&gt;. |  |
|**applyAction** | **String** | &lt;p&gt;The pending maintenance action to apply to this resource.&lt;/p&gt; &lt;p&gt;Valid values: &lt;code&gt;system-update&lt;/code&gt;, &lt;code&gt;db-upgrade&lt;/code&gt;, &lt;code&gt;hardware-maintenance&lt;/code&gt;, &lt;code&gt;ca-certificate-rotation&lt;/code&gt; &lt;/p&gt; |  |
|**optInType** | **String** | &lt;p&gt;A value that specifies the type of opt-in request, or undoes an opt-in request. An opt-in request of type &lt;code&gt;immediate&lt;/code&gt; can&#39;t be undone.&lt;/p&gt; &lt;p&gt;Valid values:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;immediate&lt;/code&gt; - Apply the maintenance action immediately.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;next-maintenance&lt;/code&gt; - Apply the maintenance action during the next maintenance window for the resource.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;undo-opt-in&lt;/code&gt; - Cancel any existing &lt;code&gt;next-maintenance&lt;/code&gt; opt-in requests.&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; |  |



