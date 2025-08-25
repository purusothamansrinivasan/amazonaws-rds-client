

# CreateGlobalClusterMessage


## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**globalClusterIdentifier** | **String** | The cluster identifier for this global database cluster. This parameter is stored as a lowercase string. |  [optional] |
|**sourceDBClusterIdentifier** | **String** | &lt;p&gt;The Amazon Resource Name (ARN) to use as the primary cluster of the global database.&lt;/p&gt; &lt;p&gt;If you provide a value for this parameter, don&#39;t specify values for the following settings because Amazon Aurora uses the values from the specified source DB cluster:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;DatabaseName&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;Engine&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;EngineVersion&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;StorageEncrypted&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; |  [optional] |
|**engine** | **String** | &lt;p&gt;The database engine to use for this global database cluster.&lt;/p&gt; &lt;p&gt;Valid Values: &lt;code&gt;aurora-mysql | aurora-postgresql&lt;/code&gt; &lt;/p&gt; &lt;p&gt;Constraints:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt;Can&#39;t be specified if &lt;code&gt;SourceDBClusterIdentifier&lt;/code&gt; is specified. In this case, Amazon Aurora uses the engine of the source DB cluster.&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; |  [optional] |
|**engineVersion** | **String** | &lt;p&gt;The engine version to use for this global database cluster.&lt;/p&gt; &lt;p&gt;Constraints:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt;Can&#39;t be specified if &lt;code&gt;SourceDBClusterIdentifier&lt;/code&gt; is specified. In this case, Amazon Aurora uses the engine version of the source DB cluster.&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; |  [optional] |
|**deletionProtection** | **Boolean** | Specifies whether to enable deletion protection for the new global database cluster. The global database can&#39;t be deleted when deletion protection is enabled. |  [optional] |
|**databaseName** | **String** | &lt;p&gt;The name for your database of up to 64 alphanumeric characters. If you don&#39;t specify a name, Amazon Aurora doesn&#39;t create a database in the global database cluster.&lt;/p&gt; &lt;p&gt;Constraints:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt;Can&#39;t be specified if &lt;code&gt;SourceDBClusterIdentifier&lt;/code&gt; is specified. In this case, Amazon Aurora uses the database name from the source DB cluster.&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; |  [optional] |
|**storageEncrypted** | **Boolean** | &lt;p&gt;Specifies whether to enable storage encryption for the new global database cluster.&lt;/p&gt; &lt;p&gt;Constraints:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt;Can&#39;t be specified if &lt;code&gt;SourceDBClusterIdentifier&lt;/code&gt; is specified. In this case, Amazon Aurora uses the setting from the source DB cluster.&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; |  [optional] |



