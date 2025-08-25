

# RebootDBInstanceMessage

<p/>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**dbInstanceIdentifier** | **String** | &lt;p&gt;The DB instance identifier. This parameter is stored as a lowercase string.&lt;/p&gt; &lt;p&gt;Constraints:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt;Must match the identifier of an existing DBInstance.&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; |  |
|**forceFailover** | **Boolean** | &lt;p&gt;A value that indicates whether the reboot is conducted through a Multi-AZ failover.&lt;/p&gt; &lt;p&gt;Constraint: You can&#39;t enable force failover if the instance isn&#39;t configured for Multi-AZ.&lt;/p&gt; |  [optional] |



