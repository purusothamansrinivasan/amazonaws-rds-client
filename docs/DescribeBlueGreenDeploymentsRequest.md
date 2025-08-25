

# DescribeBlueGreenDeploymentsRequest


## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**blueGreenDeploymentIdentifier** | **String** | &lt;p&gt;The blue/green deployment identifier. If you specify this parameter, the response only includes information about the specific blue/green deployment. This parameter isn&#39;t case-sensitive.&lt;/p&gt; &lt;p&gt;Constraints:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt;Must match an existing blue/green deployment identifier.&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; |  [optional] |
|**filters** | [**List&lt;Filter&gt;**](Filter.md) | &lt;p&gt;A filter that specifies one or more blue/green deployments to describe.&lt;/p&gt; &lt;p&gt;Valid Values:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;blue-green-deployment-identifier&lt;/code&gt; - Accepts system-generated identifiers for blue/green deployments. The results list only includes information about the blue/green deployments with the specified identifiers.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;blue-green-deployment-name&lt;/code&gt; - Accepts user-supplied names for blue/green deployments. The results list only includes information about the blue/green deployments with the specified names.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;source&lt;/code&gt; - Accepts source databases for a blue/green deployment. The results list only includes information about the blue/green deployments with the specified source databases.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;target&lt;/code&gt; - Accepts target databases for a blue/green deployment. The results list only includes information about the blue/green deployments with the specified target databases.&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; |  [optional] |
|**marker** | **String** | An optional pagination token provided by a previous &lt;code&gt;DescribeBlueGreenDeployments&lt;/code&gt; request. If you specify this parameter, the response only includes records beyond the marker, up to the value specified by &lt;code&gt;MaxRecords&lt;/code&gt;. |  [optional] |
|**maxRecords** | **Integer** | &lt;p&gt;The maximum number of records to include in the response. If more records exist than the specified &lt;code&gt;MaxRecords&lt;/code&gt; value, a pagination token called a marker is included in the response so you can retrieve the remaining results.&lt;/p&gt; &lt;p&gt;Default: 100&lt;/p&gt; &lt;p&gt;Constraints:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt;Must be a minimum of 20.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt;Can&#39;t exceed 100.&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; |  [optional] |



