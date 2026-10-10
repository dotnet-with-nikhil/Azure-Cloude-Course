# 6-Month Azure Cloud Course for Freshers and Recent Graduates (C# and .NET)

## Course Overview

| Item | Details |
|---|---|
| Duration | 26 weeks (approximately 6 months) |
| Daily commitment | 1 hour, 6 days per week (about 6 hours/week) |
| Audience | Freshers, final-year students, and recent graduates |
| Programming language | C# and .NET only |
| Excluded | Python, AI/ML, and generative AI |

**Course goal:** By the end of this course, students should be able to build a small ASP.NET Core application, deploy it to Azure, connect it to a database and storage, secure it, monitor it, automate deployment, and explain the project in an entry-level cloud/.NET interview.

## Daily Study Pattern (60 minutes)

| Time | Activity |
|---|---|
| 10 minutes | Revise yesterday's topic |
| 20 minutes | Learn one concept |
| 25 minutes | Follow a demo or do a hands-on task |
| 5 minutes | Write notes and explain what you learned aloud |

Study six days per week. Keep the seventh day for rest or catching up. Do not create paid Azure resources without checking the current price and deleting them when finished.

## Before Starting

| Requirement | Details |
|---|---|
| Computer | Windows, macOS, or Linux with a modern browser |
| Software | Current supported .NET SDK, Visual Studio or Visual Studio Code, and Git |
| Code hosting | A GitHub account for storing code |
| Azure account | Access to the Azure portal. Check current student offers and eligibility before creating a subscription. A credit card may be requested depending on the offer and account type; do not assume every student gets a free subscription |
| Services | Use free-tier or student-eligible services where available. Pricing and free quotas can change |
| Cost control | Set a budget alert where available, and delete or stop resources after labs |

## Course Roadmap

| Month | Week | Title | Weekly outcome |
|---|---|---|---|
| 1 | 1 | Cloud computing and Azure orientation | Explain core cloud terms and navigate the Azure portal |
| 1 | 2 | C# essentials, part 1 | Write small C# console programs |
| 1 | 3 | C# essentials, part 2 | Create a small C# application using OOP and collections |
| 1 | 4 | .NET, HTTP, Git, and web basics | Have a working .NET Web API in a Git repository |
| 2 | 5 | ASP.NET Core Web API | Create a clean CRUD API with validation |
| 2 | 6 | SQL and relational database basics | Write basic SQL and design a simple relational schema |
| 2 | 7 | Entity Framework Core | Persist API data in a relational database through EF Core |
| 2 | 8 | Testing, quality, and API security basics | Add meaningful tests and explain basic API security practices |
| 3 | 9 | Identity and access management | Explain identity, RBAC, and least privilege |
| 3 | 10 | Azure App Service | Deploy a working .NET API to Azure App Service |
| 3 | 11 | Azure Storage | Explain Azure Storage options and perform a basic blob operation |
| 3 | 12 | Azure SQL Database | Understand how a .NET API connects securely to a managed database |
| 4 | 13 | Azure networking fundamentals | Explain the main building blocks of Azure networking |
| 4 | 14 | Azure Functions and event-driven computing | Build and explain a small C# Azure Function |
| 4 | 15 | Azure Service Bus and asynchronous messaging | Explain a reliable asynchronous workflow |
| 4 | 16 | Monitoring and troubleshooting | Find basic failures and latency clues using logs and telemetry |
| 5 | 17 | CI/CD with GitHub Actions | Build a pipeline that restores, builds, and tests the .NET project |
| 5 | 18 | Infrastructure as Code with Bicep | Read and create a basic Bicep template |
| 5 | 19 | Azure security fundamentals | Identify and reduce common identity, secret-management, and application-security risks |
| 5 | 20 | Reliability, scaling, and cost management | Explain basic scaling, reliability, and cost decisions without overengineering |
| 6 | 21 | Capstone planning and architecture | Have a scoped, documented project ready to implement |
| 6 | 22 | Build the API and database | A functional, tested local application |
| 6 | 23 | Add Azure services and deploy | A deployed application or a reproducible deployment demonstration |
| 6 | 24 | CI/CD, security, and operational readiness | A documented, safer, repeatable project workflow |
| 6 | 25 | Interview and practical revision | Explain concepts clearly with examples rather than memorized definitions |
| 6 | 26 | Portfolio, resume, and final assessment | A portfolio-ready beginner project and a clear explanation of the Azure/.NET skills practised |

---

# Month 1: Cloud and C#/.NET Foundations

## Week 1: Cloud Computing and Azure Orientation

| Topics covered | Weekly outcome |
|---|---|
| • What cloud computing is and why companies use it<br>• IaaS, PaaS, and SaaS with simple examples<br>• Public, private, and hybrid cloud<br>• Regions, region pairs, availability zones, and datacenters<br>• Azure portal, subscriptions, resource groups, and resources<br>• Shared responsibility model; basic cloud security and cost awareness | Explain core cloud terms and navigate the Azure portal |

| Day | Daily plan |
|---|---|
| 1 | Learn cloud computing and common business use cases |
| 2 | Compare IaaS, PaaS, and SaaS |
| 3 | Learn regions, availability zones, and resilience |
| 4 | Tour the Azure portal and locate core services |
| 5 | Understand tenants, subscriptions, resource groups, and resources |
| 6 | Draw a simple diagram of a web app hosted in Azure and explain it |

## Week 2: C# Essentials, Part 1

| Topics covered | Weekly outcome |
|---|---|
| • .NET, C#, SDK, runtime, and CLR at a high level<br>• Variables, data types, operators, and type conversion<br>• Conditions and loops<br>• Methods, parameters, return values, and scope<br>• Arrays, strings, and basic debugging | Write small C# console programs |

| Day | Daily plan |
|---|---|
| 1 | Install the .NET SDK and create a console application |
| 2 | Variables, types, operators, and conversions |
| 3 | `if`, `switch`, `for`, `while`, and `foreach` |
| 4 | Methods, parameters, and return values |
| 5 | Arrays and string operations |
| 6 | Build a console-based student marks calculator |

## Week 3: C# Essentials, Part 2

| Topics covered | Weekly outcome |
|---|---|
| • Classes, objects, properties, and constructors<br>• Encapsulation, inheritance, polymorphism, and abstraction<br>• Interfaces and dependency inversion at a beginner level<br>• Collections: `List<T>`, `Dictionary<TKey,TValue>`<br>• Exceptions and basic file handling<br>• LINQ fundamentals | Create a small C# application using OOP and collections |

| Day | Daily plan |
|---|---|
| 1 | Classes, objects, properties, and constructors |
| 2 | OOP principles with simple examples |
| 3 | Interfaces and implementing an interface |
| 4 | Collections and LINQ (`Where`, `Select`, `FirstOrDefault`) |
| 5 | Exceptions and basic file read/write |
| 6 | Build a console-based student management app |

## Week 4: .NET, HTTP, Git, and Web Basics

| Topics covered | Weekly outcome |
|---|---|
| • .NET project structure and NuGet packages<br>• Introduction to ASP.NET Core and the request/response cycle<br>• HTTP methods, status codes, headers, JSON, and REST<br>• Git basics: clone, add, commit, push, branches<br>• Configuration and environment variables<br>• Introduction to debugging and logging | Have a working .NET Web API in a Git repository |

| Day | Daily plan |
|---|---|
| 1 | Explore a .NET project and use the `dotnet` CLI |
| 2 | Learn HTTP, JSON, REST, and common status codes |
| 3 | Practice Git commits and branches |
| 4 | Learn configuration files and environment variables |
| 5 | Create a basic ASP.NET Core Web API |
| 6 | Push the project to GitHub and write a README |

---

# Month 2: Build a Real .NET Application

## Week 5: ASP.NET Core Web API

| Topics covered | Weekly outcome |
|---|---|
| • Controllers or Minimal APIs<br>• Routing, model binding, and DTOs<br>• Validation and correct HTTP status codes<br>• Dependency injection and service lifetimes<br>• Middleware and exception handling<br>• Swagger/OpenAPI and API testing | Create a clean CRUD API with validation |

| Day | Daily plan |
|---|---|
| 1 | Create endpoints and understand routing |
| 2 | Use DTOs and model binding |
| 3 | Add validation and appropriate status codes |
| 4 | Register and inject a service |
| 5 | Add exception handling and Swagger |
| 6 | Build CRUD endpoints for a course catalogue |

## Week 6: SQL and Relational Database Basics

| Topics covered | Weekly outcome |
|---|---|
| • Tables, rows, columns, primary keys, and foreign keys<br>• `SELECT`, filtering, sorting, and joins<br>• Insert, update, and delete<br>• Constraints and normalization basics<br>• Index basics and why query performance matters<br>• Connection strings and database credentials | Write basic SQL and design a simple relational schema |

| Day | Daily plan |
|---|---|
| 1 | Learn relational database concepts and create tables |
| 2 | Practice `SELECT`, `WHERE`, `ORDER BY`, and `TOP` |
| 3 | Practice `INSERT`, `UPDATE`, and `DELETE` |
| 4 | Learn joins and foreign keys |
| 5 | Learn constraints and basic indexes |
| 6 | Design a small database for courses and students |

## Week 7: Entity Framework Core

| Topics covered | Weekly outcome |
|---|---|
| • ORM and EF Core concepts<br>• `DbContext`, entities, and `DbSet`<br>• Migrations and schema updates<br>• CRUD operations with EF Core<br>• Relationships and basic query efficiency<br>• Safe handling of connection strings | Persist API data in a relational database through EF Core |

| Day | Daily plan |
|---|---|
| 1 | Add EF Core packages and configure `DbContext` |
| 2 | Create entities and configure a database connection |
| 3 | Create and apply migrations |
| 4 | Implement create, read, update, and delete |
| 5 | Add a relationship and query related data |
| 6 | Connect EF Core to the course catalogue API and test it |

## Week 8: Testing, Quality, and API Security Basics

| Topics covered | Weekly outcome |
|---|---|
| • Unit testing with xUnit<br>• Arrange-Act-Assert pattern<br>• Mocking dependencies at a beginner level<br>• Input validation and safe error responses<br>• Authentication versus authorization<br>• Secrets, passwords, and connection strings: what not to commit | Add meaningful tests and explain basic API security practices |

| Day | Daily plan |
|---|---|
| 1 | Create a test project and write a first xUnit test |
| 2 | Test service logic using Arrange-Act-Assert |
| 3 | Learn dependency mocking and test edge cases |
| 4 | Add input validation and safe error handling |
| 5 | Learn authentication vs authorization and common security risks |
| 6 | Add tests to the API and scan the Git repository for accidentally committed secrets |

---

# Month 3: Azure Core Services

## Week 9: Identity and Access Management

| Topics covered | Weekly outcome |
|---|---|
| • Microsoft Entra ID terminology and purpose<br>• Authentication and authorization in Azure<br>• Users, groups, app registrations, and service principals<br>• Azure role-based access control (Azure RBAC)<br>• Least privilege and role scopes<br>• Managed identities and why they are safer than embedded credentials | Explain identity, RBAC, and least privilege. Only create identity resources if permitted by the subscription |

| Day | Daily plan |
|---|---|
| 1 | Understand Microsoft Entra ID and identity concepts |
| 2 | Learn users, groups, and app registrations conceptually |
| 3 | Explore Azure RBAC roles and scopes |
| 4 | Learn least privilege with examples |
| 5 | Understand managed identities and credential risks |
| 6 | Draw an access model for a web app and its database |

## Week 10: Azure App Service

| Topics covered | Weekly outcome |
|---|---|
| • What Azure App Service does<br>• App Service plans, apps, deployment slots, and scaling basics<br>• App settings and connection strings<br>• Deploying an ASP.NET Core API<br>• Logs and basic troubleshooting<br>• HTTPS and custom-domain concepts | Deploy a working .NET API to Azure App Service |

| Day | Daily plan |
|---|---|
| 1 | Learn App Service and App Service plans |
| 2 | Publish the .NET API locally in Release mode |
| 3 | Deploy the API to App Service using a supported deployment method |
| 4 | Configure app settings and environment-specific values |
| 5 | Inspect logs and troubleshoot a deliberate configuration error |
| 6 | Document deployment steps and remove or stop resources if not needed |

## Week 11: Azure Storage

| Topics covered | Weekly outcome |
|---|---|
| • Storage account and redundancy concepts<br>• Blob, Queue, and Table storage use cases<br>• Containers, blobs, and access tiers<br>• Shared access signatures (SAS) and access safety<br>• Upload/download from .NET using the Azure SDK<br>• Lifecycle and cost considerations | Explain Azure Storage options and perform a basic blob operation |

| Day | Daily plan |
|---|---|
| 1 | Explore storage account options and redundancy |
| 2 | Learn blobs, containers, and access tiers |
| 3 | Create a container and upload a sample file in the portal |
| 4 | Use the Azure Storage SDK from a small C# app |
| 5 | Learn SAS tokens and why credentials must be protected |
| 6 | Add a file-upload feature or document a secure upload flow for the API |

## Week 12: Azure SQL Database

| Topics covered | Weekly outcome |
|---|---|
| • Azure SQL Database versus SQL Server installed on a VM<br>• Server, database, networking, and firewall concepts<br>• Secure connection from .NET<br>• Data migration and schema changes<br>• Backups, availability, and cost basics<br>• Troubleshooting connection failures | Understand how a .NET API connects securely to a managed database |

| Day | Daily plan |
|---|---|
| 1 | Compare Azure SQL Database with SQL Server on a VM |
| 2 | Explore database configuration and pricing concepts |
| 3 | Learn firewall rules and secure connectivity |
| 4 | Connect the API to Azure SQL if budget/access allows; otherwise practise using a local SQL database and study the deployment steps |
| 5 | Learn backups, restore concepts, and connection troubleshooting |
| 6 | Update the architecture diagram and document database configuration without publishing secrets |

---

# Month 4: Networking, Messaging, and Operations

## Week 13: Azure Networking Fundamentals

| Topics covered | Weekly outcome |
|---|---|
| • Virtual networks (VNets) and subnets<br>• Public versus private IP addresses<br>• Network Security Groups (NSGs)<br>• DNS, ports, and HTTPS/TLS<br>• Private endpoints and service endpoints at a conceptual level<br>• Network troubleshooting basics | Explain the main building blocks of Azure networking |

| Day | Daily plan |
|---|---|
| 1 | Learn IP addresses, DNS, ports, and HTTPS |
| 2 | Understand VNets and subnets |
| 3 | Learn NSGs and traffic rules |
| 4 | Compare public access, private access, and private endpoints |
| 5 | Draw a secure web app/database network design |
| 6 | Troubleshoot a sample connectivity scenario on paper or in a permitted lab |

## Week 14: Azure Functions and Event-Driven Computing

| Topics covered | Weekly outcome |
|---|---|
| • Serverless computing and when to use it<br>• Azure Functions triggers and bindings<br>• HTTP trigger and timer trigger<br>• C# isolated worker model overview<br>• Configuration, logging, and local testing<br>• Function hosting plans and cost awareness | Build and explain a small C# Azure Function |

| Day | Daily plan |
|---|---|
| 1 | Learn serverless and Azure Functions use cases |
| 2 | Create a C# Azure Functions project |
| 3 | Implement an HTTP-triggered function |
| 4 | Implement or inspect a timer-triggered function |
| 5 | Add configuration and logging |
| 6 | Compare an App Service API endpoint with a Function endpoint |

## Week 15: Azure Service Bus and Asynchronous Messaging

| Topics covered | Weekly outcome |
|---|---|
| • Why queues and asynchronous processing are used<br>• Queue versus topic/subscription<br>• Message send/receive using C#<br>• Retries, dead-letter queues, and duplicate delivery<br>• Idempotency and message processing safety<br>• Observability and cost basics | Explain a reliable asynchronous workflow. Run a live lab only if the subscription and budget permit it |

| Day | Daily plan |
|---|---|
| 1 | Understand synchronous calls versus queues |
| 2 | Learn queues, topics, and subscriptions |
| 3 | Read a C# send/receive example using the Azure SDK |
| 4 | Learn retries, dead-lettering, and poison messages |
| 5 | Understand duplicate delivery and idempotent handlers |
| 6 | Draw an order-processing flow using API, Service Bus, and a worker |

## Week 16: Monitoring and Troubleshooting

| Topics covered | Weekly outcome |
|---|---|
| • Azure Monitor and Log Analytics concepts<br>• Application Insights for ASP.NET Core<br>• Logs, metrics, traces, and correlation IDs<br>• Health checks and availability<br>• Alerts and diagnostic settings<br>• Troubleshooting latency, errors, and failed dependencies | Find basic failures and latency clues using logs and telemetry |

| Day | Daily plan |
|---|---|
| 1 | Learn logs, metrics, and distributed traces |
| 2 | Add Application Insights to the .NET API where available |
| 3 | Inspect request and dependency telemetry |
| 4 | Add a health-check endpoint |
| 5 | Learn alerts and diagnostic settings |
| 6 | Troubleshoot a sample slow API/error scenario and write a short incident report |

---

# Month 5: Deployment, Security, and Cloud Architecture

## Week 17: CI/CD with GitHub Actions

| Topics covered | Weekly outcome |
|---|---|
| • CI versus CD<br>• Build, test, publish, and deploy stages<br>• GitHub Actions workflow structure<br>• Repository secrets and environment variables<br>• Deploying an ASP.NET Core app to Azure<br>• Rollback and deployment verification concepts | Build a pipeline that restores, builds, and tests the .NET project; deploy only if access is available |

| Day | Daily plan |
|---|---|
| 1 | Understand a CI/CD pipeline |
| 2 | Create a workflow that restores and builds the .NET solution |
| 3 | Add automated tests to the workflow |
| 4 | Learn publishing artifacts and environment configuration |
| 5 | Study a safe Azure deployment workflow using documented authentication methods |
| 6 | Review pipeline output and write deployment instructions |

## Week 18: Infrastructure as Code with Bicep

| Topics covered | Weekly outcome |
|---|---|
| • Why Infrastructure as Code (IaC) matters<br>• Declarative templates and repeatability<br>• Bicep syntax and parameters<br>• Resource dependencies and outputs<br>• What-if validation and deployment scopes<br>• Managing secrets outside templates | Read and create a basic Bicep template |

| Day | Daily plan |
|---|---|
| 1 | Learn IaC and compare manual versus repeatable deployment |
| 2 | Read a simple Bicep template |
| 3 | Define parameters and outputs |
| 4 | Describe resources and dependencies |
| 5 | Run validation/what-if where permitted, or inspect a sample deployment |
| 6 | Document the resources required for the capstone project |

## Week 19: Azure Security Fundamentals

| Topics covered | Weekly outcome |
|---|---|
| • Shared responsibility and defence in depth<br>• Microsoft Entra ID and Azure RBAC review<br>• Managed identities and Key Vault<br>• Secrets, certificates, and key rotation concepts<br>• Secure networking and HTTPS<br>• Secure coding and dependency updates | Identify and reduce common identity, secret-management, and application-security risks |

| Day | Daily plan |
|---|---|
| 1 | Review shared responsibility and common cloud risks |
| 2 | Review RBAC and least privilege |
| 3 | Learn Azure Key Vault use cases |
| 4 | Learn managed identity access to services |
| 5 | Review HTTPS, input validation, and dependency updates |
| 6 | Create a security checklist for the capstone application |

## Week 20: Reliability, Scaling, and Cost Management

| Topics covered | Weekly outcome |
|---|---|
| • Vertical versus horizontal scaling<br>• App Service scale-up and scale-out<br>• Availability zones and redundancy concepts<br>• Backups, recovery objectives, and disaster recovery<br>• Azure Cost Management, budgets, and tags<br>• Choosing services based on workload and cost | Explain basic scaling, reliability, and cost decisions without overengineering |

| Day | Daily plan |
|---|---|
| 1 | Learn scale-up versus scale-out |
| 2 | Understand autoscale and basic capacity planning |
| 3 | Learn availability, backup, and recovery concepts |
| 4 | Explore budgets, cost analysis, and resource tags |
| 5 | Review sample architecture trade-offs |
| 6 | Create a simple cost and reliability checklist for the capstone |

---

# Month 6: Capstone Project and Job Preparation

## Week 21: Capstone Planning and Architecture

**Project:** Course Registration Portal (ASP.NET Core Web API + C# + Azure)

| Minimum features |
|---|
| Manage courses and student registrations |
| REST endpoints with validation and correct status codes |
| EF Core and relational database |
| Unit tests |
| File upload or supporting documents using Blob Storage (optional if budget/access is limited) |
| Azure deployment and basic monitoring |
| CI workflow and documentation |

| Day | Daily plan |
|---|---|
| 1 | Write user stories and define project scope |
| 2 | Draw architecture: client, API, database, and optional storage |
| 3 | Design entities, relationships, and API endpoints |
| 4 | Create solution structure and Git repository |
| 5 | Create the initial API and add a health endpoint |
| 6 | Write a README with setup and architecture |

**Weekly outcome:** Have a scoped, documented project ready to implement.

## Week 22: Build the API and Database

| Topics covered | Weekly outcome |
|---|---|
| • Implementing CRUD endpoints<br>• Service layer and dependency injection<br>• EF Core migrations and relationships<br>• Validation, error handling, and pagination basics<br>• Unit tests for business logic<br>• Git commits and code review habits | A functional, tested local application |

| Day | Daily plan |
|---|---|
| 1 | Implement course endpoints |
| 2 | Implement student/registration endpoints |
| 3 | Configure EF Core and migrations |
| 4 | Add validation and consistent error handling |
| 5 | Write unit tests for key rules |
| 6 | Test endpoints and update the README |

## Week 23: Add Azure Services and Deploy

| Topics covered | Weekly outcome |
|---|---|
| • App Service deployment<br>• Database connection configuration<br>• App settings and secrets handling<br>• Optional Blob Storage integration<br>• Health checks and Application Insights<br>• Deployment smoke tests | A deployed application or a reproducible deployment demonstration |

| Day | Daily plan |
|---|---|
| 1 | Prepare the app for Release deployment |
| 2 | Deploy to App Service if access and budget permit |
| 3 | Configure the database connection securely |
| 4 | Add Blob Storage integration or document it as an extension |
| 5 | Verify health, logs, and core endpoints |
| 6 | Run smoke tests and record known limitations |

## Week 24: CI/CD, Security, and Operational Readiness

| Topics covered | Weekly outcome |
|---|---|
| • Build/test workflow<br>• Deployment pipeline concepts<br>• Secrets and least privilege<br>• Logs, alerts, and troubleshooting notes<br>• Cost cleanup and resource inventory<br>• Project demo preparation | A documented, safer, repeatable project workflow |

| Day | Daily plan |
|---|---|
| 1 | Add or refine CI build workflow |
| 2 | Run automated tests in the workflow |
| 3 | Review secrets and access permissions |
| 4 | Verify logs, health checks, and failure handling |
| 5 | Review Azure resources and remove unused paid resources |
| 6 | Prepare a 5-minute project demonstration |

## Week 25: Interview and Practical Revision

| Topics covered | Weekly outcome |
|---|---|
| • Cloud fundamentals and Azure core services<br>• App Service versus Functions versus virtual machines<br>• Blob versus Queue versus Table storage<br>• Azure SQL and EF Core<br>• Entra ID, RBAC, managed identities, and Key Vault<br>• Networking, monitoring, CI/CD, and cost management | Explain concepts clearly with examples rather than memorized definitions |

| Day | Daily plan |
|---|---|
| 1 | Revise cloud models, regions, subscriptions, and resource groups |
| 2 | Explain App Service, Functions, and VMs with use cases |
| 3 | Revise Storage, Azure SQL, and Service Bus |
| 4 | Revise identity, RBAC, managed identities, and Key Vault |
| 5 | Revise networking, monitoring, CI/CD, and Bicep |
| 6 | Answer 10 interview questions aloud and note weak areas |

## Week 26: Portfolio, Resume, and Final Assessment

| Topics covered | Weekly outcome |
|---|---|
| • GitHub repository hygiene and README<br>• Architecture diagram and deployment notes<br>• Project demo and limitations<br>• Basic troubleshooting scenarios<br>• Resume project description without exaggerating experience<br>• Final revision and next learning steps | A portfolio-ready beginner project and a clear explanation of the Azure/.NET skills practised |

| Day | Daily plan |
|---|---|
| 1 | Clean up the repository and remove secrets |
| 2 | Improve README: problem, architecture, setup, endpoints, and screenshots |
| 3 | Add an architecture diagram and deployment notes |
| 4 | Practise explaining the project in 3-5 minutes |
| 5 | Complete a mock interview and troubleshoot a sample issue |
| 6 | Review the course, list skills demonstrated, and plan next steps |

---

## Capstone Architecture

```text
Student / Browser / API Client
            |
            | HTTPS
            v
Azure App Service
ASP.NET Core Web API (C#)
       |             |
       |             +----> Azure Blob Storage (optional)
       |
       +------------------> Azure SQL Database
       |
       +------------------> Application Insights

GitHub Repository --> GitHub Actions (build + test)
```

| Component | Role |
|---|---|
| Azure App Service | Hosts the ASP.NET Core Web API |
| Azure SQL Database | Relational data store |
| Azure Blob Storage (optional) | Supporting documents and file uploads |
| Application Insights | Monitoring and telemetry |
| GitHub + GitHub Actions | Source control and CI (build + test) |

This is a learning architecture, not a production-ready reference design. Real production systems may require additional networking, identity, monitoring, resilience, backup, and governance controls.

## Suggested Learning Resources

Use current official Microsoft documentation because service names, portal screens, free quotas, and SDK versions can change.

| Resource | Link |
|---|---|
| Microsoft Learn | https://learn.microsoft.com/training/azure/ |
| Azure documentation | https://learn.microsoft.com/azure/ |
| C# documentation | https://learn.microsoft.com/dotnet/csharp/ |
| .NET documentation | https://learn.microsoft.com/dotnet/ |
| ASP.NET Core documentation | https://learn.microsoft.com/aspnet/core/ |
| Azure Architecture Center | https://learn.microsoft.com/azure/architecture/ |
| GitHub Actions documentation | https://docs.github.com/actions |
| Bicep documentation | https://learn.microsoft.com/azure/azure-resource-manager/bicep/ |

## Progress Checklist

Mark a week complete only when you can explain the main concepts in your own words and finish its practical task.

| Done | Week | Topic |
|---|---|---|
| [ ] | 1 | Cloud and Azure orientation |
| [ ] | 2 | C# essentials I |
| [ ] | 3 | C# essentials II |
| [ ] | 4 | .NET, HTTP, Git, and web basics |
| [ ] | 5 | ASP.NET Core Web API |
| [ ] | 6 | SQL fundamentals |
| [ ] | 7 | Entity Framework Core |
| [ ] | 8 | Testing and API security basics |
| [ ] | 9 | Identity and access management |
| [ ] | 10 | Azure App Service |
| [ ] | 11 | Azure Storage |
| [ ] | 12 | Azure SQL Database |
| [ ] | 13 | Azure networking |
| [ ] | 14 | Azure Functions |
| [ ] | 15 | Azure Service Bus |
| [ ] | 16 | Monitoring and troubleshooting |
| [ ] | 17 | GitHub Actions CI/CD |
| [ ] | 18 | Bicep and Infrastructure as Code |
| [ ] | 19 | Azure security |
| [ ] | 20 | Reliability, scaling, and cost |
| [ ] | 21 | Capstone planning |
| [ ] | 22 | Build API and database |
| [ ] | 23 | Azure deployment |
| [ ] | 24 | CI/CD and operational readiness |
| [ ] | 25 | Interview revision |
| [ ] | 26 | Portfolio and final assessment |

## Important Guidance for Students

| Area | Guidance |
|---|---|
| Consistency | Consistency matters more than long study sessions. One hour daily is enough to build a foundation if you practise regularly |
| Scope | Do not try to learn every Azure service. Focus on understanding when and why to use the services covered here |
| Secrets | Keep code in GitHub, but never commit credentials, access keys, connection strings with passwords, or published secrets |
| Cost | Azure free offers and quotas can change. Check pricing before creating resources, set budget alerts where available, and delete resources after labs |
| Honesty | Be honest on your resume: describe this as a learning/capstone project, not commercial production experience |
