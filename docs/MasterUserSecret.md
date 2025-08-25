

# MasterUserSecret

<p>Contains the secret managed by RDS in Amazon Web Services Secrets Manager for the master user password.</p> <p>For more information, see <a href=\"https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/rds-secrets-manager.html\">Password management with Amazon Web Services Secrets Manager</a> in the <i>Amazon RDS User Guide</i> and <a href=\"https://docs.aws.amazon.com/AmazonRDS/latest/AuroraUserGuide/rds-secrets-manager.html\">Password management with Amazon Web Services Secrets Manager</a> in the <i>Amazon Aurora User Guide.</i> </p>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**secretArn** | **String** | The Amazon Resource Name (ARN) of the secret. |  [optional] |
|**secretStatus** | **String** | &lt;p&gt;The status of the secret.&lt;/p&gt; &lt;p&gt;The possible status values include the following:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;creating&lt;/code&gt; - The secret is being created.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;active&lt;/code&gt; - The secret is available for normal use and rotation.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;rotating&lt;/code&gt; - The secret is being rotated.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;impaired&lt;/code&gt; - The secret can be used to access database credentials, but it can&#39;t be rotated. A secret might have this status if, for example, permissions are changed so that RDS can no longer access either the secret or the KMS key for the secret.&lt;/p&gt; &lt;p&gt;When a secret has this status, you can correct the condition that caused the status. Alternatively, modify the DB instance to turn off automatic management of database credentials, and then modify the DB instance again to turn on automatic management of database credentials.&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; |  [optional] |
|**kmsKeyId** | **String** | The Amazon Web Services KMS key identifier that is used to encrypt the secret. |  [optional] |



