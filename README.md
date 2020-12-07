# Container Security requires more than securing your images


Many of us have seen this scene play out several times over.  Customer financial records have been exposed, account numbers have been hacked.  Security and compliance in a modern-day cloud-native is not only a requirement it is a challenge to most developers at enterprise companies.  

A container is a standard unit of software that packages up code and all its dependencies so the application runs quickly and reliably from one computing environment to another.  Containers are becoming increasingly prominent, especially in cloud environments.  There are several use cases for containers such as Microservices, DevOps, and application migration and modernization.  The benefits of using containers is outline in this [report](https://www.ibm.com/cloud/blog/the-benefits-of-containerization-and-what-it-means-for-you). Those benefits include:

* Portability between different platforms and clouds

* Efficiency through using far fewer resources than virtual machines and delivering higher utilization of compute resources

* Agility that allows developers to integrate with their existing DevOps environment

* Higher speed in the delivery of enhancements

* Faster app start-up and easier scaling

* Easier management

* Improved security by isolating applications from the host system and from each other


Even though one of the bullet notes that containers include “improved security”, containerizationintroduces potential security vulnerabilities that users must address.  As more and more development shops use containers; the complexity of managing the increased growth creates management complexity and security exposures. Security needs to be built into the container pipeline so containers ensure reliability, scalability and trust.

What are the security implications of containers? Container security includes implementing security tools and policies to assure that your container is running as intended, including protection of infrastructure, software supply chain, and runtime. Container security needs to be continuous. Developers should be concerned with securing the

* applications within the container

* build pipeline

* deployment environment

* container management stack

* container host

* attack surface of the environment

Security measures should be introduced as early as possible.  It should be a core component of the build and deployement stages in addition to the runttime period. Begin the security process by integrating into it into the development cycle. Next as the containers move towards deployment, container security ensures that the secured container has not been modified.  Finally, runtime monitoring of containers looks for any signs of hacking and allows for enforcement of policies that only allow authorized activity.  A developer's container platform should be designed to automatically and regularly scan and patch containers, ensuring these containers are always using the latest versions of their dependencies and libraries. This reduces the security risk exposed by the other code one's containers depend on. There are security tools available that solve the problem from build time, shift left, to run time.  Developers should address security across the entire container lifecycle. 

Enterprise DevOps and DevSecOps teams are typically the individuals responsible for ensuring container security and compliance. It is important that these teams don't slow down the container pipeline by securing containers with manual processes. Read NeuVector's [10 Steps to Automate Container Security into the CI/CD Pipeline](https://neuvector.com/learn/container-security-automation-guide/) to:

* Learn about the top security concerns in the CI/CD pipeline

* Discover the 10 steps to start container security automation from build to ship to run

* Evaluate who should be responsible for each automation step, and what techniques can be used for integration

* Automate modern cloud-native security controls such as virtual patching, admission controls, security policy as code, and container network segmentation
ple and impactful for improving security. Here’s a summary of these, followed by a pipeline reference diagram.