

# PromoteReadReplicaMessage

<p/>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**dbInstanceIdentifier** | **String** | &lt;p&gt;The DB instance identifier. This value is stored as a lowercase string.&lt;/p&gt; &lt;p&gt;Constraints:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt;Must match the identifier of an existing read replica DB instance.&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; &lt;p&gt;Example: &lt;code&gt;mydbinstance&lt;/code&gt; &lt;/p&gt; |  |
|**backupRetentionPeriod** | **Integer** | &lt;p&gt;The number of days for which automated backups are retained. Setting this parameter to a positive number enables backups. Setting this parameter to 0 disables automated backups.&lt;/p&gt; &lt;p&gt;Default: 1&lt;/p&gt; &lt;p&gt;Constraints:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt;Must be a value from 0 to 35.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt;Can&#39;t be set to 0 if the DB instance is a source to read replicas.&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; |  [optional] |
|**preferredBackupWindow** | **String** | &lt;p&gt;The daily time range during which automated backups are created if automated backups are enabled, using the &lt;code&gt;BackupRetentionPeriod&lt;/code&gt; parameter.&lt;/p&gt; &lt;p&gt;The default is a 30-minute window selected at random from an 8-hour block of time for each Amazon Web Services Region. To see the time blocks available, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/AdjustingTheMaintenanceWindow.html\&quot;&gt; Adjusting the Preferred Maintenance Window&lt;/a&gt; in the &lt;i&gt;Amazon RDS User Guide.&lt;/i&gt; &lt;/p&gt; &lt;p&gt;Constraints:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt;Must be in the format &lt;code&gt;hh24:mi-hh24:mi&lt;/code&gt;.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt;Must be in Universal Coordinated Time (UTC).&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt;Must not conflict with the preferred maintenance window.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt;Must be at least 30 minutes.&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; |  [optional] |



