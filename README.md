# Azure-Services---Quick-Study-Notes

1. Compute Services  
🔹 Azure Virtual Machines (VMs) – Scalable cloud-based computers where you can run applications like Windows/Linux. Example: Hosting a website on a Linux VM.  
🔹 Azure App Service – A managed platform to host web apps, APIs, and mobile backends without managing infrastructure. Example: Deploying a Node.js API.  
🔹 Azure Kubernetes Service (AKS) – A managed Kubernetes platform to deploy and scale containerized applications. Example: Running microservices in Docker containers.  
🔹 Azure Functions – Serverless code execution that runs only when triggered, saving cost. Example: Auto-resizing images when uploaded to storage. 
🔹 Azure Batch – Runs parallel computing jobs efficiently. Example: Processing thousands of images in parallel.  

2. Storage Services
🔹 Azure Blob Storage – Stores large unstructured data like images, videos, and backups. Example: Saving product images for an e-commerce site.
🔹 Azure Files – Managed file shares accessible via SMB protocol. Example: Sharing files between multiple VMs.
🔹 Azure Table Storage – NoSQL key-value storage for fast data retrieval. Example: Storing user preferences.
🔹 Azure Queue Storage – Message queuing for asynchronous task processing. Example: Managing background jobs for an order system.
🔹 Azure Disk Storage – High-performance SSD/HDD storage for VMs. Example: Attaching extra storage to a VM.

3. Networking Services
🔹 Azure Virtual Network (VNet) – Creates a secure private network in Azure to connect resources. Example: Connecting multiple VMs securely.
🔹 Azure Load Balancer – Distributes traffic across multiple servers to ensure availability. Example: Managing high traffic to a website.
🔹 Azure Application Gateway – A Layer 7 (HTTP) load balancer with security features. Example: Routing traffic based on URLs.
🔹 Azure ExpressRoute – A private, high-speed connection between on-premises and Azure. Example: Secure banking data transfer.
🔹 Azure Front Door – Global traffic routing and acceleration. Example: Delivering content faster for users worldwide.
🔹 Azure DNS – Provides domain name resolution for Azure services. Example: Mapping "example.com" to a web app.

4. Identity & Security
🔹 Azure Active Directory (Azure AD) – Manages user authentication and permissions. Example: Single sign-on (SSO) for Office 365.
🔹 Azure AD B2C – Secure login for customer-facing apps. Example: A shopping app allowing users to log in via Google.
🔹 Azure Key Vault – Stores and manages sensitive information like passwords and API keys. Example: Storing a database connection string securely.
🔹 Azure Security Center – Monitors security and provides recommendations. Example: Detecting vulnerabilities in a VM.
🔹 Microsoft Defender for Cloud – Threat detection for workloads. Example: Detecting unusual login attempts.
🔹 Azure Sentinel – SIEM tool for detecting cyber threats. Example: Identifying suspicious activity in a network.

5. Databases & Analytics
🔹 Azure SQL Database – Fully managed relational database. Example: Storing user data for a SaaS app.
🔹 Azure Cosmos DB – A globally distributed NoSQL database with low latency. Example: Managing user profiles in a chat app.
🔹 Azure Database for MySQL/PostgreSQL/MariaDB – Managed open-source databases. Example: Hosting a WordPress site with MySQL.
🔹 Azure Synapse Analytics – Data warehouse for big data analytics. Example: Analyzing sales trends across multiple stores.
🔹 Azure Data Factory – ETL service for moving and transforming data. Example: Copying data from an on-prem SQL server to Azure.
🔹 Azure Databricks – Apache Spark-based analytics and AI platform. Example: Real-time fraud detection in banking.

6. DevOps & Monitoring
🔹 Azure DevOps – CI/CD pipelines, Git repos, and Agile tracking. Example: Automating deployments for a web app.
🔹 GitHub Actions for Azure – CI/CD integration with GitHub. Example: Deploying a React app to Azure automatically.
🔹 Azure Monitor – Collects logs and metrics for Azure services. Example: Tracking CPU usage on a VM.
🔹 Azure Application Insights – Monitors application performance and errors. Example: Finding slow API responses.

7. AI & Machine Learning
🔹 Azure Machine Learning – Platform for building and training ML models. Example: Predicting customer churn in a retail business.
🔹 Azure Cognitive Services – Pre-built AI models for vision, speech, and language. Example: Automatically translating languages in a chatbot.
🔹 Azure Bot Service – Platform for building AI chatbots. Example: Customer support chatbot.
🔹 Azure OpenAI Service – Access to OpenAI’s GPT models. Example: Generating automatic summaries of news articles.

8. Containers & Microservices
🔹 Azure Container Instances (ACI) – Run lightweight containers without managing infrastructure. Example: Running a microservice on demand.
🔹 Azure Service Fabric – Deploys microservices with high availability. Example: Managing a large e-commerce system.
🔹 Azure Red Hat OpenShift – A managed Kubernetes service for OpenShift users. Example: Deploying enterprise applications in containers.

9. Hybrid & Multi-Cloud Solutions
🔹 Azure Arc – Manage servers, Kubernetes, and databases across on-prem, multi-cloud, and Azure. Example: Managing AWS and on-prem resources from Azure.
🔹 Azure Stack – Extends Azure services to on-premises environments. Example: Running cloud apps in a local data center.

10. Messaging & Integration
🔹 Azure Service Bus – Enterprise-grade messaging for distributed applications. Example: Decoupling order placement from order processing in an e-commerce site.
🔹 Azure Event Grid – Event-driven architecture for real-time data processing. Example: Triggering a function when a new file is uploaded.
🔹 Azure Logic Apps – Automates workflows and connects services. Example: Syncing customer data between Salesforce and Azure.
