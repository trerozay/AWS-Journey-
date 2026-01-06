# AWS-Journey-
Follow my journey of learning AWS, and the cloud 

## AWS Certified Cloud Practitioner (CLF-C02) Study Guide

### Exam Overview
- **Exam Code**: CLF-C02
- **Duration**: 90 minutes
- **Question Format**: Multiple choice and multiple response
- **Number of Questions**: 65 questions
- **Passing Score**: 700/1000 (70%)
- **Cost**: $100 USD
- **Language**: Available in English, Japanese, Korean, and Simplified Chinese

### Exam Domains & Weighting

1. **Cloud Concepts** (24%)
   - Cloud value propositions
   - Cloud economics
   - AWS Cloud architectural principles

2. **Security and Compliance** (30%)
   - AWS shared responsibility model
   - AWS security services
   - AWS compliance and governance

3. **Cloud Technology and Services** (34%)
   - AWS services and their use cases
   - AWS Cloud global infrastructure
   - Core AWS services

4. **Billing, Pricing, and Support** (12%)
   - AWS pricing models
   - Account management
   - Billing and cost management tools

### Key Topics to Study

#### Cloud Concepts
- **Cloud Computing Models**:
  - Infrastructure as a Service (IaaS)
  - Platform as a Service (PaaS)
  - Software as a Service (SaaS)
- **Cloud Deployment Models**:
  - Public Cloud
  - Private Cloud
  - Hybrid Cloud
- **Cloud Benefits**:
  - Trade capital expense for variable expense
  - Benefit from massive economies of scale
  - Stop guessing capacity
  - Increase speed and agility
  - Stop spending money on running data centers
  - Go global in minutes
- **AWS Well-Architected Framework**:
  - Operational Excellence
  - Security
  - Reliability
  - Performance Efficiency
  - Cost Optimization
  - Sustainability

#### Core AWS Services

**Compute**:
- **EC2 (Elastic Compute Cloud)**: Virtual servers in the cloud
- **Lambda**: Serverless compute service
- **ECS (Elastic Container Service)**: Container management
- **Elastic Beanstalk**: Platform-as-a-Service for deploying applications

**Storage**:
- **S3 (Simple Storage Service)**: Object storage service
- **EBS (Elastic Block Store)**: Block storage for EC2 instances
- **EFS (Elastic File System)**: Managed file storage
- **Glacier**: Low-cost archival storage

**Database**:
- **RDS (Relational Database Service)**: Managed relational databases
- **DynamoDB**: NoSQL database service
- **Redshift**: Data warehousing service
- **Aurora**: High-performance relational database

**Networking**:
- **VPC (Virtual Private Cloud)**: Isolated network environment
- **CloudFront**: Content delivery network (CDN)
- **Route 53**: DNS and domain name registration
- **API Gateway**: API management service
- **Direct Connect**: Dedicated network connection to AWS

**Security & Identity**:
- **IAM (Identity and Access Management)**: User and access management
- **Cognito**: User authentication and authorization
- **KMS (Key Management Service)**: Encryption key management
- **Secrets Manager**: Secrets management
- **WAF (Web Application Firewall)**: Web application protection
- **Shield**: DDoS protection
- **GuardDuty**: Threat detection service

**Management & Monitoring**:
- **CloudWatch**: Monitoring and observability
- **CloudTrail**: API logging and auditing
- **Config**: Resource inventory and compliance
- **Systems Manager**: Operational insights and actions
- **Trusted Advisor**: Best practice recommendations

**Application Integration**:
- **SQS (Simple Queue Service)**: Message queuing service
- **SNS (Simple Notification Service)**: Pub/sub messaging
- **EventBridge**: Event-driven architecture

**Developer Tools**:
- **CodeCommit**: Source control service
- **CodeBuild**: Build service
- **CodeDeploy**: Deployment service
- **CodePipeline**: CI/CD service

**Migration & Transfer**:
- **Snow Family**: Physical data transfer devices
- **DataSync**: Automated data transfer
- **Migration Hub**: Migration tracking

**Analytics**:
- **Athena**: Query data in S3 using SQL
- **EMR (Elastic MapReduce)**: Big data processing
- **Kinesis**: Real-time data streaming
- **QuickSight**: Business intelligence service

**Machine Learning**:
- **SageMaker**: Machine learning platform
- **Rekognition**: Image and video analysis
- **Comprehend**: Natural language processing
- **Polly**: Text-to-speech service
- **Translate**: Translation service
- **Lex**: Conversational interfaces

**IoT**:
- **IoT Core**: Device connectivity and management

**Game Development**:
- **GameLift**: Game server hosting

#### Security & Compliance

**Shared Responsibility Model**:
- **AWS Responsibility**: Security OF the cloud (infrastructure, hardware, software, networking)
- **Customer Responsibility**: Security IN the cloud (data, platform/applications, identity/access management, encryption)

**Security Services**:
- IAM policies and roles
- MFA (Multi-Factor Authentication)
- Encryption at rest and in transit
- VPC security groups and NACLs
- AWS Organizations for account management
- AWS Artifact for compliance reports

**Compliance**:
- SOC (Service Organization Control)
- PCI DSS (Payment Card Industry Data Security Standard)
- HIPAA (Health Insurance Portability and Accountability Act)
- GDPR (General Data Protection Regulation)
- ISO certifications

#### Billing & Pricing

**Pricing Models**:
- **On-Demand**: Pay for compute capacity by the hour/second
- **Reserved Instances**: 1-3 year commitment for discounts (up to 75%)
- **Savings Plans**: Flexible pricing model with discounts
- **Spot Instances**: Bid on unused EC2 capacity (up to 90% discount)
- **Dedicated Hosts**: Physical EC2 server dedicated to your use

**Free Tier**:
- Always Free (e.g., Lambda 1M requests/month)
- 12 Months Free (e.g., EC2 t2.micro)
- Trials (e.g., GuardDuty 30-day trial)

**Cost Management Tools**:
- **AWS Cost Explorer**: Visualize and analyze costs
- **AWS Budgets**: Set custom cost and usage budgets
- **AWS Cost and Usage Reports**: Detailed billing data
- **Reserved Instance Reporting**: Track RI utilization
- **AWS Pricing Calculator**: Estimate costs

**Billing Concepts**:
- Consolidated billing (AWS Organizations)
- Cost allocation tags
- Resource groups
- Billing alerts

#### AWS Global Infrastructure

**Regions**: Geographic areas (e.g., us-east-1, eu-west-1)
- Each region is completely independent
- Choose regions based on latency, compliance, and cost

**Availability Zones (AZs)**: Data centers within a region
- Each AZ is isolated from failures in other AZs
- Connected via low-latency links
- Minimum 2 AZs per region

**Edge Locations**: Points of presence for CloudFront
- Used for caching content closer to users
- Located in major cities worldwide

**Regional Edge Caches**: Additional caching layer between CloudFront origin and edge locations

### AWS Terminology Glossary

#### Core Cloud Terms

**Availability Zone (AZ)**
- One or more discrete data centers with redundant power, networking, and connectivity
- Designed to be isolated from failures in other AZs
- Example: `us-east-1a`, `us-east-1b`, `us-east-1c`

**Region**
- Geographic area containing multiple Availability Zones
- Example: `us-east-1` (N. Virginia), `eu-west-1` (Ireland)

**Edge Location**
- Location where CloudFront caches content
- Located in major cities worldwide
- Reduces latency for end users

**VPC (Virtual Private Cloud)**
- Isolated virtual network in AWS cloud
- Complete control over virtual networking environment

**Subnet**
- Range of IP addresses in your VPC
- Public subnet: Has route to Internet Gateway
- Private subnet: No direct route to Internet Gateway

**Security Group**
- Virtual firewall for EC2 instances
- Controls inbound and outbound traffic
- Stateful (remembers previous connections)

**NACL (Network Access Control List)**
- Optional layer of security for VPC
- Controls traffic at subnet level
- Stateless (doesn't remember previous connections)

**Internet Gateway (IGW)**
- Horizontally scaled, redundant gateway
- Allows communication between VPC and internet

**NAT Gateway**
- Network Address Translation service
- Allows private subnets to access internet
- Managed by AWS

**Elastic IP**
- Static IPv4 address for dynamic cloud computing
- Associated with AWS account, not instance

**AMI (Amazon Machine Image)**
- Template for EC2 instances
- Contains OS, application server, applications

**Instance**
- Virtual server in AWS EC2
- Can be launched from AMI

**Snapshot**
- Point-in-time backup of EBS volume
- Stored in S3

**Bucket**
- Container for objects in S3
- Globally unique name
- Region-specific

**Object**
- File stored in S3 bucket
- Consists of data, key, and metadata

**Key**
- Unique identifier for object in S3 bucket
- Like a file path

**Versioning**
- S3 feature to keep multiple versions of objects
- Protects against accidental deletion

**Lifecycle Policy**
- Automates moving objects between storage classes
- Reduces storage costs

**Replication**
- Automatically copying objects across S3 buckets
- Cross-region or same-region

**Encryption**
- **At Rest**: Data encrypted when stored
- **In Transit**: Data encrypted during transmission
- **KMS**: Key Management Service for encryption keys

**IAM User**
- Person or application that interacts with AWS
- Has credentials (access key, password)

**IAM Group**
- Collection of IAM users
- Makes permissions management easier

**IAM Role**
- Set of permissions
- Assumed by users, applications, or services
- Temporary credentials

**IAM Policy**
- Document that defines permissions
- JSON format
- Attached to users, groups, or roles

**Root Account**
- Email address used to create AWS account
- Full access to all resources
- Should use MFA and avoid daily use

**MFA (Multi-Factor Authentication)**
- Additional layer of security
- Requires password + device-generated code

**CloudWatch**
- Monitoring and observability service
- Collects metrics, logs, and events

**CloudTrail**
- Service that logs API calls
- Audit trail of AWS account activity

**Event**
- Signal that system state has changed
- Triggers automated actions

**Lambda Function**
- Code that runs in response to events
- Serverless (no servers to manage)

**API Gateway**
- Service to create, publish, maintain APIs
- RESTful and WebSocket APIs

**CDN (Content Delivery Network)**
- Network of servers that deliver content
- CloudFront is AWS CDN service

**DNS (Domain Name System)**
- Translates domain names to IP addresses
- Route 53 is AWS DNS service

**Load Balancer**
- Distributes incoming traffic across targets
- Types: Application, Network, Classic, Gateway

**Auto Scaling**
- Automatically adjusts capacity
- Maintains performance and cost

**Elasticity**
- Ability to scale up or down quickly
- Match capacity to demand

**Scalability**
- Ability to handle growth
- Vertical (bigger) or Horizontal (more)

**High Availability**
- System designed to be operational 99.99% of time
- No single point of failure

**Fault Tolerance**
- System continues operating despite failures
- Redundancy built in

**Disaster Recovery**
- Process of restoring systems after disaster
- RTO (Recovery Time Objective) and RPO (Recovery Point Objective)

**Backup**
- Copy of data for recovery
- Can be automated

**Replication**
- Copying data to another location
- Synchronous or Asynchronous

**Multi-AZ Deployment**
- Deploying resources across multiple AZs
- Increases availability

**Read Replica**
- Copy of database for read operations
- Reduces load on primary database

**Primary Database**
- Main database for write operations
- Single source of truth

**Data Warehouse**
- Central repository of integrated data
- Redshift is AWS data warehouse

**ETL (Extract, Transform, Load)**
- Process of moving data
- Extract from source, Transform, Load to destination

**Streaming Data**
- Continuous flow of data
- Kinesis handles real-time streaming

**Batch Processing**
- Processing large volumes of data at once
- EMR handles batch processing

**Serverless**
- No server management required
- Pay only for compute time used
- Lambda, API Gateway, DynamoDB

**Container**
- Lightweight, portable package
- Contains application and dependencies
- ECS and EKS manage containers

**Orchestration**
- Automated arrangement and coordination
- ECS and Kubernetes orchestrate containers

**CI/CD (Continuous Integration/Continuous Deployment)**
- Automating software delivery
- CodePipeline provides CI/CD

**Infrastructure as Code (IaC)**
- Managing infrastructure through code
- CloudFormation, Terraform, CDK

**Stack**
- Collection of AWS resources
- Managed as single unit
- CloudFormation creates stacks

**Template**
- JSON or YAML file describing resources
- CloudFormation uses templates

**Tag**
- Key-value pair attached to resource
- Used for organization and billing

**Resource Group**
- Collection of resources sharing tags
- Simplifies management

**Billing Alarm**
- Notification when costs exceed threshold
- CloudWatch alarm for billing

**Cost Allocation Tag**
- Tag used to track costs
- Appears in billing reports

**Reserved Instance**
- EC2 instance reservation for 1-3 years
- Significant discount (up to 75%)

**Savings Plan**
- Flexible pricing model
- Commit to usage amount
- Applies to EC2, Lambda, Fargate

**Spot Instance**
- Unused EC2 capacity
- Up to 90% discount
- Can be interrupted

**On-Demand Instance**
- Pay for compute by hour/second
- No upfront commitment

**Dedicated Instance**
- EC2 instance on dedicated hardware
- No other customers share hardware

**Dedicated Host**
- Physical server dedicated to your use
- Full control over instance placement

**Free Tier**
- Free usage of AWS services
- Always Free, 12 Months Free, or Trials

**Consolidated Billing**
- Single bill for multiple accounts
- AWS Organizations feature

**Organization**
- Collection of AWS accounts
- Centralized management and billing

**Account**
- Container for AWS resources
- Billed separately unless consolidated

**Support Plan**
- Level of AWS support
- Basic, Developer, Business, Enterprise

**Service Limit**
- Maximum number of resources
- Can request limit increases

**Quota**
- Maximum number of resources
- Similar to service limit

**Region**
- Geographic area
- Independent of other regions

**Endpoint**
- URL to access AWS service
- Region-specific

**ARN (Amazon Resource Name)**
- Unique identifier for AWS resource
- Format: `arn:aws:service:region:account-id:resource`

**Account ID**
- 12-digit number
- Unique identifier for AWS account

**Access Key**
- Credential for programmatic access
- Access Key ID + Secret Access Key

**Secret Access Key**
- Secret credential
- Used with Access Key ID
- Never share publicly

**Session Token**
- Temporary credential
- Used with access keys
- Expires after set time

**STS (Security Token Service)**
- Service that provides temporary credentials
- Used for cross-account access

**Assume Role**
- Process of taking on IAM role
- Provides temporary credentials

**Trust Policy**
- Policy that defines who can assume role
- Part of IAM role

**Resource Policy**
- Policy attached to resource
- Defines who can access resource

**Bucket Policy**
- Resource policy for S3 bucket
- Defines bucket access permissions

**CORS (Cross-Origin Resource Sharing)**
- Allows web pages to access resources
- Configured in S3 bucket policy

**Pre-signed URL**
- URL with embedded authentication
- Grants temporary access to S3 object

**Transfer Acceleration**
- S3 feature for faster uploads
- Uses CloudFront edge locations

**Static Website Hosting**
- Hosting static website in S3
- No server required

**CloudFront Distribution**
- Configuration for CDN
- Defines origin and caching behavior

**Origin**
- Source of content for CloudFront
- S3 bucket, EC2, or custom origin

**Cache**
- Stored copy of content
- Reduces latency and bandwidth

**TTL (Time To Live)**
- How long content is cached
- Measured in seconds

**Invalidation**
- Removing cached content
- Forces CloudFront to fetch new content

**Route 53 Hosted Zone**
- Container for DNS records
- Represents domain

**DNS Record**
- Mapping of domain name to value
- Types: A, AAAA, CNAME, MX, TXT, etc.

**Health Check**
- Monitors resource health
- Route 53 uses for failover

**Failover**
- Switching to backup resource
- Automatic when primary fails

**Geolocation Routing**
- Route traffic based on user location
- Route 53 feature

**Latency-Based Routing**
- Route to lowest latency endpoint
- Route 53 feature

**Weighted Routing**
- Distribute traffic across resources
- Route 53 feature

**Database Instance**
- Isolated database environment
- RDS creates database instances

**DB Engine**
- Database software
- MySQL, PostgreSQL, Oracle, SQL Server, MariaDB, Aurora

**Multi-AZ**
- Deploy database across AZs
- Automatic failover

**Read Replica**
- Read-only copy of database
- Improves read performance

**Parameter Group**
- Container for database parameters
- Controls database behavior

**Option Group**
- Container for database options
- Enables additional features

**Backup Window**
- Time when automated backups occur
- Configurable

**Maintenance Window**
- Time when maintenance can occur
- Configurable

**Snapshot**
- Point-in-time backup
- Manual or automated

**Restore**
- Creating new database from backup
- Uses snapshot

**Point-in-Time Recovery**
- Restore to any point in time
- Uses transaction logs

**DynamoDB Table**
- Collection of items
- NoSQL database

**Item**
- Single record in DynamoDB
- Consists of attributes

**Attribute**
- Data element in DynamoDB item
- Key-value pair

**Primary Key**
- Uniquely identifies item
- Partition key or partition + sort key

**Partition Key**
- First part of primary key
- Determines item location

**Sort Key**
- Second part of primary key
- Orders items within partition

**Global Secondary Index (GSI)**
- Index with different partition key
- Enables different query patterns

**Local Secondary Index (LSI)**
- Index with same partition key
- Different sort key

**Provisioned Throughput**
- Read/write capacity units
- Must specify for table

**On-Demand**
- Pay-per-request pricing
- No capacity planning

**DynamoDB Streams**
- Time-ordered sequence of changes
- Enables real-time processing

**TTL (Time To Live)**
- Automatically delete items
- Based on timestamp

**ElastiCache**
- In-memory caching service
- Redis or Memcached

**Cache Cluster**
- Collection of cache nodes
- ElastiCache creates clusters

**Cache Node**
- Single cache server
- Part of cache cluster

**Parameter Group**
- Container for cache parameters
- Controls cache behavior

**Security Group**
- Firewall for cache cluster
- Controls network access

**Subnet Group**
- Collection of subnets
- Used for cache cluster placement

**VPC Peering**
- Connect two VPCs
- Private connectivity

**Transit Gateway**
- Central hub for VPC connections
- Simplifies network architecture

**VPN (Virtual Private Network)**
- Encrypted connection
- Site-to-Site or Client VPN

**Direct Connect**
- Dedicated network connection
- Bypasses internet

**Direct Connect Gateway**
- Connects multiple VPCs
- Uses Direct Connect

**Elastic Beanstalk**
- Platform-as-a-Service
- Deploys and manages applications

**Application**
- Logical collection of components
- Elastic Beanstalk application

**Environment**
- Version of application
- Runs on AWS resources

**Application Version**
- Specific code version
- Deployed to environment

**Platform**
- Operating system and runtime
- Elastic Beanstalk provides platforms

**Configuration**
- Settings for environment
- Can be saved and reused

**CloudFormation Stack**
- Collection of AWS resources
- Managed as single unit

**Stack Template**
- JSON or YAML file
- Describes stack resources

**Stack Update**
- Modify existing stack
- Uses change sets

**Change Set**
- Preview of stack changes
- Before applying update

**Drift Detection**
- Compare actual vs expected
- CloudFormation feature

**Nested Stack**
- Stack created within stack
- Modular templates

**Stack Set**
- Manage stacks across accounts
- CloudFormation feature

**Parameter**
- Input value for template
- Customizes stack

**Output**
- Value returned from stack
- Can be used by other stacks

**Resource**
- AWS service component
- Created by CloudFormation

**Condition**
- Control resource creation
- Based on parameter value

**Mapping**
- Key-value lookup table
- Used in templates

**Intrinsic Function**
- Built-in template function
- Ref, Fn::GetAtt, Fn::Join, etc.

**Ref**
- Returns value of parameter or resource
- CloudFormation function

**Fn::GetAtt**
- Returns attribute of resource
- CloudFormation function

**Fn::Join**
- Joins array of strings
- CloudFormation function

**CodePipeline**
- CI/CD service
- Automates release process

**Pipeline**
- Workflow for code changes
- CodePipeline pipeline

**Stage**
- Phase of pipeline
- Source, Build, Deploy, etc.

**Action**
- Task in stage
- Performs specific operation

**Artifact**
- File produced by action
- Passed to next stage

**Source Action**
- Retrieves source code
- CodeCommit, S3, GitHub, etc.

**Build Action**
- Compiles and tests code
- CodeBuild, Jenkins, etc.

**Deploy Action**
- Deploys application
- CodeDeploy, CloudFormation, etc.

**Approval Action**
- Manual approval step
- Pauses pipeline

**CodeCommit**
- Source control service
- Git-based

**Repository**
- Container for code
- CodeCommit repository

**Branch**
- Parallel version of code
- Git branch

**Commit**
- Snapshot of code changes
- Git commit

**Pull Request**
- Request to merge changes
- CodeCommit feature

**CodeBuild**
- Build service
- Compiles and tests code

**Build Project**
- Configuration for builds
- CodeBuild project

**Build Environment**
- Operating system and tools
- CodeBuild environment

**Buildspec**
- Build commands file
- YAML format

**CodeDeploy**
- Deployment service
- Deploys code to instances

**Deployment**
- Process of deploying code
- CodeDeploy deployment

**Deployment Group**
- Collection of instances
- Target for deployment

**Deployment Configuration**
- Rules for deployment
- AllAtOnce, HalfAtOnce, etc.

**Revision**
- Version of application
- Deployed by CodeDeploy

**AppSpec File**
- Deployment instructions
- YAML format

**Lifecycle Event**
- Phase of deployment
- BeforeInstall, AfterInstall, etc.

**Hook**
- Script run during deployment
- Lifecycle event hook

**Lambda Function**
- Serverless compute
- Runs code in response to events

**Function**
- Code that runs in Lambda
- Lambda function

**Handler**
- Function entry point
- Method that Lambda calls

**Runtime**
- Programming language environment
- Python, Node.js, Java, etc.

**Layer**
- Additional code library
- Shared across functions

**Version**
- Immutable snapshot of function
- Lambda version

**Alias**
- Pointer to function version
- Lambda alias

**Event Source**
- Service that triggers function
- S3, DynamoDB, API Gateway, etc.

**Event Source Mapping**
- Connection between source and function
- Lambda configuration

**Concurrent Execution**
- Number of functions running simultaneously
- Lambda limit

**Reserved Concurrency**
- Reserved capacity for function
- Guarantees availability

**Provisioned Concurrency**
- Pre-warmed function instances
- Reduces cold starts

**Cold Start**
- Initial invocation delay
- Function not running

**Warm Start**
- Fast invocation
- Function already running

**Dead Letter Queue**
- Queue for failed messages
- SQS or SNS

**Environment Variable**
- Key-value pair
- Available to function code

**IAM Execution Role**
- Role assumed by function
- Grants permissions

**VPC Configuration**
- Network settings for function
- Connects to VPC

**API Gateway API**
- Collection of resources and methods
- RESTful or WebSocket

**Resource**
- Logical entity
- Represents API endpoint

**Method**
- HTTP verb
- GET, POST, PUT, DELETE, etc.

**Integration**
- Connection to backend
- Lambda, HTTP, AWS service, etc.

**Integration Request**
- Request transformation
- Before sending to backend

**Integration Response**
- Response transformation
- Before returning to client

**Method Request**
- Request validation
- Before integration

**Method Response**
- Response definition
- After integration

**Stage**
- Deployment of API
- Dev, Prod, etc.

**Deployment**
- Publishing API to stage
- Makes API accessible

**Custom Domain**
- Your own domain name
- Points to API

**API Key**
- Identifier for API access
- Used for throttling

**Usage Plan**
- Throttle and quota settings
- Applied to API key

**Throttle**
- Limit request rate
- API Gateway feature

**Quota**
- Limit total requests
- API Gateway feature

**Authorizer**
- Authentication/authorization
- Lambda or Cognito

**CORS**
- Cross-Origin Resource Sharing
- Allows browser access

**Model**
- Data structure definition
- JSON schema

**Mapping Template**
- Request/response transformation
- Velocity Template Language

**Cache**
- Store API responses
- Reduces backend load

**SQS Queue**
- Message queue
- Decouples components

**Message**
- Unit of data
- Sent to queue

**Queue**
- Container for messages
- SQS queue

**Standard Queue**
- Unlimited throughput
- At-least-once delivery

**FIFO Queue**
- First-In-First-Out
- Exactly-once processing

**Visibility Timeout**
- Time message is hidden
- After being received

**Message Retention**
- How long message kept
- Up to 14 days

**Dead Letter Queue**
- Queue for failed messages
- After max receives

**Long Polling**
- Wait for messages
- Reduces empty responses

**Short Polling**
- Immediate return
- Even if no messages

**Batch**
- Multiple messages
- Single API call

**SNS Topic**
- Communication channel
- Pub/sub messaging

**Topic**
- Logical access point
- SNS topic

**Subscription**
- Endpoint for messages
- Email, SMS, SQS, Lambda, etc.

**Publisher**
- Sends messages to topic
- Application or service

**Subscriber**
- Receives messages
- Endpoint subscribed to topic

**Message**
- Data sent to topic
- JSON format

**Filter Policy**
- Filter messages
- Based on attributes

**Fanout**
- One message to many
- SNS pattern

**EventBridge**
- Serverless event bus
- Event-driven architecture

**Event Bus**
- Router for events
- EventBridge bus

**Event**
- Signal of state change
- JSON format

**Rule**
- Routes events to targets
- EventBridge rule

**Target**
- Service that processes event
- Lambda, SQS, SNS, etc.

**Pattern**
- Criteria for matching events
- EventBridge rule pattern

**Schema Registry**
- Store event schemas
- EventBridge feature

**Custom Event Bus**
- Your own event bus
- Isolated from default

**Partner Event Source**
- Third-party events
- SaaS provider events

**CloudWatch Metric**
- Data point over time
- CPU utilization, etc.

**Metric**
- Measurement of system
- CloudWatch metric

**Namespace**
- Container for metrics
- AWS/service name

**Dimension**
- Metric identifier
- InstanceId, etc.

**Statistic**
- Aggregation of data points
- Average, Sum, Min, Max

**Period**
- Time interval
- 1 minute, 5 minutes, etc.

**Alarm**
- Monitors metric
- Sends notification

**Threshold**
- Value that triggers alarm
- Above or below

**Action**
- Response to alarm
- SNS, Auto Scaling, etc.

**Dashboard**
- Visual display of metrics
- CloudWatch dashboard

**Widget**
- Component of dashboard
- Graph, number, etc.

**Log Group**
- Container for log streams
- CloudWatch Logs

**Log Stream**
- Sequence of log events
- From single source

**Log Event**
- Single log entry
- Timestamp and message

**Metric Filter**
- Extract metric from logs
- CloudWatch Logs

**Subscription Filter**
- Stream logs to destination
- Kinesis, Lambda, etc.

**Retention**
- How long logs kept
- CloudWatch Logs

**Insight**
- Automated log analysis
- CloudWatch Logs Insights

**Query**
- Search log data
- CloudWatch Logs Insights

**CloudTrail Trail**
- Configuration for logging
- CloudTrail trail

**Event**
- API call recorded
- CloudTrail event

**Event History**
- Last 90 days of events
- CloudTrail feature

**Trail**
- Logging configuration
- CloudTrail trail

**Management Event**
- API call for management
- Create, delete, modify

**Data Event**
- API call for data
- S3 object, Lambda invoke

**Insight Event**
- Unusual API activity
- CloudTrail Insights

**Config Rule**
- Evaluates resource configuration
- AWS Config rule

**Configuration Item**
- Snapshot of resource
- AWS Config

**Configuration History**
- Changes over time
- AWS Config

**Configuration Snapshot**
- Point-in-time configuration
- AWS Config

**Compliance**
- Conformance to rules
- AWS Config

**Remediation**
- Fix non-compliant resource
- AWS Config

**Conformance Pack**
- Collection of rules
- AWS Config

**Aggregator**
- Aggregate data from accounts
- AWS Config

**Systems Manager Parameter**
- Secure configuration data
- Systems Manager

**Parameter Store**
- Centralized configuration
- Systems Manager

**Document**
- Automation script
- Systems Manager

**Run Command**
- Execute command on instances
- Systems Manager

**Session Manager**
- Secure shell access
- Systems Manager

**Patch Manager**
- Automate patching
- Systems Manager

**State Manager**
- Maintain desired state
- Systems Manager

**Inventory**
- Collect software inventory
- Systems Manager

**Maintenance Window**
- Schedule for operations
- Systems Manager

**Trusted Advisor**
- Best practice recommendations
- AWS service

**Check**
- Specific recommendation
- Trusted Advisor

**Category**
- Group of checks
- Cost, Security, Performance, etc.

**Refresh**
- Update recommendations
- Trusted Advisor

**S3 Storage Class**
- Storage tier
- Cost and access optimization

**Standard**
- General purpose storage
- Frequently accessed

**Standard-IA**
- Infrequent access
- Lower storage cost

**One Zone-IA**
- Infrequent access, single AZ
- Lowest cost, less durable

**Intelligent-Tiering**
- Automatic optimization
- Moves objects automatically

**Glacier Instant Retrieval**
- Archive, instant access
- Milliseconds retrieval

**Glacier Flexible Retrieval**
- Archive, flexible retrieval
- 3 retrieval options

**Glacier Deep Archive**
- Lowest cost archive
- 12-hour retrieval

**Reduced Redundancy**
- Deprecated storage class
- Use Standard-IA instead

**S3 Transfer Acceleration**
- Faster uploads
- Uses CloudFront

**S3 Select**
- Query object contents
- SQL-like queries

**S3 Batch Operations**
- Bulk operations
- Copy, restore, etc.

**S3 Object Lock**
- Prevent deletion
- Compliance feature

**S3 Versioning**
- Keep multiple versions
- Protect against deletion

**S3 Replication**
- Copy objects automatically
- Cross-region or same-region

**S3 Lifecycle**
- Automate transitions
- Move between classes

**S3 Event Notification**
- Trigger on object events
- SQS, SNS, Lambda

**S3 Access Points**
- Manage access at scale
- S3 feature

**S3 Multi-Part Upload**
- Upload large objects
- Parallel uploads

**S3 Presigned URL**
- Temporary access
- Time-limited URL

**EBS Volume**
- Block storage device
- Attached to EC2

**Volume Type**
- Performance characteristics
- gp3, gp2, io1, io2, st1, sc1

**gp3**
- General purpose SSD
- Latest generation

**gp2**
- General purpose SSD
- Previous generation

**io1/io2**
- Provisioned IOPS SSD
- High performance

**st1**
- Throughput Optimized HDD
- Big data, data warehouses

**sc1**
- Cold HDD
- Infrequently accessed

**Snapshot**
- Point-in-time backup
- EBS volume backup

**Encryption**
- Encrypt volume
- KMS encryption

**EFS File System**
- Managed file storage
- NFS file system

**Mount Target**
- Network interface
- Connects to file system

**Access Point**
- Application entry point
- EFS access point

**Performance Mode**
- Throughput or latency
- GeneralPurpose or MaxIO

**Throughput Mode**
- Bursting or Provisioned
- EFS throughput

**Lifecycle Policy**
- Move to Infrequent Access
- EFS lifecycle

**RDS Instance Class**
- Compute and memory
- db.t3, db.r5, etc.

**Instance Class**
- Hardware configuration
- RDS instance

**Storage Type**
- SSD or magnetic
- RDS storage

**Allocated Storage**
- Storage size
- RDS instance

**IOPS**
- Input/Output Operations Per Second
- Performance metric

**Storage Autoscaling**
- Automatically increase storage
- RDS feature

**Automated Backup**
- Automatic snapshots
- RDS feature

**Manual Snapshot**
- On-demand backup
- RDS snapshot

**Restore**
- Create instance from backup
- RDS restore

**Point-in-Time Recovery**
- Restore to any time
- RDS feature

**Multi-AZ**
- High availability
- Standby in another AZ

**Read Replica**
- Read-only copy
- Improves read performance

**Parameter Group**
- Database configuration
- RDS parameter group

**Option Group**
- Additional features
- RDS option group

**Maintenance Window**
- Scheduled maintenance
- RDS feature

**Backup Window**
- Automated backup time
- RDS feature

**Encryption**
- Encrypt database
- RDS encryption

**VPC Security**
- Network security
- Security Groups, NACLs

**Security Group**
- Instance firewall
- Stateful rules

**NACL**
- Subnet firewall
- Stateless rules

**Network ACL**
- Network Access Control List
- Subnet-level security

**Route Table**
- Routing rules
- VPC routing

**Internet Gateway**
- Internet access
- VPC gateway

**NAT Gateway**
- Outbound internet
- Private subnet access

**NAT Instance**
- NAT using EC2
- Legacy option

**VPC Peering**
- Connect VPCs
- Private connectivity

**Transit Gateway**
- Central hub
- Multiple VPC connections

**VPN Connection**
- Encrypted tunnel
- Site-to-Site or Client

**Direct Connect**
- Dedicated connection
- Bypass internet

**Elastic IP**
- Static IP address
- Persistent public IP

**Elastic Network Interface**
- Virtual network card
- ENI

**Placement Group**
- Instance placement strategy
- Cluster, Spread, Partition

**Cluster Placement**
- Low latency
- Same rack

**Spread Placement**
- Isolated hardware
- Different racks

**Partition Placement**
- Large distributed systems
- Multiple partitions

**Elastic IP**
- Static public IP
- Persistent address

**Elastic Network Interface**
- Virtual network interface
- Attach to instances

**Enhanced Networking**
- Higher performance
- SR-IOV

**Instance Metadata**
- Instance information
- Available at metadata URL

**User Data**
- Script run at launch
- EC2 instance

**Launch Template**
- Instance configuration
- Reusable template

**AMI**
- Machine image
- Template for instances

**Public AMI**
- Shared by AWS or community
- Available to all

**Private AMI**
- Your own AMI
- Only your account

**Marketplace AMI**
- Paid AMI
- From AWS Marketplace

**Instance Store**
- Ephemeral storage
- Lost on stop/terminate

**EBS Volume**
- Persistent storage
- Survives instance stop

**Elastic IP**
- Static public IP
- Reattach to instances

**Auto Scaling Group**
- Automatically adjust capacity
- Maintain desired capacity

**Launch Configuration**
- Template for instances
- Legacy (use Launch Template)

**Launch Template**
- Instance configuration
- Reusable template

**Desired Capacity**
- Target number of instances
- Auto Scaling

**Min Size**
- Minimum instances
- Auto Scaling

**Max Size**
- Maximum instances
- Auto Scaling

**Scaling Policy**
- When to scale
- Target tracking, step, simple

**Target Tracking**
- Maintain metric at target
- Auto Scaling policy

**Step Scaling**
- Scale by steps
- Based on alarm breach

**Simple Scaling**
- Single adjustment
- Based on alarm

**Scheduled Scaling**
- Scale on schedule
- Predictable patterns

**Cooldown Period**
- Wait after scaling
- Prevent rapid changes

**Health Check**
- Instance health
- ELB or EC2

**Termination Policy**
- Which instance to terminate
- Auto Scaling

**Lifecycle Hook**
- Pause during lifecycle
- Auto Scaling

**Load Balancer**
- Distribute traffic
- High availability

**Application Load Balancer**
- Layer 7 load balancing
- HTTP/HTTPS

**Network Load Balancer**
- Layer 4 load balancing
- TCP/UDP

**Gateway Load Balancer**
- Third-party appliances
- Transparent gateway

**Classic Load Balancer**
- Legacy load balancer
- Previous generation

**Listener**
- Check for connection requests
- Port and protocol

**Target Group**
- Group of targets
- Instances, IPs, Lambda

**Target**
- Backend resource
- Receives traffic

**Health Check**
- Monitor target health
- HTTP, HTTPS, TCP

**Sticky Session**
- Route to same target
- Session affinity

**Connection Draining**
- Complete requests before termination
- Graceful shutdown

**Cross-Zone Load Balancing**
- Distribute across AZs
- Load balancer feature

**SSL/TLS Certificate**
- Encryption certificate
- ACM certificate

**ACM**
- Certificate Manager
- SSL/TLS certificates

**Route 53**
- DNS service
- Domain registration

**Hosted Zone**
- Container for DNS records
- Route 53

**DNS Record**
- Name to value mapping
- A, AAAA, CNAME, etc.

**Record Type**
- Type of DNS record
- A, AAAA, CNAME, MX, TXT

**A Record**
- IPv4 address
- Route 53

**AAAA Record**
- IPv4 address
- Route 53

**CNAME Record**
- Canonical name
- Alias to another name

**MX Record**
- Mail exchange
- Email routing

**TXT Record**
- Text record
- Verification, SPF, etc.

**NS Record**
- Name server
- Delegates subdomain

**SOA Record**
- Start of authority
- Zone information

**PTR Record**
- Pointer record
- Reverse DNS

**SRV Record**
- Service record
- Service location

**Alias Record**
- AWS resource alias
- Route 53 feature

**Health Check**
- Monitor resource health
- Route 53

**Routing Policy**
- How to route traffic
- Simple, Weighted, Latency, etc.

**Simple Routing**
- One record per name
- Route 53

**Weighted Routing**
- Distribute by weight
- Route 53

**Latency-Based Routing**
- Route to lowest latency
- Route 53

**Failover Routing**
- Active-passive failover
- Route 53

**Geolocation Routing**
- Route by location
- Route 53

**Geoproximity Routing**
- Route by location and bias
- Route 53

**Multivalue Answer Routing**
- Multiple healthy records
- Route 53

**CloudFront Distribution**
- CDN configuration
- Content delivery

**Origin**
- Source of content
- S3, EC2, custom

**Origin Access Identity**
- Restrict S3 access
- CloudFront only

**Origin Access Control**
- Modern OAI replacement
- CloudFront

**Cache Behavior**
- How to handle requests
- CloudFront

**Cache Policy**
- What to cache
- CloudFront

**Origin Request Policy**
- What to forward
- CloudFront

**Response Headers Policy**
- Modify response headers
- CloudFront

**Invalidation**
- Clear cache
- CloudFront

**Edge Location**
- Cache location
- CloudFront

**Regional Edge Cache**
- Additional cache layer
- CloudFront

**Lambda@Edge**
- Run code at edge
- CloudFront

**WAF**
- Web Application Firewall
- Protect applications

**WAF Rule**
- Security rule
- Block, allow, count

**WAF Rule Group**
- Collection of rules
- Reusable

**WAF Web ACL**
- Collection of rules
- Applied to resource

**Managed Rule**
- AWS-managed rule
- Common protections

**Custom Rule**
- Your own rule
- WAF

**Rate-Based Rule**
- Limit request rate
- WAF

**IP Set**
- Collection of IPs
- WAF

**Regex Pattern Set**
- Collection of patterns
- WAF

**String Match Set**
- Collection of strings
- WAF

**Geo Match Set**
- Collection of countries
- WAF

**Shield Standard**
- DDoS protection
- Included with AWS

**Shield Advanced**
- Enhanced DDoS protection
- Paid service

**GuardDuty**
- Threat detection
- Monitors VPC, S3, DNS

**Finding**
- Security issue detected
- GuardDuty

**Threat Intelligence**
- Known threats
- GuardDuty

**Anomaly Detection**
- Unusual activity
- GuardDuty

**Malware Protection**
- Scan for malware
- GuardDuty

**KMS**
- Key Management Service
- Encryption keys

**Customer Master Key**
- Encryption key
- CMK

**AWS Managed Key**
- AWS-managed key
- Automatic rotation

**Customer Managed Key**
- Your own key
- Full control

**Key Policy**
- Key permissions
- KMS

**Key Rotation**
- Automatic key rotation
- KMS

**Alias**
- Friendly key name
- KMS

**Data Key**
- Encryption key
- Generated by KMS

**Envelope Encryption**
- Encrypt data key
- KMS pattern

**Secrets Manager**
- Store secrets
- Automatic rotation

**Secret**
- Stored secret
- Secrets Manager

**Rotation**
- Automatic rotation
- Secrets Manager

**Lambda Rotation Function**
- Rotate secret
- Secrets Manager

**Cognito User Pool**
- User directory
- Sign-up, sign-in

**User Pool**
- User directory
- Cognito

**Identity Pool**
- Grant AWS access
- Cognito

**Federated Identity**
- External identity provider
- Cognito

**OIDC**
- OpenID Connect
- Identity provider

**SAML**
- Security Assertion Markup Language
- Enterprise SSO

**Social Identity Provider**
- Facebook, Google, etc.
- Cognito

**MFA**
- Multi-Factor Authentication
- Additional security

**SMS MFA**
- Text message MFA
- Cognito

**TOTP MFA**
- Authenticator app MFA
- Cognito

**Backup**
- Backup service
- Centralized backups

**Backup Plan**
- Backup schedule
- AWS Backup

**Backup Rule**
- What to backup
- AWS Backup

**Backup Vault**
- Container for backups
- AWS Backup

**Recovery Point**
- Point-in-time backup
- AWS Backup

**Restore**
- Restore from backup
- AWS Backup

**Copy**
- Copy backup to region
- AWS Backup

**Resource Tag**
- Tag for backup
- AWS Backup

**CloudFormation**
- Infrastructure as Code
- Template-based

**Stack**
- Collection of resources
- CloudFormation

**Template**
- Resource definition
- JSON or YAML

**Stack Update**
- Modify stack
- CloudFormation

**Change Set**
- Preview changes
- CloudFormation

**Drift Detection**
- Compare actual vs expected
- CloudFormation

**Nested Stack**
- Stack within stack
- CloudFormation

**Stack Set**
- Manage across accounts
- CloudFormation

**Parameter**
- Template input
- CloudFormation

**Output**
- Stack output
- CloudFormation

**Resource**
- AWS resource
- CloudFormation

**Condition**
- Conditional creation
- CloudFormation

**Mapping**
- Lookup table
- CloudFormation

**Intrinsic Function**
- Built-in function
- CloudFormation

**Ref**
- Reference value
- CloudFormation

**Fn::GetAtt**
- Get attribute
- CloudFormation

**Fn::Join**
- Join strings
- CloudFormation

**Fn::Sub**
- Substitute variables
- CloudFormation

**CodePipeline**
- CI/CD service
- Automate releases

**Pipeline**
- Release workflow
- CodePipeline

**Stage**
- Pipeline phase
- Source, Build, Deploy

**Action**
- Stage task
- CodePipeline

**Artifact**
- Action output
- CodePipeline

**Source Action**
- Get source code
- CodePipeline

**Build Action**
- Build code
- CodePipeline

**Deploy Action**
- Deploy application
- CodePipeline

**Approval Action**
- Manual approval
- CodePipeline

**CodeCommit**
- Source control
- Git-based

**Repository**
- Code container
- CodeCommit

**Branch**
- Code version
- Git branch

**Commit**
- Code snapshot
- Git commit

**Pull Request**
- Merge request
- CodeCommit

**CodeBuild**
- Build service
- Compile and test

**Build Project**
- Build configuration
- CodeBuild

**Build Environment**
- OS and tools
- CodeBuild

**Buildspec**
- Build commands
- YAML file

**CodeDeploy**
- Deployment service
- Deploy to instances

**Deployment**
- Deploy process
- CodeDeploy

**Deployment Group**
- Target instances
- CodeDeploy

**Deployment Configuration**
- Deployment rules
- CodeDeploy

**Revision**
- Application version
- CodeDeploy

**AppSpec File**
- Deployment instructions
- YAML file

**Lifecycle Event**
- Deployment phase
- CodeDeploy

**Hook**
- Deployment script
- CodeDeploy

**Lambda**
- Serverless compute
- Event-driven

**Function**
- Code unit
- Lambda

**Handler**
- Entry point
- Lambda

**Runtime**
- Language environment
- Python, Node.js, etc.

**Layer**
- Additional library
- Lambda

**Version**
- Function snapshot
- Lambda

**Alias**
- Version pointer
- Lambda

**Event Source**
- Trigger service
- S3, DynamoDB, etc.

**Event Source Mapping**
- Source connection
- Lambda

**Concurrent Execution**
- Simultaneous invocations
- Lambda limit

**Reserved Concurrency**
- Reserved capacity
- Lambda

**Provisioned Concurrency**
- Pre-warmed instances
- Lambda

**Cold Start**
- Initial delay
- Lambda

**Warm Start**
- Fast invocation
- Lambda

**Dead Letter Queue**
- Failed message queue
- Lambda

**Environment Variable**
- Configuration
- Lambda

**IAM Execution Role**
- Function permissions
- Lambda

**VPC Configuration**
- Network settings
- Lambda

**API Gateway**
- API management
- RESTful and WebSocket

**API**
- API collection
- API Gateway

**Resource**
- API endpoint
- API Gateway

**Method**
- HTTP verb
- GET, POST, etc.

**Integration**
- Backend connection
- Lambda, HTTP, etc.

**Integration Request**
- Request transformation
- API Gateway

**Integration Response**
- Response transformation
- API Gateway

**Method Request**
- Request validation
- API Gateway

**Method Response**
- Response definition
- API Gateway

**Stage**
- API deployment
- Dev, Prod, etc.

**Deployment**
- Publish API
- API Gateway

**Custom Domain**
- Your domain
- API Gateway

**API Key**
- Access identifier
- API Gateway

**Usage Plan**
- Throttle and quota
- API Gateway

**Throttle**
- Request rate limit
- API Gateway

**Quota**
- Total request limit
- API Gateway

**Authorizer**
- Authentication
- Lambda or Cognito

**CORS**
- Cross-Origin Resource Sharing
- Browser access

**Model**
- Data structure
- JSON schema

**Mapping Template**
- Transformation
- Velocity Template

**Cache**
- Response cache
- API Gateway

**SQS**
- Message queue
- Decouple components

**Queue**
- Message container
- SQS

**Message**
- Data unit
- SQS

**Standard Queue**
- Unlimited throughput
- At-least-once

**FIFO Queue**
- First-In-First-Out
- Exactly-once

**Visibility Timeout**
- Hide message time
- SQS

**Message Retention**
- Keep message time
- SQS

**Dead Letter Queue**
- Failed message queue
- SQS

**Long Polling**
- Wait for messages
- SQS

**Short Polling**
- Immediate return
- SQS

**Batch**
- Multiple messages
- SQS

**SNS**
- Pub/sub messaging
- Notification service

**Topic**
- Communication channel
- SNS

**Subscription**
- Message endpoint
- SNS

**Publisher**
- Message sender
- SNS

**Subscriber**
- Message receiver
- SNS

**Message**
- Data sent
- SNS

**Filter Policy**
- Message filter
- SNS

**Fanout**
- One to many
- SNS pattern

**EventBridge**
- Event bus
- Event-driven

**Event Bus**
- Event router
- EventBridge

**Event**
- State change signal
- EventBridge

**Rule**
- Event router
- EventBridge

**Target**
- Event processor
- Lambda, SQS, etc.

**Pattern**
- Event criteria
- EventBridge

**Schema Registry**
- Event schemas
- EventBridge

**Custom Event Bus**
- Your event bus
- EventBridge

**Partner Event Source**
- Third-party events
- EventBridge

**CloudWatch**
- Monitoring service
- Metrics and logs

**Metric**
- Measurement
- CloudWatch

**Namespace**
- Metric container
- CloudWatch

**Dimension**
- Metric identifier
- CloudWatch

**Statistic**
- Data aggregation
- Average, Sum, etc.

**Period**
- Time interval
- CloudWatch

**Alarm**
- Metric monitor
- CloudWatch

**Threshold**
- Trigger value
- CloudWatch

**Action**
- Alarm response
- SNS, Auto Scaling

**Dashboard**
- Visual display
- CloudWatch

**Widget**
- Dashboard component
- CloudWatch

**Log Group**
- Log container
- CloudWatch Logs

**Log Stream**
- Log sequence
- CloudWatch Logs

**Log Event**
- Log entry
- CloudWatch Logs

**Metric Filter**
- Extract metric
- CloudWatch Logs

**Subscription Filter**
- Stream logs
- CloudWatch Logs

**Retention**
- Keep logs time
- CloudWatch Logs

**Insight**
- Log analysis
- CloudWatch Logs Insights

**Query**
- Search logs
- CloudWatch Logs Insights

**CloudTrail**
- API logging
- Audit trail

**Trail**
- Logging configuration
- CloudTrail

**Event**
- API call
- CloudTrail

**Event History**
- Last 90 days
- CloudTrail

**Management Event**
- Management API call
- CloudTrail

**Data Event**
- Data API call
- CloudTrail

**Insight Event**
- Unusual activity
- CloudTrail Insights

**Config**
- Configuration management
- Resource inventory

**Config Rule**
- Configuration rule
- AWS Config

**Configuration Item**
- Resource snapshot
- AWS Config

**Configuration History**
- Changes over time
- AWS Config

**Configuration Snapshot**
- Point-in-time config
- AWS Config

**Compliance**
- Rule conformance
- AWS Config

**Remediation**
- Fix non-compliance
- AWS Config

**Conformance Pack**
- Rule collection
- AWS Config

**Aggregator**
- Aggregate accounts
- AWS Config

**Systems Manager**
- Operations management
- Centralized control

**Parameter**
- Configuration data
- Systems Manager

**Parameter Store**
- Centralized config
- Systems Manager

**Document**
- Automation script
- Systems Manager

**Run Command**
- Execute command
- Systems Manager

**Session Manager**
- Secure shell
- Systems Manager

**Patch Manager**
- Automate patching
- Systems Manager

**State Manager**
- Maintain state
- Systems Manager

**Inventory**
- Software inventory
- Systems Manager

**Maintenance Window**
- Operation schedule
- Systems Manager

**Trusted Advisor**
- Best practices
- AWS service

**Check**
- Recommendation
- Trusted Advisor

**Category**
- Check group
- Cost, Security, etc.

**Refresh**
- Update recommendations
- Trusted Advisor

### Visual Diagrams & Concepts

#### Cloud Computing Models (IaaS, PaaS, SaaS)

```
┌─────────────────────────────────────────────────────────┐
│                    TRADITIONAL IT                        │
│  ┌──────────┐  ┌──────────┐  ┌──────────┐             │
│  │Applications│ │Applications│ │Applications│            │
│  └──────────┘  └──────────┘  └──────────┘             │
│  ┌──────────────────────────────────────────┐          │
│  │         Data & Runtime                    │          │
│  └──────────────────────────────────────────┘          │
│  ┌──────────────────────────────────────────┐          │
│  │         Middleware & O/S                   │          │
│  └──────────────────────────────────────────┘          │
│  ┌──────────────────────────────────────────┐          │
│  │         Virtualization                    │          │
│  └──────────────────────────────────────────┘          │
│  ┌──────────────────────────────────────────┐          │
│  │         Servers & Storage                 │          │
│  └──────────────────────────────────────────┘          │
│  ┌──────────────────────────────────────────┐          │
│  │         Networking                        │          │
│  └──────────────────────────────────────────┘          │
└─────────────────────────────────────────────────────────┘

┌─────────────────────────────────────────────────────────┐
│                    INFRASTRUCTURE AS A SERVICE (IaaS)    │
│  ┌──────────┐  ┌──────────┐  ┌──────────┐             │
│  │Applications│ │Applications│ │Applications│            │
│  └──────────┘  └──────────┘  └──────────┘             │
│  ┌──────────────────────────────────────────┐          │
│  │         Data & Runtime                    │          │
│  └──────────────────────────────────────────┘          │
│  ┌──────────────────────────────────────────┐          │
│  │         Middleware & O/S                   │          │
│  └──────────────────────────────────────────┘          │
│  ┌──────────────────────────────────────────┐          │
│  │         Virtualization                    │          │
│  └──────────────────────────────────────────┘          │
│  ┌──────────────────────────────────────────┐          │
│  │         Servers & Storage  ← YOU MANAGE   │          │
│  └──────────────────────────────────────────┘          │
│  ┌──────────────────────────────────────────┐          │
│  │         Networking      ← YOU MANAGE      │          │
│  └──────────────────────────────────────────┘          │
│                    AWS PROVIDES                          │
└─────────────────────────────────────────────────────────┘
Example: EC2, VPC, EBS

┌─────────────────────────────────────────────────────────┐
│                    PLATFORM AS A SERVICE (PaaS)           │
│  ┌──────────┐  ┌──────────┐  ┌──────────┐             │
│  │Applications│ │Applications│ │Applications│            │
│  └──────────┘  └──────────┘  └──────────┘             │
│  ┌──────────────────────────────────────────┐          │
│  │         Data & Runtime    ← YOU MANAGE    │          │
│  └──────────────────────────────────────────┘          │
│  ┌──────────────────────────────────────────┐          │
│  │         Middleware & O/S  ← AWS MANAGES   │          │
│  └──────────────────────────────────────────┘          │
│  ┌──────────────────────────────────────────┐          │
│  │         Virtualization  ← AWS MANAGES     │          │
│  └──────────────────────────────────────────┘          │
│  ┌──────────────────────────────────────────┐          │
│  │         Servers & Storage ← AWS MANAGES   │          │
│  └──────────────────────────────────────────┘          │
│  ┌──────────────────────────────────────────┐          │
│  │         Networking      ← AWS MANAGES    │          │
│  └──────────────────────────────────────────┘          │
└─────────────────────────────────────────────────────────┘
Example: Elastic Beanstalk, RDS

┌─────────────────────────────────────────────────────────┐
│                    SOFTWARE AS A SERVICE (SaaS)          │
│  ┌──────────┐  ┌──────────┐  ┌──────────┐             │
│  │Applications│ │Applications│ │Applications│            │
│  └──────────┘  └──────────┘  └──────────┘             │
│  ┌──────────────────────────────────────────┐          │
│  │         Data & Runtime  ← AWS MANAGES     │          │
│  └──────────────────────────────────────────┘          │
│  ┌──────────────────────────────────────────┐          │
│  │         Middleware & O/S ← AWS MANAGES    │          │
│  └──────────────────────────────────────────┘          │
│  ┌──────────────────────────────────────────┐          │
│  │         Virtualization  ← AWS MANAGES     │          │
│  └──────────────────────────────────────────┘          │
│  ┌──────────────────────────────────────────┐          │
│  │         Servers & Storage ← AWS MANAGES   │          │
│  └──────────────────────────────────────────┘          │
│  ┌──────────────────────────────────────────┐          │
│  │         Networking      ← AWS MANAGES    │          │
│  └──────────────────────────────────────────┘          │
└─────────────────────────────────────────────────────────┘
Example: Gmail, Office 365, Salesforce
```

#### AWS Shared Responsibility Model

```
┌─────────────────────────────────────────────────────────┐
│                    AWS RESPONSIBILITY                    │
│  ┌──────────────────────────────────────────┐          │
│  │  Security OF the Cloud                   │          │
│  │  • Infrastructure (Hardware, Software)    │          │
│  │  • Network Infrastructure                │          │
│  │  • Virtualization Layer                  │          │
│  │  • Compute, Storage, Database Services   │          │
│  │  • Global Infrastructure                 │          │
│  │  • Regions, Availability Zones, Edge    │          │
│  └──────────────────────────────────────────┘          │
└─────────────────────────────────────────────────────────┘

┌─────────────────────────────────────────────────────────┐
│                  CUSTOMER RESPONSIBILITY                 │
│  ┌──────────────────────────────────────────┐          │
│  │  Security IN the Cloud                    │          │
│  │  • Data (Encryption, Classification)      │          │
│  │  • Platform & Applications                │          │
│  │  • Identity & Access Management (IAM)     │          │
│  │  • Operating System, Network, Firewall   │          │
│  │  • Client-side Data Encryption           │          │
│  │  • Server-side Encryption (File System)  │          │
│  │  • Network Traffic Protection            │          │
│  │  • Security Group & NACL Configuration   │          │
│  └──────────────────────────────────────────┘          │
└─────────────────────────────────────────────────────────┘
```

#### AWS Global Infrastructure

```
                    ┌─────────────────┐
                    │   AWS REGION    │
                    │   (us-east-1)   │
                    └─────────────────┘
                            │
        ┌───────────────────┼───────────────────┐
        │                   │                   │
  ┌─────────┐         ┌─────────┐        ┌─────────┐
  │   AZ-a  │         │   AZ-b  │        │   AZ-c  │
  │         │         │         │        │         │
  │ ┌─────┐ │         │ ┌─────┐ │        │ ┌─────┐ │
  │ │Data │ │         │ │Data │ │        │ │Data │ │
  │ │Center│ │         │ │Center│ │        │ │Center│ │
  │ └─────┘ │         │ └─────┘ │        │ └─────┘ │
  └─────────┘         └─────────┘        └─────────┘
        │                   │                   │
        └───────────────────┼───────────────────┘
                            │
                    Low-Latency Links
                            │
        ┌───────────────────┴───────────────────┐
        │                                       │
  ┌─────────┐                           ┌─────────┐
  │  Edge   │                           │  Edge   │
  │Location │                           │Location │
  │(CloudFront)                         │(CloudFront)
  └─────────┘                           └─────────┘
```

#### VPC Architecture

```
┌─────────────────────────────────────────────────────────┐
│                        INTERNET                          │
└────────────────────────┬────────────────────────────────┘
                         │
                         │
            ┌────────────▼────────────┐
            │   Internet Gateway (IGW)│
            └────────────┬────────────┘
                         │
            ┌────────────▼────────────┐
            │      VPC (10.0.0.0/16)  │
            │                         │
            │  ┌──────────────────┐  │
            │  │  Public Subnet   │  │
            │  │  10.0.1.0/24     │  │
            │  │                  │  │
            │  │  ┌────────────┐  │  │
            │  │  │ EC2 Instance│  │  │
            │  │  │ (Web Server)│  │  │
            │  │  └────────────┘  │  │
            │  │                  │  │
            │  │  ┌────────────┐  │  │
            │  │  │ NAT Gateway │  │  │
            │  │  └────────────┘  │  │
            │  └──────────────────┘  │
            │           │            │
            │  ┌────────▼────────┐  │
            │  │ Private Subnet │  │
            │  │  10.0.2.0/24   │  │
            │  │                 │  │
            │  │  ┌───────────┐ │  │
            │  │  │EC2 Instance│ │  │
            │  │  │(Database) │ │  │
            │  │  └───────────┘ │  │
            │  └────────────────┘  │
            │                      │
            │  ┌──────────────────┐│
            │  │  Route Tables    ││
            │  │  Security Groups ││
            │  │  NACLs           ││
            │  └──────────────────┘│
            └──────────────────────┘
```

#### S3 Storage Classes Comparison

```
┌─────────────────────────────────────────────────────────┐
│  FREQUENCY OF ACCESS  →  COST  →  RETRIEVAL TIME        │
│                                                          │
│  ┌──────────────┐                                       │
│  │   STANDARD   │  ← Frequently accessed, instant       │
│  │  (Highest $) │     retrieval, 99.99% durability     │
│  └──────────────┘                                       │
│         │                                                │
│         ▼                                                │
│  ┌──────────────┐                                       │
│  │ STANDARD-IA  │  ← Infrequent access, instant        │
│  │  (Lower $)   │     retrieval, retrieval fee          │
│  └──────────────┘                                       │
│         │                                                │
│         ▼                                                │
│  ┌──────────────┐                                       │
│  │ONE ZONE-IA   │  ← Infrequent access, single AZ      │
│  │  (Lowest $)  │     instant retrieval, less durable  │
│  └──────────────┘                                       │
│         │                                                │
│         ▼                                                │
│  ┌──────────────┐                                       │
│  │  GLACIER     │  ← Archive, minutes to hours         │
│  │  (Very Low $)│     retrieval, retrieval fee         │
│  └──────────────┘                                       │
│         │                                                │
│         ▼                                                │
│  ┌──────────────┐                                       │
│  │ DEEP ARCHIVE │  ← Long-term archive, 12 hours       │
│  │ (Lowest $)   │     retrieval, lowest cost           │
│  └──────────────┘                                       │
└─────────────────────────────────────────────────────────┘
```

#### EC2 Pricing Models

```
┌─────────────────────────────────────────────────────────┐
│                    EC2 PRICING MODELS                    │
│                                                          │
│  ┌──────────────────────────────────────────┐          │
│  │  ON-DEMAND                                │          │
│  │  • Pay by hour/second                     │          │
│  │  • No upfront cost                        │          │
│  │  • No commitment                          │          │
│  │  • Best for: Short-term, unpredictable    │          │
│  └──────────────────────────────────────────┘          │
│                                                          │
│  ┌──────────────────────────────────────────┐          │
│  │  RESERVED INSTANCES                       │          │
│  │  • 1-3 year commitment                   │          │
│  │  • Up to 75% discount                     │          │
│  │  • Standard, Convertible, Scheduled      │          │
│  │  • Best for: Predictable, steady state   │          │
│  └──────────────────────────────────────────┘          │
│                                                          │
│  ┌──────────────────────────────────────────┐          │
│  │  SAVINGS PLANS                           │          │
│  │  • Flexible pricing model                │          │
│  │  • Commit to $ amount                    │          │
│  │  • Up to 72% discount                    │          │
│  │  • Best for: Flexible workloads          │          │
│  └──────────────────────────────────────────┘          │
│                                                          │
│  ┌──────────────────────────────────────────┐          │
│  │  SPOT INSTANCES                           │          │
│  │  • Bid on unused capacity                │          │
│  │  • Up to 90% discount                    │          │
│  │  • Can be interrupted                    │          │
│  │  • Best for: Fault-tolerant, flexible   │          │
│  └──────────────────────────────────────────┘          │
│                                                          │
│  ┌──────────────────────────────────────────┐          │
│  │  DEDICATED HOSTS                         │          │
│  │  • Physical server dedicated to you      │          │
│  │  • Full control over instance placement │          │
│  │  • Compliance requirements               │          │
│  │  • Best for: Compliance, licensing       │          │
│  └──────────────────────────────────────────┘          │
└─────────────────────────────────────────────────────────┘
```

#### Load Balancer Types

```
┌─────────────────────────────────────────────────────────┐
│                    LOAD BALANCER TYPES                   │
│                                                          │
│  ┌──────────────────────────────────────────┐          │
│  │  APPLICATION LOAD BALANCER (ALB)          │          │
│  │  • Layer 7 (HTTP/HTTPS)                   │          │
│  │  • Path-based routing                     │          │
│  │  • Host-based routing                     │          │
│  │  • Best for: Web applications             │          │
│  └──────────────────────────────────────────┘          │
│                                                          │
│  ┌──────────────────────────────────────────┐          │
│  │  NETWORK LOAD BALANCER (NLB)             │          │
│  │  • Layer 4 (TCP/UDP)                     │          │
│  │  • Ultra-high performance                │          │
│  │  • Static IP addresses                   │          │
│  │  • Best for: High performance, low latency│          │
│  └──────────────────────────────────────────┘          │
│                                                          │
│  ┌──────────────────────────────────────────┐          │
│  │  GATEWAY LOAD BALANCER (GWLB)            │          │
│  │  • Layer 3 (IP)                          │          │
│  │  • Transparent gateway                   │          │
│  │  • Third-party appliances               │          │
│  │  • Best for: Security appliances         │          │
│  └──────────────────────────────────────────┘          │
│                                                          │
│  ┌──────────────────────────────────────────┐          │
│  │  CLASSIC LOAD BALANCER (CLB)             │          │
│  │  • Legacy load balancer                  │          │
│  │  • Layer 4 and Layer 7                  │          │
│  │  • Basic features                       │          │
│  │  • Best for: Legacy applications         │          │
│  └──────────────────────────────────────────┘          │
└─────────────────────────────────────────────────────────┘
```

#### Database Types

```
┌─────────────────────────────────────────────────────────┐
│                    DATABASE TYPES                       │
│                                                          │
│  ┌──────────────────────────────────────────┐          │
│  │  RELATIONAL DATABASES (RDS)              │          │
│  │  • Structured data                       │          │
│  │  • SQL queries                           │          │
│  │  • ACID compliance                       │          │
│  │  • MySQL, PostgreSQL, Oracle, SQL Server │          │
│  │  • Best for: Structured, transactional  │          │
│  └──────────────────────────────────────────┘          │
│                                                          │
│  ┌──────────────────────────────────────────┐          │
│  │  NOSQL DATABASES (DynamoDB)              │          │
│  │  • Unstructured data                     │          │
│  │  • Key-value, document                   │          │
│  │  • High performance                      │          │
│  │  • Serverless                            │          │
│  │  • Best for: High scale, flexible schema │          │
│  └──────────────────────────────────────────┘          │
│                                                          │
│  ┌──────────────────────────────────────────┐          │
│  │  DATA WAREHOUSE (Redshift)                │          │
│  │  • Analytics and reporting               │          │
│  │  • Columnar storage                      │          │
│  │  • Petabyte scale                        │          │
│  │  • Best for: Business intelligence       │          │
│  └──────────────────────────────────────────┘          │
│                                                          │
│  ┌──────────────────────────────────────────┐          │
│  │  IN-MEMORY (ElastiCache)                 │          │
│  │  • Redis or Memcached                    │          │
│  │  • Sub-millisecond latency               │          │
│  │  • Caching layer                         │          │
│  │  • Best for: Caching, session stores    │          │
│  └──────────────────────────────────────────┘          │
└─────────────────────────────────────────────────────────┘
```

#### Well-Architected Framework Pillars

```
                    ┌─────────────────┐
                    │   OPERATIONAL   │
                    │   EXCELLENCE    │
                    └────────┬────────┘
                             │
        ┌────────────────────┼────────────────────┐
        │                    │                    │
┌───────▼──────┐    ┌────────▼────────┐   ┌──────▼──────┐
│   SECURITY   │    │   RELIABILITY   │   │ PERFORMANCE │
│              │    │                 │   │  EFFICIENCY  │
└───────┬──────┘    └────────┬────────┘   └──────┬──────┘
        │                    │                    │
        └────────────────────┼────────────────────┘
                             │
                    ┌────────▼────────┐
                    │  COST           │
                    │  OPTIMIZATION   │
                    └─────────────────┘
                             │
                    ┌────────▼────────┐
                    │  SUSTAINABILITY │
                    └─────────────────┘
```



### Study Tips

1. **Create a Study Schedule**: Dedicate 2-4 weeks of consistent study
2. **Hands-On Practice**: Use AWS Free Tier to practice services
3. **Focus on Understanding**: Don't just memorize; understand concepts
4. **Take Practice Exams**: Identify weak areas and review
5. **Review Exam Guide**: Ensure you understand all domains
6. **Join Study Groups**: AWS User Groups, Reddit r/AWSCertifications
7. **Use Flashcards**: Create cards for service names and use cases
8. **Watch Video Tutorials**: Visual learning helps retention

### Important Concepts to Memorize

- **S3 Storage Classes**: Standard, IA, One Zone-IA, Intelligent-Tiering, Glacier, Deep Archive
- **EC2 Instance Types**: General purpose, Compute optimized, Memory optimized, Storage optimized, Accelerated computing
- **Database Types**: RDS (SQL), DynamoDB (NoSQL), Redshift (Data Warehouse)
- **IAM Policy Structure**: Version, Statement, Effect, Action, Resource, Principal
- **CloudWatch vs CloudTrail**: CloudWatch (metrics/logs) vs CloudTrail (API calls/audit)
- **S3 vs EBS vs EFS**: Object storage vs Block storage vs File storage
- **VPC Components**: Subnets, Route Tables, Internet Gateway, NAT Gateway, Security Groups, NACLs

### Exam Day Tips

1. **Read Questions Carefully**: Look for keywords like "most cost-effective", "most secure", "best practice"
2. **Eliminate Wrong Answers**: Process of elimination helps
3. **Flag for Review**: Mark questions you're unsure about
4. **Manage Time**: ~1.3 minutes per question
5. **Review Flagged Questions**: Use remaining time to review
6. **Stay Calm**: Take deep breaths if feeling overwhelmed

### Common Exam Topics

- AWS Well-Architected Framework pillars
- Shared Responsibility Model
- IAM best practices
- S3 storage classes and use cases
- EC2 pricing models
- VPC networking basics
- CloudWatch vs CloudTrail
- AWS Organizations and consolidated billing
- Cost optimization strategies
- Security best practices
- Compliance and governance

### After Passing

- Maintain certification (valid for 3 years)
- Consider next certifications:
  - AWS Certified Solutions Architect - Associate
  - AWS Certified Developer - Associate
  - AWS Certified SysOps Administrator - Associate

### Notes
- Review the notes in `AWS-Certified-Cloud-Practitioner-Certification-My-Notes-main.zip`
-