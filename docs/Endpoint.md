

# Endpoint

<p>This data type represents the information you need to connect to an Amazon RDS DB instance. This data type is used as a response element in the following actions:</p> <ul> <li> <p> <code>CreateDBInstance</code> </p> </li> <li> <p> <code>DescribeDBInstances</code> </p> </li> <li> <p> <code>DeleteDBInstance</code> </p> </li> </ul> <p>For the data structure that represents Amazon Aurora DB cluster endpoints, see <code>DBClusterEndpoint</code>.</p>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**address** | **String** | Specifies the DNS address of the DB instance. |  [optional] |
|**port** | **Integer** | Specifies the port that the database engine is listening on. |  [optional] |
|**hostedZoneId** | **String** | Specifies the ID that Amazon Route 53 assigns when you create a hosted zone. |  [optional] |



