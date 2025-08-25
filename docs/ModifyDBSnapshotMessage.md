

# ModifyDBSnapshotMessage


## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**dbSnapshotIdentifier** | **String** | The identifier of the DB snapshot to modify. |  |
|**engineVersion** | **String** | &lt;p&gt;The engine version to upgrade the DB snapshot to.&lt;/p&gt; &lt;p&gt;The following are the database engines and engine versions that are available when you upgrade a DB snapshot.&lt;/p&gt; &lt;p&gt; &lt;b&gt;MySQL&lt;/b&gt; &lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;5.5.46&lt;/code&gt; (supported for 5.1 DB snapshots)&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; &lt;p&gt; &lt;b&gt;Oracle&lt;/b&gt; &lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;19.0.0.0.ru-2022-01.rur-2022-01.r1&lt;/code&gt; (supported for 12.2.0.1 DB snapshots)&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;19.0.0.0.ru-2022-07.rur-2022-07.r1&lt;/code&gt; (supported for 12.1.0.2 DB snapshots)&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;12.1.0.2.v8&lt;/code&gt; (supported for 12.1.0.1 DB snapshots)&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;11.2.0.4.v12&lt;/code&gt; (supported for 11.2.0.2 DB snapshots)&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;11.2.0.4.v11&lt;/code&gt; (supported for 11.2.0.3 DB snapshots)&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; &lt;p&gt; &lt;b&gt;PostgreSQL&lt;/b&gt; &lt;/p&gt; &lt;p&gt;For the list of engine versions that are available for upgrading a DB snapshot, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/USER_UpgradeDBInstance.PostgreSQL.html#USER_UpgradeDBInstance.PostgreSQL.MajorVersion\&quot;&gt; Upgrading the PostgreSQL DB Engine for Amazon RDS&lt;/a&gt;.&lt;/p&gt; |  [optional] |
|**optionGroupName** | **String** | &lt;p&gt;The option group to identify with the upgraded DB snapshot.&lt;/p&gt; &lt;p&gt;You can specify this parameter when you upgrade an Oracle DB snapshot. The same option group considerations apply when upgrading a DB snapshot as when upgrading a DB instance. For more information, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/USER_UpgradeDBInstance.Oracle.html#USER_UpgradeDBInstance.Oracle.OGPG.OG\&quot;&gt;Option group considerations&lt;/a&gt; in the &lt;i&gt;Amazon RDS User Guide.&lt;/i&gt; &lt;/p&gt; |  [optional] |



