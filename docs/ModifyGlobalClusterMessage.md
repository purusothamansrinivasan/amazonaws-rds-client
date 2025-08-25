

# ModifyGlobalClusterMessage


## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**globalClusterIdentifier** | **String** | &lt;p&gt;The cluster identifier for the global cluster to modify. This parameter isn&#39;t case-sensitive.&lt;/p&gt; &lt;p&gt;Constraints:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt;Must match the identifier of an existing global database cluster.&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; |  [optional] |
|**newGlobalClusterIdentifier** | **String** | &lt;p&gt;The new cluster identifier for the global database cluster. This value is stored as a lowercase string.&lt;/p&gt; &lt;p&gt;Constraints:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt;Must contain from 1 to 63 letters, numbers, or hyphens.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt;The first character must be a letter.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt;Can&#39;t end with a hyphen or contain two consecutive hyphens.&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; &lt;p&gt;Example: &lt;code&gt;my-cluster2&lt;/code&gt; &lt;/p&gt; |  [optional] |
|**deletionProtection** | **Boolean** | Specifies whether to enable deletion protection for the global database cluster. The global database cluster can&#39;t be deleted when deletion protection is enabled. |  [optional] |
|**engineVersion** | **String** | &lt;p&gt;The version number of the database engine to which you want to upgrade. &lt;/p&gt; &lt;p&gt;To list all of the available engine versions for &lt;code&gt;aurora-mysql&lt;/code&gt; (for MySQL-based Aurora global databases), use the following command:&lt;/p&gt; &lt;p&gt; &lt;code&gt;aws rds describe-db-engine-versions --engine aurora-mysql --query &#39;*[]|[?SupportsGlobalDatabases &#x3D;&#x3D; &#x60;true&#x60;].[EngineVersion]&#39;&lt;/code&gt; &lt;/p&gt; &lt;p&gt;To list all of the available engine versions for &lt;code&gt;aurora-postgresql&lt;/code&gt; (for PostgreSQL-based Aurora global databases), use the following command:&lt;/p&gt; &lt;p&gt; &lt;code&gt;aws rds describe-db-engine-versions --engine aurora-postgresql --query &#39;*[]|[?SupportsGlobalDatabases &#x3D;&#x3D; &#x60;true&#x60;].[EngineVersion]&#39;&lt;/code&gt; &lt;/p&gt; |  [optional] |
|**allowMajorVersionUpgrade** | **Boolean** | &lt;p&gt;Specifies whether to allow major version upgrades.&lt;/p&gt; &lt;p&gt;Constraints: Must be enabled if you specify a value for the &lt;code&gt;EngineVersion&lt;/code&gt; parameter that&#39;s a different major version than the global cluster&#39;s current version.&lt;/p&gt; &lt;p&gt;If you upgrade the major version of a global database, the cluster and DB instance parameter groups are set to the default parameter groups for the new version. Apply any custom parameter groups after completing the upgrade.&lt;/p&gt; |  [optional] |



