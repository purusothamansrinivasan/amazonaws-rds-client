

# DBInstanceAutomatedBackup

An automated backup of a DB instance. It consists of system backups, transaction logs, and the database instance properties that existed at the time you deleted the source instance.

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**dbInstanceArn** | **String** | The Amazon Resource Name (ARN) for the automated backups. |  [optional] |
|**dbiResourceId** | **String** | The resource ID for the source DB instance, which can&#39;t be changed and which is unique to an Amazon Web Services Region. |  [optional] |
|**region** | **String** | The Amazon Web Services Region associated with the automated backup. |  [optional] |
|**dbInstanceIdentifier** | **String** | The identifier for the source DB instance, which can&#39;t be changed and which is unique to an Amazon Web Services Region. |  [optional] |
|**restoreWindow** | [**RestoreWindow**](RestoreWindow.md) | Earliest and latest time an instance can be restored to. |  [optional] |
|**allocatedStorage** | **Integer** | Specifies the allocated storage size in gibibytes (GiB). |  [optional] |
|**status** | **String** | &lt;p&gt;Provides a list of status information for an automated backup:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;active&lt;/code&gt; - Automated backups for current instances.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;retained&lt;/code&gt; - Automated backups for deleted instances.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;creating&lt;/code&gt; - Automated backups that are waiting for the first automated snapshot to be available.&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; |  [optional] |
|**port** | **Integer** | &lt;p&gt;The port number that the automated backup used for connections.&lt;/p&gt; &lt;p&gt;Default: Inherits from the source DB instance&lt;/p&gt; &lt;p&gt;Valid Values: &lt;code&gt;1150-65535&lt;/code&gt; &lt;/p&gt; |  [optional] |
|**availabilityZone** | **String** | The Availability Zone that the automated backup was created in. For information on Amazon Web Services Regions and Availability Zones, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/Concepts.RegionsAndAvailabilityZones.html\&quot;&gt;Regions and Availability Zones&lt;/a&gt;. |  [optional] |
|**vpcId** | **String** | Provides the VPC ID associated with the DB instance. |  [optional] |
|**instanceCreateTime** | **OffsetDateTime** | Provides the date and time that the DB instance was created. |  [optional] |
|**masterUsername** | **String** | The master user name of an automated backup. |  [optional] |
|**engine** | **String** | The name of the database engine for this automated backup. |  [optional] |
|**engineVersion** | **String** | The version of the database engine for the automated backup. |  [optional] |
|**licenseModel** | **String** | License model information for the automated backup. |  [optional] |
|**iops** | **Integer** | The IOPS (I/O operations per second) value for the automated backup. |  [optional] |
|**optionGroupName** | **String** | The option group the automated backup is associated with. If omitted, the default option group for the engine specified is used. |  [optional] |
|**tdeCredentialArn** | **String** | The ARN from the key store with which the automated backup is associated for TDE encryption. |  [optional] |
|**encrypted** | **Boolean** | Specifies whether the automated backup is encrypted. |  [optional] |
|**storageType** | **String** | Specifies the storage type associated with the automated backup. |  [optional] |
|**kmsKeyId** | **String** | &lt;p&gt;The Amazon Web Services KMS key ID for an automated backup.&lt;/p&gt; &lt;p&gt;The Amazon Web Services KMS key identifier is the key ARN, key ID, alias ARN, or alias name for the KMS key.&lt;/p&gt; |  [optional] |
|**timezone** | **String** | The time zone of the automated backup. In most cases, the &lt;code&gt;Timezone&lt;/code&gt; element is empty. &lt;code&gt;Timezone&lt;/code&gt; content appears only for Microsoft SQL Server DB instances that were created with a time zone specified. |  [optional] |
|**iaMDatabaseAuthenticationEnabled** | **Boolean** | True if mapping of Amazon Web Services Identity and Access Management (IAM) accounts to database accounts is enabled, and otherwise false. |  [optional] |
|**backupRetentionPeriod** | **Integer** | The retention period for the automated backups. |  [optional] |
|**dbInstanceAutomatedBackupsArn** | **String** | The Amazon Resource Name (ARN) for the replicated automated backups. |  [optional] |
|**dbInstanceAutomatedBackupsReplications** | [**List&lt;DBInstanceAutomatedBackupsReplication&gt;**](DBInstanceAutomatedBackupsReplication.md) | The list of replications to different Amazon Web Services Regions associated with the automated backup. |  [optional] |
|**backupTarget** | **String** | Specifies where automated backups are stored: Amazon Web Services Outposts or the Amazon Web Services Region. |  [optional] |
|**storageThroughput** | **Integer** | Specifies the storage throughput for the automated backup. |  [optional] |



