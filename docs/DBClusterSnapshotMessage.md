

# DBClusterSnapshotMessage

Provides a list of DB cluster snapshots for the user as the result of a call to the <code>DescribeDBClusterSnapshots</code> action.

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**marker** | **String** | An optional pagination token provided by a previous &lt;code&gt;DescribeDBClusterSnapshots&lt;/code&gt; request. If this parameter is specified, the response includes only records beyond the marker, up to the value specified by &lt;code&gt;MaxRecords&lt;/code&gt;. |  [optional] |
|**dbClusterSnapshots** | [**List&lt;DBClusterSnapshot&gt;**](DBClusterSnapshot.md) | Provides a list of DB cluster snapshots for the user. |  [optional] |



