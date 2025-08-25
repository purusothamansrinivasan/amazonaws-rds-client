

# DBInstanceAutomatedBackupMessage

Contains the result of a successful invocation of the <code>DescribeDBInstanceAutomatedBackups</code> action.

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**marker** | **String** | An optional pagination token provided by a previous request. If this parameter is specified, the response includes only records beyond the marker, up to the value specified by &lt;code&gt;MaxRecords&lt;/code&gt;. |  [optional] |
|**dbInstanceAutomatedBackups** | [**List&lt;DBInstanceAutomatedBackup&gt;**](DBInstanceAutomatedBackup.md) | A list of &lt;code&gt;DBInstanceAutomatedBackup&lt;/code&gt; instances. |  [optional] |



