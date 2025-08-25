

# TargetHealth

Information about the connection health of an RDS Proxy target.

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**state** | **TargetState** | &lt;p&gt;The current state of the connection health lifecycle for the RDS Proxy target. The following is a typical lifecycle example for the states of an RDS Proxy target:&lt;/p&gt; &lt;p&gt; &lt;code&gt;registering&lt;/code&gt; &amp;gt; &lt;code&gt;unavailable&lt;/code&gt; &amp;gt; &lt;code&gt;available&lt;/code&gt; &amp;gt; &lt;code&gt;unavailable&lt;/code&gt; &amp;gt; &lt;code&gt;available&lt;/code&gt; &lt;/p&gt; |  [optional] |
|**reason** | **TargetHealthReason** | The reason for the current health &lt;code&gt;State&lt;/code&gt; of the RDS Proxy target. |  [optional] |
|**description** | **String** | A description of the health of the RDS Proxy target. If the &lt;code&gt;State&lt;/code&gt; is &lt;code&gt;AVAILABLE&lt;/code&gt;, a description is not included. |  [optional] |



