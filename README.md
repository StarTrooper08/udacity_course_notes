# Udacity Cloud Native course (personal notes)

Course Ouline :
1. Welcome
2. Architecture Considerations
3. Container Orchestration
4. Open Source PaaS
5. Cloud Native CI/CD

Prerequisites :
* Flask Web App development
* should have known basic of CLI
* basic of git
* DockerHub account

Lesson 1 :

Cloud Native :

* Informal defination:
1. Cloud native is all about changing the way you think about constructing critical business systems.
2. Cloud-native systems are designed to embrace rapid change, large scale, and resilience.

* Cloud types:
There are 4 main types of cloud computing:

1. Public Cloud

The public cloud allows systems and services to be easily accessible to the general public. Public cloud may be less secure because of its openness.

 2. Private Cloud
 
The private cloud allows systems and services to be accessible within an organization. It is more secured because of its private nature.

 3. Hybrid Cloud
 
The hybrid cloud is a mixture of public and private cloud, in which the critical activities are performed using private cloud while the non-critical activities are performed using public cloud.

* Cloud Services :
There are also 3 main types of cloud computing services:

1. Infrastructure-as-a-Service (IaaS)

The Infrastructure-as-a-Service (IaaS) is the most basic level of service. Each of the service models inherit the security and management mechanism from the underlying model, as shown in the following diagram:

![image](https://user-images.githubusercontent.com/72031540/123563422-2c397880-d7d2-11eb-9fb8-a6cf2217032a.png)

2. Platforms-as-a-Service (PaaS)

PaaS provides the runtime environment for applications, development and deployment tools, etc.

3. Software-as-a-Service (SaaS)

SaaS model allows to use software applications as a service to end-users.

* Containers :

![image](https://user-images.githubusercontent.com/72031540/123563607-5475a700-d7d3-11eb-9b94-fcfefa7580f4.png)

A container is a standard unit of software that packages up code and all its dependencies so the application runs quickly and reliably from one computing environment to another. A Docker container image is a lightweight, standalone, executable package of software that includes everything needed to run an application: code, runtime, system tools, system libraries and settings.

* Kubernetes
Kubernetes, also known as K8s, is an open-source system for automating deployment, scaling, and management of containerized applications.
* CNCF
* StakeHolders
An engineering team can use cloud-native tooling to enable quick delivery of value to customers and easily extend to new features and technologies. These are the main reasons why an organization needs to adopt cloud-native technologies. However, when trialing cloud-native tooling, there are two main perspectives to address: business and technical stakeholders.

From a business perspective, the adoption of cloud-native tooling represents:

Agility - perform strategic transformations
Growth - quickly iterate on customer feedback
Service availability - ensures the product is available to customers 24/7
From a technical perspective, the adoption of cloud-native tooling represents:

Automation - release a service without human intervention
Orchestration - introduce a container orchestrator to manage thousands of services with minimal effort
Observability - ability to independently troubleshoot and debug each component



* Required Tools and Dependencies :
1. Python (modules - Flask / Virtual environment)
2. Git
3. Docker
4. Vagrant
5. VirtualBox(6.1.16 or higher)



