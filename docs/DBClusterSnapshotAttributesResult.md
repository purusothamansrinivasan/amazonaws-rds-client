

# DBClusterSnapshotAttributesResult

<p>Contains the results of a successful call to the <code>DescribeDBClusterSnapshotAttributes</code> API action.</p> <p>Manual DB cluster snapshot attributes are used to authorize other Amazon Web Services accounts to copy or restore a manual DB cluster snapshot. For more information, see the <code>ModifyDBClusterSnapshotAttribute</code> API action.</p>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**dbClusterSnapshotIdentifier** | **String** | The identifier of the manual DB cluster snapshot that the attributes apply to. |  [optional] |
|**dbClusterSnapshotAttributes** | [**List&lt;DBClusterSnapshotAttribute&gt;**](DBClusterSnapshotAttribute.md) | The list of attributes and values for the manual DB cluster snapshot. |  [optional] |



