# AWS cloud_practitioner exam

learn with: 
source 1 : https://www.youtube.com/watch?v=SOTamWNgDKc&ab_channel=freeCodeCamp.org
source 2 : https://digitalcloud.training/category/aws-cheat-sheets/aws-cloud-practitioner/




Domain 1: Cloud Concepts
1.1 Define the AWS Cloud and its value proposition
##  Define the benefits of the AWS cloud including:
- Security
- Reliability
- High Availability
- Elasticity
- Agility
- Pay-as-you go pricing
- Scalability
- Global Reach
- Economy of scale
##  Explain how the AWS cloud allows users to focus on business value
- Shifting technical resources to revenue-generating activities as opposed to managing
infrastructure
1.2 Identify aspects of AWS Cloud economics
##  Define items that would be part of a Total Cost of Ownership proposal
- Understand the role of operational expenses (OpEx)
- Understand the role of capital expenses (CapEx)
- Understand labor costs associated with on-premises operations
- Understand the impact of software licensing costs when moving to the cloud
##  Identify which operations will reduce costs by moving to the cloud
- Right-sized infrastructure
- Benefits of automation
- Reduce compliance scope (for example, reporting)
- Managed services (for example, RDS, ECS, EKS, DynamoDB)
1.3 Explain the different cloud architecture design principles
##  Explain the design principles
- Design for failure
- Decouple components versus monolithic architecture
- Implement elasticity in the cloud versus on-premises
- Think parallel
Version 2.1 CLF-C01 4 | PAGE
Domain 2: Security and Compliance
2.1 Define the AWS shared responsibility model
##  Recognize the elements of the Shared Responsibility Model
##  Describe the customer’s responsibly on AWS
- Describe how the customer’s responsibilities may shift depending on the service used
(for example with RDS, Lambda, or EC2)
##  Describe AWS responsibilities
2.2 Define AWS Cloud security and compliance concepts
##  Identify where to find AWS compliance information
- Locations of lists of recognized available compliance controls (for example, HIPPA,
SOCs)
- Recognize that compliance requirements vary among AWS services
##  At a high level, describe how customers achieve compliance on AWS
- Identify different encryption options on AWS (for example, In transit, At rest)
##  Describe who enables encryption on AWS for a given service
##  Recognize there are services that will aid in auditing and reporting
- Recognize that logs exist for auditing and monitoring (do not have to understand the
logs)
- Define Amazon CloudWatch, AWS Config, and AWS CloudTrail
##  Explain the concept of least privileged access
2.3 Identify AWS access management capabilities
##  Understand the purpose of User and Identity Management
- Access keys and password policies (rotation, complexity)
- Multi-Factor Authentication (MFA)
- AWS Identity and Access Management (IAM)
• Groups/users
• Roles
• Policies, managed policies compared to custom policies
- Tasks that require use of root accounts
Protection of root accounts
2.4 Identify resources for security support
##  Recognize there are different network security capabilities
- Native AWS services (for example, security groups, Network ACLs, AWS WAF)
o 3
rd party security products from the AWS Marketplace
##  Recognize there is documentation and where to find it (for example, best practices,
whitepapers, official documents)
- AWS Knowledge Center, Security Center, security forum, and security blogs
- Partner Systems Integrators
##  Know that security checks are a component of AWS Trusted Advisor

Domain 3: Technology
3.1 Define methods of deploying and operating in the AWS Cloud
##  Identify at a high level different ways of provisioning and operating in the AWS cloud
- Programmatic access, APIs, SDKs, AWS Management Console, CLI, Infrastructure as
Code
##  Identify different types of cloud deployment models
- All in with cloud/cloud native
- Hybrid
- On-premises
##  Identify connectivity options
- VPN
- AWS Direct Connect
- Public internet
3.2 Define the AWS global infrastructure
##  Describe the relationships among Regions, Availability Zones, and Edge Locations
##  Describe how to achieve high availability through the use of multiple Availability Zones
- Recall that high availability is achieved by using multiple Availability Zones
- Recognize that Availability Zones do not share single points of failure
##  Describe when to consider the use of multiple AWS Regions
- Disaster recovery/business continuity
- Low latency for end-users
- Data sovereignty
##  Describe at a high level the benefits of Edge Locations
- Amazon CloudFront
- AWS Global Accelerator
3.3 Identify the core AWS services
##  Describe the categories of services on AWS (compute, storage, network, database)
##  Identify AWS compute services
- Recognize there are different compute families
- Recognize the different services that provide compute (for example, AWS Lambda
compared to Amazon Elastic Container Service (Amazon ECS), or Amazon EC2, etc.)
- Recognize that elasticity is achieved through Auto Scaling
- Identify the purpose of load balancers
##  Identify different AWS storage services
- Describe Amazon S3
- Describe Amazon Elastic Block Store (Amazon EBS)
- Describe Amazon S3 Glacier
- Describe AWS Snowball
- Describe Amazon Elastic File System (Amazon EFS)
- Describe AWS Storage Gateway
##  Identify AWS networking services
- Identify VPC
- Identify security groups
- Identify the purpose of Amazon Route 53
- Identify VPN, AWS Direct Connect
##  Identify different AWS database services
- Install databases on Amazon EC2 compared to AWS managed databases
- Identify Amazon RDS
- Identify Amazon DynamoDB
- Identify Amazon Redshift
3.4 Identify resources for technology support
##  Recognize there is documentation (best practices, whitepapers, AWS Knowledge Center,
forums, blogs)
##  Identify the various levels and scope of AWS support
- AWS Abuse
- AWS support cases
- Premium support
- Technical Account Managers
##  Recognize there is a partner network (marketplace, third-party) including Independent
Software Vendors and System Integrators
##  Identify sources of AWS technical assistance and knowledge including professional services,
solution architects, training and certification, and the Amazon Partner Network
##  Identify the benefits of using AWS Trusted Advisor
Domain 4: Billing and Pricing
4.1 Compare and contrast the various pricing models for AWS (for example, On-Demand Instances,
Reserved Instances, and Spot Instance pricing)
##  Identify scenarios/best fit for On-Demand Instance pricing
##  Identify scenarios/best fit for Reserved-Instance pricing
- Describe Reserved-Instances flexibility
- Describe Reserved-Instances behavior in AWS Organizations
##  Identify scenarios/best fit for Spot Instance pricing
4.2 Recognize the various account structures in relation to AWS billing and pricing
##  Recognize that consolidated billing is a feature of AWS Organizations
##  Identify how multiple accounts aid in allocating costs across departments
4.3 Identify resources available for billing support
##  Identify ways to get billing support and information
- Cost Explorer, AWS Cost and Usage Report, Amazon QuickSight, third-party partners,
and AWS Marketplace tools
- Open a billing support case
- The role of the Concierge for AWS Enterprise Support Plan customers
##  Identify where to find pricing information on AWS services
- AWS Simple Monthly Calculator
- AWS Services product pages
- AWS Pricing API
##  Recognize that alarms/alerts exist
##  Identify how tags are used in cost allocation

Appendix
Which key tools, technologies, and concepts might be covered on the exam?
The following is a non-exhaustive list of the tools and technologies that could appear on the exam. This list
is subject to change and is provided to help you understand the general scope of services, features, or
technologies on the exam. The general tools and technologies in this list appear in no particular order.
AWS services are grouped according to their primary functions. While some of these technologies will likely
be covered more than others on the exam, the order and placement of them in this list are no indication of
relative weight or importance:
##  APIs
-  Cost Explorer
-  AWS Cost and Usage Report
-  AWS Command Line Interface (CLI)
-  Elastic Load Balancers
-  Amazon EC2 instance types (for example, Reserved, On-Demand, Spot)
-  AWS global infrastructure (for example, AWS Regions, Availability Zones)
-  Infrastructure as Code (IaC)
-  Amazon Machine Images (AMIs)
-  AWS Management Console
-  AWS Marketplace
-  AWS Professional Services
-  AWS Personal Health Dashboard
-  Security groups
-  AWS Service Catalog
-  AWS Service Health Dashboard
-  Service quotas
-  AWS software development kits (SDKs)
-  AWS Support Center
-  AWS Support tiers
-  Virtual private networks (VPNs)
AWS services and features
Analytics:
-  Amazon Athena
-  Amazon Kinesis
-  Amazon QuickSight
Application Integration:
-  Amazon Simple Notification Service (Amazon SNS)
-  Amazon Simple Queue Service (Amazon SQS)
Compute and Serverless:
-  AWS Batch
-  Amazon EC2
-  AWS Elastic Beanstalk
-  AWS Lambda
-  Amazon Lightsail
-  Amazon WorkSpaces
Containers:
-  Amazon Elastic Container Service (Amazon ECS)
-  Amazon Elastic Kubernetes Service (Amazon EKS)
-  AWS Fargate
Database:
-  Amazon Aurora
-  Amazon DynamoDB
-  Amazon ElastiCache
-  Amazon RDS
-  Amazon Redshift
Developer Tools:
-  AWS CodeBuild
-  AWS CodeCommit
-  AWS CodeDeploy
-  AWS CodePipeline
-  AWS CodeStar
Customer Engagement:
-  Amazon Connect
Management, Monitoring, and Governance:
-  AWS Auto Scaling
-  AWS Budgets
-  AWS CloudFormation
-  AWS CloudTrail
-  Amazon CloudWatch
-  AWS Config
-  AWS Cost and Usage Report
-  Amazon EventBridge (Amazon CloudWatch Events)
-  AWS License Manager
-  AWS Managed Services
-  AWS Organizations
-  AWS Secrets Manager
-  AWS Systems Manager
-  AWS Systems Manager Parameter Store
-  AWS Trusted Advisor
Networking and Content Delivery:
-  Amazon API Gateway
-  Amazon CloudFront
-  AWS Direct Connect
-  Amazon Route 53
-  Amazon VPC
Security, Identity, and Compliance:
-  AWS Artifact
-  AWS Certificate Manager (ACM)
-  AWS CloudHSM
-  Amazon Cognito
-  Amazon Detective
-  Amazon GuardDuty
-  AWS Identity and Access Management (IAM)
-  Amazon Inspector
-  AWS License Manager
-  Amazon Macie
-  AWS Shield
-  AWS WAF
Storage:
-  AWS Backup
-  Amazon Elastic Block Store (Amazon EBS)
-  Amazon Elastic File System (Amazon EFS)
-  Amazon S3
-  Amazon S3 Glacier
-  AWS Snowball Edge
-  AWS Storage Gateway