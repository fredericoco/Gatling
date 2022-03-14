# Gatling
## Gatling and testing
We need to perform various tests on our webpage in order to make sure that it will survive in the real world.

### Gatling 
Gatling is an open-source load and performance testing tool which can be used for your integrated development environment, version control systems and continuous integration solutions.

# Types of Testing

### Loading Testing
Load testing measures system performance as the workload increases. That workload could mean concurrent users or transactions.The system is monitored to measure response time and system staying power as workload increases. That workload falls within the parameters of normal working conditions.
### Stress Testing
stress testing — also known as fatigue testing — is meant to measure system performance outside of the parameters of normal working conditions. The software is given more users or transactions that can be handled. The goal of stress testing is to measure the software stability. At what point does software fail, and how does the software recover from failure?
### Soak Testing
soak testing is an evaluation of how software performs with a normal workload over an extended amount of time. The goal of endurance testing is to check for system problems such as memory leaks. (A memory leak occurs when a system fails to release discarded memory. The memory leak can impair system performance or cause it to fail.)
### Spike Testing
Spike testing is a type of stress testing that evaluates software performance when workloads are substantially increased quickly and repeatedly. The workload is beyond normal expectations for short amounts of time.

# SLO, SLI, and SLA

### What is a SLA? 
A SLA (service level agreement) is an agreement between provider and client about measurable metrics like uptime, responsiveness, and responsibilities.

### Problems with SLAs

- SLAs are notoriously difficult to measure, report on, and meet. These agreements—generally written by people who aren’t in the tech trenches themselves—often make promises that are difficult for teams to measure, don’t always align with current and ever-evolving business priorities, and don’t account for nuance.

- For example, an SLA may promise that teams will resolve reported issues with Product X within 24 hours. But that same SLA doesn’t spell out what happens if the client takes 24 hours to send answers or screenshots to help your team diagnose the problem. Does it mean the team’s 24-hour window been eaten up by client slow-downs or does the clock start and stop based on when clients respond? SLAs need to answer these questions, but they often fail to do so—a fact that has created a lot of animosity toward them from IT managers.

- For many experts, the answer to this challenge is, first and foremost, that tech should be involved in the creation of SLAs. The more IT and DevOps collaborate with legal and business development to develop SLAs that address real-world scenarios, the more SLAs will start to reflect key realities, such as clients delaying their own issue resolution.
  
### Who needs SLA?
A SLA is an agreement between a vendor and a paying customer. Companies providing a service to users for free are unlikely to want or need an SLA for those free users.

### What is a SLO? 
An SLO (service level objective) is an agreement within an SLA about a specific metric like uptime or response time. So, if the SLA is the formal agreement between you and your customer, SLOs are the individual promises you’re making to that customer. SLOs are what set customer expectations and tell IT and DevOps teams what goals they need to hit and measure themselves against.

### The challenges of SLOs -
SLOs get less hate than SLAs, but they can create just as many problems if they’re vague, overly complicated, or impossible to measure. The key to SLOs that don’t make your engineers want to tear their hair out is simplicity and clarity. Only the most important metrics should qualify for SLO status, the objectives should be spelled out in plain language, and, as with SLAs, they should always account for issues such as client-side delays.
### Who needs SLOs? -
Where SLAs are only relevant in the case of paying customers, SLOs can be useful for both paid and unpaid accounts, as well as internal and external customers.
Internal systems, such as CRMs, client data repositories, and intranet, can be just as important as external-facing systems. And having SLOs for those internal systems is an important piece of not only meeting business goals but enabling internal teams to meet their own customer-facing goals.
### What is an SLI? -
An SLI (service level indicator) measures compliance with an SLO (service level objective). So, for example, if your SLA specifies that your systems will be available 99.95% of the time, your SLO is likely 99.95% uptime and your SLI is the actual measurement of your uptime. Maybe it’s 99.96%. Maybe 99.99%. To stay in compliance with your SLA, the SLI will need to meet or exceed the promises made in that document.
### The challenges of SLIs -
As with SLOs, the challenge of SLIs is keeping them simple, choosing the right metrics to track, and not overcomplicating IT’s job by tracking too many metrics that don’t actually matter to clients.
### Who needs SLIs? -
Any company measuring their performance against SLOs needs SLIs in order to make those measurements. You can’t really have SLOs without SLIs.

## Installation of Gatling

These are the steps required to install gatling on windows:
Step 1: Install Java 8 JDK
- Go to oracle and get the correct version of Java (https://www.oracle.com/java/technologies/downloads/), put it in the C:\Program Files\Java
- Go to the environment variables and set a system variable to `JAVA_HOME` To the location of Java on the computer.
- Go to path on system variables
Step 2:Install Apache Maven
STEP 3: Install Gatling
STEP 4: Install IntelliJ with Scala Plugin
https://medium.com/swlh/a-beginners-guide-to-performance-testing-with-gatling-225ef2c20cda

https://mkyong.com/maven/how-to-install-maven-in-windows/