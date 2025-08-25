

# UpgradeTarget

The version of the database engine that a DB instance can be upgraded to.

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**engine** | **String** | The name of the upgrade target database engine. |  [optional] |
|**engineVersion** | **String** | The version number of the upgrade target database engine. |  [optional] |
|**description** | **String** | The version of the database engine that a DB instance can be upgraded to. |  [optional] |
|**autoUpgrade** | **Boolean** | A value that indicates whether the target version is applied to any source DB instances that have &lt;code&gt;AutoMinorVersionUpgrade&lt;/code&gt; set to true. |  [optional] |
|**isMajorVersionUpgrade** | **Boolean** | A value that indicates whether upgrading to the target version requires upgrading the major version of the database engine. |  [optional] |
|**supportedEngineModes** | **List&lt;String&gt;** | A list of the supported DB engine modes for the target engine version. |  [optional] |
|**supportsParallelQuery** | **Boolean** | A value that indicates whether you can use Aurora parallel query with the target engine version. |  [optional] |
|**supportsGlobalDatabases** | **Boolean** | A value that indicates whether you can use Aurora global databases with the target engine version. |  [optional] |
|**supportsBabelfish** | **Boolean** | A value that indicates whether you can use Babelfish for Aurora PostgreSQL with the target engine version. |  [optional] |
|**supportsLocalWriteForwarding** | **Boolean** | &lt;p&gt;A value that indicates whether the target engine version supports forwarding write operations from reader DB instances to the writer DB instance in the DB cluster. By default, write operations aren&#39;t allowed on reader DB instances.&lt;/p&gt; &lt;p&gt;Valid for: Aurora DB clusters only&lt;/p&gt; |  [optional] |



