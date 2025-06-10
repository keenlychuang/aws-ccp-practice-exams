# Practice Exam 4

1. According to the AWS Well-Architected Framework, which pillar emphasizes minimizing waste and maximizing efficiency in resource usage?
    - A. Cost Optimization
    - B. Sustainability
    - C. Performance Efficiency
    - D. Operational Excellence

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
    </details>

2. What is the primary advantage of cloud computing's pay-as-you-go model compared to traditional IT infrastructure?
    - A. Higher performance
    - B. Better security
    - C. Converting fixed costs to variable costs
    - D. Guaranteed uptime

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
    </details>

3. A company wants to "lift and shift" their existing applications to AWS with minimal changes. Which migration strategy does this represent?
    - A. Retire
    - B. Retain
    - C. Rehost
    - D. Repurchase

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
    </details>

4. Which economic benefit allows AWS customers to achieve lower unit costs as AWS grows?
    - A. Reserved capacity
    - B. Economies of scale
    - C. Pay-as-you-go pricing
    - D. Automation benefits

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
    </details>

5. In the AWS shared responsibility model, if you're using Amazon RDS, who is responsible for database engine patches?
    - A. Customer
    - B. AWS
    - C. Both customer and AWS
    - D. Database vendor

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
    </details>

6. Which AWS service helps you understand what data you have, where it's stored, and how it's being used for compliance purposes?
    - A. AWS Config
    - B. Amazon Macie
    - C. AWS CloudTrail
    - D. Amazon Inspector

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
    </details>

7. A developer needs programmatic access to AWS resources. What is the most secure way to authenticate API calls?
    - A. Embedding access keys in application code
    - B. Using IAM roles with temporary credentials
    - C. Sharing IAM user credentials
    - D. Using root account credentials

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
    </details>

8. Which AWS service provides centralized management of security findings from multiple AWS security services?
    - A. AWS WAF
    - B. AWS Security Hub
    - C. Amazon GuardDuty
    - D. AWS Shield

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
    </details>

9. When accessing AWS services, which method provides the most flexibility for automation and scripting?
    - A. AWS Management Console
    - B. AWS Mobile App
    - C. AWS CLI and SDKs
    - D. Third-party tools only

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
    </details>

10. A company deploys their application across three Availability Zones. If one AZ experiences an outage, what should happen to the application?
    - A. The entire application becomes unavailable
    - B. Performance degrades but the application remains available
    - C. Only data in the failed AZ is lost
    - D. The application automatically migrates to a different region

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
    </details>

11. Which AWS compute service is most suitable for applications that run continuously for months or years?
    - A. AWS Lambda
    - B. Amazon EC2
    - C. AWS Fargate
    - D. AWS Batch

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
    </details>

12. A startup needs to run containerized microservices without managing servers. Which service combination would be most appropriate?
    - A. Amazon EC2 + Docker
    - B. Amazon ECS + AWS Fargate
    - C. AWS Lambda + Amazon API Gateway
    - D. Amazon EKS + Amazon EC2

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
    </details>

13. Which AWS compute service automatically handles capacity provisioning, load balancing, and health monitoring?
    - A. Amazon EC2
    - B. AWS Elastic Beanstalk
    - C. Amazon ECS
    - D. AWS Lambda

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
    </details>

14. A gaming application requires extremely low latency database responses. Which AWS database service would be most appropriate?
    - A. Amazon RDS
    - B. Amazon DynamoDB with DynamoDB Accelerator (DAX)
    - C. Amazon Redshift
    - D. Amazon Aurora

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
    </details>

15. Which database migration scenario would benefit most from AWS Database Migration Service (DMS)?
    - A. Moving from one DynamoDB table to another
    - B. Migrating from Oracle on-premises to Amazon RDS
    - C. Backing up database data to S3
    - D. Replicating data within the same database

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
    </details>

16. A company needs to connect multiple VPCs across different regions. Which service provides the most scalable solution?
    - A. VPC Peering
    - B. AWS Transit Gateway
    - C. AWS Direct Connect
    - D. AWS Site-to-Site VPN

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
    </details>

17. Which AWS service would you use to accelerate global API performance by routing traffic through AWS's global network?
    - A. Amazon CloudFront
    - B. AWS Global Accelerator
    - C. Amazon Route 53
    - D. Elastic Load Balancing

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
    </details>

18. A company stores 100TB of data that is accessed once per quarter. Which S3 storage class would minimize costs?
    - A. S3 Standard
    - B. S3 Standard-IA
    - C. S3 Glacier Flexible Retrieval
    - D. S3 Glacier Deep Archive

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
    </details>

19. Which AWS storage service automatically scales and provides concurrent access from multiple EC2 instances?
    - A. Amazon EBS
    - B. Amazon EFS
    - C. Amazon S3
    - D. Instance Store

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
    </details>

20. A company needs to retain backups for 7 years for compliance but wants to minimize storage costs. What approach should they use?
    - A. Store everything in S3 Standard
    - B. Use S3 Lifecycle policies to move data to cheaper storage classes over time
    - C. Delete and recreate backups annually
    - D. Use only Amazon EBS snapshots

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
    </details>

21. Which AWS service would help a company automatically extract invoice data from scanned documents?
    - A. Amazon Comprehend
    - B. Amazon Textract
    - C. Amazon Rekognition
    - D. Amazon Transcribe

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
    </details>

22. A retail company wants to analyze customer behavior patterns from their e-commerce data. Which service would be most appropriate?
    - A. Amazon Kinesis Data Streams
    - B. Amazon EMR
    - C. AWS Glue
    - D. Amazon QuickSight

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D
    </details>

23. Which messaging pattern ensures that messages are processed in the exact order they were sent?
    - A. Amazon SQS Standard Queue
    - B. Amazon SQS FIFO Queue
    - C. Amazon SNS
    - D. Amazon EventBridge

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
    </details>

24. A company wants to send promotional emails to millions of customers. Which AWS service is specifically designed for this use case?
    - A. Amazon SNS
    - B. Amazon SQS
    - C. Amazon SES
    - D. Amazon Connect

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
    </details>

25. Which AWS service would help a company organize and govern commonly deployed IT services in a catalog?
    - A. AWS Organizations
    - B. AWS Service Catalog
    - C. AWS Config
    - D. AWS Systems Manager

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
    </details>

26. A development team wants to set up automated testing that runs every time code is committed. Which service combination would achieve this?
    - A. AWS CodeCommit + AWS CodeBuild
    - B. Amazon S3 + AWS Lambda
    - C. AWS CloudFormation + Amazon EC2
    - D. Amazon ECS + AWS Fargate

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A
    </details>

27. Which AWS service provides a managed artifact repository for storing packages like Maven, npm, and Python packages?
    - A. AWS CodeCommit
    - B. Amazon ECR
    - C. AWS CodeArtifact
    - D. Amazon S3

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
    </details>

28. A company needs to trace requests through their distributed microservices architecture. Which service would help with this?
    - A. AWS CloudTrail
    - B. Amazon CloudWatch
    - C. AWS X-Ray
    - D. AWS Config

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
    </details>

29. Which AWS service provides secure browser access to applications without requiring VPN software on end-user devices?
    - A. Amazon WorkSpaces
    - B. Amazon WorkSpaces Secure Browser
    - C. AWS Client VPN
    - D. Amazon AppStream 2.0

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
    </details>

30. A company is building a mobile app that needs offline capabilities and real-time data synchronization. Which AWS service would be most helpful?
    - A. Amazon DynamoDB
    - B. AWS AppSync
    - C. Amazon API Gateway
    - D. AWS Lambda

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
    </details>

31. Which IoT service provides device connectivity and message routing for IoT applications?
    - A. AWS IoT Device Management
    - B. AWS IoT Core
    - C. AWS IoT Analytics
    - D. AWS IoT Events

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
    </details>

32. A company runs batch processing jobs that can tolerate interruptions and has flexible timing requirements. Which EC2 pricing model offers the greatest cost savings?
    - A. On-Demand Instances
    - B. Reserved Instances
    - C. Spot Instances
    - D. Dedicated Instances

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
    </details>

33. Which statement about Convertible Reserved Instances is true?
    - A. They offer higher discounts than Standard Reserved Instances
    - B. They can be exchanged for different instance families, operating systems, or tenancies
    - C. They require a 3-year commitment minimum
    - D. They cannot be sold in the Reserved Instance Marketplace

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
    </details>

34. A company wants to receive alerts when their monthly AWS bill exceeds a certain threshold. Which service should they use?
    - A. AWS Cost Explorer
    - B. AWS Budgets
    - C. AWS Trusted Advisor
    - D. AWS Pricing Calculator

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
    </details>

35. Which feature allows you to see how costs would be affected by changing Reserved Instance attributes?
    - A. AWS Cost Explorer Reserved Instance recommendations
    - B. AWS Pricing Calculator
    - C. AWS Budgets
    - D. AWS Cost and Usage Reports

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A
    </details>

36. A company needs detailed, programmatic access to support case information. Which support plan provides access to the AWS Support API?
    - A. Basic
    - B. Developer
    - C. Business
    - D. All plans include API access

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
    </details>

37. Which AWS support plan includes a designated Technical Account Manager (TAM)?
    - A. Developer
    - B. Business
    - C. Enterprise On-Ramp
    - D. Enterprise

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D
    </details>

38. A company wants to find AWS experts to help design their cloud architecture. Where would they look for certified AWS consultants?
    - A. AWS Marketplace
    - B. AWS Partner Network
    - C. AWS Training and Certification
    - D. AWS Support Center

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
    </details>

39. Which resource provides implementation guides for specific AWS solutions and use cases?
    - A. AWS Documentation
    - B. AWS Prescriptive Guidance
    - C. AWS Whitepapers
    - D. AWS Training Materials

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
    </details>

40. A company wants to monitor the overall health and performance of their AWS services. Which dashboard should they use?
    - A. AWS Personal Health Dashboard
    - B. AWS Service Health Dashboard
    - C. AWS Trusted Advisor Dashboard
    - D. Amazon CloudWatch Dashboard

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A
    </details>

41. Which cloud architecture principles support building resilient applications? (Choose TWO)
    - A. Design for failure
    - B. Implement loose coupling
    - C. Use tight coupling
    - D. Avoid redundancy
    - E. Single points of failure

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, B
    </details>

42. Which migration approaches involve changing the application architecture? (Choose TWO)
    - A. Rehost
    - B. Replatform
    - C. Refactor
    - D. Repurchase
    - E. Retain

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C, D
    </details>

43. Which factors make cloud computing more economical than traditional data centers? (Choose TWO)
    - A. No need for IT staff
    - B. Reduced capital expenditure
    - C. Elimination of operational expenses
    - D. Pay only for resources consumed
    - E. Guaranteed cost savings

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B, D
    </details>

44. Which tasks are shared responsibilities between AWS and customers? (Choose TWO)
    - A. Physical security of data centers
    - B. Patch management
    - C. Configuration management
    - D. Hardware disposal
    - E. Network controls

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B, C
    </details>

45. Which AWS services provide data encryption capabilities? (Choose TWO)
    - A. AWS KMS
    - B. AWS CloudHSM
    - C. Amazon Route 53
    - D. AWS Direct Connect
    - E. Amazon CloudFront

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, B
    </details>

46. Which IAM best practices enhance security? (Choose TWO)
    - A. Enable MFA for privileged users
    - B. Use root account for daily operations
    - C. Rotate access keys regularly
    - D. Share IAM credentials between users
    - E. Disable unused services

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, C
    </details>

47. Which compute services can automatically scale based on demand? (Choose TWO)
    - A. AWS Lambda
    - B. Amazon EC2 with Auto Scaling
    - C. Amazon EBS
    - D. Amazon S3
    - E. Amazon VPC

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, B
    </details>

48. Which database services are fully managed by AWS? (Choose TWO)
    - A. Amazon DynamoDB
    - B. Amazon RDS
    - C. MySQL on EC2
    - D. PostgreSQL on EC2
    - E. MongoDB on EC2

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, B
    </details>

49. Which services improve application performance globally? (Choose TWO)
    - A. Amazon CloudFront
    - B. AWS Global Accelerator
    - C. Amazon S3
    - D. Amazon EBS
    - E. AWS Lambda

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, B
    </details>

50. Which S3 storage classes are designed for archival use cases? (Choose TWO)
    - A. S3 Standard
    - B. S3 Glacier Flexible Retrieval
    - C. S3 Glacier Deep Archive
    - D. S3 Standard-IA
    - E. S3 One Zone-IA

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B, C
    </details>

51. Which AI services provide pre-built machine learning capabilities? (Choose TWO)
    - A. Amazon Rekognition
    - B. Amazon Comprehend
    - C. Amazon SageMaker
    - D. Amazon EC2
    - E. Amazon RDS

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, B
    </details>

52. Which tools help optimize AWS costs? (Choose TWO)
    - A. AWS Trusted Advisor
    - B. AWS Compute Optimizer
    - C. Amazon CloudWatch
    - D. AWS Config
    - E. AWS CloudTrail

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, B
    </details>

53. A financial services company needs to ensure their application can handle a 10x increase in traffic during market opening hours. Which AWS capability should they implement?
    - A. Vertical scaling only
    - B. Horizontal scaling with Auto Scaling
    - C. Manual scaling
    - D. Over-provisioning resources

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
    </details>

54. Which AWS service would help detect and respond to unusual API activity that might indicate a security breach?
    - A. AWS CloudTrail
    - B. Amazon GuardDuty
    - C. AWS Config
    - D. Amazon CloudWatch

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
    </details>

55. A company wants to implement infrastructure as code to ensure consistent deployments. Which service should they use?
    - A. AWS CodeDeploy
    - B. AWS CloudFormation
    - C. AWS Config
    - D. AWS Systems Manager

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
    </details>

56. Which monitoring service provides the most comprehensive view of application performance across AWS services?
    - A. AWS CloudTrail
    - B. Amazon CloudWatch
    - C. AWS X-Ray
    - D. AWS Config

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
    </details>

57. A company needs to deploy a simple WordPress website quickly without managing servers. Which service provides the easiest solution?
    - A. Amazon EC2
    - B. AWS Elastic Beanstalk
    - C. Amazon Lightsail
    - D. AWS Lambda

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
    </details>

58. Which service would help a company build a conversational interface for their customer service application?
    - A. Amazon Polly
    - B. Amazon Lex
    - C. Amazon Comprehend
    - D. Amazon Transcribe

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
    </details>

59. If a company has predictable, steady-state compute requirements for 3 years, which pricing model provides the best value?
    - A. On-Demand Instances
    - B. Spot Instances
    - C. 3-year All Upfront Reserved Instances
    - D. Savings Plans

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
    </details>

60. Which AWS service provides language translation capabilities for applications?
    - A. Amazon Comprehend
    - B. Amazon Transcribe
    - C. Amazon Translate
    - D. Amazon Polly

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
    </details>

61. A company needs to store 50TB of data that will be accessed unpredictably. Which S3 storage class automatically optimizes costs?
    - A. S3 Standard
    - B. S3 Intelligent-Tiering
    - C. S3 Standard-IA
    - D. S3 Glacier

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
    </details>

62. Which service helps protect against Layer 3/4 DDoS attacks automatically?
    - A. AWS WAF
    - B. AWS Shield Standard
    - C. Amazon GuardDuty
    - D. AWS Security Hub

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
    </details>

63. A company wants to ensure their auto scaling responds to both CPU utilization and application-specific metrics. Which service should they use?
    - A. Amazon EC2 Auto Scaling only
    - B. AWS Auto Scaling with custom metrics
    - C. Elastic Load Balancing
    - D. Amazon CloudWatch Alarms only

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
    </details>

64. Which AWS service provides the most secure and efficient way to transfer terabytes of data from on-premises to AWS over the internet?
    - A. AWS Snow Family
    - B. AWS DataSync
    - C. AWS Direct Connect
    - D. S3 Transfer Acceleration

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
    </details>

65. A company needs instances with guaranteed network performance for high-frequency trading applications. Which EC2 feature should they use?
    - A. Placement Groups
    - B. Enhanced Networking
    - C. Both Placement Groups and Enhanced Networking
    - D. Dedicated Hosts only

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
    </details>
