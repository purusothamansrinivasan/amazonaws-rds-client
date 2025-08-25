

# DBSnapshot

<p>Contains the details of an Amazon RDS DB snapshot.</p> <p>This data type is used as a response element in the <code>DescribeDBSnapshots</code> action.</p>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**dbSnapshotIdentifier** | **String** | Specifies the identifier for the DB snapshot. |  [optional] |
|**dbInstanceIdentifier** | **String** | Specifies the DB instance identifier of the DB instance this DB snapshot was created from. |  [optional] |
|**snapshotCreateTime** | **OffsetDateTime** | Specifies when the snapshot was taken in Coordinated Universal Time (UTC). Changes for the copy when the snapshot is copied. |  [optional] |
|**engine** | **String** | Specifies the name of the database engine. |  [optional] |
|**allocatedStorage** | **Integer** | Specifies the allocated storage size in gibibytes (GiB). |  [optional] |
|**status** | **String** | Specifies the status of this DB snapshot. |  [optional] |
|**port** | **Integer** | Specifies the port that the database engine was listening on at the time of the snapshot. |  [optional] |
|**availabilityZone** | **String** | Specifies the name of the Availability Zone the DB instance was located in at the time of the DB snapshot. |  [optional] |
|**vpcId** | **String** | Provides the VPC ID associated with the DB snapshot. |  [optional] |
|**instanceCreateTime** | **OffsetDateTime** | Specifies the time in Coordinated Universal Time (UTC) when the DB instance, from which the snapshot was taken, was created. |  [optional] |
|**masterUsername** | **String** | Provides the master username for the DB snapshot. |  [optional] |
|**engineVersion** | **String** | Specifies the version of the database engine. |  [optional] |
|**licenseModel** | **String** | License model information for the restored DB instance. |  [optional] |
|**snapshotType** | **String** | Provides the type of the DB snapshot. |  [optional] |
|**iops** | **Integer** | Specifies the Provisioned IOPS (I/O operations per second) value of the DB instance at the time of the snapshot. |  [optional] |
|**optionGroupName** | **String** | Provides the option group name for the DB snapshot. |  [optional] |
|**percentProgress** | **Integer** | The percentage of the estimated data that has been transferred. |  [optional] |
|**sourceRegion** | **String** | The Amazon Web Services Region that the DB snapshot was created in or copied from. |  [optional] |
|**sourceDBSnapshotIdentifier** | **String** | The DB snapshot Amazon Resource Name (ARN) that the DB snapshot was copied from. It only has a value in the case of a cross-account or cross-Region copy. |  [optional] |
|**storageType** | **String** | Specifies the storage type associated with DB snapshot. |  [optional] |
|**tdeCredentialArn** | **String** | The ARN from the key store with which to associate the instance for TDE encryption. |  [optional] |
|**encrypted** | **Boolean** | Specifies whether the DB snapshot is encrypted. |  [optional] |
|**kmsKeyId** | **String** | &lt;p&gt;If &lt;code&gt;Encrypted&lt;/code&gt; is true, the Amazon Web Services KMS key identifier for the encrypted DB snapshot.&lt;/p&gt; &lt;p&gt;The Amazon Web Services KMS key identifier is the key ARN, key ID, alias ARN, or alias name for the KMS key.&lt;/p&gt; |  [optional] |
|**dbSnapshotArn** | **String** | The Amazon Resource Name (ARN) for the DB snapshot. |  [optional] |
|**timezone** | **String** | The time zone of the DB snapshot. In most cases, the &lt;code&gt;Timezone&lt;/code&gt; element is empty. &lt;code&gt;Timezone&lt;/code&gt; content appears only for snapshots taken from Microsoft SQL Server DB instances that were created with a time zone specified. |  [optional] |
|**iaMDatabaseAuthenticationEnabled** | **Boolean** | True if mapping of Amazon Web Services Identity and Access Management (IAM) accounts to database accounts is enabled, and otherwise false. |  [optional] |
|**processorFeatures** | [**List&lt;ProcessorFeature&gt;**](ProcessorFeature.md) | The number of CPU cores and the number of threads per core for the DB instance class of the DB instance when the DB snapshot was created. |  [optional] |
|**dbiResourceId** | **String** | The identifier for the source DB instance, which can&#39;t be changed and which is unique to an Amazon Web Services Region. |  [optional] |
|**tagList** | [**List&lt;Tag&gt;**](Tag.md) | A list of tags. For more information, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/USER_Tagging.html\&quot;&gt;Tagging Amazon RDS Resources&lt;/a&gt; in the &lt;i&gt;Amazon RDS User Guide.&lt;/i&gt;  |  [optional] |
|**originalSnapshotCreateTime** | **OffsetDateTime** | Specifies the time of the CreateDBSnapshot operation in Coordinated Universal Time (UTC). Doesn&#39;t change when the snapshot is copied. |  [optional] |
|**snapshotDatabaseTime** | **OffsetDateTime** | &lt;p&gt;The timestamp of the most recent transaction applied to the database that you&#39;re backing up. Thus, if you restore a snapshot, SnapshotDatabaseTime is the most recent transaction in the restored DB instance. In contrast, originalSnapshotCreateTime specifies the system time that the snapshot completed.&lt;/p&gt; &lt;p&gt;If you back up a read replica, you can determine the replica lag by comparing SnapshotDatabaseTime with originalSnapshotCreateTime. For example, if originalSnapshotCreateTime is two hours later than SnapshotDatabaseTime, then the replica lag is two hours.&lt;/p&gt; |  [optional] |
|**snapshotTarget** | **String** | Specifies where manual snapshots are stored: Amazon Web Services Outposts or the Amazon Web Services Region. |  [optional] |
|**storageThroughput** | **Integer** | Specifies the storage throughput for the DB snapshot. |  [optional] |
|**dbSystemId** | **String** | The Oracle system identifier (SID), which is the name of the Oracle database instance that manages your database files. The Oracle SID is also the name of your CDB. |  [optional] |



