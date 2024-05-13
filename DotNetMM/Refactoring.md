# AWS Toolkit for .NET Refactoring

The AWS Toolkit for .NET Refactoring, an extension for Visual Studio, streamlines the process of refactoring legacy .NET applications to cloud-based solutions on AWS, minimizing time and effort.

The AWS Toolkit for .NET Refactoring evaluates application source code within the Visual Studio IDE to execute the following tasks:

* Suggest potential modernization routes, like transitioning to .NET Core.
* Recognize configurations pertinent to Internet Information Services (IIS) for Windows and Active Directory dependencies.
* Adjust code where feasible to ensure compatibility with Linux.
* Assist in validating refactored applications on AWS services.

Utilizing the AWS Toolkit for .NET Refactoring allows you to leverage familiar interfaces within Visual Studio, eliminating uncertainties in the process of refactoring applications for AWS.

With the AWS Toolkit for .NET Refactoring extension, you can use porting, containerization, and deployment features seamlessly from inside Visual Studio. The AWS Toolkit for .NET Refactoring extension provides prescriptive guidance to help you assess and port your Windows .NET Framework applications to .NET Core on Linux.

After you port a web application, you can test the application on AWS. The extension facilitates collaboration with other developers who are analyzing, debugging, testing, and refactoring the same application code.

## AWS Toolkit for .NET Refactoring process

AWS Toolkit for .NET Refactoring helps refactor legacy .NET applications to AWS. From the Extensions menu in Visual Studio, you can view the built-in dashboard and start assessments.

### Assessment

After providing AWS credentials and an AWS Region to use for testing, you choose a target framework on which to base the assessment and port the solution. AWS Toolkit for .NET Refactoring scans your .NET application to identify refactoring pathways.

### Porting

From the dashboard, you can see how many APIs and packages are compatible and start the porting process. AWS Toolkit for .NET Refactoring assists with code modifications to start refactoring.

### Run and test on AWS

When the porting process is complete, you can validate the changes by deploying the application on Amazon ECS.

[AWS Toolkit for .NET Refactoring VS 2022](https://marketplace.visualstudio.com/items?itemName=AWSTR.refactoringtoolkit2022)


