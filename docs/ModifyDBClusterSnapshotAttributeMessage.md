

# ModifyDBClusterSnapshotAttributeMessage

<p/>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**dbClusterSnapshotIdentifier** | **String** | The identifier for the DB cluster snapshot to modify the attributes for. |  |
|**attributeName** | **String** | &lt;p&gt;The name of the DB cluster snapshot attribute to modify.&lt;/p&gt; &lt;p&gt;To manage authorization for other Amazon Web Services accounts to copy or restore a manual DB cluster snapshot, set this value to &lt;code&gt;restore&lt;/code&gt;.&lt;/p&gt; &lt;note&gt; &lt;p&gt;To view the list of attributes available to modify, use the &lt;a&gt;DescribeDBClusterSnapshotAttributes&lt;/a&gt; API operation.&lt;/p&gt; &lt;/note&gt; |  |
|**valuesToAdd** | **List&lt;String&gt;** | &lt;p&gt;A list of DB cluster snapshot attributes to add to the attribute specified by &lt;code&gt;AttributeName&lt;/code&gt;.&lt;/p&gt; &lt;p&gt;To authorize other Amazon Web Services accounts to copy or restore a manual DB cluster snapshot, set this list to include one or more Amazon Web Services account IDs, or &lt;code&gt;all&lt;/code&gt; to make the manual DB cluster snapshot restorable by any Amazon Web Services account. Do not add the &lt;code&gt;all&lt;/code&gt; value for any manual DB cluster snapshots that contain private information that you don&#39;t want available to all Amazon Web Services accounts.&lt;/p&gt; |  [optional] |
|**valuesToRemove** | **List&lt;String&gt;** | &lt;p&gt;A list of DB cluster snapshot attributes to remove from the attribute specified by &lt;code&gt;AttributeName&lt;/code&gt;.&lt;/p&gt; &lt;p&gt;To remove authorization for other Amazon Web Services accounts to copy or restore a manual DB cluster snapshot, set this list to include one or more Amazon Web Services account identifiers, or &lt;code&gt;all&lt;/code&gt; to remove authorization for any Amazon Web Services account to copy or restore the DB cluster snapshot. If you specify &lt;code&gt;all&lt;/code&gt;, an Amazon Web Services account whose account ID is explicitly added to the &lt;code&gt;restore&lt;/code&gt; attribute can still copy or restore a manual DB cluster snapshot.&lt;/p&gt; |  [optional] |



