# AWS Pagination Rules

## JS SDK

Service | Request Key | Response Key
--- | --- | ---
ACM | NextToken | NextToken
ACMPCA | NextToken | NextToken
AlexaForBusiness | NextToken | NextToken
Amplify | nextToken | nextToken
APIGateway | position | position
ApiGatewayManagementApi | N/A | N/A
ApiGatewayV2 | NextToken | NextToken
ApplicationAutoScaling | NextToken | NextToken
ApplicationInsights | NextToken | NextToken
AppMesh | nextToken | nextToken
AppStream | NextToken | NextToken
AppSync | nextToken | nextToken
Athena | NextToken | NextToken
AutoScaling | NextToken | NextToken
AutoScalingPlans | NextToken | NextToken
Backup | NextToken | NextToken
Batch | nextToken | nextToken
Budgets | NextToken | NextToken
Chime | NextToken | NextToken
Cloud9 | nextToken | nextToken
CloudDirectory | NextToken | NextToken
CloudFormation | NextToken | NextToken
CloudFront | Marker | _dict[0]_.NextMarker
CloudHSM | NextToken | NextToken
CloudHSMV2 | NextToken | NextToken
CloudSearch | N/A | N/A
CloudSearchDomain | N/A | N/A
CloudTrail | NextToken | NextToken
CloudWatch | NextToken | NextToken
CloudWatchEvents | NextToken | NextToken
CloudWatchLogs | nextToken | nextToken
CodeBuild | nextToken | nextToken
CodeCommit | nextToken | nextToken
CodeDeploy | nextToken | nextToken
CodePipeline | nextToken | nextToken
CodeStar | nextToken | nextToken
CognitoIdentity | NextToken | NextToken
CognitoIdentityServiceProvider | NextToken | NextToken
CognitoSync | NextToken | NextToken
Comprehend | NextToken | NextToken
ComprehendMedical | NextToken | NextToken
ConfigService | nextToken | nextToken
Connect | NextToken | NextToken
CostExplorer | NextPageToken | NextPageToken
CUR | NextToken | NextToken
DataPipeline | marker | marker
DataSync | NextToken | NextToken
DAX | NextToken | NextToken
DeviceFarm | nextToken | nextToken
DirectConnect | nextToken | nextToken
DirectoryService | NextToken | NextToken
Discovery | nextToken | nextToken
DLM | N/A | N/A
DMS | Marker | Marker
DocDB | Marker | Marker
DynamoDB | * | *
DynamoDBStreams | * | *
EC2 | NextToken | NextToken
EC2InstanceConnect | N/A | N/A
ECR | nextToken | nextToken
ECS | nextToken | nextToken
EFS | Marker | NextMarker
EKS | nextToken | nextToken
ElastiCache | Marker | Marker
ElasticBeanstalk | NextToken | NextToken
ElasticTranscoder | PageToken | NextPageToken
ELB | Marker | NextMarker
ELBv2 | Marker | NextMarker
EMR | Marker | Marker
ES | NextToken | NextToken
...