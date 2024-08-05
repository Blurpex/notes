# analytics
### Amazon Athena
- serverless interactive query service that allows you to analyze large number of data directly in Amazon S3 using SQL
- no need to set up or manage infrastructure, simply point Athena to data stored in S3
### AWS Data Exchange
- allows you to securely and easily find, subscribe to, and use third-party data in AWS cloud
- browse and discover data products from data marketplace, subscribe to data products
### Amazon EMR (Elastic MapReduce)
- big data platform that simplifies the processing and analysis of large datasets
- uses open-source frameworks such as Apache Hadoop, Apache Spark, Apache HBase, and Apache Flink
### AWS Glue
- serverless service that simplifies and automates the process of moving and preparing data for analysis
- also called ETL tool - extract data from a source, transform it right way, and load it back to the data warehouse
### Amazon Kinesis
- designed to process large-scale data streams from a multiple services in real time
### Amazon Managed Streaming for Apache Kafka (MSK)
- **Apache Kafka** -> open source platform designed for building real time data pipelines and streaming applications
- MSK takes the complexity out of managing Apache Kafka clusters by handling the operational aspects
### Amazon OpenSearch Service
- **OpenSearch** -> open-source search and analytics engine derived from Elastisearch
### Amazon QuickSight
- **Business Intelligence (BI)** -> turn data into actionable insights to help businesses make better decisions
- QuickSight allows you to turn raw data into insights through interactive charts, graphs, and dashboards
### Amazon Redshift
- lets you store store and analyze large amounts of data quickly and efficiently
---
# application integration
### Amazon EventBridge
- **event-driven architecture** -> design pattern where the flow of a system is determined by events and components of a system communicate with each other by sending and receiving events
- EventBridge simplifies the process of connecting applications using events from various sources
### Amazon Simple Notification Service (SNS)
- serverless service that enables you to send notifications and messages to a variety of endpoints
- endpoints might include email, SMS, HTTP, SQS, application, etc
### Amazon Simple Queue Service (SQS)
- serverless service that enables you to decouple and scale microservices, distributele, and cost-effective solution for managing customer interactions. It enables businesses tod systems, and serverless applications
### AWS Step Functions
- serverless service that enables you to design, build, and manage complex workflows by defining a series of steps, that execute in a specific order
---
# business applications
### Amazon Connect
- enables businesses to set up and manage contact centers with minimal infrastructure and operational overhead
### Amazon Simple Email Service (SES)
- designed for sending transactional emails, marketing emails, etc
---
# cloud financial management
### AWS Billing Conductor
- designed to simplify and manage AWS billing and cost allocation for organizations with complex billing requirements
- provides granular control over cost allocation
### AWS Budgets
- helps you set and manage budgets for AWS spending and usage
- provides alerts and notifications when costs or usage exceed predefined budgets thresholds
### AWS Cost and Usage Report
- detailed and comprehensive report that provides a detailed breakdown of AWS cost or usage
- provides granular breakdown and can be integrated with other services for analysis
### AWS Cost Explorer
- helps you visualize, understand, and manage AWS spending and usage over time
### AWS Marketplace
- online store that offers a wide range of software, services, and solutions for AWS customers
---
# compute
### AWS Batch
- fully managed batch computing service that plans, schedules, and runs your containerized batch ML, simulation, and analytics workloads
### Amazon EC2
- scalable virtual servers in the cloud
### AWS Elastic BeanStalk
- automatically handles provisioning, deployment, scaling, and monitoring given a code
### Amazon Lightsail
- designed to make it easier for users to set up and manage virtual private servers with minimal configuration
### AWS Local Zones
- type of AWS infrastructure deployment that extends AWS services closer to end-users, enabling lower-latency access to applications and data
- brings AWS services closer to large population centers, industry hubs, and IT centers that are geographically distance from AWS's traditional regions
### AWS Outposts
- provides a hybrid cloud solution that allows you to run AWS services and applications on-premises
### AWS Wavelength
- aims to deliver ultra-low latency and high-bandwidth applications by extending AWS's cloud capabilities to the edge of the network
---
# containers
### Amazon Elastic Container Registry (ECR)
- allows you to store, manage, and deploy Docker containers images and other container artifacts
### Amazon Elastic Container Service (ECS)
- allows you to run, manage, and scale Docker containers on a cluster of EC2 instances or with AWS Fargate
### Amazon Elastic Kubernetes Service (EKS)
- simplifies the deployment, management, and scaling of Kubernetes applications by handling the operational overhead
---
# customer engagement
### AWS Activate for Startups
### AWS IQ
### AWS Managed Services (AMS)
### AWS Support
---
# database
---
# developer tools
### AWS AppConfig
- centralizes management of configuration data and gives you the ability to create, manage, and deploy configuration changes separate from code
- helps avoid deploying the service repeatedly for small changes
### AWS CLI
- allows to interact with AWS services using commands and scripts
### AWS Cloud9
- IDE preconfigured with AWS SDKs and tools
### AWS CloudShell
- browser based shell that provides a command line interface to interact with AWS services
### AWS CodeArtfiact
- artifact repository that allows you to store, manage, and share software packages used in your development software
- stores libraries and dependencies that your team might have developed
### AWS CodeBuild
- compiles source code, runs tests, and produces artifacts ready for development
- similar to GitHub actions
### AWS CodeCommit
- source control service that provides secure and scalable Git repositories
- similar to GitHub
### AWS CodeDeploy
- automates the deployment of applications to various compute services 
### AWS CodePipeline
- continuous integration and continuous delivery (CI/CD) service that automates the build, test, and deployment of applications
### AWS CodeStar
- interface for managing software development projects and CI/CD pipelines
- offers predefined templates for quick setup of development environments and pipelines
### AWS X-Ray
- distributed tracing service that helps developers analyze and debug complex, microservice-based applications 
---
# end user computing
---
# frontend web and mobile
---
# internet of things (IoT)
---
# machine learning
### Amazon Comprehend
- natural language processing (NLP) service that uses ML to uncover insights and relationships in text
### Amazon Kendra
- search service that uses ML to provide more accurate and relevant search results
- enterprises might have large volume of documentation, Kendra helps search proper one
### Amazon Lex
- service for building conversational interfaces and chatbots using voice and text
### Amazon Polly
- converts text into lifelike speech 
### Amazon Rekognition
- provides image and video analysis using deep learning, detects objects, scenes, and faces withing images and videos
### Amazon SageMaker
- enables developers to build, train, and deploy ML models quickly and easily
### Amazon Textract
- extracts text and data from documents and images 
- extracts handwriting, tables, forms
### Amazon Transcribe
- speech to text service that converts audio recordings into written text
### Amazon Translate
- nerual machine translation service that provides language translation for text
---
# management & governance
### AWS Auto Scaling
- service that automatically adjusts the number of instances in your application to ensure optimal performance and cost efficiency
### AWS CloudFormation
- service that allows you to define and provision AWS infrastructure using code
### AWS CloudTrail
- service that enables governance, compliance, and operational auditing of your AWS account by logging and monitoring API calls made on your account
### Amazon CloudWatch
- monitoring and observational serve that provides data and actionable insights from AWS cloud resources, applications, and services
### AWS Compute Optimizer
- helps optimize performance and cost of EC2 instances by recommending the best instance types based on usage pattern
### AWS Config
- enables you to assess, audit, and evaluate the configurations of your AWS services
### AWS Control Tower
- provides a simplified way to set up and govern a multi-account AWS environment
### AWS Health Dashboard
- provides a personalized view into the performance and availability of your AWS services
- offers insights into ongoing and upcoming events such as maintenance
### AWS Launch Wizard
- simpl
### AWS License Manager
- helps manage and track software licences 
### AWS Management Console
- web based interface that allows users to interact with and manage AWS services
### AWS Organizations
- helps you centrally manage and govern multiple AWS accounts
### AWS Resource Groups and Tag Editor
- allow you to organize and manage AWS resources using tags and resource groups
### AWS Service Catalog
- create, share, organize, and govern IaC templates
### AWS Systems Manager
- helps automate common administration tasks and provides visibility into resource configurations
### AWS Trusted Advisor
- service that provides real-time guidance to help follow AWS best practices
### AWS Well-Architected Tool
- helps you review and improve cloud-based architectures using AWS best practices

---
# migration & transfer
---
# networking & content delivery
### Amazon API Gateway
- service that makes it easy for developers to create, publish, maintain, monitor, and secure APIs at any scale
### Amazon CloudFront
- fast content delivery network (CDN) that delivers data to customers globally with low latency and high transfer speeds
### AWS Direct Connect
- service that makes it easy to establish a dedicated network connection from on-premises to AWS
### AWS Global Accelerator
- networking service that improves the availability and performance with global users 
### Amazon Route 53
- domain name system (DNS) web service designed to route end-user requests to applications
### Amazon VPC
- virtual private cloud allows you to provision a logically isolated section of the AWS cloud where you can launch AWS resources in a virtual network that you define
### AWS VPN
- enables you to establish a secure connection between on-premises network and AWS VPC
---
# security, identity, & compliance
### AWS artifact
- central resource for compliance-related information
### AWS Audit Manager
- helps audit AWS usage to simplify how you assess risk and compliance with regulations and industry standards
### AWS Certificate Manager
- service that lets you easily provision, manage, and deploy public and private SSL/TLS certificates for use with AWS services and your internal connected resources
### AWS CloudHSM (Hardware Security Module)
- provides a secure environment for cryptographic key generation and storage
### Amazon Cognito
- service that simplifies the process of adding authentication, authorization, and user management to your web and mobile applications
### Amazon Detective
- analyzes and visualizes security data to investigate potential security issues
- collects data from from CloudTrail, GuardDuty, etc, and processes data to build a comprehensive view of your resources and interactions
### AWS Directory Service
- **active directory** -> database for enterprise to look up people and resources in the company, manage permissions, policies, authentication, etc
- enables you to use managed Active Directory in the AWS cloud
### AWS Firewall Manager
- allows you to centrally configure and manage firewall rules across your AWS accounts and applications
### Amazon GuardDuty
- threat detection service that monitors your AWS accounts and workloads for malicious activity and unauthorized behavior
### AWS Identity & Access Management (IAM)
- create and manage AWS users and groups, assign granular permissions, role based access control, and user federation
### AWS IAM Identity Center (AWS Single Sign-On)
- simplifies access management by allowing users to access multiple AWS accounts with a single set of credentials
### Amazon Inspector
- automated security assessment service that helps improve the security and compliance of applications deployed on AWS
### AWS Key Management Service (KMS)
- service that makes it easy to create and control cryptographic keys used to encrypt data
### Amazon Macie
- data security and data privacy service that uses ML to automatically discover, classify, and protect sensitive data
### AWS Network Firewall
- provides enhanced protection for your VPCs
### AWS Resource Access Manager (RAM)
- allows you to share AWS resources with other AWS accounts or within your organization
### AWS Secrets Manager
- secret manager, automatic rotation, secure access
### AWS Security Hub
- centralized security view, compliance monitoring, automated response
### AWS Shield
- DDoS protection service 
### AWS WAF
- protects web application from common web exploits and vulnerabilities
---
# serverless
---
# storage

---
# summary
## analytics
- **Athena** -> interactive query service
- **Data Exchange** -> data marketplace
- **Elastic MapReduce** -> big data processing
- **Glue** -> ETL (extract, transform, load)
- **Kinesis** -> real time data processing
- **Managed Streaming for Kafka** -> Kafka wrapper service
- **OpenSearch** -> search (data quickly) and analytics
- **QuickSight** -> business intelligence service
- **Redshift** -> data warehousing
## management & governance
- **AWS Auto Scaling**: Automatically adjusts the number of EC2 instances based on demand.
- **AWS CloudFormation**: Treats infrastructure as code for provisioning AWS resources.
- **AWS CloudTrail**: Logs and monitors API activity for governance and auditing.
- **Amazon CloudWatch**: Provides monitoring and observability for AWS resources.
- **AWS Compute Optimizer**: Recommends optimal resources for cost and performance.
- **AWS Config**: Tracks and evaluates resource configurations for compliance.
- **AWS Control Tower**: Simplifies setup and governance of a multi-account AWS environment.
- **AWS Health Dashboard**: Offers personalized views of AWS service health and events.
- **AWS Launch Wizard**: Guides you through the deployment of applications.
- **AWS License Manager**: Manages software licenses across AWS and on-premises.
- **AWS Management Console**: Provides a web-based interface for managing AWS resources.
- **AWS Organizations**: Manages multiple AWS accounts with policy-based management.
- **AWS Resource Groups and Tag Editor**: Organizes and manages resources using tags.
- **AWS Service Catalog**: Manages catalogs of approved IT services.
- **AWS Systems Manager**: Offers unified management and automation of AWS resources.
- **AWS Trusted Advisor**: Provides real-time best practice guidance.
- **AWS Well-Architected Tool**: Reviews and improves cloud architectures based on best practices.
---
