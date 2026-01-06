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

### Study Resources

#### Official AWS Resources
- [AWS Certified Cloud Practitioner Official Page](https://aws.amazon.com/certification/certified-cloud-practitioner/)
- [AWS Training and Certification](https://aws.amazon.com/training/)
- [AWS Cloud Practitioner Exam Guide](https://d1.awsstatic.com/training-and-certification/docs-cloud-practitioner/AWS-Certified-Cloud-Practitioner_Exam-Guide.pdf)
- [AWS Whitepapers](https://aws.amazon.com/whitepapers/)
- [AWS Well-Architected Framework](https://aws.amazon.com/architecture/well-architected/)

#### Free Training
- **AWS Cloud Practitioner Essentials (Digital)**: Free 6-hour course
- **AWS Skill Builder**: Free learning paths
- **AWS re:Invent Videos**: YouTube channel with sessions

#### Practice Exams
- AWS Official Practice Exam
- Tutorials Dojo practice tests
- Whizlabs practice exams
- ExamPro practice tests

#### Study Materials
- AWS documentation for each service
- AWS FAQs
- AWS Service Health Dashboard
- AWS Architecture Center

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
- Practice with AWS Free Tier to get hands-on experience
- Focus on understanding use cases for each service, not just memorizing names

---

**Good luck with your AWS Cloud Practitioner certification journey!** 🚀
