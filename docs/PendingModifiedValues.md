

# PendingModifiedValues

This data type is used as a response element in the <code>ModifyDBInstance</code> operation and contains changes that will be applied during the next maintenance window.

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**dbInstanceClass** | **String** | The name of the compute and memory capacity class for the DB instance. |  [optional] |
|**allocatedStorage** | **Integer** | The allocated storage size for the DB instance specified in gibibytes (GiB). |  [optional] |
|**masterUserPassword** | **String** | The master credentials for the DB instance. |  [optional] |
|**port** | **Integer** | The port for the DB instance. |  [optional] |
|**backupRetentionPeriod** | **Integer** | The number of days for which automated backups are retained. |  [optional] |
|**multiAZ** | **Boolean** | A value that indicates that the Single-AZ DB instance will change to a Multi-AZ deployment. |  [optional] |
|**engineVersion** | **String** | The database engine version. |  [optional] |
|**licenseModel** | **String** | &lt;p&gt;The license model for the DB instance.&lt;/p&gt; &lt;p&gt;Valid values: &lt;code&gt;license-included&lt;/code&gt; | &lt;code&gt;bring-your-own-license&lt;/code&gt; | &lt;code&gt;general-public-license&lt;/code&gt; &lt;/p&gt; |  [optional] |
|**iops** | **Integer** | The Provisioned IOPS value for the DB instance. |  [optional] |
|**dbInstanceIdentifier** | **String** | The database identifier for the DB instance. |  [optional] |
|**storageType** | **String** | The storage type of the DB instance. |  [optional] |
|**caCertificateIdentifier** | **String** | &lt;p&gt;The identifier of the CA certificate for the DB instance.&lt;/p&gt; &lt;p&gt;For more information, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/UsingWithRDS.SSL.html\&quot;&gt;Using SSL/TLS to encrypt a connection to a DB instance&lt;/a&gt; in the &lt;i&gt;Amazon RDS User Guide&lt;/i&gt; and &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/AmazonRDS/latest/AuroraUserGuide/UsingWithRDS.SSL.html\&quot;&gt; Using SSL/TLS to encrypt a connection to a DB cluster&lt;/a&gt; in the &lt;i&gt;Amazon Aurora User Guide&lt;/i&gt;.&lt;/p&gt; |  [optional] |
|**dbSubnetGroupName** | **String** | The DB subnet group for the DB instance. |  [optional] |
|**pendingCloudwatchLogsExports** | [**PendingCloudwatchLogsExports**](PendingCloudwatchLogsExports.md) |  |  [optional] |
|**processorFeatures** | [**List&lt;ProcessorFeature&gt;**](ProcessorFeature.md) | The number of CPU cores and the number of threads per core for the DB instance class of the DB instance. |  [optional] |
|**iaMDatabaseAuthenticationEnabled** | **Boolean** | Whether mapping of Amazon Web Services Identity and Access Management (IAM) accounts to database accounts is enabled. |  [optional] |
|**automationMode** | **AutomationMode** | The automation mode of the RDS Custom DB instance: &lt;code&gt;full&lt;/code&gt; or &lt;code&gt;all-paused&lt;/code&gt;. If &lt;code&gt;full&lt;/code&gt;, the DB instance automates monitoring and instance recovery. If &lt;code&gt;all-paused&lt;/code&gt;, the instance pauses automation for the duration set by &lt;code&gt;--resume-full-automation-mode-minutes&lt;/code&gt;. |  [optional] |
|**resumeFullAutomationModeTime** | **OffsetDateTime** | The number of minutes to pause the automation. When the time period ends, RDS Custom resumes full automation. The minimum value is 60 (default). The maximum value is 1,440. |  [optional] |
|**storageThroughput** | **Integer** | The storage throughput of the DB instance. |  [optional] |
|**engine** | **String** | The database engine of the DB instance. |  [optional] |



