
# What is Serverless?


Serverless is a cloud application development and execution model that lets developers build and run code without managing servers, and without paying for idle cloud infrastructure.

* Serverless does not mean 'no servers'

The name notwithstanding, there are most definitely servers in serverless computing. 'Serverless' describes the developer’s experience with those servers—they are are invisible to the developer, who doesn't see them, manage them, or interact with them in any way.



* Serverless is more than just FaaS
Function-as-a-service, or FaaS, is a cloud computing service that enables developers to run code or containers in response to specific events or requests, without specifying or managing the infrastructure required to run to code.

* FaaS is the compute model central to serverless, and the two terms are often used interchangeably. But serverless is much more than FaaS. Serverless is an entire stack of services that can respond to specific events or requests, and scale to zero when no longer in use—and for which provisioning, management and billing are handled by the cloud provider and invisible to developers. In addition to FaaS, these services include:

* Serverless databases and storage:

 Databases (SQL and NoSQL) and storage (particularly object storage) are the foundation of the data layer. A serverless approach to these technologies involves transitioning away from provisioning “instances” with defined capacity, connection and query limits, and moving toward models that scale linearly with demand in both infrastructure and pricing.

* Event streaming and messaging:

 Serverless architectures are well-suited for event-driven and stream-processing workloads most notably the open source Apache Kafka event streaming platform.

* API gateways: 

API gateways act as proxies to web actions and provide HTTP method routing, client ID and secrets, rate limits, CORS, viewing API usage, viewing response logs,


---



## Get started with serverless computing


You can expand your serverless computing skills with these tutorials:

* Getting started with IBM Cloud Code Engine: Visit our “Hello world” tutorial to see for yourself how easy it is to create and deploy an IBM Cloud Code Engine application.
* Build a container image from source with the Code Engine CLI: The build process uses the buildpacks strategy and stores the image from the build 
* process on Docker Hub. Code Engine supports building from a Dockerfile and Cloud Native Buildpacks
* Run batch jobs: Learn how to run a batch job using the Code Engine console. A job runs one or more instances of your executable code. Unlike 
* applications, which handle HTTP requests, jobs are designed to run one time and exit.
* Serverless web app and eventing for data retrieval and analytics. Create an application to automatically collect GitHub traffic statistics for 
* repositories and provide the foundation for traffic analytics.
* Quick lab: No infrastructure, just code. See the simplicity of serverless: In this 45-minute lab, you'll create an IBM Cloud account and then use Node.js to create an action, an event-based trigger, and a web action.