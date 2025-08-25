

# DBClusterAutomatedBackup

An automated backup of a DB cluster. It consists of system backups, transaction logs, and the database cluster properties that existed at the time you deleted the source cluster.

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**engine** | **String** | The name of the database engine for this automated backup. |  [optional] |
|**vpcId** | **String** | The VPC ID associated with the DB cluster. |  [optional] |
|**dbClusterAutomatedBackupsArn** | **String** | The Amazon Resource Name (ARN) for the automated backups. |  [optional] |
|**dbClusterIdentifier** | **String** | The identifier for the source DB cluster, which can&#39;t be changed and which is unique to an Amazon Web Services Region. |  [optional] |
|**restoreWindow** | [**RestoreWindow**](RestoreWindow.md) |  |  [optional] |
|**masterUsername** | **String** | The master user name of the automated backup. |  [optional] |
|**dbClusterResourceId** | **String** | The resource ID for the source DB cluster, which can&#39;t be changed and which is unique to an Amazon Web Services Region. |  [optional] |
|**region** | **String** | The Amazon Web Services Region associated with the automated backup. |  [optional] |
|**licenseModel** | **String** | The license model information for this DB cluster automated backup. |  [optional] |
|**status** | **String** | &lt;p&gt;A list of status information for an automated backup:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;retained&lt;/code&gt; - Automated backups for deleted clusters.&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; |  [optional] |
|**iaMDatabaseAuthenticationEnabled** | **Boolean** | True if mapping of Amazon Web Services Identity and Access Management (IAM) accounts to database accounts is enabled, and otherwise false. |  [optional] |
|**clusterCreateTime** | **OffsetDateTime** | The time when the DB cluster was created, in Universal Coordinated Time (UTC). |  [optional] |
|**storageEncrypted** | **Boolean** | Specifies whether the source DB cluster is encrypted. |  [optional] |
|**allocatedStorage** | **Integer** | For all database engines except Amazon Aurora, &lt;code&gt;AllocatedStorage&lt;/code&gt; specifies the allocated storage size in gibibytes (GiB). For Aurora, &lt;code&gt;AllocatedStorage&lt;/code&gt; always returns 1, because Aurora DB cluster storage size isn&#39;t fixed, but instead automatically adjusts as needed. |  [optional] |
|**engineVersion** | **String** | The version of the database engine for the automated backup. |  [optional] |
|**dbClusterArn** | **String** | The Amazon Resource Name (ARN) for the source DB cluster. |  [optional] |
|**backupRetentionPeriod** | **Integer** | The retention period for the automated backups. |  [optional] |
|**engineMode** | **String** | The engine mode of the database engine for the automated backup. |  [optional] |
|**availabilityZones** | **List&lt;String&gt;** | The Availability Zones where instances in the DB cluster can be created. For information on Amazon Web Services Regions and Availability Zones, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/AmazonRDS/latest/AuroraUserGuide/Concepts.RegionsAndAvailabilityZones.html\&quot;&gt;Regions and Availability Zones&lt;/a&gt;. |  [optional] |
|**port** | **Integer** | &lt;p&gt;The port number that the automated backup used for connections.&lt;/p&gt; &lt;p&gt;Default: Inherits from the source DB cluster&lt;/p&gt; &lt;p&gt;Valid Values: &lt;code&gt;1150-65535&lt;/code&gt; &lt;/p&gt; |  [optional] |
|**kmsKeyId** | **String** | &lt;p&gt;The Amazon Web Services KMS key ID for an automated backup.&lt;/p&gt; &lt;p&gt;The Amazon Web Services KMS key identifier is the key ARN, key ID, alias ARN, or alias name for the KMS key.&lt;/p&gt; |  [optional] |
|**storageType** | **String** | &lt;p&gt;The storage type associated with the DB cluster.&lt;/p&gt; &lt;p&gt;This setting is only for non-Aurora Multi-AZ DB clusters.&lt;/p&gt; |  [optional] |
|**iops** | **Integer** | &lt;p&gt;The IOPS (I/O operations per second) value for the automated backup.&lt;/p&gt; &lt;p&gt;This setting is only for non-Aurora Multi-AZ DB clusters.&lt;/p&gt; |  [optional] |



