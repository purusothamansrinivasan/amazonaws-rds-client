

# ExportTask

<p>Contains the details of a snapshot or cluster export to Amazon S3.</p> <p>This data type is used as a response element in the <code>DescribeExportTasks</code> action.</p>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**exportTaskIdentifier** | **String** | A unique identifier for the snapshot or cluster export task. This ID isn&#39;t an identifier for the Amazon S3 bucket where the data is exported. |  [optional] |
|**sourceArn** | **String** | The Amazon Resource Name (ARN) of the snapshot or cluster exported to Amazon S3. |  [optional] |
|**exportOnly** | **List&lt;String&gt;** | &lt;p&gt;The data exported from the snapshot or cluster. Valid values are the following:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;database&lt;/code&gt; - Export all the data from a specified database.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;database.table&lt;/code&gt; &lt;i&gt;table-name&lt;/i&gt; - Export a table of the snapshot or cluster. This format is valid only for RDS for MySQL, RDS for MariaDB, and Aurora MySQL.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;database.schema&lt;/code&gt; &lt;i&gt;schema-name&lt;/i&gt; - Export a database schema of the snapshot or cluster. This format is valid only for RDS for PostgreSQL and Aurora PostgreSQL.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;database.schema.table&lt;/code&gt; &lt;i&gt;table-name&lt;/i&gt; - Export a table of the database schema. This format is valid only for RDS for PostgreSQL and Aurora PostgreSQL.&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; |  [optional] |
|**snapshotTime** | **OffsetDateTime** | The time that the snapshot was created. |  [optional] |
|**taskStartTime** | **OffsetDateTime** | The time that the snapshot or cluster export task started. |  [optional] |
|**taskEndTime** | **OffsetDateTime** | The time that the snapshot or cluster export task ended. |  [optional] |
|**s3Bucket** | **String** | The Amazon S3 bucket that the snapshot or cluster is exported to. |  [optional] |
|**s3Prefix** | **String** | The Amazon S3 bucket prefix that is the file name and path of the exported data. |  [optional] |
|**iamRoleArn** | **String** | The name of the IAM role that is used to write to Amazon S3 when exporting a snapshot or cluster. |  [optional] |
|**kmsKeyId** | **String** | The key identifier of the Amazon Web Services KMS key that is used to encrypt the data when it&#39;s exported to Amazon S3. The KMS key identifier is its key ARN, key ID, alias ARN, or alias name. The IAM role used for the export must have encryption and decryption permissions to use this KMS key. |  [optional] |
|**status** | **String** | &lt;p&gt;The progress status of the export task. The status can be one of the following:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;CANCELED&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;CANCELING&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;COMPLETE&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;FAILED&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;IN_PROGRESS&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;STARTING&lt;/code&gt; &lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; |  [optional] |
|**percentProgress** | **Integer** | The progress of the snapshot or cluster export task as a percentage. |  [optional] |
|**totalExtractedDataInGB** | **Integer** | The total amount of data exported, in gigabytes. |  [optional] |
|**failureCause** | **String** | The reason the export failed, if it failed. |  [optional] |
|**warningMessage** | **String** | A warning about the snapshot or cluster export task. |  [optional] |
|**sourceType** | **ExportSourceType** | The type of source for the export. |  [optional] |



