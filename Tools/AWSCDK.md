# AWS CDK

The AWS CDK stands as a framework enabling the definition of cloud infrastructure through code, and its provisioning via CloudFormation. It furnishes high-level components that come preconfigured with established defaults for cloud resources, thereby enabling the construction of cloud applications without requiring specialized expertise.

Utilizing a supported programming language, such as C# for .NET, allows you to accomplish the following:

* Employ logic constructs like if-statements and for-loops in defining cloud infrastructure.
* Utilize object-oriented methodologies to construct a system model.
* Organize projects into coherent modules.
* Benefit from code completion capabilities within your integrated development environment (IDE) or editor.

## AWS CDK Concepts

* Construct - Basic building block of AWS CDK apps.  Constructs represnet a cloud component and encapulates everything CloudFormation needs to create the component.  Each construct defines one or more concrete AWS resources, such as S3 buckets, Lambda functions, or DynamoDB tables.
* Stack - A unit of deployment.  All AWS resources defined in the scope of a stack are provisioned as a single unit.
* App - Container for one or more stacks.  An app serves as a scope for stacks.  Stacks within a single app can refer to each other's resources.
* CloudFormation Template - AWS CDK code is converted to CloudFormation templates
* CloudFormation - Provisiones the demplates and deploys resources in an AWS account.


## Resources

[AWS CDK developer tool](https://aws.amazon.com/cdk/)
[Working with the AWS CDK in C#](https://docs.aws.amazon.com/cdk/v2/guide/work-with-cdk-csharp.html)
