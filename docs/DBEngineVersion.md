

# DBEngineVersion

This data type is used as a response element in the action <code>DescribeDBEngineVersions</code>.

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**engine** | **String** | The name of the database engine. |  [optional] |
|**engineVersion** | **String** | The version number of the database engine. |  [optional] |
|**dbParameterGroupFamily** | **String** | The name of the DB parameter group family for the database engine. |  [optional] |
|**dbEngineDescription** | **String** | The description of the database engine. |  [optional] |
|**dbEngineVersionDescription** | **String** | The description of the database engine version. |  [optional] |
|**defaultCharacterSet** | [**CharacterSet**](CharacterSet.md) | The default character set for new instances of this engine version, if the &lt;code&gt;CharacterSetName&lt;/code&gt; parameter of the CreateDBInstance API isn&#39;t specified. |  [optional] |
|**image** | [**CustomDBEngineVersionAMI**](CustomDBEngineVersionAMI.md) | The EC2 image |  [optional] |
|**dbEngineMediaType** | **String** | A value that indicates the source media provider of the AMI based on the usage operation. Applicable for RDS Custom for SQL Server. |  [optional] |
|**supportedCharacterSets** | [**List&lt;CharacterSet&gt;**](CharacterSet.md) | A list of the character sets supported by this engine for the &lt;code&gt;CharacterSetName&lt;/code&gt; parameter of the &lt;code&gt;CreateDBInstance&lt;/code&gt; operation. |  [optional] |
|**supportedNcharCharacterSets** | [**List&lt;CharacterSet&gt;**](CharacterSet.md) | A list of the character sets supported by the Oracle DB engine for the &lt;code&gt;NcharCharacterSetName&lt;/code&gt; parameter of the &lt;code&gt;CreateDBInstance&lt;/code&gt; operation. |  [optional] |
|**validUpgradeTarget** | [**List&lt;UpgradeTarget&gt;**](UpgradeTarget.md) | A list of engine versions that this database engine version can be upgraded to. |  [optional] |
|**supportedTimezones** | [**List&lt;Timezone&gt;**](Timezone.md) | A list of the time zones supported by this engine for the &lt;code&gt;Timezone&lt;/code&gt; parameter of the &lt;code&gt;CreateDBInstance&lt;/code&gt; action. |  [optional] |
|**exportableLogTypes** | **List&lt;String&gt;** | The types of logs that the database engine has available for export to CloudWatch Logs. |  [optional] |
|**supportsLogExportsToCloudwatchLogs** | **Boolean** | A value that indicates whether the engine version supports exporting the log types specified by ExportableLogTypes to CloudWatch Logs. |  [optional] |
|**supportsReadReplica** | **Boolean** | Indicates whether the database engine version supports read replicas. |  [optional] |
|**supportedEngineModes** | **List&lt;String&gt;** | A list of the supported DB engine modes. |  [optional] |
|**supportedFeatureNames** | **List&lt;String&gt;** | &lt;p&gt;A list of features supported by the DB engine.&lt;/p&gt; &lt;p&gt;The supported features vary by DB engine and DB engine version.&lt;/p&gt; &lt;p&gt;To determine the supported features for a specific DB engine and DB engine version using the CLI, use the following command:&lt;/p&gt; &lt;p&gt; &lt;code&gt;aws rds describe-db-engine-versions --engine &amp;lt;engine_name&amp;gt; --engine-version &amp;lt;engine_version&amp;gt;&lt;/code&gt; &lt;/p&gt; &lt;p&gt;For example, to determine the supported features for RDS for PostgreSQL version 13.3 using the CLI, use the following command:&lt;/p&gt; &lt;p&gt; &lt;code&gt;aws rds describe-db-engine-versions --engine postgres --engine-version 13.3&lt;/code&gt; &lt;/p&gt; &lt;p&gt;The supported features are listed under &lt;code&gt;SupportedFeatureNames&lt;/code&gt; in the output.&lt;/p&gt; |  [optional] |
|**status** | **String** | The status of the DB engine version, either &lt;code&gt;available&lt;/code&gt; or &lt;code&gt;deprecated&lt;/code&gt;. |  [optional] |
|**supportsParallelQuery** | **Boolean** | A value that indicates whether you can use Aurora parallel query with a specific DB engine version. |  [optional] |
|**supportsGlobalDatabases** | **Boolean** | A value that indicates whether you can use Aurora global databases with a specific DB engine version. |  [optional] |
|**majorEngineVersion** | **String** | The major engine version of the CEV. |  [optional] |
|**databaseInstallationFilesS3BucketName** | **String** | The name of the Amazon S3 bucket that contains your database installation files. |  [optional] |
|**databaseInstallationFilesS3Prefix** | **String** | The Amazon S3 directory that contains the database installation files. If not specified, then no prefix is assumed. |  [optional] |
|**dbEngineVersionArn** | **String** | The ARN of the custom engine version. |  [optional] |
|**kmSKeyId** | **String** | The Amazon Web Services KMS key identifier for an encrypted CEV. This parameter is required for RDS Custom, but optional for Amazon RDS. |  [optional] |
|**createTime** | **OffsetDateTime** | The creation time of the DB engine version. |  [optional] |
|**tagList** | [**List&lt;Tag&gt;**](Tag.md) | A list of tags. For more information, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/USER_Tagging.html\&quot;&gt;Tagging Amazon RDS Resources&lt;/a&gt; in the &lt;i&gt;Amazon RDS User Guide.&lt;/i&gt;  |  [optional] |
|**supportsBabelfish** | **Boolean** | A value that indicates whether the engine version supports Babelfish for Aurora PostgreSQL. |  [optional] |
|**customDBEngineVersionManifest** | **String** | JSON string that lists the installation files and parameters that RDS Custom uses to create a custom engine version (CEV). RDS Custom applies the patches in the order in which they&#39;re listed in the manifest. You can set the Oracle home, Oracle base, and UNIX/Linux user and group using the installation parameters. For more information, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/custom-cev.preparing.html#custom-cev.preparing.manifest.fields\&quot;&gt;JSON fields in the CEV manifest&lt;/a&gt; in the &lt;i&gt;Amazon RDS User Guide&lt;/i&gt;.  |  [optional] |
|**supportsCertificateRotationWithoutRestart** | **Boolean** | A value that indicates whether the engine version supports rotating the server certificate without rebooting the DB instance. |  [optional] |
|**supportedCACertificateIdentifiers** | **List&lt;String&gt;** | &lt;p&gt;A list of the supported CA certificate identifiers.&lt;/p&gt; &lt;p&gt;For more information, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/UsingWithRDS.SSL.html\&quot;&gt;Using SSL/TLS to encrypt a connection to a DB instance&lt;/a&gt; in the &lt;i&gt;Amazon RDS User Guide&lt;/i&gt; and &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/AmazonRDS/latest/AuroraUserGuide/UsingWithRDS.SSL.html\&quot;&gt; Using SSL/TLS to encrypt a connection to a DB cluster&lt;/a&gt; in the &lt;i&gt;Amazon Aurora User Guide&lt;/i&gt;.&lt;/p&gt; |  [optional] |
|**supportsLocalWriteForwarding** | **Boolean** | &lt;p&gt;A value that indicates whether the DB engine version supports forwarding write operations from reader DB instances to the writer DB instance in the DB cluster. By default, write operations aren&#39;t allowed on reader DB instances.&lt;/p&gt; &lt;p&gt;Valid for: Aurora DB clusters only&lt;/p&gt; |  [optional] |



