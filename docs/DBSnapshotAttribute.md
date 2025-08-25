

# DBSnapshotAttribute

<p>Contains the name and values of a manual DB snapshot attribute</p> <p>Manual DB snapshot attributes are used to authorize other Amazon Web Services accounts to restore a manual DB snapshot. For more information, see the <code>ModifyDBSnapshotAttribute</code> API.</p>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**attributeName** | **String** | &lt;p&gt;The name of the manual DB snapshot attribute.&lt;/p&gt; &lt;p&gt;The attribute named &lt;code&gt;restore&lt;/code&gt; refers to the list of Amazon Web Services accounts that have permission to copy or restore the manual DB cluster snapshot. For more information, see the &lt;code&gt;ModifyDBSnapshotAttribute&lt;/code&gt; API action.&lt;/p&gt; |  [optional] |
|**attributeValues** | **List&lt;String&gt;** | &lt;p&gt;The value or values for the manual DB snapshot attribute.&lt;/p&gt; &lt;p&gt;If the &lt;code&gt;AttributeName&lt;/code&gt; field is set to &lt;code&gt;restore&lt;/code&gt;, then this element returns a list of IDs of the Amazon Web Services accounts that are authorized to copy or restore the manual DB snapshot. If a value of &lt;code&gt;all&lt;/code&gt; is in the list, then the manual DB snapshot is public and available for any Amazon Web Services account to copy or restore.&lt;/p&gt; |  [optional] |



