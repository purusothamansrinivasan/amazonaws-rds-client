

# DBClusterSnapshot

<p>Contains the details for an Amazon RDS DB cluster snapshot</p> <p>This data type is used as a response element in the <code>DescribeDBClusterSnapshots</code> action.</p>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**availabilityZones** | **List&lt;String&gt;** | Provides the list of Availability Zones (AZs) where instances in the DB cluster snapshot can be restored. |  [optional] |
|**dbClusterSnapshotIdentifier** | **String** | Specifies the identifier for the DB cluster snapshot. |  [optional] |
|**dbClusterIdentifier** | **String** | Specifies the DB cluster identifier of the DB cluster that this DB cluster snapshot was created from. |  [optional] |
|**snapshotCreateTime** | **OffsetDateTime** | Provides the time when the snapshot was taken, in Universal Coordinated Time (UTC). |  [optional] |
|**engine** | **String** | Specifies the name of the database engine for this DB cluster snapshot. |  [optional] |
|**engineMode** | **String** | Provides the engine mode of the database engine for this DB cluster snapshot. |  [optional] |
|**allocatedStorage** | **Integer** | Specifies the allocated storage size in gibibytes (GiB). |  [optional] |
|**status** | **String** | &lt;p&gt;Specifies the status of this DB cluster snapshot. Valid statuses are the following:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;available&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;copying&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;creating&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; |  [optional] |
|**port** | **Integer** | Specifies the port that the DB cluster was listening on at the time of the snapshot. |  [optional] |
|**vpcId** | **String** | Provides the VPC ID associated with the DB cluster snapshot. |  [optional] |
|**clusterCreateTime** | **OffsetDateTime** | Specifies the time when the DB cluster was created, in Universal Coordinated Time (UTC). |  [optional] |
|**masterUsername** | **String** | Provides the master username for this DB cluster snapshot. |  [optional] |
|**engineVersion** | **String** | Provides the version of the database engine for this DB cluster snapshot. |  [optional] |
|**licenseModel** | **String** | Provides the license model information for this DB cluster snapshot. |  [optional] |
|**snapshotType** | **String** | Provides the type of the DB cluster snapshot. |  [optional] |
|**percentProgress** | **Integer** | Specifies the percentage of the estimated data that has been transferred. |  [optional] |
|**storageEncrypted** | **Boolean** | Specifies whether the DB cluster snapshot is encrypted. |  [optional] |
|**kmsKeyId** | **String** | &lt;p&gt;If &lt;code&gt;StorageEncrypted&lt;/code&gt; is true, the Amazon Web Services KMS key identifier for the encrypted DB cluster snapshot.&lt;/p&gt; &lt;p&gt;The Amazon Web Services KMS key identifier is the key ARN, key ID, alias ARN, or alias name for the KMS key.&lt;/p&gt; |  [optional] |
|**dbClusterSnapshotArn** | **String** | Specifies the Amazon Resource Name (ARN) for the DB cluster snapshot. |  [optional] |
|**sourceDBClusterSnapshotArn** | **String** | If the DB cluster snapshot was copied from a source DB cluster snapshot, the Amazon Resource Name (ARN) for the source DB cluster snapshot, otherwise, a null value. |  [optional] |
|**iaMDatabaseAuthenticationEnabled** | **Boolean** | True if mapping of Amazon Web Services Identity and Access Management (IAM) accounts to database accounts is enabled, and otherwise false. |  [optional] |
|**tagList** | [**List&lt;Tag&gt;**](Tag.md) | A list of tags. For more information, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/USER_Tagging.html\&quot;&gt;Tagging Amazon RDS Resources&lt;/a&gt; in the &lt;i&gt;Amazon RDS User Guide.&lt;/i&gt;  |  [optional] |
|**dbSystemId** | **String** | Reserved for future use. |  [optional] |
|**storageType** | **String** | &lt;p&gt;The storage type associated with the DB cluster snapshot.&lt;/p&gt; &lt;p&gt;This setting is only for Aurora DB clusters.&lt;/p&gt; |  [optional] |
|**dbClusterResourceId** | **String** | Specifies the resource ID of the DB cluster that this DB cluster snapshot was created from. |  [optional] |



