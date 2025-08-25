

# ValidStorageOptions

Information about valid modifications that you can make to your DB instance. Contains the result of a successful call to the <code>DescribeValidDBInstanceModifications</code> action.

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**storageType** | **String** | The valid storage types for your DB instance. For example: gp2, gp3, io1. |  [optional] |
|**storageSize** | [**List&lt;Range&gt;**](Range.md) | The valid range of storage in gibibytes (GiB). For example, 100 to 16,384. |  [optional] |
|**provisionedIops** | [**List&lt;Range&gt;**](Range.md) | The valid range of provisioned IOPS. For example, 1000-256,000. |  [optional] |
|**iopsToStorageRatio** | [**List&lt;DoubleRange&gt;**](DoubleRange.md) | The valid range of Provisioned IOPS to gibibytes of storage multiplier. For example, 3-10, which means that provisioned IOPS can be between 3 and 10 times storage. |  [optional] |
|**supportsStorageAutoscaling** | **Boolean** | Whether or not Amazon RDS can automatically scale storage for DB instances that use the new instance class. |  [optional] |
|**provisionedStorageThroughput** | [**List&lt;Range&gt;**](Range.md) | The valid range of provisioned storage throughput. For example, 500-4,000 mebibytes per second (MiBps). |  [optional] |
|**storageThroughputToIopsRatio** | [**List&lt;DoubleRange&gt;**](DoubleRange.md) | The valid range of storage throughput to provisioned IOPS ratios. For example, 0-0.25. |  [optional] |



