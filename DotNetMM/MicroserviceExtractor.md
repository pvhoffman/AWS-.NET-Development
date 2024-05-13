# AWS Microservice Extractor for .NET

The AWS Microservice Extractor for .NET is a standalone tool designed for installation on your developer workstation. Its purpose is to facilitate the decomposition of monolithic applications, whether they operate within the AWS Cloud or on local servers, into autonomously operated and managed services.

This tool scrutinizes an application's source code and generates a comprehensive visualization of its structure, incorporating classes, namespaces, and the interactions between methods. This visualization enables you to logically categorize functionalities based on various criteria, such as class dependencies, namespaces, and frequency of method calls.

Once functionalities are organized into distinct groups, the Microservice Extractor offers guidance to streamline the refactoring process of the code base, making it primed for extraction into smaller, more manageable services. Once the code base is suitably prepared, the Extractor proceeds to extract these functionalities into separate code solutions. These solutions can then be edited manually and deployed as independent services.

## AWS Microservice Extractor process

Microservice Extractor simplifies the process of refactoring older monolithic apps into small code projects that fit into a microservices-based architecture.

### Scan and onboard the application

To start, scan the application by providing source code. You can optionally run the tools' profile to collect runtime metrics.

### Group components

Next, visually identify components to be extracted from the application by grouping and labeling parts of the application to create independent services.

### Prepare for extraction

Microservice Extractor identifies candidates by using a heuristics-based approach to provide a guided experience. Then you modify code to prepare the application for extraction.

### Refactor and extract

Refactor the code by isolating business domains and removing dependencies. Then you can extract parts of the application's code base as separate code projects.

### Build and deploy

Finally, manually refactor, build, and deploy the extracted services and the modified code.

---

Microservice Extractor uses heuristics-based techniques to identify common extraction candidates and highlight them in visualization. You can use the recommendations as they are or as a starting point to extract microservices from a monolithic code base.

Automated recommendations from Microservice Extractor help to speed up refactoring large applications, even if the developer is unfamiliar with the code base. You can also extract the code base into separate projects that teams can develop, build, and operate independently to improve agility, uptime, and scalability.

[Prerequisites to use AWS Microservice Extractor for .NET](https://docs.aws.amazon.com/microservice-extractor/latest/userguide/microservice-extractor-prerequisites.html)
