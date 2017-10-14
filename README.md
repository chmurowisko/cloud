# CLOUD COMPUTING

List of resources, tools, links around cloud computing topics - mainly AWS, Azure, GCP.

# AWS
## NETWORKING
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


## SECURITY + IDENTITY + COMPLIANCE

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

