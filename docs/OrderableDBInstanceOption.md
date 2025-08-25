

# OrderableDBInstanceOption

<p>Contains a list of available options for a DB instance.</p> <p>This data type is used as a response element in the <code>DescribeOrderableDBInstanceOptions</code> action.</p>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**engine** | **String** | The engine type of a DB instance. |  [optional] |
|**engineVersion** | **String** | The engine version of a DB instance. |  [optional] |
|**dbInstanceClass** | **String** | The DB instance class for a DB instance. |  [optional] |
|**licenseModel** | **String** | The license model for a DB instance. |  [optional] |
|**availabilityZoneGroup** | **String** | The Availability Zone group for a DB instance. |  [optional] |
|**availabilityZones** | [**List&lt;AvailabilityZone&gt;**](AvailabilityZone.md) | A list of Availability Zones for a DB instance. |  [optional] |
|**multiAZCapable** | **Boolean** | Indicates whether a DB instance is Multi-AZ capable. |  [optional] |
|**readReplicaCapable** | **Boolean** | Indicates whether a DB instance can have a read replica. |  [optional] |
|**vpc** | **Boolean** | Indicates whether a DB instance is in a VPC. |  [optional] |
|**supportsStorageEncryption** | **Boolean** | Indicates whether a DB instance supports encrypted storage. |  [optional] |
|**storageType** | **String** | Indicates the storage type for a DB instance. |  [optional] |
|**supportsIops** | **Boolean** | Indicates whether a DB instance supports provisioned IOPS. |  [optional] |
|**supportsEnhancedMonitoring** | **Boolean** | Indicates whether a DB instance supports Enhanced Monitoring at intervals from 1 to 60 seconds. |  [optional] |
|**supportsIAMDatabaseAuthentication** | **Boolean** | Indicates whether a DB instance supports IAM database authentication. |  [optional] |
|**supportsPerformanceInsights** | **Boolean** | True if a DB instance supports Performance Insights, otherwise false. |  [optional] |
|**minStorageSize** | **Integer** | Minimum storage size for a DB instance. |  [optional] |
|**maxStorageSize** | **Integer** | Maximum storage size for a DB instance. |  [optional] |
|**minIopsPerDbInstance** | **Integer** | Minimum total provisioned IOPS for a DB instance. |  [optional] |
|**maxIopsPerDbInstance** | **Integer** | Maximum total provisioned IOPS for a DB instance. |  [optional] |
|**minIopsPerGib** | **Double** | Minimum provisioned IOPS per GiB for a DB instance. |  [optional] |
|**maxIopsPerGib** | **Double** | Maximum provisioned IOPS per GiB for a DB instance. |  [optional] |
|**availableProcessorFeatures** | [**List&lt;AvailableProcessorFeature&gt;**](AvailableProcessorFeature.md) | A list of the available processor features for the DB instance class of a DB instance. |  [optional] |
|**supportedEngineModes** | **List&lt;String&gt;** | A list of the supported DB engine modes. |  [optional] |
|**supportsStorageAutoscaling** | **Boolean** | Whether Amazon RDS can automatically scale storage for DB instances that use the specified DB instance class. |  [optional] |
|**supportsKerberosAuthentication** | **Boolean** | Whether a DB instance supports Kerberos Authentication. |  [optional] |
|**outpostCapable** | **Boolean** | &lt;p&gt;Whether a DB instance supports RDS on Outposts.&lt;/p&gt; &lt;p&gt;For more information about RDS on Outposts, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/rds-on-outposts.html\&quot;&gt;Amazon RDS on Amazon Web Services Outposts&lt;/a&gt; in the &lt;i&gt;Amazon RDS User Guide.&lt;/i&gt; &lt;/p&gt; |  [optional] |
|**supportedActivityStreamModes** | **List&lt;String&gt;** | The list of supported modes for Database Activity Streams. Aurora PostgreSQL returns the value &lt;code&gt;[sync, async]&lt;/code&gt;. Aurora MySQL and RDS for Oracle return &lt;code&gt;[async]&lt;/code&gt; only. If Database Activity Streams isn&#39;t supported, the return value is an empty list. |  [optional] |
|**supportsGlobalDatabases** | **Boolean** | A value that indicates whether you can use Aurora global databases with a specific combination of other DB engine attributes. |  [optional] |
|**supportsClusters** | **Boolean** | &lt;p&gt;Whether DB instances can be configured as a Multi-AZ DB cluster.&lt;/p&gt; &lt;p&gt;For more information on Multi-AZ DB clusters, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/multi-az-db-clusters-concepts.html\&quot;&gt; Multi-AZ deployments with two readable standby DB instances&lt;/a&gt; in the &lt;i&gt;Amazon RDS User Guide.&lt;/i&gt; &lt;/p&gt; |  [optional] |
|**supportedNetworkTypes** | **List&lt;String&gt;** | &lt;p&gt;The network types supported by the DB instance (&lt;code&gt;IPV4&lt;/code&gt; or &lt;code&gt;DUAL&lt;/code&gt;).&lt;/p&gt; &lt;p&gt;A DB instance can support only the IPv4 protocol or the IPv4 and the IPv6 protocols (&lt;code&gt;DUAL&lt;/code&gt;).&lt;/p&gt; &lt;p&gt;For more information, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/USER_VPC.WorkingWithRDSInstanceinaVPC.html\&quot;&gt; Working with a DB instance in a VPC&lt;/a&gt; in the &lt;i&gt;Amazon RDS User Guide.&lt;/i&gt; &lt;/p&gt; |  [optional] |
|**supportsStorageThroughput** | **Boolean** | Indicates whether a DB instance supports storage throughput. |  [optional] |
|**minStorageThroughputPerDbInstance** | **Integer** | Minimum storage throughput for a DB instance. |  [optional] |
|**maxStorageThroughputPerDbInstance** | **Integer** | Maximum storage throughput for a DB instance. |  [optional] |
|**minStorageThroughputPerIops** | **Double** | Minimum storage throughput to provisioned IOPS ratio for a DB instance. |  [optional] |
|**maxStorageThroughputPerIops** | **Double** | Maximum storage throughput to provisioned IOPS ratio for a DB instance. |  [optional] |



