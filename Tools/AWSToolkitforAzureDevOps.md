# AWS Toolkit for Azure DevOps

The AWS Toolkit for Azure DevOps, an extension compatible with both hosted and on-premises Microsoft Azure DevOps environments, streamlines application management and deployment processes with AWS. For Azure DevOps users, this toolkit facilitates the deployment of code to AWS through Elastic Beanstalk or CodeDeploy, seamlessly integrating with existing build and release pipelines and workflows. It also enables the deployment of serverless applications and .NET Core C# functions to Lambda.

Furthermore, the toolkit simplifies CloudFormation template deployments, offering an efficient means of managing, provisioning, and updating a collection of AWS resources directly within Azure DevOps. With integrated access to various AWS services, it simplifies the storage of build artifacts in Amazon S3 and aids in executing commands using the AWS Tools for PowerShell and AWS Command Line Interface (CLI). Additionally, it assists in managing notifications through Amazon SNS or Amazon Simple Queue Service (SQS) queues.


## AWS Toolkit for Azure DevOps process
To use the AWS Toolkit for Azure DevOps, create a new Azure DevOps project and add a new pipeline. The screenshots that follow use the classic editor.

### Add tasks
To start, add tasks to your build pipeline and configure their parameters. In this example, the AWS CLI and Invoke Lambda Function tasks have been added.

### Run the build

With the tasks configured, you are ready to queue and run the build.

### Review the build

During and after the build, you can view the available logs by choosing the build number displayed in the queue message at the top of the page.

### Detailed logs

Choose a log to view the details related to the running of the task.

[AWS Toolkit for Azure DevOps installation](https://docs.aws.amazon.com/vsts/latest/userguide/getting-started.html)
[Task reference](https://docs.aws.amazon.com/vsts/latest/userguide/task-reference.html)
