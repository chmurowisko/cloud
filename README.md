# CLOUD COMPUTING

List of resources, tools, links around cloud computing topics - mainly AWS, Azure, GCP. All in one page. Simply use search to find what you need.

# AWS

## COMPUTE

### Amazon EC2
#### Description
#### Similar Services
#### Important Links
#### Tools + Repos + Labs
#### Price
#### Video
#### Important
#### History

### Amazon EC2 Container Registry
#### Description
#### Similar Services
#### Important Links
#### Tools + Repos + Labs
#### Price
#### Video
#### Important
#### History

### Amazon EC2 Container Service
#### Description
#### Similar Services
#### Important Links
#### Tools + Repos + Labs
#### Price
#### Video
#### Important
#### History

### Amazon Lightsail
#### Description
#### Similar Services
#### Important Links
#### Tools + Repos + Labs
#### Price
#### Video
#### Important
#### History

### AWS Batch
#### Description
#### Similar Services
#### Important Links
#### Tools + Repos + Labs
#### Price
#### Video
#### Important
#### History

### AWS Elastic Beanstalk
#### Description
#### Similar Services
#### Important Links
#### Tools + Repos + Labs
#### Price
#### Video
#### Important
#### History

### AWS Lambda
#### Description

A web service that lets you run code without provisioning or managing servers. You can run code for virtually any type of application or back-end service with zero administration. [[source](http://docs.aws.amazon.com/general/latest/gr/glos-chap.html)]

#### Similar Services
- Azure => [Azure Functions](https://azure.microsoft.com/en-us/services/functions/)
- GCP => [Google Cloud Functions](https://cloud.google.com/functions/)
- IBM BlueMix => [IBM Cloud Functions](https://console.bluemix.net/openwhisk/)

#### Important Links

#### Tools + Repos + Labs

- [Microsoft/WingtipSaaS](https://github.com/Microsoft/WingtipSaaS) - A sample SaaS application and associated tutorials, built on Azure App Service and Azure SQL Database.

#### Price

#### Video

- [AWS Lambda@Edge Lightning Demos](https://www.youtube.com/watch?v=jJsWB7CjY-U)

#### Important

#### History

## STORAGE

### Amazon Simple Storage Service (S3)
#### Description
#### Similar Services
#### Important Links
#### Tools + Repos + Labs
#### Price
#### Video
#### Important
#### History

### Amazon Elastic Block Storage (EBS)
#### Description
#### Similar Services
#### Important Links
#### Tools + Repos + Labs
#### Price
#### Video
#### Important
#### History

### Amazon Elastic File System (EFS)
#### Description
#### Similar Services
#### Important Links
#### Tools + Repos + Labs
#### Price
#### Video
#### Important
#### History

### Amazon Glacier
#### Description
#### Similar Services
#### Important Links
#### Tools + Repos + Labs
#### Price
#### Video
#### Important
#### History

### AWS Storage Gateway
#### Description
#### Similar Services
#### Important Links
#### Tools + Repos + Labs
#### Price
#### Video
#### Important
#### History

### AWS Snowball
#### Description
#### Similar Services
#### Important Links
#### Tools + Repos + Labs
#### Price
#### Video
#### Important
#### History

### AWS Snowball Edge
#### Description
#### Similar Services
#### Important Links
#### Tools + Repos + Labs
#### Price
#### Video
#### Important
#### History

### AWS Snowmobile
#### Description
#### Similar Services
#### Important Links
#### Tools + Repos + Labs
#### Price
#### Video
#### Important
#### History

## DATABASE

### Amazon RDS
#### Description
#### Similar Services
#### Important Links
#### Tools + Repos + Labs
#### Price
#### Video
#### Important
#### History

### Amazon DynamoDB
#### Description
#### Similar Services
#### Important Links
#### Tools + Repos + Labs
#### Price
#### Video
#### Important
#### History

### Amazon DynamoDB Accelerator (DAX)
#### Description
#### Similar Services
#### Important Links
#### Tools + Repos + Labs
#### Price
#### Video
#### Important
#### History

### Amazon ElastiCache
#### Description
#### Similar Services
#### Important Links
#### Tools + Repos + Labs
#### Price
#### Video
#### Important
#### History

### Amazon Redshift
#### Description
#### Similar Services
#### Important Links
#### Tools + Repos + Labs
#### Price
#### Video
#### Important
#### History

## MIGRATION

### AWS Migration Hub
### AWS Application Discovery Service
### AWS Database Migration Service
AWS Schema Conversion Tool
### AWS Server Migration Service

## NETWORKING

### Amazon VPC
#### Description
#### Similar Services
#### Important Links
#### Tools + Repos + Labs
#### Price
#### Video
#### Important
#### History

### Amazon CloudFront
#### Description
#### Similar Services
#### Important Links
#### Tools + Repos + Labs
#### Price
#### Video
#### Important
#### History

### Amazon Route 53
#### Description
#### Similar Services
#### Important Links
#### Tools + Repos + Labs
#### Price
#### Video
#### Important
#### History

### Elastic Load Balancing
#### Description

A web service that improves an application's availability by distributing incoming traffic between two or more EC2 instances. [[source](http://docs.aws.amazon.com/general/latest/gr/glos-chap.html)][[graphic by awskeek](https://www.awsgeek.com/images/aws-alb-summary.jpg)]

#### Similar Services
#### Important Links
#### Tools + Repos + Labs
#### Price
#### Video
#### Important
#### History

### AWS Direct Connect
#### Description

A web service that simplifies establishing a dedicated network connection from your premises to AWS. [[source](http://docs.aws.amazon.com/general/latest/gr/glos-chap.html)]

#### Similar Services

#### Important Links

- [FAQ](https://aws.amazon.com/directconnect/faqs/)
- [Product Details](https://aws.amazon.com/directconnect/details/)
- [CLI Reference](http://docs.aws.amazon.com/cli/latest/reference/directconnect/index.html)
- [Documentation](http://docs.aws.amazon.com/directconnect/latest/UserGuide/Welcome.html)
- [API Reference](http://docs.aws.amazon.com/directconnect/latest/APIReference/Welcome.html)

#### Tools + Repos + Labs
#### Price

##### Two factors:
- Wielkość portu po stronie AWS
- Transfer danych wychodzący z AWS

##### Example for Frankfurt:
- Port 100 Mb/s po stronie AWS
- Kolokacja portu w CE Colo Prague to/from EU Central (Frankfurt) Region
- Wysyłamy z AWS 400 GB danych miesięcznie do lokalnego Data Center
- Port - $0.06/hour
- Transfer - $0.030/GB
- **Suma** - (30 * 24 * $0.06) + (400 * $0.030) = $43,2 + $12 = $**55,2**

##### Important:
- We must pay for links, transfer, equipment, etc. for a local ISP.


#### Video

- [AWS re:Invent 2016: Deep Dive: AWS Direct Connect and VPNs (NET402)](https://www.youtube.com/watch?v=Qep11X1r1QA)

#### Important

- If you want to have redundancy you need a second AWS Direct Connect link (price x2) or VPN connection.
- AWS Direct Connect doesn’t have Service Level Agreement (SLA)
- AWS announces all ip prefixes from a certain AWS region via AWS Direct Connect
- It’s possible to add another BGP session for IPv6 traffic

#### History

- 2017.10.10 - [Now you can configure Amazon side private ASN for your Virtual Private Gateway](https://aws.amazon.com/about-aws/whats-new/2017/10/now-you-can-configure-amazon-side-private-autonomous-system-number-for-your-virtual-private-gateway/)
- 2017.09.12 - [Announcing New AWS Direct Connect Location in Houston, TX](https://aws.amazon.com/about-aws/whats-new/2017/)
- 2017.08.31 - [Announcing New AWS Direct Connect Location in Boston, MA](https://aws.amazon.com/about-aws/whats-new/2017/08/announcing-new-aws-direct-connect-location-in-boston-ma/)
- 2017.07.29 - [AWS Direct Connect now provides Amazon CloudWatch Monitoring](https://aws.amazon.com/about-aws/whats-new/2017/06/aws-direct-connect-now-provides-amazon-cloudwatch-monitoring/)
- 2017.06.27 - [Announcing New AWS Direct Connect Locations in Kuala Lumpur and Seoul](https://aws.amazon.com/about-aws/whats-new/2017/06/announcing-new-aws-direct-connect-locations-in-kuala-lumpur-and-seoul/)
- 2017.05.31 - [Announcing New AWS Direct Connect Locations in Atlanta, Columbus and Toronto](https://aws.amazon.com/about-aws/whats-new/2017/05/announcing-new-aws-direct-connect-locations-in-atlanta-columbus-and-toronto/)
- 2017.05.23 - [Announcing New Direct Connect Locations in Marseille, France and Warsaw, Poland](https://aws.amazon.com/about-aws/whats-new/2017/05/announcing-new-direct-connect-locations-in-marseille-france-and-warsaw-poland/)
- 2017.05.21 - [Announcing New Direct Connect Locations in Philadelphia, PA and Newark, NJ](https://aws.amazon.com/about-aws/whats-new/2017/05/announcing-new-direct-connect-locations-in-philadelphia-pa-and-newark-nj/)
- 2017.03.28 - [Announcing New Direct Connect Locations in Munich, Prague, Berlin, and Zurich](https://aws.amazon.com/about-aws/whats-new/2017/03/announcing-new-aws-direct-connect-location-in-munich-prague-berlin-zurich/)
- 2017.03.10 - [AWS Direct Connect joins growing list of HIPAA-eligible services from AWS!](https://aws.amazon.com/about-aws/whats-new/2017/03/aws-direct-connect-joins-growing-list-of-hipaa-eligible-services-from-aws/)
- 2017.03.08 - [Announcing New Direct Connect Location in Vienna](https://aws.amazon.com/about-aws/whats-new/2017/03/announcing-new-aws-direct-connect-location-in-vienna/)
- 2017.02.28 - [AWS Direct Connect enables Link Aggregation Group for additional AWS regions](https://aws.amazon.com/about-aws/whats-new/2017/02/aws-direct-connect-enables-link-aggregation-group-for-additional-aws-regions/)
- 2017.02.13 - [AWS Direct Connect announces support for Link Aggregation](https://aws.amazon.com/about-aws/whats-new/2017/02/aws-direct-connect-announces-support-for-link-aggregation/)
- 2011.08.03 - [Announcing AWS Direct Connect](https://aws.amazon.com/about-aws/whats-new/2011/08/03/Announcing-AWS-Direct-Connect/)

## DEVELOPER TOOLS

### AWS CodeStar
#### Description
#### Similar Services
#### Important Links
#### Tools + Repos + Labs
#### Price
#### Video
#### Important
#### History

### AWS CodeCommit
#### Description
#### Similar Services
#### Important Links
#### Tools + Repos + Labs
#### Price
#### Video
#### Important
#### History

### AWS CodeBuild
#### Description
#### Similar Services
#### Important Links
#### Tools + Repos + Labs
#### Price
#### Video
#### Important
#### History

### AWS CodeDeploy
#### Description
#### Similar Services
#### Important Links
#### Tools + Repos + Labs
#### Price
#### Video
#### Important
#### History

### AWS CodePipeline
#### Description
#### Similar Services
#### Important Links
#### Tools + Repos + Labs
#### Price
#### Video
#### Important
#### History

### AWS X-Ray
#### Description
#### Similar Services
#### Important Links
#### Tools + Repos + Labs
#### Price
#### Video
#### Important
#### History



## MANAGEMENT

### Amazon CloudWatch
### Amazon EC2 Systems Manager
### AWS CloudFormation
### AWS CloudTrail
### AWS Config
### AWS OpsWorks
### AWS Service Catalog
### AWS Trusted Advisor
### AWS Personal Health Dashboard
### AWS Managed Services

## ARTIFICIAL INTELLIGENCE

### Amazon Lex
### Amazon Polly
### Amazon Rekognition
### Amazon Machine Learning

## ANALYTICS

### Amazon Athena
### Amazon EMR
### Amazon CloudSearch
### Amazon Elasticsearch Service
### Amazon Kinesis
### Amazon QuickSight
### AWS Data Pipeline
### AWS Glue

## INTERNET OF THINGS

### AWS IoT Platform
### AWS Greengrass

## SECURITY + IDENTITY + COMPLIANCE

### AWS Identity and Access Management (IAM)
### Amazon Cloud Directory
### Amazon Inspector
### Amazon Macie
### AWS Certificate Manager
### AWS CloudHSM
### AWS Directory Service
### AWS Key Management Service
### AWS Shield
### AWS WAF
### AWS Artifact

### AWS Organizations
#### Description
An account management service that enables you to consolidate multiple AWS accounts into an organization that you create and centrally manage. [[source](http://docs.aws.amazon.com/general/latest/gr/glos-chap.html)]

#### Similar Services
#### Important Links
#### Tools + Repos + Labs
- [Creating AWS Accounts From The Command Line With AWS Organizations](https://alestic.com/2017/09/aws-organizations-cli/)

#### Price
#### Video
#### Important
#### History

## WEB & MOBILE

### AWS Mobile Hub
#### Description
#### Similar Services
#### Important Links
#### Tools + Repos + Labs
#### Price
#### Video
#### Important
#### History

### Amazon Cognito
#### Description
#### Similar Services
#### Important Links
#### Tools + Repos + Labs
#### Price
#### Video
#### Important
#### History

### Amazon Pinpoint
#### Description
#### Similar Services
#### Important Links
#### Tools + Repos + Labs
#### Price
#### Video
#### Important
#### History

### AWS Device Farm
#### Description
#### Similar Services
#### Important Links
#### Tools + Repos + Labs
#### Price
#### Video
#### Important
#### History

### Amazon API Gateway
#### Description
#### Similar Services
#### Important Links
#### Tools + Repos + Labs
#### Price
#### Video
#### Important
#### History

### Amazon Elastic Transcoder
#### Description
#### Similar Services
#### Important Links
#### Tools + Repos + Labs
#### Price
#### Video
#### Important
#### History

### AWS Step Functions
#### Description
#### Similar Services
#### Important Links
#### Tools + Repos + Labs
#### Price
#### Video
#### Important
#### History

## MESSAGING

### Amazon Simple Queue Service (SQS)
### Amazon Simple Notification Service (SNS)
### Amazon Pinpoint
### Amazon Simple Email Service (SES)

## BUSINESS PRODUCTIVITY

### Amazon Chime
### Amazon WorkDocs
### Amazon WorkMail
### Amazon Connect

## DESKTOP & APP STREAMING

### Amazon WorkSpaces
### Amazon AppStream 2.0

## Game Development

### Amazon GameLift

## Other AWS Tools/Libraries Around Cloud Computing

### AWS Schema Conversion Tool
### AWS Personal Health Dashboard
### AWS Command Line Interface
### AWS ElasticBeanstalk CLI
### Amazon ECS CLI
### AWS PowerShell Tools
### AWS Management Console
### Apache MXNet on AWS
### TensorFlow on AWS
### AWS Deep Learning AMIs
### Amazon Lumberyard
### AWS IoT Button
### AWS Marketplace
### AWS Cost Explorer
### AWS Budgets
### IDE Toolkit Eclipse
### IDE Toolkit Visual Studio

### SDK

#### Java Script
#### Node.js
#### Python
#### PHP
#### .NET
#### Ruby
#### Java
#### Go
#### C++

### Mobile SDK

#### iOS
#### Android/FireOS
#### Xamarin
#### Unity
#### React Native

### IoT SDK

#### Embedded C
#### JavaScript
#### Arduino Yún
#### Java
#### Python
#### C++

# AZURE
## WEB + MOBILE

### Azure App Service

#### Description

#### Similar Services

#### Important Links

#### Tools + Repos + Labs

- [Microsoft/WingtipSaaS](https://github.com/Microsoft/WingtipSaaS) - A sample SaaS application and associated tutorials, built on Azure App Service and Azure SQL Database.

#### Price

#### Video

#### Important

#### History


## DATABASES 

### Azure SQL Database

#### Description

#### Similar Services

- AWS => [Amazon Relational Database Service (RDS)](https://aws.amazon.com/rds/)
- GCP => [Google Cloud SQL](https://cloud.google.com/sql/)
- GCP => [Google Cloud Spanner](https://cloud.google.com/spanner/)

#### Important Links

#### Tools + Repos + Labs

- [Microsoft/WingtipSaaS](https://github.com/Microsoft/WingtipSaaS) - A sample SaaS application and associated tutorials, built on Azure App Service and Azure SQL Database.

#### Price

#### Video

#### Important

#### History

