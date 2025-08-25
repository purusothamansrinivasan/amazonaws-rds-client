

# DBSnapshotAttributesResult

<p>Contains the results of a successful call to the <code>DescribeDBSnapshotAttributes</code> API action.</p> <p>Manual DB snapshot attributes are used to authorize other Amazon Web Services accounts to copy or restore a manual DB snapshot. For more information, see the <code>ModifyDBSnapshotAttribute</code> API action.</p>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**dbSnapshotIdentifier** | **String** | The identifier of the manual DB snapshot that the attributes apply to. |  [optional] |
|**dbSnapshotAttributes** | [**List&lt;DBSnapshotAttribute&gt;**](DBSnapshotAttribute.md) | The list of attributes and values for the manual DB snapshot. |  [optional] |



