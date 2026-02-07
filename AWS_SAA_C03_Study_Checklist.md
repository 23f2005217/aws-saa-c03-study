# AWS Solutions Architect - Associate (SAA-C03)

## Domain 1: Design Secure Architectures (30%)

### Task 1.1: Design Secure Access to AWS Resources

- [ ] Learn AWS shared responsibility model
- [ ] Configure IAM users, groups, roles, and policies
- [ ] Implement MFA for root users and IAM users
- [ ] Design role-based access control with STS
- [ ] Configure cross-account access strategies
- [ ] Implement federated access with IAM Identity Center
- [ ] Design multi-account security with AWS Control Tower
- [ ] Apply service control policies (SCPs)
- [ ] Configure resource policies for AWS services
- [ ] Integrate directory services with IAM roles

### Task 1.2: Design Secure Workloads and Applications

- [ ] Design VPC architectures with security groups
- [ ] Configure network ACLs and route tables
- [ ] Implement NAT gateways for private subnets
- [ ] Design network segmentation strategies
- [ ] Secure application endpoints
- [ ] Configure AWS WAF for web applications
- [ ] Implement AWS Shield for DDoS protection
- [ ] Integrate AWS GuardDuty for threat detection
- [ ] Use AWS Secrets Manager for credentials
- [ ] Secure external connections with VPN
- [ ] Configure AWS Direct Connect
- [ ] Map threat vectors (DDoS, SQL injection)

### Task 1.3: Determine Data Security Controls

- [ ] Implement encryption at rest with AWS KMS
- [ ] Configure encryption in transit with ACM
- [ ] Manage TLS certificates
- [ ] Design key rotation strategies
- [ ] Implement access policies for encryption keys
- [ ] Classify and label data
- [ ] Design data backup strategies
- [ ] Configure cross-region replication
- [ ] Implement data lifecycle policies
- [ ] Align AWS technologies with compliance requirements
- [ ] Use AWS Macie for sensitive data discovery

### Domain 1 Revision

- [ ] Review IAM policy syntax and evaluation logic
- [ ] Compare security group vs network ACL behavior
- [ ] Verify understanding of encryption key hierarchies
- [ ] Test knowledge of federated identity flows
- [ ] Confirm multi-account security patterns

## Domain 2: Design Resilient Architectures (26%)

### Task 2.1: Design Scalable and Loosely Coupled Architectures

- [ ] Learn microservices design principles
- [ ] Compare stateless vs stateful workloads
- [ ] Design event-driven architectures
- [ ] Configure Amazon API Gateway
- [ ] Implement REST API patterns
- [ ] Design queuing with Amazon SQS
- [ ] Configure pub/sub with Amazon SNS
- [ ] Implement caching strategies
- [ ] Configure Application Load Balancer
- [ ] Design multi-tier architectures
- [ ] Orchestrate containers with Amazon ECS
- [ ] Manage Kubernetes with Amazon EKS
- [ ] Implement serverless with AWS Lambda
- [ ] Configure AWS Fargate
- [ ] Design workflow orchestration with Step Functions
- [ ] Compare horizontal vs vertical scaling
- [ ] Configure read replicas for databases
- [ ] Implement edge caching with CloudFront

### Task 2.2: Design Highly Available and Fault-Tolerant Architectures

- [ ] Learn AWS global infrastructure (Regions, AZs)
- [ ] Design failover strategies across AZs
- [ ] Implement multi-region architectures
- [ ] Configure Amazon Route 53 for DNS failover
- [ ] Design disaster recovery strategies
- [ ] Compare RPO and RTO requirements
- [ ] Implement backup and restore patterns
- [ ] Design pilot light DR strategy
- [ ] Configure warm standby architectures
- [ ] Implement active-active failover
- [ ] Use immutable infrastructure patterns
- [ ] Configure RDS Proxy for database resilience
- [ ] Implement distributed design patterns
- [ ] Monitor workload health with AWS X-Ray
- [ ] Configure service quotas and throttling
- [ ] Design storage for durability and availability
- [ ] Automate infrastructure integrity checks

### Domain 2 Revision

- [ ] Review scaling strategies for each service
- [ ] Compare DR strategies and their trade-offs
- [ ] Verify understanding of Route 53 routing policies
- [ ] Test knowledge of container orchestration options
- [ ] Confirm messaging patterns (SQS vs SNS vs EventBridge)

## Domain 3: Design High-Performing Architectures (24%)

### Task 3.1: Determine High-Performing Storage Solutions

- [ ] Compare S3, EFS, and EBS use cases
- [ ] Learn storage types (object, file, block)
- [ ] Design hybrid storage solutions
- [ ] Configure storage for performance requirements
- [ ] Implement storage scaling strategies
- [ ] Optimize S3 performance patterns
- [ ] Configure EFS performance modes
- [ ] Design EBS volume types for workloads

### Task 3.2: Design High-Performing Compute Solutions

- [ ] Select EC2 instance types and families
- [ ] Configure EC2 Auto Scaling policies
- [ ] Implement AWS Auto Scaling
- [ ] Design serverless compute with Lambda
- [ ] Optimize Lambda memory and concurrency
- [ ] Configure containerized compute with Fargate
- [ ] Implement batch processing with AWS Batch
- [ ] Design distributed computing patterns
- [ ] Decouple workloads for independent scaling
- [ ] Configure scaling metrics and triggers
- [ ] Learn AWS compute services use cases
- [ ] Optimize compute utilization

### Task 3.3: Determine High-Performing Database Solutions

- [ ] Compare database engines (MySQL, PostgreSQL)
- [ ] Select database types (RDS, Aurora, DynamoDB)
- [ ] Design database architectures
- [ ] Configure read replicas
- [ ] Implement caching with ElastiCache
- [ ] Plan database capacity (IOPS, instance types)
- [ ] Configure database proxies
- [ ] Compare read-intensive vs write-intensive patterns
- [ ] Design heterogeneous database migrations
- [ ] Compare relational vs non-relational databases

### Task 3.4: Determine High-Performing Network Architectures

- [ ] Design network topology (global, hybrid, multi-tier)
- [ ] Configure subnet tiers and routing
- [ ] Implement IP addressing strategies
- [ ] Select load balancing strategies
- [ ] Configure Application Load Balancer
- [ ] Compare ALB, NLB, and GLB use cases
- [ ] Design edge networking with CloudFront
- [ ] Implement AWS Global Accelerator
- [ ] Configure network connectivity options
- [ ] Design scalable network configurations
- [ ] Optimize resource placement

### Task 3.5: Determine Data Ingestion and Transformation Solutions

- [ ] Design data streaming with Amazon Kinesis
- [ ] Build data lakes with Lake Formation
- [ ] Implement data transfer with AWS DataSync
- [ ] Configure Storage Gateway for hybrid
- [ ] Use AWS Glue for data transformation
- [ ] Query data with Amazon Athena
- [ ] Visualize data with Amazon QuickSight
- [ ] Transform data formats (CSV to Parquet)
- [ ] Select compute for data processing (EMR)
- [ ] Configure ingestion access points
- [ ] Design data analytics architectures

### Domain 3 Revision

- [ ] Review storage performance characteristics
- [ ] Compare database service options
- [ ] Verify understanding of caching strategies
- [ ] Test knowledge of load balancer types
- [ ] Confirm streaming data patterns

## Domain 4: Design Cost-Optimized Architectures (20%)

### Task 4.1: Design Cost-Optimized Storage Solutions

- [ ] Compare S3 storage classes
- [ ] Configure S3 lifecycle policies
- [ ] Implement intelligent tiering
- [ ] Design backup and archival strategies
- [ ] Compare EBS volume types (HDD vs SSD)
- [ ] Select cost-effective storage services
- [ ] Configure storage auto scaling
- [ ] Optimize data transfer costs
- [ ] Design hybrid storage (DataSync, Transfer Family)
- [ ] Manage S3 object lifecycles
- [ ] Configure Requester Pays buckets
- [ ] Monitor storage costs

### Task 4.2: Design Cost-Optimized Compute Solutions

- [ ] Compare EC2 purchasing options
- [ ] Configure Spot Instances
- [ ] Implement Reserved Instances
- [ ] Apply Savings Plans
- [ ] Select appropriate instance families
- [ ] Right-size compute resources
- [ ] Configure compute auto scaling
- [ ] Implement EC2 hibernation
- [ ] Compare Lambda, EC2, and Fargate costs
- [ ] Design distributed compute strategies
- [ ] Configure hybrid compute (Outposts, Snowball)
- [ ] Monitor compute costs

### Task 4.3: Design Cost-Optimized Database Solutions

- [ ] Compare RDS vs DynamoDB costs
- [ ] Select serverless database options
- [ ] Configure read replicas for scaling
- [ ] Implement caching to reduce costs
- [ ] Design backup and retention policies
- [ ] Compare database engine costs
- [ ] Select cost-effective database types
- [ ] Plan database capacity units
- [ ] Migrate schemas for cost optimization
- [ ] Monitor database costs

### Task 4.4: Design Cost-Optimized Network Architectures

- [ ] Compare NAT gateway configurations
- [ ] Optimize VPC peering vs Transit Gateway
- [ ] Configure cost-effective network connections
- [ ] Compare Direct Connect vs VPN costs
- [ ] Design CDN strategies with CloudFront
- [ ] Optimize cross-AZ and cross-Region traffic
- [ ] Configure VPC endpoints
- [ ] Implement throttling strategies
- [ ] Optimize bandwidth allocation
- [ ] Review network transfer costs
- [ ] Monitor network costs

### Domain 4 Revision

- [ ] Review storage tier pricing models
- [ ] Compare compute purchasing options
- [ ] Verify understanding of data transfer costs
- [ ] Test knowledge of NAT gateway pricing
- [ ] Confirm right-sizing strategies

## In-Scope AWS Services by Category

### Analytics

- [ ] Amazon Athena
- [ ] AWS Data Exchange
- [ ] AWS Data Pipeline
- [ ] Amazon EMR
- [ ] AWS Glue
- [ ] Amazon Kinesis
- [ ] AWS Lake Formation
- [ ] Amazon MSK
- [ ] Amazon OpenSearch Service
- [ ] Amazon QuickSight
- [ ] Amazon Redshift

### Application Integration

- [ ] Amazon AppFlow
- [ ] AWS AppSync
- [ ] Amazon EventBridge
- [ ] Amazon MQ
- [ ] Amazon SNS
- [ ] Amazon SQS
- [ ] AWS Step Functions

### AWS Cost Management

- [ ] AWS Budgets
- [ ] AWS Cost and Usage Report
- [ ] AWS Cost Explorer
- [ ] Savings Plans

### Compute

- [ ] AWS Batch
- [ ] Amazon EC2
- [ ] Amazon EC2 Auto Scaling
- [ ] AWS Elastic Beanstalk
- [ ] AWS Outposts
- [ ] AWS Serverless Application Repository
- [ ] VMware Cloud on AWS
- [ ] AWS Wavelength

### Containers

- [ ] Amazon ECS Anywhere
- [ ] Amazon EKS Anywhere
- [ ] Amazon EKS Distro
- [ ] Amazon ECR
- [ ] Amazon ECS
- [ ] Amazon EKS

### Database

- [ ] Amazon Aurora
- [ ] Amazon Aurora Serverless
- [ ] Amazon DocumentDB
- [ ] Amazon DynamoDB
- [ ] Amazon ElastiCache
- [ ] Amazon Keyspaces
- [ ] Amazon Neptune
- [ ] Amazon QLDB
- [ ] Amazon RDS
- [ ] Amazon Redshift

### Developer Tools

- [ ] AWS X-Ray

### Front-End Web and Mobile

- [ ] AWS Amplify
- [ ] Amazon API Gateway
- [ ] AWS Device Farm
- [ ] Amazon Pinpoint

### Machine Learning

- [ ] Amazon Comprehend
- [ ] Amazon Forecast
- [ ] Amazon Fraud Detector
- [ ] Amazon Kendra
- [ ] Amazon Lex
- [ ] Amazon Polly
- [ ] Amazon Rekognition
- [ ] Amazon SageMaker
- [ ] Amazon Textract
- [ ] Amazon Transcribe
- [ ] Amazon Translate

### Management and Governance

- [ ] AWS Auto Scaling
- [ ] AWS CloudFormation
- [ ] AWS CloudTrail
- [ ] Amazon CloudWatch
- [ ] AWS CLI
- [ ] AWS Compute Optimizer
- [ ] AWS Config
- [ ] AWS Control Tower
- [ ] AWS Health Dashboard
- [ ] AWS License Manager
- [ ] Amazon Managed Grafana
- [ ] Amazon Managed Service for Prometheus
- [ ] AWS Management Console
- [ ] AWS Organizations
- [ ] AWS Proton
- [ ] AWS Service Catalog
- [ ] AWS Systems Manager
- [ ] AWS Trusted Advisor
- [ ] AWS Well-Architected Tool

### Media Services

- [ ] Amazon Elastic Transcoder
- [ ] Amazon Kinesis Video Streams

### Migration and Transfer

- [ ] AWS Application Discovery Service
- [ ] AWS Application Migration Service
- [ ] AWS DMS
- [ ] AWS DataSync
- [ ] AWS Migration Hub
- [ ] AWS Snow Family
- [ ] AWS Transfer Family

### Networking and Content Delivery

- [ ] AWS Client VPN
- [ ] Amazon CloudFront
- [ ] AWS Direct Connect
- [ ] Elastic Load Balancing
- [ ] AWS Global Accelerator
- [ ] AWS PrivateLink
- [ ] Amazon Route 53
- [ ] AWS Site-to-Site VPN
- [ ] AWS Transit Gateway
- [ ] Amazon VPC

### Security, Identity, and Compliance

- [ ] AWS Artifact
- [ ] AWS Audit Manager
- [ ] AWS Certificate Manager
- [ ] AWS CloudHSM
- [ ] Amazon Cognito
- [ ] Amazon Detective
- [ ] AWS Directory Service
- [ ] AWS Firewall Manager
- [ ] Amazon GuardDuty
- [ ] AWS IAM Identity Center
- [ ] AWS Identity and Access Management
- [ ] Amazon Inspector
- [ ] AWS Key Management Service
- [ ] Amazon Macie
- [ ] AWS Network Firewall
- [ ] AWS Resource Access Manager
- [ ] AWS Secrets Manager
- [ ] AWS Security Hub
- [ ] AWS Shield
- [ ] AWS WAF

### Serverless

- [ ] AWS AppSync
- [ ] AWS Fargate
- [ ] AWS Lambda

### Storage

- [ ] AWS Backup
- [ ] Amazon EBS
- [ ] Amazon EFS
- [ ] Amazon FSx
- [ ] Amazon S3
- [ ] Amazon S3 Glacier
- [ ] AWS Storage Gateway

## Final Review Checklist

- [ ] Review all 4 domains thoroughly
- [ ] Practice designing secure architectures
- [ ] Practice designing resilient architectures
- [ ] Practice designing high-performing architectures
- [ ] Practice designing cost-optimized architectures
- [ ] Complete hands-on labs for key services
- [ ] Review AWS Well-Architected Framework pillars
- [ ] Take practice exams
- [ ] Review incorrect answers
- [ ] Schedule exam when consistently scoring 80%+
