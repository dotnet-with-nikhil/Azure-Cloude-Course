# 6-Month Azure Cloud Course for Freshers and Recent Graduates

**Duration:** 26 weeks (approximately 6 months)\
**Daily commitment:** 1 hour, 6 days per week (about 6 hours/week)\
**Audience:** Freshers, final-year students, and recent graduates\
**Programming language:** C# and .NET only\
**Excluded:** Python, AI/ML, and generative AI

## Course goal

By the end of this course, students should be able to build a small
ASP.NET Core application, deploy it to Azure, connect it to a database
and storage, secure it, monitor it, automate deployment, and explain the
project in an entry-level cloud/.NET interview.

## Daily study pattern (60 minutes)

Use this pattern on most days: - **10 minutes:** Revise yesterday's
topic. - **20 minutes:** Learn one concept. - **25 minutes:** Follow a
demo or do a hands-on task. - **5 minutes:** Write notes and explain
what you learned aloud.

Study six days per week. Keep the seventh day for rest or catching up.
Do not create paid Azure resources without checking the current price
and deleting them when finished.

## Before starting

-   A Windows, macOS, or Linux computer with a modern browser.
-   Install the current supported .NET SDK, Visual Studio or Visual
    Studio Code, and Git.
-   A GitHub account for storing code.
-   An Azure account with access to the Azure portal. Check current
    student offers and account eligibility before creating a
    subscription. A credit card may be requested depending on the offer
    and account type; do not assume every student gets a free
    subscription.
-   Follow the course using free-tier or student-eligible services where
    available. Pricing and free quotas can change.
-   Set a budget alert where available, and delete or stop resources
    after labs.

## Month 1 --- Cloud and C#/.NET foundations

### Week 1: Cloud computing and Azure orientation

**Topics** - What cloud computing is and why companies use it. - IaaS,
PaaS, and SaaS with simple examples. - Public, private, and hybrid
cloud. - Regions, region pairs, availability zones, and datacenters. -
Azure portal, subscriptions, resource groups, and resources. - Shared
responsibility model; basic cloud security and cost awareness.

**Daily plan** 1. Learn cloud computing and common business use cases.
2. Compare IaaS, PaaS, and SaaS. 3. Learn regions, availability zones,
and resilience. 4. Tour the Azure portal and locate core services. 5.
Understand tenants, subscriptions, resource groups, and resources. 6.
Draw a simple diagram of a web app hosted in Azure and explain it.

**Weekly outcome:** Explain core cloud terms and navigate the Azure
portal.

### Week 2: C# essentials --- part 1

**Topics** - .NET, C#, SDK, runtime, and CLR at a high level. -
Variables, data types, operators, and type conversion. - Conditions and
loops. - Methods, parameters, return values, and scope. - Arrays,
strings, and basic debugging.

**Daily plan** 1. Install the .NET SDK and create a console application.
2. Variables, types, operators, and conversions. 3. `if`, `switch`,
`for`, `while`, and `foreach`. 4. Methods, parameters, and return
values. 5. Arrays and string operations. 6. Build a console-based
student marks calculator.

**Weekly outcome:** Write small C# console programs.

### Week 3: C# essentials --- part 2

**Topics** - Classes, objects, properties, and constructors. -
Encapsulation, inheritance, polymorphism, and abstraction. - Interfaces
and dependency inversion at a beginner level. - Collections: `List<T>`,
`Dictionary<TKey,TValue>`. - Exceptions and basic file handling. - LINQ
fundamentals.

**Daily plan** 1. Classes, objects, properties, and constructors. 2. OOP
principles with simple examples. 3. Interfaces and implementing an
interface. 4. Collections and LINQ (`Where`, `Select`,
`FirstOrDefault`). 5. Exceptions and basic file read/write. 6. Build a
console-based student management app.

**Weekly outcome:** Create a small C# application using OOP and
collections.

### Week 4: .NET, HTTP, Git, and web basics

**Topics** - .NET project structure and NuGet packages. - Introduction
to ASP.NET Core and the request/response cycle. - HTTP methods, status
codes, headers, JSON, and REST. - Git basics: clone, add, commit, push,
branches. - Configuration and environment variables. - Introduction to
debugging and logging.

**Daily plan** 1. Explore a .NET project and use the `dotnet` CLI. 2.
Learn HTTP, JSON, REST, and common status codes. 3. Practice Git commits
and branches. 4. Learn configuration files and environment variables. 5.
Create a basic ASP.NET Core Web API. 6. Push the project to GitHub and
write a README.

**Weekly outcome:** Have a working .NET Web API in a Git repository.

## Month 2 --- Build a real .NET application

### Week 5: ASP.NET Core Web API

**Topics** - Controllers or Minimal APIs. - Routing, model binding, and
DTOs. - Validation and correct HTTP status codes. - Dependency injection
and service lifetimes. - Middleware and exception handling. -
Swagger/OpenAPI and API testing.

**Daily plan** 1. Create endpoints and understand routing. 2. Use DTOs
and model binding. 3. Add validation and appropriate status codes. 4.
Register and inject a service. 5. Add exception handling and Swagger. 6.
Build CRUD endpoints for a course catalogue.

**Weekly outcome:** Create a clean CRUD API with validation.

### Week 6: SQL and relational database basics

**Topics** - Tables, rows, columns, primary keys, and foreign keys. -
`SELECT`, filtering, sorting, and joins. - Insert, update, and delete. -
Constraints and normalization basics. - Index basics and why query
performance matters. - Connection strings and database credentials.

**Daily plan** 1. Learn relational database concepts and create tables.
2. Practice `SELECT`, `WHERE`, `ORDER BY`, and `TOP`. 3. Practice
`INSERT`, `UPDATE`, and `DELETE`. 4. Learn joins and foreign keys. 5.
Learn constraints and basic indexes. 6. Design a small database for
courses and students.

**Weekly outcome:** Write basic SQL and design a simple relational
schema.

### Week 7: Entity Framework Core

**Topics** - ORM and EF Core concepts. - `DbContext`, entities, and
`DbSet`. - Migrations and schema updates. - CRUD operations with EF
Core. - Relationships and basic query efficiency. - Safe handling of
connection strings.

**Daily plan** 1. Add EF Core packages and configure `DbContext`. 2.
Create entities and configure a database connection. 3. Create and apply
migrations. 4. Implement create, read, update, and delete. 5. Add a
relationship and query related data. 6. Connect EF Core to the course
catalogue API and test it.

**Weekly outcome:** Persist API data in a relational database through EF
Core.

### Week 8: Testing, quality, and API security basics

**Topics** - Unit testing with xUnit. - Arrange-Act-Assert pattern. -
Mocking dependencies at a beginner level. - Input validation and safe
error responses. - Authentication versus authorization. - Secrets,
passwords, and connection strings: what not to commit.

**Daily plan** 1. Create a test project and write a first xUnit test. 2.
Test service logic using Arrange-Act-Assert. 3. Learn dependency mocking
and test edge cases. 4. Add input validation and safe error handling. 5.
Learn authentication vs authorization and common security risks. 6. Add
tests to the API and scan the Git repository for accidentally committed
secrets.

**Weekly outcome:** Add meaningful tests and explain basic API security
practices.

## Month 3 --- Azure core services

### Week 9: Identity and access management

**Topics** - Microsoft Entra ID terminology and purpose. -
Authentication and authorization in Azure. - Users, groups, app
registrations, and service principals. - Azure role-based access control
(Azure RBAC). - Least privilege and role scopes. - Managed identities
and why they are safer than embedded credentials.

**Daily plan** 1. Understand Microsoft Entra ID and identity concepts.
2. Learn users, groups, and app registrations conceptually. 3. Explore
Azure RBAC roles and scopes. 4. Learn least privilege with examples. 5.
Understand managed identities and credential risks. 6. Draw an access
model for a web app and its database.

**Weekly outcome:** Explain identity, RBAC, and least privilege. Only
create identity resources if permitted by the subscription.

### Week 10: Azure App Service

**Topics** - What Azure App Service does. - App Service plans, apps,
deployment slots, and scaling basics. - App settings and connection
strings. - Deploying an ASP.NET Core API. - Logs and basic
troubleshooting. - HTTPS and custom-domain concepts.

**Daily plan** 1. Learn App Service and App Service plans. 2. Publish
the .NET API locally in Release mode. 3. Deploy the API to App Service
using a supported deployment method. 4. Configure app settings and
environment-specific values. 5. Inspect logs and troubleshoot a
deliberate configuration error. 6. Document deployment steps and remove
or stop resources if not needed.

**Weekly outcome:** Deploy a working .NET API to Azure App Service.

### Week 11: Azure Storage

**Topics** - Storage account and redundancy concepts. - Blob, Queue, and
Table storage use cases. - Containers, blobs, and access tiers. - Shared
access signatures (SAS) and access safety. - Upload/download from .NET
using the Azure SDK. - Lifecycle and cost considerations.

**Daily plan** 1. Explore storage account options and redundancy. 2.
Learn blobs, containers, and access tiers. 3. Create a container and
upload a sample file in the portal. 4. Use the Azure Storage SDK from a
small C# app. 5. Learn SAS tokens and why credentials must be protected.
6. Add a file-upload feature or document a secure upload flow for the
API.

**Weekly outcome:** Explain Azure Storage options and perform a basic
blob operation.

### Week 12: Azure SQL Database

**Topics** - Azure SQL Database versus SQL Server installed on a VM. -
Server, database, networking, and firewall concepts. - Secure connection
from .NET. - Data migration and schema changes. - Backups, availability,
and cost basics. - Troubleshooting connection failures.

**Daily plan** 1. Compare Azure SQL Database with SQL Server on a VM. 2.
Explore database configuration and pricing concepts. 3. Learn firewall
rules and secure connectivity. 4. Connect the API to Azure SQL if
budget/access allows; otherwise practise using a local SQL database and
study the deployment steps. 5. Learn backups, restore concepts, and
connection troubleshooting. 6. Update the architecture diagram and
document database configuration without publishing secrets.

**Weekly outcome:** Understand how a .NET API connects securely to a
managed database.

## Month 4 --- Networking, messaging, and operations

### Week 13: Azure networking fundamentals

**Topics** - Virtual networks (VNets) and subnets. - Public versus
private IP addresses. - Network Security Groups (NSGs). - DNS, ports,
and HTTPS/TLS. - Private endpoints and service endpoints at a conceptual
level. - Network troubleshooting basics.

**Daily plan** 1. Learn IP addresses, DNS, ports, and HTTPS. 2.
Understand VNets and subnets. 3. Learn NSGs and traffic rules. 4.
Compare public access, private access, and private endpoints. 5. Draw a
secure web app/database network design. 6. Troubleshoot a sample
connectivity scenario on paper or in a permitted lab.

**Weekly outcome:** Explain the main building blocks of Azure
networking.

### Week 14: Azure Functions and event-driven computing

**Topics** - Serverless computing and when to use it. - Azure Functions
triggers and bindings. - HTTP trigger and timer trigger. - C# isolated
worker model overview. - Configuration, logging, and local testing. -
Function hosting plans and cost awareness.

**Daily plan** 1. Learn serverless and Azure Functions use cases. 2.
Create a C# Azure Functions project. 3. Implement an HTTP-triggered
function. 4. Implement or inspect a timer-triggered function. 5. Add
configuration and logging. 6. Compare an App Service API endpoint with a
Function endpoint.

**Weekly outcome:** Build and explain a small C# Azure Function.

### Week 15: Azure Service Bus and asynchronous messaging

**Topics** - Why queues and asynchronous processing are used. - Queue
versus topic/subscription. - Message send/receive using C#. - Retries,
dead-letter queues, and duplicate delivery. - Idempotency and message
processing safety. - Observability and cost basics.

**Daily plan** 1. Understand synchronous calls versus queues. 2. Learn
queues, topics, and subscriptions. 3. Read a C# send/receive example
using the Azure SDK. 4. Learn retries, dead-lettering, and poison
messages. 5. Understand duplicate delivery and idempotent handlers. 6.
Draw an order-processing flow using API, Service Bus, and a worker.

**Weekly outcome:** Explain a reliable asynchronous workflow. Run a live
lab only if the subscription and budget permit it.

### Week 16: Monitoring and troubleshooting

**Topics** - Azure Monitor and Log Analytics concepts. - Application
Insights for ASP.NET Core. - Logs, metrics, traces, and correlation
IDs. - Health checks and availability. - Alerts and diagnostic
settings. - Troubleshooting latency, errors, and failed dependencies.

**Daily plan** 1. Learn logs, metrics, and distributed traces. 2. Add
Application Insights to the .NET API where available. 3. Inspect request
and dependency telemetry. 4. Add a health-check endpoint. 5. Learn
alerts and diagnostic settings. 6. Troubleshoot a sample slow API/error
scenario and write a short incident report.

**Weekly outcome:** Find basic failures and latency clues using logs and
telemetry.

## Month 5 --- Deployment, security, and cloud architecture

### Week 17: CI/CD with GitHub Actions

**Topics** - CI versus CD. - Build, test, publish, and deploy stages. -
GitHub Actions workflow structure. - Repository secrets and environment
variables. - Deploying an ASP.NET Core app to Azure. - Rollback and
deployment verification concepts.

**Daily plan** 1. Understand a CI/CD pipeline. 2. Create a workflow that
restores and builds the .NET solution. 3. Add automated tests to the
workflow. 4. Learn publishing artifacts and environment configuration.
5. Study a safe Azure deployment workflow using documented
authentication methods. 6. Review pipeline output and write deployment
instructions.

**Weekly outcome:** Build a pipeline that restores, builds, and tests
the .NET project; deploy only if access is available.

### Week 18: Infrastructure as Code with Bicep

**Topics** - Why Infrastructure as Code (IaC) matters. - Declarative
templates and repeatability. - Bicep syntax and parameters. - Resource
dependencies and outputs. - What-if validation and deployment scopes. -
Managing secrets outside templates.

**Daily plan** 1. Learn IaC and compare manual versus repeatable
deployment. 2. Read a simple Bicep template. 3. Define parameters and
outputs. 4. Describe resources and dependencies. 5. Run
validation/what-if where permitted, or inspect a sample deployment. 6.
Document the resources required for the capstone project.

**Weekly outcome:** Read and create a basic Bicep template.

### Week 19: Azure security fundamentals

**Topics** - Shared responsibility and defence in depth. - Microsoft
Entra ID and Azure RBAC review. - Managed identities and Key Vault. -
Secrets, certificates, and key rotation concepts. - Secure networking
and HTTPS. - Secure coding and dependency updates.

**Daily plan** 1. Review shared responsibility and common cloud risks.
2. Review RBAC and least privilege. 3. Learn Azure Key Vault use cases.
4. Learn managed identity access to services. 5. Review HTTPS, input
validation, and dependency updates. 6. Create a security checklist for
the capstone application.

**Weekly outcome:** Identify and reduce common identity,
secret-management, and application-security risks.

### Week 20: Reliability, scaling, and cost management

**Topics** - Vertical versus horizontal scaling. - App Service scale-up
and scale-out. - Availability zones and redundancy concepts. - Backups,
recovery objectives, and disaster recovery. - Azure Cost Management,
budgets, and tags. - Choosing services based on workload and cost.

**Daily plan** 1. Learn scale-up versus scale-out. 2. Understand
autoscale and basic capacity planning. 3. Learn availability, backup,
and recovery concepts. 4. Explore budgets, cost analysis, and resource
tags. 5. Review sample architecture trade-offs. 6. Create a simple cost
and reliability checklist for the capstone.

**Weekly outcome:** Explain basic scaling, reliability, and cost
decisions without overengineering.

## Month 6 --- Capstone project and job preparation

### Week 21: Capstone planning and architecture

**Project:** Course Registration Portal (ASP.NET Core Web API + C# +
Azure)

**Minimum features** - Manage courses and student registrations. - REST
endpoints with validation and correct status codes. - EF Core and
relational database. - Unit tests. - File upload or supporting documents
using Blob Storage (optional if budget/access is limited). - Azure
deployment and basic monitoring. - CI workflow and documentation.

**Daily plan** 1. Write user stories and define project scope. 2. Draw
architecture: client, API, database, and optional storage. 3. Design
entities, relationships, and API endpoints. 4. Create solution structure
and Git repository. 5. Create the initial API and add a health endpoint.
6. Write a README with setup and architecture.

**Weekly outcome:** Have a scoped, documented project ready to
implement.

### Week 22: Build the API and database

**Topics** - Implementing CRUD endpoints. - Service layer and dependency
injection. - EF Core migrations and relationships. - Validation, error
handling, and pagination basics. - Unit tests for business logic. - Git
commits and code review habits.

**Daily plan** 1. Implement course endpoints. 2. Implement
student/registration endpoints. 3. Configure EF Core and migrations. 4.
Add validation and consistent error handling. 5. Write unit tests for
key rules. 6. Test endpoints and update the README.

**Weekly outcome:** A functional, tested local application.

### Week 23: Add Azure services and deploy

**Topics** - App Service deployment. - Database connection
configuration. - App settings and secrets handling. - Optional Blob
Storage integration. - Health checks and Application Insights. -
Deployment smoke tests.

**Daily plan** 1. Prepare the app for Release deployment. 2. Deploy to
App Service if access and budget permit. 3. Configure the database
connection securely. 4. Add Blob Storage integration or document it as
an extension. 5. Verify health, logs, and core endpoints. 6. Run smoke
tests and record known limitations.

**Weekly outcome:** A deployed application or a reproducible deployment
demonstration.

### Week 24: CI/CD, security, and operational readiness

**Topics** - Build/test workflow. - Deployment pipeline concepts. -
Secrets and least privilege. - Logs, alerts, and troubleshooting
notes. - Cost cleanup and resource inventory. - Project demo
preparation.

**Daily plan** 1. Add or refine CI build workflow. 2. Run automated
tests in the workflow. 3. Review secrets and access permissions. 4.
Verify logs, health checks, and failure handling. 5. Review Azure
resources and remove unused paid resources. 6. Prepare a 5-minute
project demonstration.

**Weekly outcome:** A documented, safer, repeatable project workflow.

### Week 25: Interview and practical revision

**Topics** - Cloud fundamentals and Azure core services. - App Service
versus Functions versus virtual machines. - Blob versus Queue versus
Table storage. - Azure SQL and EF Core. - Entra ID, RBAC, managed
identities, and Key Vault. - Networking, monitoring, CI/CD, and cost
management.

**Daily plan** 1. Revise cloud models, regions, subscriptions, and
resource groups. 2. Explain App Service, Functions, and VMs with use
cases. 3. Revise Storage, Azure SQL, and Service Bus. 4. Revise
identity, RBAC, managed identities, and Key Vault. 5. Revise networking,
monitoring, CI/CD, and Bicep. 6. Answer 10 interview questions aloud and
note weak areas.

**Weekly outcome:** Explain concepts clearly with examples rather than
memorized definitions.

### Week 26: Portfolio, resume, and final assessment

**Topics** - GitHub repository hygiene and README. - Architecture
diagram and deployment notes. - Project demo and limitations. - Basic
troubleshooting scenarios. - Resume project description without
exaggerating experience. - Final revision and next learning steps.

**Daily plan** 1. Clean up the repository and remove secrets. 2. Improve
README: problem, architecture, setup, endpoints, and screenshots. 3. Add
an architecture diagram and deployment notes. 4. Practise explaining the
project in 3--5 minutes. 5. Complete a mock interview and troubleshoot a
sample issue. 6. Review the course, list skills demonstrated, and plan
next steps.

**Weekly outcome:** A portfolio-ready beginner project and a clear
explanation of the Azure/.NET skills practised.

## Capstone architecture

``` text
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

This is a learning architecture, not a production-ready reference
design. Real production systems may require additional networking,
identity, monitoring, resilience, backup, and governance controls.

## Suggested learning resources

Use current official Microsoft documentation because service names,
portal screens, free quotas, and SDK versions can change.

-   Microsoft Learn: https://learn.microsoft.com/training/azure/
-   Azure documentation: https://learn.microsoft.com/azure/
-   C# documentation: https://learn.microsoft.com/dotnet/csharp/
-   .NET documentation: https://learn.microsoft.com/dotnet/
-   ASP.NET Core documentation: https://learn.microsoft.com/aspnet/core/
-   Azure Architecture Center:
    https://learn.microsoft.com/azure/architecture/
-   GitHub Actions documentation: https://docs.github.com/actions
-   Bicep documentation:
    https://learn.microsoft.com/azure/azure-resource-manager/bicep/

## Progress checklist

Mark a week complete only when you can explain the main concepts in your
own words and finish its practical task.

-   [ ] Week 1 --- Cloud and Azure orientation
-   [ ] Week 2 --- C# essentials I
-   [ ] Week 3 --- C# essentials II
-   [ ] Week 4 --- .NET, HTTP, Git, and web basics
-   [ ] Week 5 --- ASP.NET Core Web API
-   [ ] Week 6 --- SQL fundamentals
-   [ ] Week 7 --- Entity Framework Core
-   [ ] Week 8 --- Testing and API security basics
-   [ ] Week 9 --- Identity and access management
-   [ ] Week 10 --- Azure App Service
-   [ ] Week 11 --- Azure Storage
-   [ ] Week 12 --- Azure SQL Database
-   [ ] Week 13 --- Azure networking
-   [ ] Week 14 --- Azure Functions
-   [ ] Week 15 --- Azure Service Bus
-   [ ] Week 16 --- Monitoring and troubleshooting
-   [ ] Week 17 --- GitHub Actions CI/CD
-   [ ] Week 18 --- Bicep and Infrastructure as Code
-   [ ] Week 19 --- Azure security
-   [ ] Week 20 --- Reliability, scaling, and cost
-   [ ] Week 21 --- Capstone planning
-   [ ] Week 22 --- Build API and database
-   [ ] Week 23 --- Azure deployment
-   [ ] Week 24 --- CI/CD and operational readiness
-   [ ] Week 25 --- Interview revision
-   [ ] Week 26 --- Portfolio and final assessment

## Important guidance for students

-   Consistency matters more than long study sessions. One hour daily is
    enough to build a foundation if you practise regularly.
-   Do not try to learn every Azure service. Focus on understanding when
    and why to use the services covered here.
-   Keep code in GitHub, but never commit credentials, access keys,
    connection strings with passwords, or published secrets.
-   Azure free offers and quotas can change. Check pricing before
    creating resources, set budget alerts where available, and delete
    resources after labs.
-   Be honest on your resume: describe this as a learning/capstone
    project, not commercial production experience.
