# Notes on AWS Well-Architected Framework

## Introduction

- Helps you understand the pros and cons of decisions you make while building systems on AWS.
- Helps you learn architectural best practices for designing and operating secure, reliable, efficient, cost-effective, and sustainable workloads in the AWS Cloud.
- Provides a way for you to consistently measure your architectures against best practices and identify areas for improvement.
- Documents a set of foundational questions that allow you to understand if a specific architecture aligns well with cloud best practices.
- The [AWS Well-Architected Tool](http://aws.amazon.com/well-architected-tool/) (AWS WA Tool) provides recommendations for making your workloads more reliable, secure, efficient, and cost-effective.
- [AWS Well-Architected Labs](https://www.wellarchitectedlabs.com/) provides you with a repository of code and documentation to give you hands-on experience implementing best practices.
- AWS Partner Network (APN) Partners, who are members of the [AWS Well-Architected Partner program](http://aws.amazon.com/architecture/well-architected/partners/) can help you review and improve your workloads.

### Definitions

- 6 pillars:
  - **Operational excellence**: the ability to support development and run workloads effectively, gain insight into their operations, and to continuously improve supporting processes and procedures.
  - **Security**: describes how to take advantage of cloud technologies to protect data, systems, and assets in a way that can improve your security posture.
  - **Reliability**: encompasses the ability of a workload to perform its intended function correctly and consistently when it's expected to, including the ability to operate and test the workload through its total lifecycle.
  - **Performance efficiency**: the ability to use computing resources efficiently to meet system requirements, and to maintain that efficiency as demand changes and technologies evolve.
  - **Cost optimization**: the ability to run systems to deliver business value at the lowest price point.
  - **Sustainability**: the ability to continually improve sustainability impacts by reducing energy consumption and increasing efficiency across all components of a workload by maximizing the benefits from the provisioned resources and minimizing the total resources required.
- Terms:
  - **Component**: code, configuration, and AWS Resources that together deliver against a requirement; often the unit of technical ownership, and is decoupled from other components.
  - **Workload**: a set of components that together deliver business value.
  - **Architecture**: how components work together in a workload; how components communicate and interact.
  - **Milestones**: key changes in your architecture as it evolves throughout the product lifecycle (design, implementation, testing, go live, and in production).
  - **Technology portfolio**: collection of workloads that are required for the business to operate.
  - **Level of effort**: the amount of time, effort, and complexity a task requires for implementation.
    - High: the work might take multiple weeks or multiple months, and could be broken out into multiple stories, releases, and tasks.
    - Medium: the work might take multiple days or multiple weeks, and could be broken out into multiple releases and tasks.
    - Low: the work might take multiple hours or multiple days, and could be broken out into multiple tasks.
- Trade-offs
  - You make trade-offs between pillars based on your business context.
  - You might optimize to improve sustainability impact and reduce cost at the expense of reliability in development environments.
  - For mission-critical solutions, you might optimize reliability with increased costs and sustainability impact.
  - Security and operational excellence are generally not traded-off against the other pillars.

### General design principles

- Stop guessing your capacity needs: With cloud computing, you can use as much or as little capacity as you need, and scale up and down automatically.
- Test systems at production scale.
- Automate to make architectural experimentation easier.
- Allow for evolutionary architectures: In the cloud, the capability to automate and test on demand lowers the risk of impact from design changes.
- Drive architectures using data.
- Improve through [game days](https://wa.aws.amazon.com/wellarchitected/2020-07-02T19-33-23/wat.concept.gameday.en.html): Test how your architecture and processes perform by regularly scheduling game days to simulate events in production.

## Sources

- "AWS Well-Architected Framework - AWS Well-Architected Framework." _Amazon.com_, 2022, [docs.aws.amazon.com/wellarchitected/latest/framework/welcome.html](https://docs.aws.amazon.com/wellarchitected/latest/framework/welcome.html).
