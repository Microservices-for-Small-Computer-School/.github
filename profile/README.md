# Architect, Design, Develop, Deploy, Monitor and Maintain Microservices

This is a series of video course on the `Architect, Design, Develop, Deploy, Monitor and Maintain Microservices`. The series is divided into **`Multiple seasons`**.

In this series we will learn 1. Multiple Microservices, 2. Minimal API, 3. API with Controller, 4. Polyglot Data Store (MS SQL Server, Mongo Db, Cosmos Db), 5. Server side Apps (Blazor Server), 6. Single Page Apps (Angular 15 / React 18 / Blazor WASM), 7. Docker, 8. Docker Compose, 9. ARM/Biceps, 10. Terraform, 11. IaC, 12. DevOps (Azure / GitHub), 13. Azure Services, 14. API Gateways, 15. Deploy to Azure Kubernetes Services, 16. Rabbit MQ, 17, Polly, 18 Open Telemetry etc.

## Microservices Series is divided into `18 Courses` and `Multiple Seasons`

### Course **1** - March 2023 - Minimal API in .NET 7 with In-Memory Database, EF Core - **`Completed`**

**Pre-requisites:** Postman, GitHub Organization / Account, Azure Subscription, VS Code, VS 2022

> 1. .NET 7 Minimal API with Static data
> 1. .NET 7 Minimal API with Dynamic data
> 1. .NET 7 Minimal API DI, IOC, record, DTOs, AutoMapper, and Extension Methods
> 1. .NET 7 Minimal API Swagger, Repository, Business Layer, and GitHub Actions
> 1. .NET 7 Minimal API Serilog, CORS, Angular 15, and Azure App Service

---

### Course **2** - Apr 2023 - Minimal API in .NET 7 with Azure SQL Database, .SQLProj, EF Core, CRUD Operations - **`In Progress`**

**Pre-requisites:**  Azure CLI, PowerShell Core, GitHub Accounts, and Azure Data Studio

#### Day 1 - Deploying Minimal API to IIS inside VM (`IaaS`), and Azure App Service (`PaaS`), Comparing IaaS vs PaaS deployments

> 1. Setting up Azure Key Vault, and Purge Protection Demo
> 1. Azure Disks Server-Side Encryption - SSE with CMK and PME
> 1. Setting up Azure VM with IIS, .NET 7, and Software Prerequisites
> 1. Deploying Minimal API to IaaS VM in Azure
> 1. Deploying Minimal API to Azure App Service
> 1. Using Postman to test the Minimal API in IaaS VM and Azure App Service
> 1. Comparing IaaS (deploying in VM) vs PaaS (deploying in Azure App Service)

#### Day 2 - Creating Azure SQL, Azure SQL Server and Database Security Features, deploying .SqlProj into Azure SQL using VS 2022

> 1. Creating .SqlProj, adding table, and Prepolulation of data
> 1. Deploying .SqlProj into Local Sql Server using VS 2022
> 1. Creating Azure SQL using Azure Portal
> 1. Azure SQL Server and Database Security Features, Elastic Pool, and Azure SQL Server Firewall
> 1. Deploying .SqlProj into Azure SQL using VS 2022
> 1. Connecting to Sql Azure using VS Code | Azure Data Studio | VS 2022

#### Day 3 - Moving the logic into different libraries, and Integration of Local Web API with Sql Azure

> 1. Minimal API - Moving Logic into different Libraries.
> 1. Secrets.json, and appsettings.json
> 1. Integration of Local Web API with Sql Azure.
> 1. Deploy Minimal API to Azure App Service.
> 1. Investigating the Connectivity issues to Sql Azure from Azure App Service
> 1. Update the Postman Collection to test the operations locally and in Azure App Service

#### Day 4 - CRUD Operations in Minimal API, Azure Key Vault, and App Service Configuration

> 1. Update Minimal API to support Get By Id, Add Course, Update, and Delete operations.
> 1. Deploy Minimal API to Azure App Service
> 1. Update the appsettings.json with SQL Server Details
> 1. Update the Configuration in Azure App Service
> 1. Update the Azure Key Vault with SQL Server Details
> 1. Update the Configuration in Azure App Service to use Azure Key Vault
> 1. Test Local / Deploy API with Postman

#### Day 5 - Creating Azure Resource using PowerShell / Azure CLI / ARM Templates, and GitHub Actions

> 1. Creating Azure Resource using PowerShell
> 1. Creating Azure Resource using Azure CLI
> 1. Creating Azure Resource using ARM Templates
> 1. Just Enough ARM. Creating Sql Azure Server, and Database using ARM Templates and PowerShell/ Azure CLI
> 1. Just enough GitHub Actions. GitHub Actions to push .SqlProj into Sql Azure

**Note:**

> 1. [https://github.com/vishipayyallore/cloudnative-dot-net6-azure/blob/main/.github/workflows/booksdatastore-cicd.yml](https://github.com/vishipayyallore/cloudnative-dot-net6-azure/blob/main/.github/workflows/booksdatastore-cicd.yml)

---

### Course **3** - May 2023 - ADO.NET, Dapper and EF Core with Polyglot database Crash Course

#### Day 1

> 1. ADO.NET with SQL Server

#### Day 2

> 1. Dapper with SQL Server

#### Day 3

> 1. EF Core with SQLite
> 1. Strongly Typed Configuration in .NET 7

#### Day 4

> 1. EF Core with Cosmos Db

#### Day 5

> 1. EF Core with Postgres

#### Stretch Goal

> 1. Just Enough ARM. Web App / App Service Plan using ARM Templates and PowerShell, Azure CLI
> 1. GitHub Actions to push Minimal Api into App Service
> 1. Blazor Admin App in Azure -> CRUD Operations | Angular 15 Client app in Azure -> Only Get All Courses

---

### Course **4** - Jun 2023 - Just enough Docker, Dockerize Data stores, Minimal API, and Intergration with Angular 15 UI / Blazor Server Admin App

> 1. Docker Fundamentals - Day 1
> 1. Docker Fundamentals - Day 2
> 1. Dockerize Static Html Web Site, and Data Stores
> 1. Dockerize Minimal API
> 1. Dockerize Blazor Server Admin App and Angular 15 Client App
> 1. PowerShell and Shell Scripts to Dockerize Data Stores, Minimal API, and Admin App

---

### Course **5** - Jul 2023 - Blazor Server / WASM in .NET 7 for Course Admin Application, its Dockerization

> 1. Blazor Server Admin App in .NET 7
> 1. Blazor Server Admin App in .NET 7 with Azure SQL Database
> 1. Blazor Server Admin App in .NET 7 with Azure SQL Database and Docker
> 1. Blazor Server Admin App in .NET 7 with Azure SQL Database and Docker Compose
> 1. Blazor Server Admin App in .NET 7 with Azure SQL Database and Docker Compose and GitHub Actions

---

### Course **6** - Aug 2023 - Angular 15 Crash Course, creating Client SPA, Dockerization of SPA

> 1. Angular 15 Crash Course
> 1. Angular 15 Client App with Minimal API
> 1. Angular 15 Client App with Minimal API and Docker
> 1. Angular 15 Client App with Minimal API and Docker Compose
> 1. Angular 15 Client App with Minimal API and Docker Compose and GitHub Actions

---

### Course **7** - Sep 2023 - Docker-Compose to execute Data Stores, Minimal API, Admin, and Client App

---

### Course **8** - Oct 2023 - Web API in .NET 8 with Mongo Db Database

---

### Course **9** - Nov 2023 - Cache-Aside Pattern with Redis, Sync Service to Service Communication, Resiliency Timeouts, Wait-and-retry, Circuit Breaker Pattern

---

### Course 10 - Dec 2023 - Creating our own Identity System for Single Sign On

### Course 11 - Jan 2024 - Implementing Security in Micro Services

### Course 12 - Feb 2024 - Implementing API Gateways (Ocelot / Envoy / something latest )

### Course 13 - Mar 2024 - Asynchronous communication between microservices using RabbitMQ, Mass Transit

### Course 14 - Apr 2024 - Creating Resource using ARM / Biceps / Terraform

### Course 15 - May 2024 - IaC, and DevOps deep dive

### Course 16 - Jun 2024 - Observability / Alerts / Monitoring / Distrbuted Tracing / Logging

### Course 17 - Jul 2024 - Deploying End-to-End solution in Azure Kubernetes Service Azure

### Course 18 - Aug 2024 - Deploying End-to-End solution in Elastic Kubernetes Service in AWS

### Others: React JS 18, gRPC, Azure Services (Service Bus, Redis, Key Valut, etc)

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
