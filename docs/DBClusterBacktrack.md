

# DBClusterBacktrack

This data type is used as a response element in the <code>DescribeDBClusterBacktracks</code> action.

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**dbClusterIdentifier** | **String** | Contains a user-supplied DB cluster identifier. This identifier is the unique key that identifies a DB cluster. |  [optional] |
|**backtrackIdentifier** | **String** | Contains the backtrack identifier. |  [optional] |
|**backtrackTo** | **OffsetDateTime** | The timestamp of the time to which the DB cluster was backtracked. |  [optional] |
|**backtrackedFrom** | **OffsetDateTime** | The timestamp of the time from which the DB cluster was backtracked. |  [optional] |
|**backtrackRequestCreationTime** | **OffsetDateTime** | The timestamp of the time at which the backtrack was requested. |  [optional] |
|**status** | **String** | &lt;p&gt;The status of the backtrack. This property returns one of the following values:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;applying&lt;/code&gt; - The backtrack is currently being applied to or rolled back from the DB cluster.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;completed&lt;/code&gt; - The backtrack has successfully been applied to or rolled back from the DB cluster.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;failed&lt;/code&gt; - An error occurred while the backtrack was applied to or rolled back from the DB cluster.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt; &lt;code&gt;pending&lt;/code&gt; - The backtrack is currently pending application to or rollback from the DB cluster.&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; |  [optional] |



