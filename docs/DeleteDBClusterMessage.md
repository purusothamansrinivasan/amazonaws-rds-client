

# DeleteDBClusterMessage

<p/>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**dbClusterIdentifier** | **String** | &lt;p&gt;The DB cluster identifier for the DB cluster to be deleted. This parameter isn&#39;t case-sensitive.&lt;/p&gt; &lt;p&gt;Constraints:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt;Must match an existing DBClusterIdentifier.&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; |  |
|**skipFinalSnapshot** | **Boolean** | &lt;p&gt;A value that indicates whether to skip the creation of a final DB cluster snapshot before the DB cluster is deleted. If skip is specified, no DB cluster snapshot is created. If skip isn&#39;t specified, a DB cluster snapshot is created before the DB cluster is deleted. By default, skip isn&#39;t specified, and the DB cluster snapshot is created. By default, this parameter is disabled.&lt;/p&gt; &lt;note&gt; &lt;p&gt;You must specify a &lt;code&gt;FinalDBSnapshotIdentifier&lt;/code&gt; parameter if &lt;code&gt;SkipFinalSnapshot&lt;/code&gt; is disabled.&lt;/p&gt; &lt;/note&gt; |  [optional] |
|**finalDBSnapshotIdentifier** | **String** | &lt;p&gt;The DB cluster snapshot identifier of the new DB cluster snapshot created when &lt;code&gt;SkipFinalSnapshot&lt;/code&gt; is disabled.&lt;/p&gt; &lt;note&gt; &lt;p&gt;Specifying this parameter and also skipping the creation of a final DB cluster snapshot with the &lt;code&gt;SkipFinalShapshot&lt;/code&gt; parameter results in an error.&lt;/p&gt; &lt;/note&gt; &lt;p&gt;Constraints:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt;Must be 1 to 255 letters, numbers, or hyphens.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt;First character must be a letter&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt;Can&#39;t end with a hyphen or contain two consecutive hyphens&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; |  [optional] |
|**deleteAutomatedBackups** | **Boolean** | A value that indicates whether to remove automated backups immediately after the DB cluster is deleted. This parameter isn&#39;t case-sensitive. The default is to remove automated backups immediately after the DB cluster is deleted. |  [optional] |



