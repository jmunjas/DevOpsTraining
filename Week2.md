# Sprint Two DevSecOps

## Assumptions and Principles

### Key DevSecOps Principles
There are several key principles to implementing a successful DevSecOps approach:
• Remove bottlenecks (including human ones) and manual actions.
• Automate as much of the development and deployment activities as possible.
• Adopt common tools from planning and requirements through deployment and operations.
• Leverage agile software principles and favor small, incremental, frequent updates over larger, more sporadic releases.
• Apply the cross-functional skill sets of Development, Cybersecurity, and Operations throughout the software lifecycle, embracing a continuous monitoring approach in parallel instead of waiting to apply each skill set sequentially.
• Security risks of the underlying infrastructure must be measured and quantified, so that the total risks and impacts to software applications are understood.
• Deploy immutable infrastructure, such as containers. The concept of immutable infrastructure is an IT strategy in which deployed components are replaced in their entirety, rather than being updated in place. Deploying immutable infrastructure requires standardization and emulation of common infrastructure components to achieve consistent and predictable results.

### Key Terms
Key Terms | Definition
------------- | ----------
**DevSecOps Ecosystem** | A collection of tools and process workflows created and executed on the tools to support all the activities throughout the full DevSecOps lifecycle. The process workflows may be fully automated, semi-automated, or manual.
**Software Factory** | A software assembly plant that contains multiple pipelines, which are equipped with a set of tools, process workflows, scripts, and environments, to produce a set of software deployable artifacts with minimal human intervention. It automates the activities in the develop, build, test, release, and deliver phases. The software factory supports multi-tenancy.
**CI/CD Pipeline** | The set of tools and the associated process workflows to achieve continuous integration and continuous delivery with build, test, security, and release delivery activities, which are steered by a CI/CD orchestrator and automated as much as practice allows.
**CI/CD Pipeline Instance** | A single process workflow and the tools to execute the workflow for a specific software language and application type for a project. As much of the pipeline process is automated as is practicable.
**Environment** | Sets a runtime boundary for the software component to be deployed and executed. Typical environments include development, integration, test, pre-production, and production.
**Software Factory Artifact Repository** | A local repository tied to the software factory. It stores artifacts pulled from DoD Centralized Artifact Repository (DCAR) as well as locally developed artifacts to be used in DevSecOps processes. The artifacts include, but are not limited to, virtual machine (VM) images, container images, binary executables, archives, and documentation. It supports multi-tenancy. *Note that programs may have a single artifact repository and use tags to distinguish the content types. It is also possible to have separate artifact repositories to store local artifacts and released artifacts.*
**Containers** | A standard unit of software that packages up code and all its dependencies, down to, but not including the Operating System (OS). It is a lightweight, standalone, executable package of software that includes everything needed to run an application except the OS: code, runtime, system tools, system libraries and settings. Several containers can run in the same OS without conflicting with one another.

## Test Driven Development
