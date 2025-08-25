

# CreateBlueGreenDeploymentRequest


## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**blueGreenDeploymentName** | **String** | &lt;p&gt;The name of the blue/green deployment.&lt;/p&gt; &lt;p&gt;Constraints:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt;Can&#39;t be the same as an existing blue/green deployment name in the same account and Amazon Web Services Region.&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; |  |
|**source** | **String** | &lt;p&gt;The Amazon Resource Name (ARN) of the source production database.&lt;/p&gt; &lt;p&gt;Specify the database that you want to clone. The blue/green deployment creates this database in the green environment. You can make updates to the database in the green environment, such as an engine version upgrade. When you are ready, you can switch the database in the green environment to be the production database.&lt;/p&gt; |  |
|**targetEngineVersion** | **String** | &lt;p&gt;The engine version of the database in the green environment.&lt;/p&gt; &lt;p&gt;Specify the engine version to upgrade to in the green environment.&lt;/p&gt; |  [optional] |
|**targetDBParameterGroupName** | **String** | &lt;p&gt;The DB parameter group associated with the DB instance in the green environment.&lt;/p&gt; &lt;p&gt;To test parameter changes, specify a DB parameter group that is different from the one associated with the source DB instance.&lt;/p&gt; |  [optional] |
|**targetDBClusterParameterGroupName** | **String** | &lt;p&gt;The DB cluster parameter group associated with the Aurora DB cluster in the green environment.&lt;/p&gt; &lt;p&gt;To test parameter changes, specify a DB cluster parameter group that is different from the one associated with the source DB cluster.&lt;/p&gt; |  [optional] |
|**tags** | [**List&lt;Tag&gt;**](Tag.md) | Tags to assign to the blue/green deployment. |  [optional] |



