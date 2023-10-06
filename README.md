# AWS
## Compute Services

- **Amazon EC2 (Elastic Compute Cloud)**:
  - Provides virtual machines for hosting applications traditionally run on on-premises servers.
  - Key Components: Amazon Machine Image (AMI), Instance type, Network settings, Instance store (temporary block-level storage).

- **AWS Lambda**:
  - Enables code execution without provisioning or managing servers.

- **AWS Elastic Beanstalk**:
  - Platform as a Service (PaaS) for quick deployment, scaling, and management of applications.
  - Supported Servers: Apache HTTP Server, Microsoft IIS.

- **AWS EC2 Autoscaling**:
  - Maintains application availability by adding or removing EC2 instances based on defined conditions.
  - Tracks instance health and terminates unhealthy instances.

## Container Services

- **Amazon ECS (Elastic Container Service)**:
  - Container management service supporting Docker containers.

- **Amazon EKS (Elastic Kubernetes Service)**:
  - Facilitates deployment, management, and scaling of containerized applications using Kubernetes.

- **Amazon ECR (Elastic Container Registry)**:
  - Fully managed Docker container registry for storing, managing, and deploying container images.

- **AWS Fargate**:
  - Compute engine for running containers without managing servers or clusters.

## Storage Services

- **Amazon S3 (Simple Storage Service)**:
  - Object storage service with data stored redundantly in buckets.

- **Amazon S3 Glacier**:
  - Cloud storage class for data archiving and long-term backup.

- **Amazon EFS (Elastic File System)**:
  - Scalable, fully managed Network File System (NFS) for use with AWS, auto-scaling to petabytes.

- **Amazon EBS (Elastic Block Store)**:
  - High-performance block storage for use with Amazon EC2.

- **AWS Storage Gateway**:
  - Hybrid storage service for integrating on-premises applications with AWS Cloud storage.

## Database Services

- **Amazon RDS (Relational Database Service)**:
  - Cloud-based relational database service.

- **Amazon DynamoDB**:
  - Key-value and document database, NoSQL. Data stored in partitions.

- **Amazon Redshift**:
  - Fully managed, petabyte-scale data warehouse service in the cloud.

- **Amazon Aurora**:
  - Relational database compatible with MySQL and PostgreSQL.

- **AWS Data Migration Service (DMS)**:
  - Migrates databases to AWS easily and securely.

- **AWS Athena**:
  - SQL querying service for data in Amazon S3.

## 7 Layers of the OSI Model
- **Physical Layer**: Network Hardening.
- **Data Link Layer**: Systems Hardening.
- **Network Layer**: Data Security.
- **Transport Layer**: Identity Management.
- **Session Layer**: Information Management.
- **Presentation Layer**: Data format translation, encryption, and decryption.
- **Application Layer**: Interaction with software applications, ensuring communication, and data delivery to end-users.

## Data Transfer Services

- **AWS Transfer Family**:
  - Transfer files over SFTP, FTPS, and FTP.

- **AWS DataSync**:
  - Simplifies, automates, and accelerates moving and replicating data between on-premises storage systems and AWS storage services.

- **AWS Snowball**:
  - Secure, rugged devices for bringing AWS computing and storage capabilities to edge environments and transferring data into and out of AWS.

## Security, Identity, and Compliance Services

- **AWS IAM (Identity and Access Management)**:
  - Manages access to AWS services and resources securely through users, groups, and roles.
  - Charges: None.

- **Amazon Cognito**:
  - Provides user management, authentication, and authorization for web and mobile apps.

- **AWS Shield**:
  - Managed DDoS protection service.

- **AWS Artifact**:
  - On-demand access to AWS security and compliance reports and select online agreements.

- **AWS KMS (Key Management Service)**:
  - Creates and manages keys for secure data encryption.

- **AWS Organizations**:
  - Account management service for restricting service and action access within accounts.

- **AWS GuardDuty**:
  - Threat detection service, works like an anti-virus.

- **AWS Config**:
  - Tracks resource inventory and changes, aiding in compliance auditing, security analysis, and troubleshooting.

- **Amazon Macie**: 
  - Fully managed data security and data privacy service that uses machine learning to discover, monitor, and protect sensitive data.

## Networking and Content Delivery Services

- **Amazon VPC (Virtual Private Cloud)**:
  - Provisions logically isolated sections of the AWS Cloud.
  - Charges: None.

- **Amazon Route 53**:
  - Scalable cloud Domain Name System (DNS) web service for reliable routing to internet applications.

- **Amazon CloudFront**:
  - Fast content delivery network (CDN) service for secure data and dynamic web content delivery.

- **Elastic Load Balancing**:
  - Distributes incoming application traffic across multiple targets based on rules and listeners.

- **AWS Transit Gateway**:
  - Connects virtual private clouds (VPCs) and on-premises networks to a single gateway.

- **AWS Direct Connect**:
  - Establishes a dedicated private network connection from your premises to AWS.

- **AWS VPN**:
  - Provides a secure private tunnel from your network or device to the AWS global network.

- **Amazon API Gateway**:
  - Handles tasks involved in accepting and processing concurrent API calls at scale.

- **AWS App Mesh**:
  - Service mesh that provides application-level networking to make it easy for your services to communicate with each other across multiple types of compute infrastructure.

## Management and Governance Services

- **Amazon CloudWatch**:
  - Monitors resources and applications, collects and tracks log files.

- **AWS Trusted Advisor**:
  - Online resource for reducing cost, increasing performance, and improving security by optimizing the AWS environment.

- **AWS CloudTrail**:
  - Generates logs of calls to the AWS application programming interface (API).

- **AWS Well-Architected Tool**:
  - Helps review and improve workloads by following best practices.

- **AWS Auto Scaling**:
  - Scales multiple resources to meet demand.

- **AWS CLI (Command Line Interface)**:
  - Unified tool to manage AWS services.

- **AWS Config**:
  - Tracks resource inventory and changes.

- **AWS Management Console**:
  - Web-based interface for accessing AWS account.

- **AWS Systems Manager**:
  - Automates common and repetitive IT operations and management tasks across AWS resources.

- **AWS OpsWorks**:
  - Configuration management service providing managed instances of Chef and Puppet.

- **AWS CloudFormation**:
  - Creates and provisions AWS infrastructure deployments predictably and repeatedly.

- **AWS Control Tower**:
    - Provides an easy way to set up and govern a new, secure, multi-account AWS environment based on best practices established through AWS's experience working with thousands of enterprises as they move to the cloud.

## AWS Cost Management Services

- **AWS Cost and Usage Report**:
  - Comprehensive set of AWS cost and usage data.

- **AWS Budget**:
  - Sets custom budgets that alert when costs or usage exceed or are forecasted to exceed the budgeted amount.

- **AWS Cost Explorer**:
  - Interface for visualizing, understanding, and managing AWS costs and usage over time.

- **AWS Pricing Calculator**:
  - Estimates AWS monthly services costs, identifies cost reduction opportunities, and models solutions using templates.

- **AWS Savings Plans**:
    - Offers significant savings over specified usage in exchange for a commitment to use a specific amount of resources for a one or three-year period

## Additional AWS Services and Frameworks

- **Amazon Workspaces**:
  - Allows employees to connect remotely.

- **AWS Cloud Adoption Framework (AWS CAF)**:
  - Guides organizations in developing efficient and effective plans for cloud adoption focusing on Business and Technical capacities.

- **Well-Architected Framework**:
  - Provides a consistent approach to evaluate cloud architectures and offers guidance for implementation.

- **SysOps (Systems Operations)**:
  - Involves the administration of large, multiuser systems.

- **AWS Tools for PowerShell**:
  - Enables scripting operations on AWS resources from the PowerShell command line.

- **AWS Step Functions**:
  - Coordinates multiple AWS services into serverless workflows for quick application building and updating.

- **AWS Support**:
  - Offers varying levels of support including Basic, Developer, Business, and Enterprise support.

- **AWS X-Ray**:
    - Helps developers analyze and debug production, distributed applications, such as those built using a microservices architecture.


## Business Continuity Planning (BCP) and Disaster Recovery Planning (DRP)

- **BCP**: Strategies for running the business in a reduced capacity during disruptions.
- **DRP**: Strategies for recovering from outages or losses and returning to normal operations as quickly as possible.
