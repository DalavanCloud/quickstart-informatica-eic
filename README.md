# quickstart-informatica-eic

This Quick Start deploys Enterprise Information Catalog from Informatica on the AWS Cloud. Enterprise Information Catalog helps you discover and catalog assets along with their relationships from data sources across your enterprise. Assets are data objects such as tables, columns, reports, views, and schemas, and might exist in relational databases, purpose-built applications, ETL or business intelligence tools, and big data systems.

![Quick Start Informatica Enterprise Information Catalog Design Architecture](https://d0.awsstatic.com/partner-network/QuickStart/datasheets/informatica-eic-architecture-on-aws.png)

Deployment steps:

1. Sign up for an AWS account at http://aws.amazon.com, select a region, and create a key pair.
2. Obtain a license for Enterprise Information Catalog from [Informatica](https://now.informatica.com/enterprise-information-catalog-aws-contact-us.html).
3. In the AWS CloudFormation console, launch one of the following templates from the S3 URL to build a new stack:
  * [informatica-eic-master.template](https://fwd.aws/Be5Kp) (to deploy Informatica Enterprise Information Catalog into a new VPC)
  * [informatica-eic.template](https://fwd.aws/XP4DB) (to deploy Informatica Enterprise Information Catalog into your existing VPC)

To customize your deployment, you can choose different instance types for your resources and configure the size of the Informatica embedded cluster. You can also choose to import sample catalog data to start using Enterprise Information Catalog on AWS.

For detailed deployment and configuration instructions, see the [Quick Start deployment guide](https://fwd.aws/gqWWa).
 
