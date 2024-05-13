# AWS App2Container

Once your applications are portable and prepared for containerization, AWS App2Container offers an automated solution for the task.

AWS App2Container is a command-line utility tailored for modernizing .NET and Java applications typically running within on-premises data centers or on virtual machines (VMs). It streamlines the transition of these applications into containers, managed by Amazon ECS, Amazon EKS, or App Runner.

By conducting an analysis and compiling an inventory of applications across virtual machines, on-premises environments, or the cloud, AWS App2Container provides the flexibility to select which applications to containerize. It then proceeds to package the application artifacts along with identified dependencies into container images, configuring network ports, and generating necessary Dockerfiles and AWS artifacts for container deployment.

Leveraging CloudFormation, AWS App2Container orchestrates the provisioning of cloud infrastructure and sets up continuous integration and delivery (CI/CD) pipelines essential for deploying the containerized .NET or Java applications into production environments. This process not only modernizes existing applications but also standardizes deployment and operational practices through containerization.

## Streamline Operations

With AWS App2Container, you can containerize existing applications. For monitoring, operations, and software delivery, AWS App2Container standardizes on a single set of tooling. By containerizing applications with AWS App2Container, you can unify infrastructure and skill sets needed to operate applications. This can save time and infrastructure and training costs.

## Accelerate Application Modernization

AWS App2Container analyzes applications that are candidates for being containerized. It automatically generates a container image configured with the correct dependencies, network configurations, and deployment instructions for Amazon ECS, Amazon EKS, or AWS App Runner. You save time and help avoid manual settings and errors from negligence.

## Scales and Secures Applications

With AWS App2Container, you can deploy an existing application on the cloud that is provisioned with the correct networking and security configurations.


## AWS App2Container workflow

### Download and install AWS App2Container

Download and install AWS App2Container on the computer where the application to containerize runs. You can download and run AWS App2Container on Linux or Windows computers. The download includes an install script. You can generate hashes on the installer archive to verify the authenticity of the download. 

#### Windows

AWS App2Container is packaged as a zip archive. After extracting the package, run the install script and follow the prompts.

`PS> .\install.ps1`

#### Linux

AWS App2Container is packaged as a tar.gz archive. After extracting the package, run the script and follow the prompts.

`$ sudo ./install.sh`

### Initialize AWS App2Container

In this one-time task, initialize AWS App2Container global settings and configure settings. Enter the required information at the command prompt. 

#### Windows

On each server where you installed AWS App2Container, run the following command:

`PS> app2container init`

#### Linux

On each server where you installed AWS App2Container, run the following command:

`$ sudo app2container init`

### Analyze the application

Analyze the server to create an inventory of applications to containerize.

#### Windows

To analyze the server to create an inventory of ASP.NET applications to containerize, run the app2container inventory command.

`PS> app2container inventory`

#### Linux

To analyze the server to create an inventory of ASP.NET applications to containerize, run the app2container inventory command.

`$ sudo app2container inventory`

### Create containers to transform the application

In the next step, create the container that your application will run in after you deploy it to Amazon ECS, Amazon EKS, or App Runner, if eligible.

#### Windows

To containerize an application on an application server, run the following command:

`PS> app2container containerize --application-id my-iis-app-id`

#### Linux

To containerize an application on an application server, run the following command:

`$ sudo app2container analyze --application-id my-iis-app-id`

### Generate application deployment files

To generate application deployment files to deploy the containers that you can optionally customize, run the app2container generate app-deployment command. 

Run the following command to deploy the application on AWS:

#### Windows

`PS> app2container generate app-deployment --application-id my-iis-obj-id`

#### Linux

`$ sudo app2container generate app-deployment --application-id my-iis-obj-id`

### Clean up

To remove AWS App2Container from your application server or workstation, complete the following steps.

To remove AWS App2Container, delete the following folder and remove it from your path.

#### Windows

`C:\Users\Administrator\app2container`

#### Linux

`/usr/local/app2container`


[Getting started with AWS App2Container](https://docs.aws.amazon.com/app2container/latest/UserGuide/start-intro.html)
