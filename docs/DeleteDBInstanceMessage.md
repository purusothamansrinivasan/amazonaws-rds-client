

# DeleteDBInstanceMessage

<p/>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**dbInstanceIdentifier** | **String** | &lt;p&gt;The DB instance identifier for the DB instance to be deleted. This parameter isn&#39;t case-sensitive.&lt;/p&gt; &lt;p&gt;Constraints:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt;Must match the name of an existing DB instance.&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; |  |
|**skipFinalSnapshot** | **Boolean** | &lt;p&gt;A value that indicates whether to skip the creation of a final DB snapshot before deleting the instance. If you enable this parameter, RDS doesn&#39;t create a DB snapshot. If you don&#39;t enable this parameter, RDS creates a DB snapshot before the DB instance is deleted. By default, skip isn&#39;t enabled, and the DB snapshot is created.&lt;/p&gt; &lt;note&gt; &lt;p&gt;If you don&#39;t enable this parameter, you must specify the &lt;code&gt;FinalDBSnapshotIdentifier&lt;/code&gt; parameter.&lt;/p&gt; &lt;/note&gt; &lt;p&gt;When a DB instance is in a failure state and has a status of &lt;code&gt;failed&lt;/code&gt;, &lt;code&gt;incompatible-restore&lt;/code&gt;, or &lt;code&gt;incompatible-network&lt;/code&gt;, RDS can delete the instance only if you enable this parameter.&lt;/p&gt; &lt;p&gt;If you delete a read replica or an RDS Custom instance, you must enable this setting.&lt;/p&gt; &lt;p&gt;This setting is required for RDS Custom.&lt;/p&gt; |  [optional] |
|**finalDBSnapshotIdentifier** | **String** | &lt;p&gt;The &lt;code&gt;DBSnapshotIdentifier&lt;/code&gt; of the new &lt;code&gt;DBSnapshot&lt;/code&gt; created when the &lt;code&gt;SkipFinalSnapshot&lt;/code&gt; parameter is disabled.&lt;/p&gt; &lt;note&gt; &lt;p&gt;If you enable this parameter and also enable SkipFinalShapshot, the command results in an error.&lt;/p&gt; &lt;/note&gt; &lt;p&gt;This setting doesn&#39;t apply to RDS Custom.&lt;/p&gt; &lt;p&gt;Constraints:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt;Must be 1 to 255 letters or numbers.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt;First character must be a letter.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt;Can&#39;t end with a hyphen or contain two consecutive hyphens.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt;Can&#39;t be specified when deleting a read replica.&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; |  [optional] |
|**deleteAutomatedBackups** | **Boolean** | A value that indicates whether to remove automated backups immediately after the DB instance is deleted. This parameter isn&#39;t case-sensitive. The default is to remove automated backups immediately after the DB instance is deleted. |  [optional] |



