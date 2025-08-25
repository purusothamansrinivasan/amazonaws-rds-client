

# DBClusterCapacityInfo


## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**dbClusterIdentifier** | **String** | A user-supplied DB cluster identifier. This identifier is the unique key that identifies a DB cluster. |  [optional] |
|**pendingCapacity** | **Integer** | A value that specifies the capacity that the DB cluster scales to next. |  [optional] |
|**currentCapacity** | **Integer** | The current capacity of the DB cluster. |  [optional] |
|**secondsBeforeTimeout** | **Integer** | The number of seconds before a call to &lt;code&gt;ModifyCurrentDBClusterCapacity&lt;/code&gt; times out. |  [optional] |
|**timeoutAction** | **String** | The timeout action of a call to &lt;code&gt;ModifyCurrentDBClusterCapacity&lt;/code&gt;, either &lt;code&gt;ForceApplyCapacityChange&lt;/code&gt; or &lt;code&gt;RollbackCapacityChange&lt;/code&gt;. |  [optional] |



