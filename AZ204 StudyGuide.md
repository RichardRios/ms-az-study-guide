# **AZ-204 Study Guide**
- [**AZ-204 Study Guide**](#az-204-study-guide)
  - [**Create Azure App Service Web Apps**](#create-azure-app-service-web-apps)
    - [**Explore Azure App Service**](#explore-azure-app-service)
      - [**Examine Azure App Service**](#examine-azure-app-service)
      - [**Examine Azure App Service Plans**](#examine-azure-app-service-plans)
      - [**Deploy to App Service**](#deploy-to-app-service)
      - [**Explore Authentication and Authorization in App Service**](#explore-authentication-and-authorization-in-app-service)
      - [**Discover App Service networking features**](#discover-app-service-networking-features)
    - [**Configure Web App Settings**](#configure-web-app-settings)
      - [**Configure Application Settings**](#configure-application-settings)
      - [**Configure general settings**](#configure-general-settings)
      - [**Configure Path Mappings**](#configure-path-mappings)
      - [**Enable Diagnostic Logging**](#enable-diagnostic-logging)
      - [**Configure Security certificates**](#configure-security-certificates)
      - [**Manage App Features**](#manage-app-features)
    - [**Scale Apps in Azure**](#scale-apps-in-azure)
      - [**Examine autoscale factors**](#examine-autoscale-factors)
      - [**Identify autoscale factors**](#identify-autoscale-factors)
      - [**Enable autoscale in App Service**](#enable-autoscale-in-app-service)
      - [**Explore autoscale best practices**](#explore-autoscale-best-practices)
    - [**Explore Azure App Service deployment slots**](#explore-azure-app-service-deployment-slots)
      - [**Explore Staging Environments**](#explore-staging-environments)
      - [**Examing Slot Swapping**](#examing-slot-swapping)
      - [**Swap Deployment Slots**](#swap-deployment-slots)
      - [**Route Traffic in App Service**](#route-traffic-in-app-service)
  - [**Implement Azure Functions**](#implement-azure-functions)
    - [**Explore Azure Functions**](#explore-azure-functions)
      - [**Discover Azure Functions**](#discover-azure-functions)
      - [**Compare Azure Functions hosting options**](#compare-azure-functions-hosting-options)
      - [**Scale Azure Functions**](#scale-azure-functions)
    - [**Develop Azure Functions**](#develop-azure-functions)
      - [**Explore Azure Functions development**](#explore-azure-functions-development)
      - [**Create triggers and bindings**](#create-triggers-and-bindings)
      - [**Connect functions to Azure services**](#connect-functions-to-azure-services)
      - [**Exercise: Create an Azure Function by using VS Code**](#exercise-create-an-azure-function-by-using-vs-code)
    - [**Implement Durable Functions**](#implement-durable-functions)
      - [**Explore Durable Functions app patterns**](#explore-durable-functions-app-patterns)
      - [**Discover the four function types**](#discover-the-four-function-types)
      - [**Explore task hubs**](#explore-task-hubs)
      - [**Explore durable orchestrations**](#explore-durable-orchestrations)
      - [**Control timing in Durable Functions**](#control-timing-in-durable-functions)
      - [**Send and wait for events**](#send-and-wait-for-events)
  - [**Develop Solutions that use Blob storage**](#develop-solutions-that-use-blob-storage)
    - [**Explore Azure Blob storage**](#explore-azure-blob-storage)
      - [**Explore Azure Blob storage**](#explore-azure-blob-storage-1)
      - [**Discover Azure Blob storage resource types**](#discover-azure-blob-storage-resource-types)
      - [**Explore Azure Storage security features**](#explore-azure-storage-security-features)
      - [**Evaluate Azure Storage redundancy options**](#evaluate-azure-storage-redundancy-options)
      - [**Exercise: Create a block blob storage account**](#exercise-create-a-block-blob-storage-account)
    - [**Manage the Azure Blob storage lifecycles**](#manage-the-azure-blob-storage-lifecycles)
      - [**Explore Azure Blob storage lifecycle**](#explore-azure-blob-storage-lifecycle)
      - [**Discover Blob storage lifecycle policies**](#discover-blob-storage-lifecycle-policies)
      - [**Implement Blob storage lifecycle policies**](#implement-blob-storage-lifecycle-policies)
      - [**Rehydrate blob data from archive tier**](#rehydrate-blob-data-from-archive-tier)
    - [**Work with Azure Blob storage**](#work-with-azure-blob-storage)
      - [**Explore Azure Blob storage client library**](#explore-azure-blob-storage-client-library)
      - [**Exercise: Create Blob storage resources by using .NET client library**](#exercise-create-blob-storage-resources-by-using-net-client-library)
      - [**Manage container properties and metadata by using .NET**](#manage-container-properties-and-metadata-by-using-net)
      - [**Set and retrieve properties and metadata for blob resources by using REST**](#set-and-retrieve-properties-and-metadata-for-blob-resources-by-using-rest)
  - [**Develop solutions that use Azure Cosmos DB**](#develop-solutions-that-use-azure-cosmos-db)
    - [**Explore Azure Cosmos DB**](#explore-azure-cosmos-db)
      - [**Identify key benefits of Azure Cosmos DB**](#identify-key-benefits-of-azure-cosmos-db)
      - [**Explore the resource hierarchy**](#explore-the-resource-hierarchy)
      - [**Explore consistency levels**](#explore-consistency-levels)
      - [**Choose the right consistency level**](#choose-the-right-consistency-level)
      - [**Explore supported APIs**](#explore-supported-apis)
      - [**Discover request units**](#discover-request-units)
      - [**Exercise: Create Azure Cosmos DB resources by using Azure Portal**](#exercise-create-azure-cosmos-db-resources-by-using-azure-portal)
    - [**Implement Partitioning in Azure Cosmos DB**](#implement-partitioning-in-azure-cosmos-db)
      - [**Explore Partitions**](#explore-partitions)
      - [**Choose a partition key**](#choose-a-partition-key)
      - [**Create a synthetic partition key**](#create-a-synthetic-partition-key)
    - [**Work with Azure Cosmos DB**](#work-with-azure-cosmos-db)
      - [**Explore Microsoft .NET SDK v3 for Azure Cosmos DB**](#explore-microsoft-net-sdk-v3-for-azure-cosmos-db)
      - [**Exercise: Create resources by using the Microsoft .NET SDK 3**](#exercise-create-resources-by-using-the-microsoft-net-sdk-3)
      - [**Create stored procedures**](#create-stored-procedures)
      - [**Create triggers and user-defined functions**](#create-triggers-and-user-defined-functions)
  - [**Implement Infrastructure as a Service solutions (IaaS)**](#implement-infrastructure-as-a-service-solutions-iaas)
    - [**Provision Virtual Machines in Azure**](#provision-virtual-machines-in-azure)
      - [**Explore Azure Virtual Machines**](#explore-azure-virtual-machines)
      - [**Compare Virtual Machine availability options**](#compare-virtual-machine-availability-options)
      - [**Determine appropriate virtual machine size**](#determine-appropriate-virtual-machine-size)
      - [**Exercise: Create a VM by using the Azure CLI**](#exercise-create-a-vm-by-using-the-azure-cli)
    - [**Create and Deploy Azure Resource Manager Templates (ARM)**](#create-and-deploy-azure-resource-manager-templates-arm)
      - [**Explore Azure Resource Manager**](#explore-azure-resource-manager)
      - [**Deploy multi-tiered solutions**](#deploy-multi-tiered-solutions)
      - [**Explore conditional deployment**](#explore-conditional-deployment)
      - [**Set the correct deployment mode**](#set-the-correct-deployment-mode)
      - [**Exercise: Create and deploy ARM templates by using VS Code**](#exercise-create-and-deploy-arm-templates-by-using-vs-code)
    - [**Manage Container Images in Azure Container Registry (ACR)**](#manage-container-images-in-azure-container-registry-acr)
      - [**Discover the Azure Container Registry (ACR)**](#discover-the-azure-container-registry-acr)
      - [**Explore storage capabilities**](#explore-storage-capabilities)
      - [**Build and manage containers with tasks**](#build-and-manage-containers-with-tasks)
      - [**Explore elements of a Dockerfile**](#explore-elements-of-a-dockerfile)
      - [**Exercise: Build and run a container image by using Azure Container Registry (ACR) Tasks**](#exercise-build-and-run-a-container-image-by-using-azure-container-registry-acr-tasks)
    - [**Implement Azure App Configuration**](#implement-azure-app-configuration)
      - [**Explore the Azure App Configuration service**](#explore-the-azure-app-configuration-service)
      - [**Create paired keys and values**](#create-paired-keys-and-values)
      - [**Manage application features**](#manage-application-features)
      - [**Secure app configuration data**](#secure-app-configuration-data)
  - [**Implement API Management**](#implement-api-management)
    - [**Explore API Management**](#explore-api-management)
      - [**Discover API Management Service**](#discover-api-management-service)
      - [**Explore API Gateways**](#explore-api-gateways)
      - [**Explore API Management Policies**](#explore-api-management-policies)
      - [**Create advanced policies**](#create-advanced-policies)
      - [**Secure APIs by using subscriptions**](#secure-apis-by-using-subscriptions)
      - [**Secure APIs by using certificates**](#secure-apis-by-using-certificates)
      - [**Exercise: Create a backend API**](#exercise-create-a-backend-api)
  - [**Develop Event-Based Solutions**](#develop-event-based-solutions)
    - [**Explore Azure Event Grid**](#explore-azure-event-grid)
      - [**Explore Azure Event Grid**](#explore-azure-event-grid-1)
      - [**Discover event schemas**](#discover-event-schemas)
      - [**Explore event delivery durability**](#explore-event-delivery-durability)
      - [**Control access to events**](#control-access-to-events)
      - [**Receive events by using webhooks**](#receive-events-by-using-webhooks)
      - [**Filter events**](#filter-events)
      - [**Exercise: Route custom events to web endpoint by using Azure CLI**](#exercise-route-custom-events-to-web-endpoint-by-using-azure-cli)
    - [**Explore Azure Event Hubs**](#explore-azure-event-hubs)
      - [**Discover Azure Event Hubs**](#discover-azure-event-hubs)
      - [**Explore Event Hubs Capture**](#explore-event-hubs-capture)
      - [**Scale your processing application**](#scale-your-processing-application)
      - [**Control access to events**](#control-access-to-events-1)
      - [**Perform common operations with the Event Hubs client library**](#perform-common-operations-with-the-event-hubs-client-library)
  - [**Develop message-based solutions**](#develop-message-based-solutions)
      - [**Choose a message queue solution**](#choose-a-message-queue-solution)
      - [**Explore Azure Service Bus**](#explore-azure-service-bus)
      - [**Discover Service Bus queues, topics, and subscriptions**](#discover-service-bus-queues-topics-and-subscriptions)
      - [**Explore Service Bus message payloads and serialization**](#explore-service-bus-message-payloads-and-serialization)
      - [**Exercise: Send and receive message from a Service Bus queue by using .NET**](#exercise-send-and-receive-message-from-a-service-bus-queue-by-using-net)
      - [**Explore Azure Qeueue Storage**](#explore-azure-qeueue-storage)
      - [**Create and manage Azure Queue Storage and messages by using .NET**](#create-and-manage-azure-queue-storage-and-messages-by-using-net)
  - [**Instrument solutions to support monitoring and logging**](#instrument-solutions-to-support-monitoring-and-logging)
    - [**Monitor app performance**](#monitor-app-performance)
      - [**Explore Azure Monitor**](#explore-azure-monitor)
      - [**Explore Application Insights**](#explore-application-insights)
      - [**Discover log-based metrics**](#discover-log-based-metrics)
      - [**Instrument an app for monitoring**](#instrument-an-app-for-monitoring)
      - [**Select an availability test**](#select-an-availability-test)
      - [**Troubleshoot app performance by using Application Map**](#troubleshoot-app-performance-by-using-application-map)
  - [**Integrate caching and content delivery within solutions**](#integrate-caching-and-content-delivery-within-solutions)
    - [**Develop for Azure Cache for Redis**](#develop-for-azure-cache-for-redis)
      - [**Explore Azure Cache for Redis**](#explore-azure-cache-for-redis)
      - [**Configure Azure Cache for Redis**](#configure-azure-cache-for-redis)
      - [**Interact with Azure Cache for Redis by using .NET**](#interact-with-azure-cache-for-redis-by-using-net)
      - [**Exercise: Connect an app to Azure Cache for Redis by using .NET Core**](#exercise-connect-an-app-to-azure-cache-for-redis-by-using-net-core)
    - [**Develop for storage on CDNs**](#develop-for-storage-on-cdns)
      - [**Explore Azure Content Delivery Networks (CDNs)**](#explore-azure-content-delivery-networks-cdns)
      - [**Control cache behavior on Azure Content Delivery Networks**](#control-cache-behavior-on-azure-content-delivery-networks)
      - [**Interact with Azure CDNs by using .NET**](#interact-with-azure-cdns-by-using-net)

## **Create Azure App Service Web Apps**

### **Explore Azure App Service**

#### **Examine Azure App Service**

* Auto scale support: scale-in/out, scale-up/down
  * scale-in/out: Increase CPU cores/RAM
  * scale-up/down: Increase/decrease # of machines
* CI/CD Support
  * Azure DevOps, Github, Bitbucket, FTP, local Git repo
* Deployment Slots
  * <mark>App Service plan tiers</mark>: Standard, Premium, Isolated App Service
  * Live apps with own host names
  * App content and configurations can be swapped between deployment slots
* App Service on Linux
  * Native app hosting on Linus for supported app stacks
  * Run custom linux containers
    * Web app for containers
  * <mark>Supported Languages:</mark> Node.JS, Jave (JRE 8 & 11), PHP, Python, .NET core, Ruby
  * Language and supported version information
    * `az webapp list-runtimes --os-type linux`
* Limitations
  * App Service on Linux limitations:
    * App Service on Linux _not supported_ in Shared pricing tier
    * Can't mix windows and Linux apps on same App Service Plan
    * Resource Groups before Jan. 21, 2021 can not mix Windows and Linux Apps
      * _After_ Jan. 21, 2021 they can be mixed
    * AZ Portal shows only features currently working for linux apps

#### **Examine Azure App Service Plans**

In App Service, an app (web app, API, mobile) **always run in App Service plan**. App Service plans define compute resources for a web app to run. Multiple apps can be configured to run in same App Service plan (**share resources**).
<br/>
<br/>
When App Service plan is created in a region, the compute resources are created in that region.

* **Each App Service plan defines:**
  * Region
  * Number of VM instances
  * Size of VM (small, medium, large)
  * Pricing Tier
  
* **App Service pricing tiers**
  * Shared Compute
    * Both _free_ and _shared_ share resource pools with other customer apps.
    * Allocates CPU quota to each app that runs
    * Can't scale out
  * Dedicated Compute
    * _Basic, Standard, Premium, PremiumV2, and PremiumV3_ run on dedicated AZ VMs
    * Only apps in same App Service plan share compute resources
    * The higher the tier, the more VM instances available to scale-out
  * Isolated
    * Runs on dedicated AZ VMs on dedicated AZ Virtual Networks
    * Provides netowkr isolation on top of compute isolation
    * Maximum scale-out capabilities
  * Consumption
    * Only available to function apps
    * Scales dynamically depending on workload
  > 🔵**NOTE** <br/>
  > Free and Shared plans are base tiers and should be used for development and testing purposes only since they share resources with other customer apps.

* **How does my app run and scale?**
  * **Free and Shared tiers**
    * App receives CPU minutes on shared VM instance
    * Can't scale out
  * **Consumption, Dediced, Isolated tiers**
    * App runs on all VM instances configures in App Service plan
    * Multiple apps in same service plan share VM instances
    * If app has multiple deployment slots, all deployment slots run on same VM instance
    * Enabling diagnostic logs, running backups or webjobs also use CPU cycles and memory on the VM instance
  > 🔵**NOTE** <br/>
  > App Service plan is considered a _**scale unit**_ of app service apps. If plan is configured to run on 5 instances, then all apps in plan run on the five instances. If configured for auto scaling, all apps in plan are scaled out together based on the autoscale settings.

* **What if my app needs for capabilities or features?**
  * App Service plan can be scaled up or down anytime
    * May need to change pricing tier of plan to meet needs
      * Can be done any time
  * If App Service plan has many apps, might want to improve performance by isolating compute resources
    * Move app in to a separate App Service plan
  * Having many apps in same service plan may save on costs
    * Need to understand capacity of existing App Service plan and expected load for the new app since compute resources are shared
  * <mark>Isolate app in to new App Service plan when:</mark>
    * App is resource-intensive
    * Want app to scale independently of other apps
    * App needs resource in different geographical region

#### **Deploy to App Service**

* **Automated Deployment**
<br/>
Automated or _continuous_ deployment is process used to push new features and bug fixes in a fast and repetitive pattern with minimal impact on users.
* Azure Supported CD Sources
  * Azure DevOps
    * Push, build, run tests, generate release, push code to Azure Web App
  * GitHub
    * Automated deployment supported if GitHub repository is connected to Azure for automated deployment.
    * Changes made to target branch on GitHub will be automatically deployed.
  * Bitbucket
    * Same capabilities as GitHub

* **Manual Deployment**
  * Git
    * App Service web apps feature a Git URL that can be added as a remote repo. Pushing to remote will deploy app.
  * CLI
    * `webapp up` is a feature of `az` CLI that packages app and deploys it.
    * `az webapp up` can create new App Service web app if it doesn't already exist.
  * Zip deploy
    * Use `curl` or a similar HTTP utility to send a ZIP of app files to App Service
  * FTP/S
    * FTP or FTPS is  traditional way of pushing code to many hosting environments; including App Service.

* **Use Deployment Slots**
  * When possible use deployment slots when deploying a new prod build
  * _Standard App Service Plan tier or better_, deploy app to a staging environment then swap staging to production slots.
    * Swap operation warms up necessary worker instances to match prod scale
      * Eliminates down time
  
#### **Explore Authentication and Authorization in App Service**
AZ App Service provides built-in authentication and authorization support.

* **Why use the built-in authentication**
  * Provides out-of-the-box authentication with federated identity providers
    * AZ App Service allows you to integrate a variety of auth capabilities into your web app or API without implementing them yourself
    * Built directly in to the platform
      * No language, SDK, security expertise, or code required to utilize
    * Integrate with multiple login providers
      * i.e. Azure AD, Facebook, Google, Twitter
* **Identity Providers**
  | Provider | Sign-in Endpoint | How-To Guidance |
    :---|:---:|:---
    Microsoft Identity Platform | `./auth/login/aad` | [App Service Microsoft Identity Platform Login](https://learn.microsoft.com/en-us/azure/app-service/configure-authentication-provider-aad)
    Facebook | `/.auth/login/facebook` | [App Service Facebook Login](https://learn.microsoft.com/en-us/azure/app-service/configure-authentication-provider-facebook)
    Google | `/.auth/login/google` | [App Service Google Login](https://learn.microsoft.com/en-us/azure/app-service/configure-authentication-provider-google)
    Twitter | `/.auth/login/twitter` | [App Service Twitter Login](https://learn.microsoft.com/en-us/azure/app-service/configure-authentication-provider-twitter)
    Any OpenID Connect provider | `/.auth/login/<providerName>` | [App Service OpenID Connect Login](https://learn.microsoft.com/en-us/azure/app-service/configure-authentication-provider-openid-connect)
  > 🔵**NOTE**<br/>
  > When Authentication and Authorization is enabled with one of these provideres, the sign-in endpoint is available for user authentication and for validation of auth tokens from provider.
* **How it Works**<br/>
Authenticatoin and Authorization module runs in same sandbox as application code. When enabled, every incoming HTTP request passes through it before being handled by app code.
  * Module handles several things
    * Authenticates user with specified provider
    * Validates, stores, and refreshses tokens
    * Manages the authenticated session
    * Injects identity information into request headers
  > 🔵**NOTE**</br>
  > In Linux and containers the authenticate and authorization module runs in a separate, isolated container. No direct integration with specific language framework is possible because it does not run in-process.
* **Authentication Flow**
  * Flow is same for all providers
    * Differs depending on whether you want to sign in with providers SDK
  * Without Provider SDK
    * Application delegates federated sign-in to App Service
      * Typically case with browser apps
    * Server code manages sign-in process
      * Also known as _Server-directed flow_, or _Server Flow_
  * With Provider SDK
    * Application signs users in to the provider manually
      * Then submits the auth token to App Service for validation
    * Typically used in browser-less apps where a sign-in page can not be presented
    * App code manages sign-in process
      * Also known as _Client-Directed Flow_ or _Client Flow_
      * Applies to REST APIs, AZ Funcs, JS Browser clients, native mobile apps using providers SDK
  * Authentication Flow Steps (with/without provider SDK)
    * Sign user in
      * Without Provider SDK
        * Redirects client to `/.auth/login/<provider>`
      * With Provider SDK
        * Client code signs user in directly with provider's SDK and receives and authentication token. See providers documentation for more information.
    * Post-Authentication
      * Without Provider SDK
        * Provider redirects client to `/.auth/login/<provider>/callback`
      * With Provider SDK
        * Client code posts token from provider to `/.auth/login/<provider>` for validation
    * Established authenticated session
      * Without Provider SDK:
        * App Service adds authenticated cookie to response
      * With Provider SDK:
        * App Services returns its own authentication token to client code
    * Serve authenticated content:
      * Without Provider SDK:
        * Client includes authentication cookie in subsequent requests
          * Automatically handled by browser
      * With Provider SDK:
        * Client code presents authentication token in `X-ZUMO-AUTH` header
          * Automatically handled by mobile app client SDKs
    > 🔵**NOTE**</br>
    > For client browsers, App Service can automatically direct all unauthenticated users to `/.auth/login/<provider>`. Multiple providers can also be presented.
* **Authorization Behavior**</br>
In Azure portal, App Service can be configured with many behaviors when an incoming request is not authenticated.
  * Allow unauthenticated requests
    * Defers authorization of unauthenticated traffic to your app code.
    * For Authenticated requests, App Service passes along auth information in HTTP headers
    * Provides more flexibility in handling anonymous requests
    * Allows you to present multiple sign-in providers to users
  * Require Authentication
    * Will reject any unauthenticated traffic
      * Can be a redirect action to one of configured identity providers
        * In this case, browser client is redirected to `/.auth/login/<provider>` of choice.
    * If anonymous request comes from native mobile app, returned response is `HTTP 401 Unauthorized`.
      * Can configure rejection to be `HTTP 401 Unauthorized` or `HTTP 403 Forbidden` for all requests.
    > 🔴**CAUTION**</br>
    > Restricting access in this way applies to _all_ calls to your app. May not be desirable for apps wanting a publicly available home page; i.e. SPAs.

#### **Discover App Service networking features**
By default, apps in App Service are accessible directly through the internet and can reach only internet-hosted endpoints.
</br></br>
Two main deployment types of Azure App Service:
* Single-Tenant
  * App Service Environment (ASE) hosts Isolated SKU App Service plans directly in Azure virtual network
* Multi-Tenant
  * App Service plans in Free, Shared, Basic, Standard, Premium, PremiumV2, and PremiumV3 pricing SKUs.

* **Multi-Tenant App Service networking features**</br>
  * Azure App Service is a distributed system
  * _**Front ends**_ are roles that handle incoming HTTP/S requests
  * _**Workers**_ are roles that host customer workloads
  * All roles in App Service deployment exist in multi-tenant network
    * Because of this, App Service can not connect directly to your network
  * Features that _handle requests to_ your app **can't** be used to solve problems when _making calls from app_.
    * And vice verse, features that solve problems for calls from your app can't be used to solve problems to your app.
    
    | Inbound features | Outbound features |
    :--|:--
    | App-assigned addresses | Hybrid Connections |
    | Access restrictions | Gateway-required virtual network integration |
    | Service endpoints | Virtual network integration |
    | Private Endpoints | |
  * Can mix features to solve problems; with a few exceptions.
    * Inbound usecase example for App Service networking to control traffice inbound to app
    
    | Inbound Features | Outbound Features |
    |:--|:--|
    | Suport IP-based SSL needs for app | App-assigned addresses |
    | Support unshared dedicated inbound address for app | App-assigned address |
    | Restrict access to app from well-defined addresses | Access restrictions |
* **Default Networking Behavior**
  * Free and Shared SKU plans host plans on multitenant workers
  * Basic and higher plans host workloads dedicated to only one App Service plan
  * Standard App Service plan runs all apps on same worker
    * If worker scaled out, all apps in App Service plan will be replicated to new worker for each instance in App Service plan
  * **Outbound Addresses**
    * Changing VM family (pricing tiers) creates different set of outbound addresses
      * Only affects Standard to PremiumV2 and PremiumV2 to PremiumV3 VM family changes
      * Some older scale units cause both inbound and outbound addresses to change when scaling from Standard to PremiumV2
    * Outbound addresses are listed in properties of app
      * These addresses are shared by all apps in App Service deployment
    * To see all addresses app might use in a scale unit, there is a property called `possibleOutboundIpAddresses` that will list them
  * **Find outbound IPs**
    * **Azure Portal**
      * View app Properties
    * **Cloud Shell**
       ```shell
       az webapp show /
         --resource-group <group_name> /
         --name <app_name> /
         --query outboundIpaddresses /
         --output tsv
       ```
    * **All possible regardless of tier**
      ```shell
      az webapp show /
        --resource-group <group_name> /
        --name <app_name> /
        --query possibleOutboundIpAddresses /
        --output tsv
      ```
* **Exercise: Create a static HTML web app by using AZ CloudShell**</br>
Deploy a basic HTML+CSS site to Azure App Service using `az webapp up`.
  * **Setup instructions for Azure CloudShell**
    * `mkdir htmlapp`
    * `cd htmlapp`
    * `git clone https://githib.com/Azure-Samples/html-docs-hello-world.git`
    * `resourceGroup=$(az group --list query "[].{id:name}" -o tsv)`
    * `appName=az204app$RANDOM`
  * **Create web app**
    * `cd html-docs-hello-world`
    * `az webapp up -g $resourceGroup -n $appName --html`
    * When command finishes, visit app URL `https://<myAppName>.azurewebsites.net`
  * **Update and redeploy**
    * `code index.html`
    * Change `h1` heading to _Azure App Service Updated_
    * `ctrl-s` then `ctrl-q` to save and quit code
    * `az webapp up -g $resourceGroup -n $appName --html`
    * Refresh browser when deployment finishes

### **Configure Web App Settings**

#### **Configure Application Settings**</br>
App settings are variables passed as environment variables to app code. for Linux apps and custom containers, App Services uses the `--env` flag to set environment variables in container.
</br>
</br>
For _ASP.NET_ and _ASP.NET CORE_, setting app settings in App Service is like setting them in `<appSettings>` in `Web.config` or `appsettings.json`.
</br>
</br>
> 🔵**NOTE** </br>
> App settings are always encrypted when stored (encrypted-at-rest)

* **Adding and Editing Settings**
  * From Azure Portal, when in `App Service > Configuration > Application settings` click _New application setting_
    * If desired, specify deployment slot for app setting
  > 🔵**NOTE**</br>
  > Default or custom linux containers, nested JSON key structure (`ApplicationInsights:InstrumentationKey`) in appsetting needs to be configured in app service as `ApplicationInsights__InstrumentationKey`. Any `:` should replaced by `__` (double underscore)

* **Editing Application settings in bulk**
  * From Azure Portal, when in `App Service > Configuration > Application settings`, select _Advanced_, make edits, click _Update_.
    * App settings have JSON structure as
        ````JSON
        [
            {
                "name": "<key-1>",
                "value": "<value-1>",
                "slotSetting": false
            },
            {
                "name": "<key-2>",
                "value": "<value-2>",
                "slotSetting": false
            },
            ...
        ]
        ````
* **Configure connection strings**
  * For .NET and .NET core devs, values set in App Service override values in _web.config_.
    * Other language stacks it's better to use app settings instead since conn strings require special formatting in variable keys
  * Always encrypted when stored (encrypted-at-rest)
  > 🟢**TIP** </br>
  > One case where you may want to use connection strings instead of app settings for non-.NET languages: certain Azure database types are backed up along with the app only if you configure a connection string for the database in your App Service
  * Adding/Editing connection strings follow the same principles as other app settings
    * Can also define a slot setting
  * Connection strings follow the JSON format of:
    ````JSON
    [
        {
            "name": "name-1",
            "value": "conn-string-1",
            "type": "SQLServer",
            "slotSetting": false
        },
        {
            "name": "name-2",
            "value": "conn-string-2",
            "type": "PostgreSQL",
            "slotSetting": false
        },
        ...
    ]
    ````

#### **Configure general settings**</br>
Can configure some common settings in `Configuration > General settings`. Some require higher pricing tiers.
* **Available settings**
  * Stack Settings
    * Software stack to run app
      * SDK versions, language, etc...
    * Linux apps and custom container apps let you set optional start-up command or file
  * Platform settings
    * Configure settings for hosting platform
    * Bitness
      * 32 or 64-bit
    * WebSocket Protocol
      * for .NET SignalR or socket.io for example
    * Always On
      * Keep app loaded when no traffic
      * Disabled by default
      * Required for continuous WebJobs or WebJobs triggered on CRON expressions
    * Managed pipeline version
      * IIS pipeline mode
      * Set to classic for legacy apps
    * HTTP Version
      * Set to 2.0 for HTTPS/2 protocol support
    * ARR Affinity
      * in multi-instance deployments, ensure client is routed to same instance for life of session
      * Can set to _Off_ for stateless applications
    * Debugging
      * Enable remote debugging for .NET, .NET Core, or Node.js apps
        * Automatically disabled after 48 hours
    * Incoming client certificates
      * require client certificates in mutual authentication
      * TLS mutual authentication is used to restrict access to app by enabling different types of authentication for it

#### **Configure Path Mappings**
Found in `App Service > Configuration > Path mappings`. Allows you to configure handler mappings, and virtual application and directory mappings. Different options display based on OS type.
* **Windows apps (Uncontainerized)**
  * Can customize IIS handler mappings and virtual applications and directories
  * Handler mappings let you add custom script processors to handle requests for specific file extensions
  * Select `New handler` to configure a new handler
    * Extension
      * file extension you want to handle (i.e. `*.php`, `handler.cfgi`, etc...)
    * Script processor
      * Absolute path of script processor
        * `D:\home\site\wwwroot` to refer to apps root directory
    * Arguments
      * optional command-line arguments for script processor
  * To mark a virtual directory as a web application, clear the _Directory_ check box
* **Linux and containerized apps**
  * Can add custom storage for containerized apps
  * Containerized apps include all Linux apps and also Windows and Linux custom containers running on App Service
  * Click _New Azure Storage Mount_ to configure custom storage
    * **Name**: Display Name
    * **Configuration Options**: Basic or Advanced
    * **Storage type**: _Azure Blobs_ or _Azure Files_
      * Windows container apps only support Azure Files
    * **Storage container**: For basic configuration, the container you want
    * **Share name**: For advanced config, the file share name
    * **Access key**: For advanced config, the access key
    * **Mount path**: absolute path in container to mount custom storage

#### **Enable Diagnostic Logging**
  * Built-in diagnostics to assist with debugging App Service app
  * Types of logging, supported platforms, and log location
    | Type | Platform | Location | Description |
    |:--|:--|:--|:--|
    |Application Logging|Windows,Linux|App Service file system and/or Azure Storage blobs|Logs messages generated by your app code. Messages can be generated by web framework, or from app code directly using standard logging pattern. Messages assigned on of following categories: `Critical`, `Error`, `Warning`, `Info`, `Debug`, `Trace`.
    |Web Server Logging|Windows|App Service file system or Azure Storage blobs|Raw HTTP request data in W3C format. Messages includes HTTP Method, resource URI, client IP, client port, user agent, response code, etc...|
    |Detailed error logging|Windows|App Service file system|Copies of _.html_ error pages that have been sent to client browser. Detailed error pages should not be sent in production environments. App Service can save the error page each time an app error occurs that has HTTP status code >= 400|
    |Failed request tracing|Windows|App Service file system|Detailed training info on failed requests. Includes trace of IIS components used and time taken in each component. One folder generated for each failed request and contains XML log file and XSL stylesheet to view log file with|
    |Deployment logging|Windows,Linux|App Service file system|Helps determine why a deployment failed. Deployment logging happens automatically and has no configurable settings|
* **Enable application logging (Windows)**
  * Navigate to app in Portal and select _App Service logs_
  * Select _On_ for either _Application Logging (Filesystem)_ or _Application Logging(Blob), or both.
    * File system option is automatically disabled after 12 hours
  * Set _Level_ to desired logging
  * _Save_
* **Enable application logging (Linux)**
  * In _App Service logs_ set _Application logging_ to _File System_
  * In _Quota (MB)_ specify disk quota
  * In _Retention Period (Days)_ set number of days to retain logs
  * _Save_
* **Enable web server logging**
  * For _Web server logging_, select _Storage_ for blob storage or _File System_ to store logs in App Service FS
  * In _Retention Period (Days)_ set number of days to retain logs
  * _Save_
* **Stream Logs**
  * Before streaming logs in realtime, set log type you want.
    * Any files ending in .txt, .log, or .htm that are stored in /LogFiles (d:/home/logfiles) is streamed by App Service
  > 🔵**NOTE**</br>
  >  Some logging buffers writes to the log file so events may be received out of order when streaming logs
  * Azure Portal
    * Navigate to app and select _Log stream_
  * Azure CLI
    * `az webapp log tail --name appname --resource-group myResourceGroup`
  * Local console
    * `az login`
    * `az webapp log tail --name appname --resource-group myResourceGroup`
* **Access log files**
  * Azure Storage blob for log storage
    * Need a client tool that works with Azure Storage
  * App Service Filesystem for log storage
    * Linux/Container apps: `https://<app-name>.scm.azurewebsites.net/api/logs/docker/zip`
    * Windows apps: `https://<app-name>.scm.azurewebsites.net/api/dump`
  * Linux/container apps log zip file contains console output for both docker host and docker container
  * For scaled-out apps, zip file contains set of logs for each instance
  * In App Service file system, these log files are contents of `d:/home/logfiles`

#### **Configure Security certificates**
A certificate uploaded into an app is stored in a deployment unit that is bound to the App Service plan's resource group (_webspace_). This makes the certificate accessible to other apss in same RG and Region.

| Option | Description |
|:--|:--|
|Create a free App Service managed certificate|A free and private certificate. Easy to use if custom domain in App Service needs to be secured.
|Purchase an App Service certificate|Private certificate managed by Azure. Combines simplicity of automated certificate management and flexibility of renewal/export options|
|Import certificate from Key Vault|Useful if Azure KV is used to manage certs|
|Upload private cert|If you already have a private cert from a third-part provider|
|Upload a public cert|Public certs are not used to secure custom domains, but can load them in to your code if needed to access remote resources|

* **Private Certificate Requirements**</br>
Free App Service managed cert and App Service cert already satisfy requirements of App Service.
  * Exported as password-protected PFX file
  * Encrypted using triple DES
  * Contains private key at least 2048 bits long
  * Contains all intermediate certs in the cert chain

  To secure custom domain in a TLS binding, additional requirements:
  * Contains an Extended Key Usage for server auth (OID = 1.3.6.1.5.5.7.3.1)
  * Signed by a trusted cert authority
</br></br>
* **Creating free managed certificate**</br>
To create custom TLS/SSL bindings or enable client certs for App Service app, App Service plan must be in _Basic, Standard, Premium, or Isolated_ tier.
</br>

  Turn-key solution for securing custom DNS name in App Service. TLS/SSL server cert fully managed by App Service, renewed continously and automatically in six-month intervals, 45 days before expiration.
</br>

  **Limitations**:
  * Wildcard certs not supported
  * Does not support usage as a client cert by cert thumbprint
  * Not exportable
  * Not supported in App Service Environment (ASE)
  * Not supported with root domains integrated with Traffic Manager
  * If cert is for CNAME-mapped domain, CNAME must be mapped directly to `<app-name>.azurewebsites.net`
</br></br>
* **Import an App Service Certificate**</br>
If App Service Certificate purchased from Azure, the following tasks are managed:
  * Purchase from GoDaddy
  * Domain verification of cert
  * Maintains cert in Azure KV
  * Manages cert renewal
  * Syncs cert automatically with imported copies of App Service apps
  
  If already have a working App Service cert, you can:
  * Import cert into App Service
  * Manage cert
    * renew, rekey, export
</br></br>
* **Upload a private certificate**</br>
If certificate authority gives multiple certs in cert chain, they need to be merged in order. Then you can Export merged TLS/SSL cert with private key that cert request was generated with.
  * If cert generated using OpenSSL, then a private key file was generated.
  * To export to PFX: `openssl pkcs12 -export -out myserver.pfx -inkey <private-key-file> -in <merged-cert-file>`
  * Define export password when prompted
    * This will be used when uploading TLS/SSL cert to App Service

* **Enforce HTTPS**</br>
By default, app is accessible using HTTP.
  * Enable _HTTPS Only_
    * `App Service > TLS/SSL settings > Bindings > HTTPS Only: On`

#### **Manage App Features**
* Basically just feature flags
* **Basic Concepts**
  * Feature Flag
    * Variable with binary state (on/off)
    * Has associated code block
      ```CS
      if(featureA)
      {
        // Do this
      }
      ````
  * Feature Manager
    * Application package that handles lifecycle of all feature flags
    * Typically provides additional functionality such as caching feature falgs and updating states
  * Filter
    * Rule for evaluating state of feature flag
      * User group, device or browser type, geographic location, and time window are examples of what a filter can represent
* **Feature Flag declaration**
  * If feature flag has multiple filters, they are traversed in order
    * when flag is turned "on", remaining filters are skipped
  * Feature manager supports _appsettings.json_ as a configuration source
    ```JSON
        "FeatureManagement": {
        "FeatureA": true, // Feature flag set to on
        "FeatureB": false, // Feature flag set to off
        "FeatureC": {
            "EnabledFor": [
            {
                "Name": "Percentage",
                "Parameters": {
                    "Value": 50
                    }
                }
            ]
        }
    }
    ````
* **Feature Flag Repository**
  * To use FF's effectively, should externalize all flags used in app
    * Allows you to change FF states without modifying/redeploying app
  * Azure App Configuration is designed to be a centralized repo for FF's
    * Use it to define different FF's and manipulate FF state
    * Can use App Configuration libraries to easily access FF's of app

### **Scale Apps in Azure**
Enables system to adjust the resources required to meet varying demand in users, while controlling the costs associated with resources. Can use autoscaling with many Azure services, including web apps. Requires rules be configured for scale trigger conditions.

#### **Examine autoscale factors**
* Can be triggered by a schedule or by system resources
  * CPU utilization
  * memory occupancy
  * \# of requests
  * Some combination of factors
* **What is Autoscaling**
  * Performs scaling _in/out_ based on demand
* **Azure App Service Autoscaling**
  * Autoscaling monitors resource metrics of web app as it runs
  * Detects situations where additional resources are required to handle additional workload and ensures resources are available before system is overloaded
    * Adds/Removes web servers and balancing load
    * No affect on CPU power, memory, or storage
  * Only changes number of web servers
* **Autoscaling Rules**
  * Decisions based on rules defined by you
  * Rule specifies threshold for a metric and triggers autoscale event
  * Define rules carefully
    * A DoS attack could trigger autoscaling resulting in unneccessary costs
      * Would want to implement detection and filtering of requests in this use case
* **When should you consider autoscaling**
  * Any time workload can't be predicted in advance
  * When workload likely to vary by date (i.e. holidays, pay day, etc...)
  * May not be suitable for resource intensive processing since a single request could exhaust all resources
  * Number of instances is also a factor
    * May only need X instances most of the time
      * Fewer number of initial instances = less capacity and could lead to downtime while autoscaling spins up additional instances

#### **Identify autoscale factors**
Specify conditions underwhich the app should scale-out and scale-in. Each scale-out rule should have a corresponding scale-in rule.
* **Autoscaling and the App Service plan**
  * App Service plan has instance limit to prevent autoscale runaway
  * The more expensive a plan, the higher the instance count limit
  > 🔵**NOTE**</br>
  > Not all App Service Plan pricing tiers support autoscaling 
* **Autoscale Conditions**
  * Two options for autoscaling
    * Metric based - i.e. disk queue length, http requests waiting, etc...
    * Schedule based - time of day, specific date/day of week
      * Can specify an end date and system will scale back in
  * Can define combination of metric + schedule based autoscaling in same autoscale condition
    * Scale out if number of HTTP requests exceeds threshold but only between hours X and Y
  * App Service Plan has a default condition that is used if no other conditions are applicable.
    * Always active, no schedule
* **Metrics for Autoscale rules**
  * CPU Percentage
    * Metric is an indication of CPU utilization across all instances
      * High value shows instances are becoming CPU-bound and could cause delays in processing
  * Memory Percentage
    * Metric captures memory occupancy of application across all instances
    * High value indicates free memory could be running low
      * Could cause one or more instances to fail
  * Disk Queue Length
    * Measure of outstanding I/O requests across all instances
      * High value means disk contention could be occurring
  * HTTP Queue Length
    * Metric of how many clients have pending requests
      * Large number could result in HTTP 408 (Timeout) errors
  * Data In
    * Metric of numer of bytes received across all instances
  * Data Out
    * Metric of number of bytes sent by all instances
  * Other Azure Services
    * Could use Service Bus Queue as a trigger if queue length exceeds critical length
* **How an autoscale rule analyzes metrics**
  * Analyzes trends in metric values over time across all instances
  * Multi-step process
    1. rule aggregates values of a metric across all instances for a period of time (_time grain_). Each metric has own intrinsic time grain, generally 1 minute. Aggregated value is known as _time aggregation_. Options available are `Average, Minimum, Maximum, Sum, Last, Count`
    2. Since 1 minute is not enough granularity to determine whether the metric change is long-lasting, the rule performs a further aggregation calculated by the _time aggregation_ over a longer user specified period, aka (_duration_). Minimum _duration_ = 5 minutes. If the _duration_ = 10 minutes, autoscale rule will aggregate the 10 values calculated for the _time grain_.
  * **Example**
    * _duration_ = 10 minutes
    * _time grain_ = 1 minute (default)
    * _metric_ = CPU Percentage
    * _time grain statistic_ = Maximum
    * Every minute, the CPU Percentage is aggregated. If the Maximum over 10 reads is greater than the threshold, the rule is triggered.
* **Autoscale Actions**
  * Autoscale action uses an operator such as >, <, >=, etc...
  * Action can be _scale-in_ or _scale-out_
    * _scale-out_ increases \# of instances
    * _scale-in_ decreases \# of instances
  * Action can be specific \# of instances
    * i.e. if threshold reached, scale to 15. If under threshold, scale to 5
  * Minimum cool down period is 5 minutes
    * Scale rule won't be triggered during this time period
* **Pairing autoscale rules**
  * A scale-out rule should have a corresponding scale-in rule
* <mark>**Combining autoscale rules**</mark>
  * Single autoscale condition can contain many rules
    * scale-out is performed if any rule is true
    * scale-in is only performed if _all_ the conditions are true
#### **Enable autoscale in App Service**
* Autoscale can be found in the App Service under _Settings > Scale out (App Service plan)_
  * To define metrics, use _Custom autoscale_ option
* **Create Scale Rules**
  * metric-based scale conditions contain one or more scale rules
  * autoscale rule triggers can use _metrics, aggregations, operators, and thresholds_
  * Monitor scale-out/in activity in the _Run history_ tab of the _Scale out_ blade menu
    * Shows when it was triggered and what condition caused the scaling
#### **Explore autoscale best practices**
* **Autoscale Concepts**
  * scales horizontally
  * reads associated metric to scale by and checks if configured threshold has been met to scale-in/out
  * Thresholds calculated at an instance level
    * If metric is to scale-out when CPU > 80% and there are 2 instances, then the CPU needs to be > 80% across both instances
  * Scaling success/failures are logged to Activity Log
    * Can configure activity log alert to be notified via SMS, Email, or webhook
* <mark>**Autoscale Best Practices**</mark>
  * Verify Max and Min values are different with adequate margins
  * Choose appropriate diagnostic for metric
    * Most common is Average
  * Choose thresholds carefully for all metric types to avoid _flapping_
    * Flapping occurs when metrics are too similar (or close) and causes scale-in/out behavior in rapid succession
    * Example:
      ```
      == Rules in place ==
      1. Increase instances by 1 when Thread Count >= 600
      2. Decrease instances by 1 when Thread Count <= 600

      == Scenario ==
      1. 2 instances with avg thread count 625
      2. Autoscale triggers and adds third instance
      3. Average thread count drops to 575 per instance
      4. Autoscale tries to estimate what the final state will be if scale-in is triggered.
      4.a 575 threads x 3 instances = 1725
      4.b 1725 / 2 (if scaled in) = 862.5 threads
      4.c Because 862.5 > 625, it would immediately scale-out
      5. To avoid flapping, autoscale doesn't scale in at all. The condition is skipped an evaluated the next time the service's job executes
      ```
    * Estimation during scale-in is intended to avoid flapping situations
  * Should use an adequate margin in the thresholds to prevent flapping
* **Considerations for scaling when multiple rules are configured**
  * _scale-out_ - runs if _**any**_ rule is met
  * _scale-in_ - runs if _**all**_ rules are met
* _Always select a safe default instance count_
  * Autoscale scales service to this count when metrics aren't available
* **Configure autoscale notifications**
  * Activity Log will contain entries for:
    * scaling occurs
    * Autoscale Succeeds/Fails
    * Metrics aren't available for autoscale to make a scale decision
    * Metrics are available (recovery) again to make a scale decision

### **Explore Azure App Service deployment slots**
Deployment slot functionality is a powerful tool that enables you to preview, manage, test, and deploy different development environments
#### **Explore Staging Environments**
* Available only to _**Standard, Premium, or Isolated**_ App Service tiers
* Deployment slots are live apps with own hotnames
* App Content and Configurations can be swapped between deployment slots
* Benefits of deploying to non-production slot:
  * Validate app changes in staging slot first
  * Deploying app to slot first and swapping in to production avoids warm-up and downtime
    * Traffic redirection is seamless
    * No requests will be dropped because of the swap
    * Can be automated if pre-swap validation not required
  * After a swap, the previously staged app now has previous production app
    * Can perform the same swap to "roll back" app
* Staging Slots available 
  | Plan Tier | \# of Slots |
  |:--|:--:|
  | Free | 0 |
  | Shared | 0 |
  | Basic | 0 |
  | Standard | 5 |
  | Premium(V1-V3) | 20 |
  | Isolated | 20 |
#### **Examing Slot Swapping**
* App Service performs the following to ensure no downtime
  1. Apply settings from target slot to source slot to all instances of source slot
     * Slot-specific app settings and connection strings if applicable
     * Continuous deployment settings if enabled
     * App Service authentication settings if enabled  
   2. Wait for instances of source slot to restart
      * If any instance fails to restart, swap operation reverts all changes to source slot and stops
   3. If local cache is enabled, triggers local cache initialization by making HTTP request to app root ("/") on each instance of source slot and waits for each instance to return any HTTP response
      * Local cache initialization triggers a restart on each instance
    4. If auto-swap enabled with custom warm up, trigger App Initiaition by making HTTP request to app root on each instance of source slot
       * If `applicationInitialization` isn't specified, trigger HTTP request to app root of source slot on each instance
       * Is instance returns any HTTP response, it's considered warmed up
    5. If all instances are successful, swap the two slots by switching routing rules for the two slots
       * After this, the target slot now has the app that was previously warmed up in the source slot
    6. Source slot has the pre-swap app and applies settings and restarts instances
* Settings that are changed in a swap
  |Settings that are swapped|Settings that aren't swapped|
  |:--|:--|
  |General settings; i.e. framework version, 32/64-bit, web sockets|publishing endpoints|
  |App settings (can be configured to stick to a slot)|Custom comain names|
  |Connection strings (can be configured to stick to a slot)|Non-public certificates and TLS/SSL settings|
  |Handler mappings|Scale settings|
  |Public certificates|WebJobs schedulers|
  |WebJobs content|IP restrictions|
  |Hybrid connections <sup>1</sup>|Always On|
  |VNET integration <sup>1</sup>|Diagnostic log settings|
  |Service endpoints <sup>1</sup>|CORS|
  |Azure CDN <sup>1</sup>||
  <small>1. features are planned to be unswapped</small>
  > 🔵**NOTE**</br>
  > To make settings swappable, add app setting `WEBSITE_OVERRIDE_PRESERVE_DEFAULT_STICKY_SLOT_SETTINGS` in every slot of the app and set its value to `0` or `false`. All settings are swappable or none of them. Managed identities are never swapped and are not affected by this override app settings.
* To configure app setting or connection string to stick to a specific slot (not swapped), got to _**Configuration**_ page and select _**Deployment slot setting**_
  * Selecting checkbox tells App Service that the setting is not swappable
#### **Swap Deployment Slots**
* Deployment slots can be swapped on app's _Deployment slots_ page and _Overview_ page
  * Always verify: 
    * Target slot is correct
    * Settings in source slot are configured correctly for target slot
* **Manually swapping deployment slots**
  1. Go to app's _**Deployment slots**_ page > _**Swap**_. _Swap dialog box_ shows settings in source and target that will be changed
  2. Select _**Source**_ and _**Target**_ slots. Review the _**Source Changes**_ and _**Target Changes**_ to verify configuration changes are correct/expected. Select _**Swap**_ to perform the swap
  3. _Close_ dialog box when finished
* **Swap with Preview (multi-phase swap)**</br>
Validate the app runs with swapped settings before swapping to target slot. When performing a swap with preview, App Service performs the same swap operation but pauses after first step. You can then verify the result on staging slot prior to completing the swap.
  * Cancelling the swap with preview restores configuration elements to the source slot
  1. Follow [Manually swapping deployment slots](#), but select _**Perform swap with preview**_. Dialog box shows how configuration in source slot and destination slot change in Phase 1.
  2. When ready to start swap, select _**Start Swap**_
     * When phase 1 finishes, you're notified in the dialog box. Preview the swap in the source slot by going to `https://<app_name>-<source-slot-name> .azurewebsites.net`
  3. When ready to complete pending swap, select _**Complete swap**_ in _Swap action_ and select _**Complete**_ (alternatively, select _**Cancel swap**_ if desired) 
* **Configure auto swap**</br>
  Auto swap streamlines Azure DevOps scenarios for continuous deployment with zero cold starts and zero downtime. When auto swap is enabled from a slot into production, every time you push your code changes to that slot, App Service automatically swaps the app into production after it's warmed up in the source slot.
  > 🔵**NOTE**</br>
  > Auto swap is not currently supported in Web Apps for Linux
  * **Configure Auto Swap**
    * Go to App's resource page and select the deployment slot you want to configure to auto swap. The setting is on _**Configuration > General Settings**_ page
    * Set _**Auto swap enabled**_ to _On_
    * Select desired target slot > _**Save**_
    * Push code to source slot, auto swap happens after a short period and update is reflected in target slots URL
* **Specify custom warm-up**
* `applicationInitialization` configuration element in web.config allows custom intialization actions to be defined.
  ```XML
  <system.webServer>
    <applicationInitialization>
        <add initializationPage="/" hostName="[app hostname]" />
        <add initializationPage="/Home/About" hostName="[app hostname]" />
    </applicationInitialization>
  </system.webServer>
  ```
* Troubleshooting - [Most common deployment slot swap failures and how to fix them](https://ruslany.net/2017/11/most-common-deployment-slot-swap-failures-and-how-to-fix-them/)
* Customize warm-up behavior with one or both of the following app settings
  * `WEBSITE_SWAP_WARMUP_PING_PATH` - Path to ping to warm up site.
    * Add app setting by specifying custom path that begins with `/` (i.e. `/health`, default is `/`)
  * `WEBSITE_SWAP_WARMUP_PING_STATUSES` - Valid HTTP rtesponse codes for the warm-up operation
    * Comma separated list of HTTP codes(i.e. `200,201,202,204`)
    * If response code is not in the provided codes, swap operations are stopped
    * By default, all response codes are valid
* **Rollback and monitor a swap**
  * If errors occur in target slot after a swap, swap the same two slots
  * If swap takes a long time to complete, get information from _Activity log_
  * Swap operation appears in log query as `Swap Web App Slots`
    * Expand and select one of suboperations or errors to see details
#### **Route Traffic in App Service**
By default, all client requests to apps prod URL are routed to production slot. Can route portion of traffic to another slot. Useful for user feedback of new updates, A/B testing, etc...
* **Route production traffic automatically**
  1. Go to apps resource page and select _**Deployment slots**_
  2. In _**Traffic %**_ column of target slot, specify a percentage between 0 and 100, select _Save_
     1. After set, specified percentage of clients is randomly routed to non-prod slot
     2. After client is routed to specific slot, session is "pinned" to that slot for lifetime of client session
     3. View the `x-ms-routing-name` cookie in headers to see which slot
        1. If routed to "staging" cookie has `x-ms-routing-name=staging`
        2. Request routed to production slot the cookie is `x-ms-routing-name=self`
* **Route production traffic manually** 
  App Service can route requests to a specific slot. This is useful when giving users ability to opt-in or opt-out of beta features. To route manually, use the `x-ms-routing-name` query parameter
  * For example, to opt users out of beta app
    ```HTML
    <a href="<webappname>.azurewebsites.net/?x-ms-routing-name=self">Go back to production app</a>
    ``` 
    * After client browser accesses the link, it's redirected to production slot.
      * All subsequent requests will contain `x-ms-routing-name=self` cookie that pins session to production slot
  * To opt users in to beta, change the path to
    ```HTML
    <a href="<webappname>.azurewebsites.net/?x-ms-routing-name=staging">Try the beta!</a>
    ```
  * By default new slots are given a routing rule of `0%`. If it's a default, it is grey. Explicitly set values are shown in black.
    * This is useful for hiding different slots as traffic will not be directed automatically
      * Allow internal teams access by specifying the `x-ms-routing-name=<slot>` query parameter

## **Implement Azure Functions**
### **Explore Azure Functions**
#### **Discover Azure Functions**</br>
Azure functions are a great solution for processing data, integrating systems, IoT, simply APIs and Microservices. Consider Functions for tasks like image or order processing, file maintenance, or for scheduled tasks.

Azure Functions supports _triggers_ (ways to start execution of code) and _bindings_ (simplify coding for input/out of data).
* **Compare Azure Functions and Azure Logic Apps**
  * Azure Functions
    * Serverless compute service
  * Azure Logic Apps
    * Serverless workflows
  * Both Functions and Logic Apps can create complex orchestrations
    * Orchestrations are collection of functions or steps (_actions_ in logic apps) that execute to accomplish a complex task
  * Can call Functions from Logic Apps, and Logic Apps from Functions
  
    | | Azure Functions | Logic Apps |
    |:--|:--|:--|
    |**Development**|Code-first (imperative)|Designer-first (declarative)|
    |**Connectivity**|About a dozen built-in binding types, write code for custom bindings|Large collection of connectors, Enterprise Integration Pack for B2B scenarios, build custom connectors|
    |**Actions**|Each activity is an Azure function; write code for activity functions|Large collection of ready-made actions|
    |**Monitoring**|Azure Application Insights|Azure portal, Azure Monitor logs|
    |**Management**|REST API, Visual Studio|Azure portal, REST API, PowerShell, Visual Studio|
    |**Execution Context**|Can run locally or in cloud|Supports run-anywhere scenarios|
* **Compare Functions and WebJobs**
  Azure App Service WebJobs with the WebJobs SDK is a code-first integration service designed for developers. Both built on Azure App Service and support features such as source control integration, authentication, and monitoring with App Insights

  Azure Functions are _built on WebJobs SDK_ so it shares many of same event triggers and connections to other Azure services.
  * Factors to consider when choosing between Azure Functions and WebJobs with WebJobs SDK
    ||Functions|WebJobs with WebJobs SDK|
    |:--|:--|:--|
    |Serverless app model with automatic scaling | Yes | No |
    |Develop and test in browser | Yes | No |
    |Pay-per-use pricing | Yes | No |
    |Integration with Logic Apps | Yes | No |
    |Trigger events | Timer</br>Azure Storage queues and blobs</br>Azure Service Bus queues/Topics</br>Azure Comsos DB</br>Azure Event hubs</br>HTTP/WebHook(GitHub, Slack)</br>Azure Event Grid | Timer</br>Azure Storage queues and blobs</br>Azure Service bus queues/topics</br>Azure Comsos DB</br>Azure Event Hubs</br>File system|
  > 🔵**NOTE**</br>
  > Azure Functions offer more dev productivity than App Service WebJobs. Functions also offer more languages, development environments, Azure service integrations, and pricing.</br></br>_Azure Functions is the best choice in most scenarios_
#### **Compare Azure Functions hosting options**
* Three basic hosting plans available for Azure Functions (Linux and Windows VMs)
  * Consumption
  * Premium
  * Dedicated
* Hosting plan chosen dictates following behaviors
  * How function app is scaled
  * Resources available to each function app instance
  * Support for advanced functionality, i.e. Azure Virtual Network connectivity
* **Benefits of hosting plans**
  |Plan|Benefit|
  |:--|:--|
  |**Consumption Plan**|Default hosting plan. Scales automatically. Pay only for what is used. Function host instances added/removed based on \# of incoming requests|
  |**Premium Plan**|Auto sclaes based on demand using pre-warmed workers. More powerful instances. Connects to Virtual Networks|
  |**Dedicated Plan**|Run functions in App Service plan at regular App Service plan rates. Best for long-running scenarios where Durable Functions can't be used|
* **Other Hosting Options** provider highest amount of control and isolation for function apps
  |Hosting Option|Details|
  |:--|:--|
  |App Service Environment (ASE)|[App Service Environment](https://learn.microsoft.com/en-us/azure/app-service/environment/intro) is an App Service feature that provides a fully isolated and dedicated environment for securely running App Service apps at high scale|
  |Kubernetes|Kubernetes provides a fully isolated and dedicated environment running on top of Kubernetes platform. [Azure Functions on Kubernetes with KEDA](https://learn.microsoft.com/en-us/azure/azure-functions/functions-kubernetes-keda)
* **Always On**
  * If running on a _Dedicated plan_, this should be turned on
    * Apps not on a _Consumption plan_ go idle after a few minutes of inactivity and only HTTP triggers will "wake up" the function
  * _Consumption plan_ activates function apps automatically
* **Storage Account Requirements**
  * Function apps require general Azure Storage account
    * which supports Blob, Queue, Files, and Table storage
  * Functions rely on AZ Storage for ops such as managing triggers and logging function executions
  * Storage accounts that do not support queues/tables are filtered from _Storage Account_ selection when creating a function app
    * Blob only storage accounts (including premium) are excluded
    * General purpose storage accounts with zone-redundant storage replication are excluded
  * Same storage account used by function app can be used by triggers and bindings to store app data
    * storage-intensive operations should use a separate storage account
#### **Scale Azure Functions**
* _Consumption_ and _Premium_ plans - CPU and Memory resources are scaled by adding additional instances of Functions host
  * Number of instances is determined on the number of events that trigger a function
  * _Consumption Plan_ limited to 1.5 GB of memory and 1 CPU for each instance
    * An instance is the entire function app
    * All functions in function app share resources within an instance and scale at the same time
    * Function apps that share the same consumption plan scale independently
  * _Premium Plan_ - plan size determines available memory and CPU for all apps in that plan on that instance
  * Function code is stored on _Azure Files_ on functions main storage account
    * <mark>Deleting main storage account deletes functions code files and are not recoverable</mark>
* **Runtime Scaling**
  * _Scale Controller_ monitors rate of events and determines whether to scale-out/in
    * Uses heuristics for each trigger type
    * Example: Azure Queue storage trigger scales based on queue length and age of oldest queue message
  * _Unit of Scale_ for Azure Functions is the function app
    * When scaled out, additional resources are allocated to run multiple instances of Azure Functions host
    * Vice-verse for scale-in
      * \# of instances can eventually reach 0 if no functions are running within a function app
        * If this happens, the first request to the function will incur a _cold start_ latency caused by scaling from 0 to 1
* **Scaling behaviors**
  * Scaling vaaries on a number of factors and acts differently based on the trigger and language
  * Scaling behaviors to be aware of
    |||
    |:--|:--|
    |**Maximum Instances**|Single function app only scales out to a max of 200 instances. A single instance may process more than one message or request at a time. No set limit on number of concurrent executions|
    |**New instance rate**|_HTTP triggers_, new instaces are allocated, at most, once per second. </br>_Non-HTTP triggers_, new instances are allocated, at most, once every 30 seconds|
* **Azure Functions scaling in an App Service plan**</br>
  In App Service plan, can manually scale out by adding more VM instances. Can also enable _autoscale_. _Autoscale_ is slower than elastic scale of _Premium plan_.
  * _App Service plan_ is best choice when predictive scaling and costs are required

### **Develop Azure Functions**
#### **Explore Azure Functions development**
* **Functions contain two important pieces**
  * Code - variety of languages supported
  * Config - _function.json_ file
    * In compiled languages, this file is auto-generated from annotations in the code
    * Scripting languages - _function.json_ must be supplied
  * Example _function.json_ file
    ```JSON
    {
        "disabled":false,
        "bindings":[
            // ... bindings here
            {
                "type": "bindingType",
                "direction": "in",
                "name": "myParamName",
                // ... more depending on binding
            }
        ]
    }
    ```
  * `bindings` property is where _triggers_ and _bindings_ are configured
  * **All bindings require**
    |Property|Type|Comments|
    |:--|:--|:--|
    |`type`|string|Name of binding. For example, `queueTrigger`|
    |`direction`|string|Indicates whether binding is for received or sending data. For example, `in` or `out`|
    |`name`|string|Name that is used for bound data in function. For example, `myQueue`|
* **Function app**
  * Provides execution context in Azure in which functions run
  * Is the _unit of deployment and management_ of functions
  * Contains one or more individual functions that are managed, deployed, and scaled together
  * All functions in function app share
    * pricing plan
    * deployment method
    * runtime version
  > 🔵**NOTE**</br>
  > In Functions 2.x, all functions must be authored in same language
* **Folder structure**
  * Code for all functions in a specific function app is located in root project folder that contains a host configuration file
  * `host.json` contains run-time specific configurations and is in root of folder
  * `bin` folder contains packages and other library files that function requires
  * Folder structures are determined by language
    * [C# Compiled (.csproj)](https://learn.microsoft.com/en-us/azure/azure-functions/functions-dotnet-class-library#functions-class-library-project)
      * In _Visual Studio_, **Azure Functions** project template creates a C# class library containing
        * `host.json` - Configuration settings that affect all functions in project (locally or in Azure)
        * `local.settings.json` - app settings and connection strings used for running locally. File contains secrets and isn't published to function app.
          * Properties in here should be added to app setings of function
      * **Folder Structure**
        ```SHELL
        <framework.version>
        | - bin
        | - MyFirstFunction
        | | - function.json
        | - MySecondFunction
        | | - function.json
        | - host.json
        ```
      * _function.json_ - only contains trigger info, not input/output bindings
        * generated version from build contains `configurationSource` that tells runtime to use .NET attributes for bindings
          * Otherwise it tries to use _function.json_
        ```JSON
        {
          "generatedBy": "Microsoft.NET.Sdk.Functions-1.0.0.0",
          "configurationSource": "attributes",
          "bindings": [
            {
              "type": "queueTrigger",
              "queueName": "%input-queue-name%",
              "name": "myQueueItem"
            }
          ],
          "disabled": false,
          "scriptFile": "..\\bin\\FunctionApp1.dll",
          "entryPoint": "FunctionApp1.QueueTrigger.Run"
        }
        ```
    * [C# Script (.csx)](https://learn.microsoft.com/en-us/azure/azure-functions/functions-reference-csharp#folder-structure)
      * **Folder Structure**
        ```
        FunctionsProject
        | - MyFirstFunction
        | | - run.csx
        | | - function.json
        | | - function.proj
        | - MySecondFunction
        | | - run.csx
        | | - function.json
        | | - function.proj
        | - host.json
        | - extensions.csproj
        | - bin
        ```
      * _function.json_ - input or output data binding definitions
        ```JSON
        {
            "disabled": false,
            "bindings": [
                {
                    "type": "queueTrigger",
                    "direction": "in",
                    "name": "myQueueItem",
                    "queueName": "myqueue-items",
                    "connection":"MyStorageConnectionAppSetting"
                }
            ]
        }
        ```
      * _run.csx_ - contains actual function code
        ```CS
        #r "Microsoft.WindowsAzure.Storage"

        using Microsoft.Extensions.Logging;
        using Microsoft.WindowsAzure.Storage.Queue;
        using System;

        public static void Run(CloudQueueMessage myQueueItem, ILogger log)
        {
            log.LogInformation($"C# Queue trigger function processed: {myQueueItem.AsString}");
        }
        ```
      * Reusing _*.csx_ code - use `#load` to reference another CSX file
        ```CS
        #load "mylogger.csx"

        using Microsoft.Extensions.Logging;

        public static void Run(TimerInfo myTimer, ILogger log)
        {
            log.LogInformation($"Log by run.csx: {DateTime.Now}");
            MyLogger(log, $"Log by MyLogger: {DateTime.Now}");
        }
        ```
        * This can be used to create strongly-typed POCO objects between functions; for example:
          * HTTP Trigger
            ```CS
            #load "..\shared\order.csx"

            using System.Net;
            using Microsoft.Extensions.Logging;

            public static async Task<HttpResponseMessage> Run(Order req, IAsyncCollector<Order> outputQueueItem, ILogger log)
            {
                log.LogInformation("C# HTTP trigger function received an order.");
                log.LogInformation(req.ToString());
                log.LogInformation("Submitting to processing queue.");

                if (req.orderId == null)
                {
                    return new HttpResponseMessage(HttpStatusCode.BadRequest);
                }
                else
                {
                    await outputQueueItem.AddAsync(req);
                    return new HttpResponseMessage(HttpStatusCode.OK);
                }
            }
            ```
          * Queue trigger
            ```CS
            #load "..\shared\order.csx"

            using System;
            using Microsoft.Extensions.Logging;

            public static void Run(Order myQueueItem, out Order outputQueueItem, ILogger log)
            {
                log.LogInformation($"C# Queue trigger function processed order...");
                log.LogInformation(myQueueItem.ToString());

                outputQueueItem = myQueueItem;
            }
            ```
          * contents of Order.csx
            ```CS
            public class Order
            {
                public string orderId {get; set; }
                public string custName {get; set;}
                public string custAddress {get; set;}
                public string custEmail {get; set;}
                public string cartId {get; set; }

                public override String ToString()
                {
                    return "\n{\n\torderId : " + orderId +
                              "\n\tcustName : " + custName +
                              "\n\tcustAddress : " + custAddress +
                              "\n\tcustEmail : " + custEmail +
                              "\n\tcartId : " + cartId + "\n}";
                }
            }
            ```
    * [F# script](https://learn.microsoft.com/en-us/azure/azure-functions/functions-reference-fsharp#folder-structure)
      * **Folder Structure**
        ```
        FunctionsProject
        | - MyFirstFunction
        | | - run.fsx
        | | - function.json
        | | - function.proj
        | - MySecondFunction
        | | - run.fsx
        | | - function.json
        | | - function.proj
        | - host.json
        | - extensions.csproj
        | - bin
        ```
      * `host.json` - shared file for all functions in project
      * `.fsx` - code files
      * `function.json` - binding configuration file (per function)
    * [Java](https://learn.microsoft.com/en-us/azure/azure-functions/functions-reference-java#folder-structure)
      * **Folder Structure**
        ```
        FunctionsProject
        | - src
        | | - main
        | | | - java
        | | | | - FunctionApp
        | | | | | - MyFirstFunction.java
        | | | | | - MySecondFunction.java
        | - target
        | | - azure-functions
        | | | - FunctionApp
        | | | | - FunctionApp.jar
        | | | | - host.json
        | | | | - MyFirstFunction
        | | | | | - function.json
        | | | | - MySecondFunction
        | | | | | - function.json
        | | | | - bin
        | | | | - lib
        | - pom.xml
        ```
        * `target/azure-functions/FunctionApp` is what gets deployed to function app in Azure
        * `function.json` - binding configuration (per function)
        * `host.json` - shared configuration for all functions
        * `.java` - code file
        > 🔵**NOTE**</br>
        > Avoid putting functions into separate `.jar` files
    * [JavaScript](https://learn.microsoft.com/en-us/azure/azure-functions/functions-reference-node#folder-structure)
      * **Folder Structure**
        ```
        FunctionsProject
        | - MyFirstFunction
        | | - index.js
        | | - function.json
        | - MySecondFunction
        | | - index.js
        | | - function.json
        | - SharedCode
        | | - myFirstHelperFunction.js
        | | - mySecondHelperFunction.js
        | - node_modules
        | - host.json
        | - package.json
        | - extensions.csproj
        ```
        * Folder structure can be changed. See [scriptFile](https://learn.microsoft.com/en-us/azure/azure-functions/functions-reference-node?tabs=v2-v3-v4-export%2Cv2-v3-v4-done%2Cv2%2Cv2-log-custom-telemetry%2Cv2-accessing-request-and-response%2Cwindows-setting-the-node-version#using-scriptfile)
        * `host.json` - shared function configuration
        * `function.json` - binding configuration file (per function)
          * `function.json` parent directory is always name of function
        * Binding extneions required in [version 2.x](https://learn.microsoft.com/en-us/azure/azure-functions/functions-versions) of the Functions runtime are defined in `extensions.csproj`
    * [Python](https://learn.microsoft.com/en-us/azure/azure-functions/functions-reference-python#folder-structure)
      * **Folder Structure**
        ```
        <project_root>/
        | - .venv/
        | - .vscode/
        | - my_first_function/
        | | - __init__.py
        | | - function.json
        | | - example.py
        | - my_second_function/
        | | - __init__.py
        | | - function.json
        | - shared_code/
        | | - __init__.py
        | | - my_first_helper_function.py
        | | - my_second_helper_function.py
        | - tests/
        | | - test_my_second_function.py
        | - .funcignore
        | - host.json
        | - local.settings.json
        | - requirements.txt
        | - Dockerfile
        ```
      * `local.settings.json` - store app settings and connection strings for running locally. File not published to Azure
      * `requirements.txt` - list of Python packages system installs when publishing to Azure
      * `host.json` - contains configuration options affecting all functions in function app instance. Not published to Azure
      * `.vscode/` - (Optional) contains vscode configuration
      * `.venv/` - (Optional) contains python virtual environment used by local development
      * `Dockerfile` - (Optional) Used when publishing project in a [custom container](https://learn.microsoft.com/en-us/azure/azure-functions/functions-create-function-linux-custom-image)
      * `tests/` - (Optional) Test cases of function app
      * `.funcignore` - (Optional) declares files that shouldn't be published to Azure. Typicalls contains `.vscode/`, `.venv/`, `tests/`, and `local.settings.json`
* **Local Development Environments**
  * Local functions can connect to live Azure services
  * Can debug functions locally using full Functions runtime
  * Review [Code and test Azure Functions locally](https://learn.microsoft.com/en-us/azure/azure-functions/functions-develop-local)
  > 🟡**WARNING**</br>
  > Do not mix local development with portal development in the same function app. If function app is created and published from a local project, do not try to maintain or modify project code in portal
#### **Create triggers and bindings**
* Functions must have exactly 1 trigger
* Bindings can be _input_, _output_, or _both_
  * Bindings are declarative ways of connecting functions to another resource
  * Bindings are optional
* **Trigger and Binding definitions**
  |Language|Triggers and bindings are configured by...|
  |:--|:--|
  |C# class library|decorating methods and parameters with C# attributes|
  |Java|decorating methods and parameters with Java annotations|
  |JavaScript/PowerShell/Python/TypeScript|updating `function.json` schema
  * For languages that rely on `function.json`, Azure Portal has UI for adding bindings in the _**Integration**_ tab
  * For dynamically typed languages (JavaScript), use `dataType` property in `function.json`
    ```JSON
    {
      "dataType": "binary", // others include 'stream', and 'string'
      "type": "httpTrigger",
      "name": "req",
      "direction": "in"
    }
    ```
* **Binding Direction**
  * All triggers and bindings have a direction proprty in `function.json`
    * Triggers - direction is _always_ `in`
    * Input/Output bindings use `in` and `out`
    * Some bindings support special direction `inout`
      * Only _**Advanced Editor**_ is available via the _**Integration**_ tab if this binding is used
* **Azure Functions Trigger and Binding Example**
  * **Scenario**: Write a new row to Azure Table storage when new message appears in Azure Queue storage
    * `function.json` example
      ```JSON
      {
        "bindings": [
          {
            "type": "queueTrigger",
            "direction": "in",
            "name": "order",
            "queueName": "myqueue-items",
            "connection": "MY_STORAGE_ACCT_APP_SETTING"
          },
          {
            "type": "table",
            "direction": "out",
            "name": "$return",
            "tableName": "outTable",
            "connection": "MY_TABLE_STORAGE_ACCT_APP_SETTING"
          }
        ]
      }
      ```
    * `C# Script` example
      ```CS
      #r "Newtonsoft.Json"

      using Microsoft.Extensions.Logging;
      using Newtonsoft.Json.Linq;

      // From an incoming queue message that is a JSON object, add fields and write to Table storage
      // The method return value creates a new row in Table Storage
      public static Person Run(JObject order, ILogger log)
      {
          return new Person() { 
                  PartitionKey = "Orders", 
                  RowKey = Guid.NewGuid().ToString(),  
                  Name = order["Name"].ToString(),
                  MobileNumber = order["MobileNumber"].ToString() };  
      }

      public class Person
      {
          public string PartitionKey { get; set; }
          public string RowKey { get; set; }
          public string Name { get; set; }
          public string MobileNumber { get; set; }
      }
      ```
    * `JavaScript` example
      ```JAVASCRIPT
      // From an incoming queue message that is a JSON object, add fields and write to Table Storage
      module.exports = async function (context, order) {
          order.PartitionKey = "Orders";
          order.RowKey = generateRandomId(); 

          context.bindings.order = order;
      };

      function generateRandomId() {
          return Math.random().toString(36).substring(2, 15) +
              Math.random().toString(36).substring(2, 15);
      }
      ```
    * `C# Class Library` example
      ```C#
      public static class QueueTriggerTableOutput
      {
          [FunctionName("QueueTriggerTableOutput")]
          [return: Table("outTable", Connection = "MY_TABLE_STORAGE_ACCT_APP_SETTING")]
          public static Person Run(
              [QueueTrigger("myqueue-items", Connection = "MY_STORAGE_ACCT_APP_SETTING")]JObject order,
              ILogger log)
          {
              return new Person() {
                      PartitionKey = "Orders",
                      RowKey = Guid.NewGuid().ToString(),
                      Name = order["Name"].ToString(),
                      MobileNumber = order["MobileNumber"].ToString() };
          }
      }

      public class Person
      {
          public string PartitionKey { get; set; }
          public string RowKey { get; set; }
          public string Name { get; set; }
          public string MobileNumber { get; set; }
      }
      ```
#### **Connect functions to Azure services**
* Functions reference connection information by name from configuration provider
  * Does not directly accept connection details
    * Allows this be changed for each environment
  * For example, trigger definition may include a `connection` property
    * Cannot be set directly in `function.json`, instead, set `connection` to a name of an environment variables that contains the connection string
* Default configuration provider uses environment variables
  * Might be set in [Application Settings](https://learn.microsoft.com/en-us/azure/azure-functions/functions-how-to-use-azure-function-app-settings?tabs=portal#settings) when running in Azure Functions service
    * `local.settings.json` when developing locally
* **Connection Values**
  * When name resolves to a single exact value, runtime identifies value as a _connection string_
    * Details of connection string are defined by service you wish to connect
  * For example `connection` property for Azure Blob trigger may be defined as `Storage1`
    * If there is no single string value configured with `Storage1` as its name, `Storage1_serviceUri` would be used for the `serviceUri` property of the connection
      * Properties are different for each service
* **Configure an identity-based connection**
  * Some connections configured to an _identity_ instead of a _secret_
    * Support depends on extension using connection
    * Connection string may still be required in Functions
  > 🔵**NOTE**</br>
  > Identity-based connections are not supported with Durable Functions
  * When hosted in Azure Functions service, identity-based connections use a [managed identity](https://learn.microsoft.com/en-us/azure/app-service/overview-managed-identity?toc=/azure/azure-functions/toc.json)
    * System-assigned identity is used by default
    * User-assigned identity can be specified with `credential` and `clientID` properties
    * When run in other context; such as local development; developer identity is used instead.
      * Can be customized using alternative connection parameters
* **Grant Permission to Identity**
  * Identity must have permissions to perform intended actions
    * Typically done by assigning role in Azure RBAC or specifying identity in an access policy
  > 🟠**IMPORTANT**</br>
  > Some permissions might be exposed by the target service that are not necessary for all contexts. Where possible, adhere to the **principle of least privilege**, granting identity only required priveleges
#### **Exercise: Create an Azure Function by using VS Code**
* [Exercise Link](https://learn.microsoft.com/en-us/training/modules/develop-azure-functions/5-create-function-visual-studio-code)

### **Implement Durable Functions**
#### **Explore Durable Functions app patterns**
_Durable Functions_ extension lets you define stateful workflows by writing _orchestrator functions_ and stateful entities by writing _entity functions_ using Azure Functions programming model. The extension manages state, checkpoints, and restarts.
* **Supported Languages**
  * C# - precompiled class libraries and C# script
  * JavaScript - Only for version 2.x of Azure Functions runtime
    * Requires version >=1.7.0 of Durable Functions extension
  * Python - requires version >=2.3.1 of Durable Functions extension
  * F# - precompiled class libraries and F# script
    * F# script only supported for version 1.x of Azure Functions
  * PowerShell - Supported only for version 3.x of Azure Functions runtime and PowerShell 7
    * Requires version 2.x of bundle extensions
* **Application Patterns**
  Primary use case for Durable Functions is simplifying complex, stateful coordination requirements in serverless applications
  * App patterns that can benefit from Durable Functions
    * Function chaining
      * Output of one function is the input to another
      * F1 -> [data] -> F2 -> [data] -> etc...
      * Code example
        ```C#
        [FunctionName("Chaining")]
        public static async Task<object> Run(
            [OrchestrationTrigger] IDurableOrchestrationContext context)
        {
            try
            {
                var x = await context.CallActivityAsync<object>("F1", null);
                var y = await context.CallActivityAsync<object>("F2", x);
                var z = await context.CallActivityAsync<object>("F3", y);
                return  await context.CallActivityAsync<object>("F4", z);
            }
            catch (Exception)
            {
                // Error handling or compensation goes here.
            }
        }
        ```
    * Fan-out/in
      * Execute multiple functions in parallel and wait for all to finish
        * Often, some aggregation is perform on results of functions
      * Code example
        ```CS
        [FunctionName("FanOutFanIn")]
        public static async Task Run(
            [OrchestrationTrigger] IDurableOrchestrationContext context)
        {
            var parallelTasks = new List<Task<int>>();

            // Get a list of N work items to process in parallel.
            object[] workBatch = await context.CallActivityAsync<object[]>("F1", null);
            for (int i = 0; i < workBatch.Length; i++)
            {
                Task<int> task = context.CallActivityAsync<int>("F2", workBatch[i]);
                parallelTasks.Add(task);
            }

            await Task.WhenAll(parallelTasks);

            // Aggregate all N outputs and send the result to F3.
            int sum = parallelTasks.Sum(t => t.Result);
            await context.CallActivityAsync("F3", sum);
        }
        ```
      * Automatic checkpointing that happens at the `await` or `yield` call on `Task.WhenAll` or `context.df.Task.all` ensures that a potential mideway crash or reboot doesn't require statrting an already completed task
    * Async HTTP APIs
      * Pattern addresses the problem of coordinating the state of long-running operations with external clients
      * Commonly implemented by having an HTTP endpoint trigger the long-running action
        * Then, redirect client to a status endpoint that the client polls to learn when operation is finished
      * Durable Functions provides **built-in support** for this pattern, simplifying or even removing the code you need to write to interact with long-running function executions
        * extension exposes webhook HTTP APIs that query the orchestrator function status
      * Example REST commands that start orchestrator and query status
        ```MD
        > curl -X POST https://myfunc.azurewebsites.net/orchestrators/DoWork -H "Content-Length: 0" -i
        HTTP/1.1 202 Accepted
        Content-Type: application/json
        Location: https://myfunc.azurewebsites.net/runtime/webhooks/durabletask/b79baf67f717453ca9e86c5da21e03ec

        {"id":"b79baf67f717453ca9e86c5da21e03ec", ...}

        > curl https://myfunc.azurewebsites.net/runtime/webhooks/durabletask/b79baf67f717453ca9e86c5da21e03ec -i
        HTTP/1.1 202 Accepted
        Content-Type: application/json
        Location: https://myfunc.azurewebsites.net/runtime/webhooks/durabletask/b79baf67f717453ca9e86c5da21e03ec

        {"runtimeStatus":"Running","lastUpdatedTime":"2019-03-16T21:20:47Z", ...}

        > curl https://myfunc.azurewebsites.net/runtime/webhooks/durabletask/b79baf67f717453ca9e86c5da21e03ec -i
        HTTP/1.1 200 OK
        Content-Length: 175
        Content-Type: application/json

        {"runtimeStatus":"Completed","lastUpdatedTime":"2019-03-16T21:20:57Z", ...}
        ```
      * Durable Functions extension exposes built-in HTTP APIs that manage long-running orchestrations
        * Alternatively implement this on your own using function triggers and orchestration client binding
        ```CS
        public static class HttpStart
        {
            [FunctionName("HttpStart")]
            public static async Task<HttpResponseMessage> Run(
                [HttpTrigger(AuthorizationLevel.Function, methods: "post", Route = "orchestrators/{functionName}")] HttpRequestMessage req,
                [DurableClient] IDurableClient starter,
                string functionName,
                ILogger log)
            {
                // Function input comes from the request content.
                object eventData = await req.Content.ReadAsAsync<object>();
                string instanceId = await starter.StartNewAsync(functionName, eventData);

                log.LogInformation($"Started orchestration with ID = '{instanceId}'.");

                return starter.CreateCheckStatusResponse(req, instanceId);
            }
        }
        ```
      * Function must include `DurableClient` input binding to interact with orchestrators
        * Use client to start orchestration
        * Can also help return HTTP response containing URLs for checking status of new orchestration
    * Monitor
      * Refers to flexible, recurring process in workflow
        * For example: polling until specific conditions are met
      * Can be used to create flexible recurrence intervals, manage task lifetimes, and create multiple monitor processes from a single orchestration
      * Can change a monitor's `wait` interval based on a condition (for example, exponential backoff)
      ```C#
      [FunctionName("MonitorJobStatus")]
      public static async Task Run(
          [OrchestrationTrigger] IDurableOrchestrationContext context)
      {
          int jobId = context.GetInput<int>();
          int pollingInterval = GetPollingInterval();
          DateTime expiryTime = GetExpiryTime();

          while (context.CurrentUtcDateTime < expiryTime)
          {
              var jobStatus = await context.CallActivityAsync<string>("GetJobStatus", jobId);
              if (jobStatus == "Completed")
              {
                  // Perform an action when a condition is met.
                  await context.CallActivityAsync("SendAlert", machineId);
                  break;
              }

              // Orchestration sleeps until this time.
              var nextCheck = context.CurrentUtcDateTime.AddSeconds(pollingInterval);
              await context.CreateTimer(nextCheck, CancellationToken.None);
          }

          // Perform more work here, or let the orchestration end.
      }
      ```
    * Human Interaction
      * Automated processes that involve some kind of human interaction (approval process)
      * Process may allow for interaction by using timeouts and compensation logic
      * Implement using an orchestrator function
        * Orchestrator uses a durable timer to request approval
        * Orchestrator escalates if timeout occurs
        * Orchestator waits for an external event, such as a notification
        ```CS
        [FunctionName("ApprovalWorkflow")]
        public static async Task Run(
            [OrchestrationTrigger] IDurableOrchestrationContext context)
        {
            await context.CallActivityAsync("RequestApproval", null);
            using (var timeoutCts = new CancellationTokenSource())
            {
                DateTime dueTime = context.CurrentUtcDateTime.AddHours(72);
                Task durableTimeout = context.CreateTimer(dueTime, timeoutCts.Token);

                Task<bool> approvalEvent = context.WaitForExternalEvent<bool>("ApprovalEvent");
                if (approvalEvent == await Task.WhenAny(approvalEvent, durableTimeout))
                {
                    timeoutCts.Cancel();
                    await context.CallActivityAsync("ProcessApproval", approvalEvent.Result);
                }
                else
                {
                    await context.CallActivityAsync("Escalate", null);
                }
            }
        }
        ```
#### **Discover the four function types**
* **Orchestrator Functions**
  * Describe how actions are executed and the order they are executed in
  * Can interact with `entity functions`
  * Written using ordinary code
    * Strict requirements on how to write the code
      * <mark>Must be deterministic</mark>; not doing so can cause orchestrator functions to fail to run correctly
  * [Orchestrator Function Contraints](https://learn.microsoft.com/en-us/azure/azure-functions/durable/durable-functions-code-constraints?tabs=csharp)
* **Activity Functions**
  * Basic unit of work in a durable function orchestration
  * Not restricted in type of work that can be done
  * Can return data back to orchestrator function
  * _Activity trigger_ is used to define an activity function
    * .NET functions receive a `DurableActivityContext` as a parameter
    * Can also bind trigger to any JSON-serializeable object to pass inputs to function
  * In JavaScript
    * access input via `<activity trigger binding name>` property on `context.bindings`
  * Can only have a single value passed
    * To pass multiple values, use `tuples`, `arrays`, or `complex types`
* **Entity Functions**
  * Define operations for reading/updating small pieces of state
  * Often referred to as `durable entities`
  * Special trigger type _entity trigger_
  * Can be invoked from client functions or orchestrator functions
  * No specific code constraints
  * Explicitly manage state rather than implicitly via control flow
  * Important Notes
    * Entities accessed via unique identifier `entity ID`
      * `Entity ID` is a pair of strings that uniquely identifies an entity instance
    * OPerations on entities require target entity `Entity ID` and `Operation name` be specified
* **Client Functions**
  * Orchestrator and Entity functions are triggered by their binding and both triggers work by reacting to messages enqueued in a task hub
  * Any non-orchestrator function can be a client function
  * Use of _durable client output binding_ makes a function a client function
  * Orchestrator and Entity functions can not be triggered directly using buttons in Azure portal
    * To test an orchestrator or entity function in Azure portal, must run a client function that starts orchestrator or entity function
      * _manual trigger_ is recommended for this purpose
#### **Explore task hubs**
* Logical container for durable storage resources used for orchestration entities
* Orchestrator, activity, and entity functions can only directly interact with each other when they belong to same task hub
  * If multiple function apps share a storage account, each function app must be configured with a separate task hub name
    * Storage account can contain multiple task hubs
* **Azure Storage Resources**
  * Task hub consists of
    * One or more control queues
    * One work-item queue
    * One history table
    * One instances table
    * One storage container containing one or more lease blobs
    * A storage container containing large message payloads, if applicable
  * All of these resources are created automatically in the configured Azure Storage account when orchestrator, entity, or activity functions run or are scheduled
* **Task hub names**
  * Conforms to following rules
    * contains only alphanumeric characters
    * starts with a letter
    * has min length of 3, max length of 45
  * `host.json` file example
    ```JSON
    {
      "version": "2.0",
      "extensions": {
        "durableTask": {
          "hubName": "MyTaskHub"
        }
      }
    }
    ```
  * name is what differentiates one task hub from another when multiple task hubs are in a shared storage account
    * Must explicitly configure different names for each task hub in `host.json`
      * Failing to do so will cause function apps to compete for same message which would result in undefined behavior, including orchestrations getting unexpectedly stuck in `Pending` or `Running` states
#### **Explore durable orchestrations**
* _Orchestrator Function_ can be used to orchestrate execution of other Durable Functions
* Orchestrator Function characteristics
  * Defined using procedural code
    * No declarative schemas or designers needed
  * Can call other durable functions sync/async
    * Output from called functions can be saved reliably to local functions
  * Durable and reliable
    * Execution progress automatically checkpointed when function `await`s or `yield`s
    * Local state never lost when process recycles or VM reboots
  * Can be long-running
    * Can be seconds, days, months, or never-ending
* **Orchestration Identity**
  * Each _instance_ has an _instance ID_
    * By default, is an autogen GUID
      * Can be user-generated
    * Instance ID must be unique within a task hub
  * Orchestrations Instance ID is required parameter for most instance management operations
  * Important for diagnostics
  * Recommended to save to som external location (DB, app logs, etc...)
* **Reliability**
  * Reliably maintain state using event sourcing pattern
  * Uses append-only store to record series of actions function orchestration takes
  * `await`(C#) or `yield`(JavaScript) in orchestrator function yields control of orchestrator thread back to Durable Task Framework dispatcher
    * Dispatcher commits any new actions the orchestrator function scheduled (i.e. calling 1+ child functions or scheduling a durable timer) to storage
  * Transparent commit action appends execution history of orchestration instance
  * History is stored in storage table
    * Commit action adds messages to a queue to schedule work
      * At this point, the orchestrator function can be unloaded from memory
  * When orchestrator function given more work, it wakes up and re-executes the entire functoin from the start to rebuild local state
    * If code tries to call a function (or do any other async work) the Durable Task Framework consults execution history
      * If activity function has already executed and yielded a result, functions result is replayed and orchestrator continues to run
      * Replay occurs until function code is finished or until has scheduled new async work
  * **Features and Patterns**
    |Pattern/Feature|Description|
    |:--|:--|
    |Sub-orchestrations|Orchestrator functions can call activity functions, but also other orchestrator functions. For example, you can build a larger orchestration out of a library of orchestrator functions; or, run multiple instances of an orchestrator in parallel|
    |Durable timers|Orchestrations can schedule durable timers to implement delays or set up timeout handling on async actions. Use durable timers in orchestrator functions instead of `Thread.Sleep` and `Task.Delay`(C#) (or `setTimeout()` and `setInterval()` (JavaScript))|
    |External events|Orchestrator functions can wait for external events to update an orchestration instance. This Durable Functions feature often is useful for handling a human interaction or other external callbacks|
    |Error handling|Orchestrator functions can use hte error-handling features of the programming language. Existing patterns like try/catch are supported|
    |Critical sections|Orchestration instances are single-threaded so it isn't necessary to worry about race conditions _within_ an orchestration. Race conditions are possible when interacting with external systems. To mitigate race conditions when interacting with external systems, orchestrator functions can define _critical sections_ using a `LockAsync` method in .NET|
    |Calling HTTP endpoints|Orchestrator functions aren't permitted to do I/O. Workaround for this is to wrap any I/O in an activity function. Orchestrations that interact with external systems frequently use activity functions to make HTTP calls and return result to orchestration|
    |Passing multiple parameters|Not possible to pass multiple parameters to an activity function directly. Recommended to use an array or ValueTuples|
#### **Control timing in Durable Functions**
* Durable functions provides _durable timers_ for delays or timeouts on async actions
* Durable timers should replace usage of `Thread.Sleep` and `Task.Delay` (`setTimeout()` and `setInterval()` in JS, `time.sleep()` in Python)
* Create a durable time by calling `CreateTimer` in .NET; `createTimer` in JS; method of the orchestration binding
  * Method returns a task that completes on a specific date/time
* **Timer Limitations**
  * When you create a timer that expires at 4:30pm, underlying Durable Task Framework enqueues a message that is not visible until 4:30PM
  * When running Functions on the _Consumption Plan_, newly visible timer messages ensure function app gets invoked on an appropriate VM
* **Usage for Delay**
  * Example: Issuing a billing notification every day for 10 days
    ```C#
    [FunctionName("BillingIssuer")]
    public static async Task Run(
    [OrchestrationTrigger] IDurableOrchestrationContext context)
    {
        for (int i = 0; i < 10; i++)
        {
            DateTime deadline = context.CurrentUtcDateTime.Add(TimeSpan.FromDays(i + 1));
            await context.CreateTimer(deadline, CancellationToken.None);
            await context.CallActivityAsync("SendBillingEvent");
        }
    }
    ```
* **Usage for Timeout**
  * Example: How to use durable timers to implement timeouts
    ```C#
    [FunctionName("TryGetQuote")]
    public static async Task<bool> Run(
        [OrchestrationTrigger] IDurableOrchestrationContext context)
    {
        TimeSpan timeout = TimeSpan.FromSeconds(30);
        DateTime deadline = context.CurrentUtcDateTime.Add(timeout);

        using (var cts = new CancellationTokenSource())
        {
            Task activityTask = context.CallActivityAsync("GetQuote");
            Task timeoutTask = context.CreateTimer(deadline, cts.Token);

            Task winner = await Task.WhenAny(activityTask, timeoutTask);
            if (winner == activityTask)
            {
                // success case
                cts.Cancel();
                return true;
            }
            else
            {
                // timeout case
                return false;
            }
        }
    }
    ```
  > 🟡**WARNING**</br>
  > Use a `CancellationTokenSource` to cancel a durable timer in .NET; or `cancel()` on returned `TimerTask` in JS; if code will not wait for it to complete. Durable Task Framework will not change an orchestrations status to _completed_ until all outstanding tasks are completed or canceled.
  * This cancellation mechanism does not terminate in-progress activity function or sub-orchestration executions.
    * Allows orchestrator function to ignore result and move on
#### **Send and wait for events**
* Orchestrator functions have ability to wait and listen for external events
  * Useful for handling human interaction and other external triggers
* **Wait for Events**
  * `WaitForExternalEvent` in .NET; `waitForExternalEvent` in JS, `wait_for_external_event` in Python; methods allow function to asynchronously wait and listen for an external event
  * Listening orchestrator function declares _name_ of event and _shape of the data_ it expectes to receive
  * Example: List for event and take some action when received
    ```C#
    [FunctionName("BudgetApproval")]
    public static async Task Run(
        [OrchestrationTrigger] IDurableOrchestrationContext context)
    {
        bool approved = await context.WaitForExternalEvent<bool>("Approval");
        if (approved)
        {
            // approval granted - do the approved action
        }
        else
        {
            // approval denied - send a notification
        }
    }
    ```
* **Send Events**
  * the `RaiseEventAsync` in .NET; `raiseEvent` in JS; of orchestration client binding sends the events that `WaitForExternalEvent` waits for.
  * `RaiseEventAsync` method takes _eventName_ and _eventData_ as parms.
    * Event data _must_ be JSON-serializable
  * Example: Queue-triggered function that sends an "Approval" event to orchestrator function
    ```C#
    [FunctionName("ApprovalQueueProcessor")]
    public static async Task Run(
        [QueueTrigger("approval-queue")] string instanceId,
        [DurableClient] IDurableOrchestrationClient client)
    {
        await client.RaiseEventAsync(instanceId, "Approval", true);
    }
    ```
  * Internally, `RaiseEventAsync` and `raiseEvent` enqueue a message that gets picked up by the waiting orchestrator function
  * If instance is not waiting on the specified _event name_, the event message is added to an in-memory queue
  * If orchestration instance later begins listening for _event name_, it will check the queue for event messages
  
## **Develop Solutions that use Blob storage**
### **Explore Azure Blob storage**
#### **Explore Azure Blob storage**
* Optimized for storing massive amounts of unstructured data
* Designed for
  * Serving images or documents directly to a browser
  * Store files for distributed access
  * Streaming video and audio
  * Writing to log files
  * Storing data for backup/restore, DR, archiving
  * Storing data for analysis by an on-prem or Azure-hosted service
* Can be accessed via HTTP/S anywhere in world
* Objects in blob storage accessible via Azure Storage REST API, Azure PowerShell, Azure CLI, or Azure Storage client library
* Azure Storage account is a top-level container for all Azure Blob storage
  * Storage account provides unique namespace for Azure Storage
* **Types of Storage Accounts**
  * Two performance levels: Standard, Premium
    |||
    |:--|:--|
    |**Standard**|Standard GPv2 account and recommended for most scenarios|
    |**Premium**|Higher performance by utilizing SSD. Three account types available: block blobs, page blobs, or file shares|
  * Storage account recommendations by scenario
    |Storage account type|Supported storage services|Usage|
    |:--|:--|:--|
    |Standard GPv2|Blob, Queue, and Table storage, Azure Files|Standard storage account type for blobs, file shares, qeueues, and tables. Recommended for most scenarios using Azure Storage. If you want to support NFS file shares in Azure Files, use premium file shares account type|
    |Premium block blobs|Blob storage|PRemium storage account type for block blobs and append blobs. Recommended for scenarios with high transactions rates, or scenarios that use smaller objects or require consistently low storage latency|
    |Premium page blobs|Page blobs only| Premium storage account type for page blobs only|
    |Premium file shares|Azure files|Premium storage account type for file shares only|
* **Access tiers for block blob data**
  * Different options for different usage patterns
  * Selecting the appropriate access tier you can store block blob data in most cost-effective manner
    |Tier|Description|
    |:--|:--|
    |Hot|Optimized for frequent access. Highest storage cost, lowest access cost. New storage accounts are created in hot tier by default|
    |Cool|Optimized for storing large amounts of data infrequently accessed and stored for at least 30 days. Lower storage costs, higher access costs compared to Hot|
    |Archive|Available for individual block blobs only. Optimized for data that can tolerate several hours of retrieval latency and will remain in Archive for at least 180 days. Most cost-effective option for storing data, most expensive for data access|
  * Can switch between access tiers at any time if requirements shift
#### **Discover Azure Blob storage resource types**
* 3 types of resources
  * Storage Account
  * Container in Storage Account
  * Blob in a Container
* **Storage Accounts**
* Every Azure Storage account provides a unique namespace
  * Account name + Azure Storage blob endpoint forms base address for objects in storage account
  * Example: if storage account is named _mystorageaccount_
    ```
    http://mystorageaccount.blob.core.windows.net
    ```
* **Containers**
  * Organizes a set of blobs
  * Similar to a directory in a file system
  * Storage account can include unlimited number of containers
  * Containers can store unlimited number of blobs
  * Name must always be lowercase
* **Blobs**
  * Azure Storage supports 3 types of blobs
    |Type|Description|
    |:--|:--|
    |Block|Store text/binary data, up to ~190.7TB. Made up of blocks of data that be managed individually|
    |Append|Made up of blocks like blobs, but optimized for append operations. Ideal for logging data from VMs|
    |Page|Random access files up to 8TB. Store virtual hard drive (VHD) files and serve as disks for Azure VMs|
#### **Explore Azure Storage security features**
* Provides a comprehensive set of security capabilities
  * All data written to Azure Storage is automatically encrypted using Storage Service Encryption(SSE)
  * Azure AD and RBAC are supported for both resource management and data operations
    * Can assign RBAC roles scoped to storage account to security principals and use Azure AD to authorize resource management operations such as key management
    * Azure AD integration is supported for blob and queue data operations. Can assign RBAC roles scoped to a subscription, resource group, storage account, or individual container or queue to a security principal or managed identity for Azure resources
  * Data in transit (app -> azure) can be secured using Client-Side Encryption, HTTPS, or SMB 3.0
  * OS and data disks used by Azure VMs can be encrypted using Azure Disk Encryption
  * Delegated access to data objects in Azure Storage can be granted using a shared access signature
* **Azure Storage encryption for data at rest**
  * Azure Storage automatically encrypts data when persisting to cloud
  * Encrypted and Decrypted transparently using 256-bit AES encryption
    * FIPS 140-2 compliant
    * Similar to BitLocker encryption on Windows
  * Encryption is enabled for all new/existing storage accounts
    * Can not be disabled
  * Encrypted regardless of performance tier or deployment model
  * All Azure Storage redundancy options support encryption and all copies of a storage account are encrypted
  * All Azure Storage resources are encrypted including: blobs, disks, files, queues, and tables.
    * Metadata is also encrypted
* **Encryption Key Management**
  * Can rely on Microsoft-managed keys for encryption of storage account or manage encryption with own key
  * If using own keys, there are two possible options:
    * Specify a _customer-managed_ key to use for encrypting/decrypting
      * Used to encrypt all data in all services in storage account
    * Specify a _customer-provided_ key on Blob stoage operations
      * Client making a read/write requests against Blob storage can include an encryption key on the request for granular control over how blob data is encrypted/decrypted
  * Key Management options for Azure Storage encryption
    ||Microsoft-managed keys|Customer-managed keys|Customer-provided keys|
    |:--|:--|:--|:--|
    |Encrypt/Decrypt Ops|Azure|Azure|Azure|
    |Azure Storage services supported|All|Blob, Azure Files|Blob|
    |Key storage|Microsoft key store|Azure Key Vault|Azure Key Vault or any other key store|
    |Key rotation responsibility|Microsoft|Customer|Customer|
    |Key usage|Microsoft|Azure portal, Storage Resource Provider REST API, Azure Storage management libraries, PowerShell, CLI|Azure Storage REST API (Blob storage), Azure Storage client libraries|
    |Key acess|Microsoft only|Microsoft, Customer|Customer only|
#### **Evaluate Azure Storage redundancy options**
* Azure Storage always stores multiple copies of data
* When choosing redundancy option, consider trade offs between lower costs and higher availability
  * How data is replicated in primary region
  * Whether data is replicated to a second region that is geographically distant to primary region
    * Geo-Redundant Storage to protect against regional distasters
  * Application requires read access to replicated data in secondary region if primary region becomes unavailable
* **Redundancy in primary region**
  * Data is replicated 3 times by default in primary region
  * Two options for primary region
    |||
    |:--|:--|
    |Locally Redundant Storage (LRS)|Copies data synchronously 3 times within a single physical location. Least expensive, but not recommended for apps requiring high availability or durability|
    |Zone-redundant Storage (ZRS)|Copies data synchronously across 3 Azure Availability Zones in primary region. For apps requiring high availability, use ZRS in primary region and also replicate to secondary region|
* **Redundancy in a Secondary Region**
  * For apps requiring high durability, you can choose to copy data in storage account to a secondary region
    * If copied to a secondary region, data is considered durable
      * Think of regional outages or disaster in primary region
  * Secondary region is determined by primary region and is not modifiable
  * Two options available for copying data to secondary region
    |||
    |:--|:--|
    |Geo-Redundant Storage (GRS)|Copies data synchronously 3 times within  a single physical location in primary region using LRS. Then it copies data asynchronously to a single physical location in the secondary region. Within secondary region, data is copied synchronously 3 times using LRS|
    |Geo-Zone-Redundant-Storage (GZRS)|Copies data synchronously across 3 Azure availability zones in primary region using LRS. Then copies data asynchronously to secondary region and then copied synchronously 3 times using LRS|
#### **Exercise: Create a block blob storage account**
1. Log in to Azure Portal
2. Create new resource group
   1. `az group create --name az204-blob-rg --location <my_location>`
3. Create block blob storage account
   1. ```SHELL
      az storage account create \
      --resoure-group az204-blob-rg \
      --name <myStorageAccount> \
      --location <my_location> \
      --kind BlockBlobStorage \
      --sku Premium_LRS
      ```
4. When finished, clean up
   1. `az group delete --name az204-blob-rg --no-wait` 
### **Manage the Azure Blob storage lifecycles**
#### **Explore Azure Blob storage lifecycle**
* **Access tiers**
  |Tier|Purpose|
  |:--|:--|
  |Hot|Optimized for freguently accessed data|
  |Cool|Optimized for data infrequently accessed and stored for >= 30 days|
  |Archive|Optimized for rarely accessed data and stored for >= 180 days with flexible latency requirements, on the order of hours|
  * Considerations
    * Access tier can be set on blob during or after upload
    * Hot/cool tiers can be set at account level
    * Archive tier can only be set at blob level
    * Cool access tier has lower availability, has high durability, retrieval latency, and throughput characteristics similar to hot tier
    * Archive tier is stored offline. Lowest cost tier, highest access costs and latency
    * Hot/cool tiers support all redundancy options
    * Archive tier only supports LRS, GRS, and RA-GRS
    * Data storage limits are set at account level and not per access tier
      * Can choose to use all of your limit in one tier or across all 3 tiers
* **Manage the data lifecycle**
  * Azure Blob storage lifecycle management offers rich, rule-based policy for GPv2 and Blob storage accounts
    * Use policy to transition data to appropriate access tiers or expire at end of data's lifecycle
  * Lifecycle management policy lets you
    * Transition blobs to a cooler storage tier (Hot-to-cool, cool-to-archive, hot-to-archive) to optimize performance and cost
    * Delete blobs at end of lifecycle
    * Define rules to run once per day at storage account level
    * Apply rules to containers or a subset of blobs (using prefixes as filters)
  > 🔵**NOTE**</br>
  > Data stored in a _premium block blob_ storage account cannot be tiered to Hot, Cool, or Archive using Set Blob Tier or using Azure Blob Storage lifecycle management. To move data, you must synchronously copy blobs from the block blob storage account to the Hot tier in a different account using the Put Block From URL API or a version of AzCopy that supports this API. Put Block From URL API synchronously copies data on the server, meaning the call completes only once all data is moved from original server location to destination location.
#### **Discover Blob storage lifecycle policies**
* Lifecycle management policy is collection of rules in a JSON document
* Each rule definition within a policy includes a _filter set_ and an _action set_
  * Filter set: limits rule actions to certain set of object in a container or objects names
  * Action set: applies the tier or delete actions to filtered set
  ```JSON
  {
    "rules": [
      {
        "name": "rule1",
        "enabled": true,
        "type": "Lifecycle",
        "definition": {...}
      },
      {
        "name": "rule2",
        "type": "Lifecycle",
        "definition": {...}
      }
    ]
  }
  ```
* A policy is a collection of rules
  |Parameter name|Parameter type|Notes|
  |:--|:--|:--|
  |`rules`|Array of rule objects|at least one rule is required in a policy. Can define up to 100 rules in a policy.|
* Each rule within a policy has several parameters
  |Parameter name|Parameter type|Notes|Required|
  |:--|:--|:--|:--|
  |`name`|String|Name of rule, upto 256 alphanumeric characters. _Rule name is case-sensitive_. Must be unique within a policy.|True|
  |`enabled`|Boolean|Optional boolean to allow rule to be temporary disabled. Default value is true if it's not set|False|
  |`type`|An enum value|The current valid type is `Lifecycle`|True|
  |`definition`|An object that defines lifecycle rule|Each definition is made up of a _filter set_ and an _action set_|True|
* **Rules**
  * Each rule includes a _filter set_ and an _action set_
  * Rule definition example:
    * Tier blob to cool tier 30 days after last modification
    * Tier blob to archive tier 90 days after last modification
    * Delete blob 2,555 days (seven years) after last modification
    * Delete blob snapshots every 90 days after snapshot creation
    ```JSON
    {
      "rules": [
        {
          "name": "ruleFoo",
          "enabled": true,
          "type": "Lifecycle",
          "definition": {
            "filters": {
              "blobTypes": [ "blockBlob" ],
              "prefixMatch": [ "container1/foo" ]
            },
            "actions": {
              "baseBlob": {
                "tierToCool": { "daysAfterModificationGreaterThan": 30 },
                "tierToArchive": { "daysAfterModificationGreaterThan": 90 },
                "delete": { "daysAfterModificationGreaterThan": 2555 }
              },
              "snapshot": {
                "delete": { "daysAfterCreationGreaterThan": 90 }
              }
            }
          }
        }
      ]
    }
    ```
* **Rule Filters**
  |Filter name|Filter type|Is Required|
  |:--|:--|:--|
  |blobTypes|An array of predefined enum values|Yes|
  |prefixMatch|An array of strings for prefixes to be matched. Each rule can define up to 10 prefixes. A prefix string must start with a container name|No|
  |blobIndexMatch|An array of dictionary values consisting of blob index tag key and value conditions to be matched. Each rule and define up to 10 blob index tag conditions|No|
* **Rule Actions**
  * Must define at least 1 action for each rule on blobs or blob snapshots
    |Action|Base Blob|Snapshot|Version|
    |:--|:--|:--|:--|
    |tierToCool|Supported for `blockBlob`|Supported|Supported|
    |enableAutoTierToHotFromCool|Supported for `blockBlob`|Not supported| Not supported|
    |tierToArchive|Supported for `blockBlob`|Supported|Supported|
    |delete|Supported for `blockBlob` and `appendBlob`|Supported|Supported|
  > 🔵**NOTE**</br>
  > If more than one action on same blob is defined, lifecycle management applies least expensive action to the blob. For example, the `delete` action is cheaper than `tierToArchive` action, and `tierToArchive` is cheaper than `tierToCool`
  * Run conditions are based on age.
    * Base blobs use last modified time to track age
    * Blob snapshots use the snapshot creation time to track age
    
    |Action run condition|Condition value|Description|
    |:--|:--|:--|
    |daysAfterModificationGreaterThan|Integer value indicating age in days|Condition for base blob actions|
    |daysAfterCreationGreaterThan|Integer value indicating age in days|Condition for blob snapshot actions|
    |daysAfterLastAccessTimeGreaterThan|Integer value indicating age in days|Condition for a current version of a blob when access tracking is enabled|
    |daysAfterLastTierChangeGreaterThan|Integer value indicating age in days after last blob tier change time|Condition applies only to `tierToArchive` actions and can be used only with the `daysAfterModificationGreaterThan` condition|
#### **Implement Blob storage lifecycle policies**
* From Azure portal
  * `All resources > (your) Storage account > Data Management > Lifecycle management > List view > Add rule`
  * fill out `Action set` form fields
  * `Filter set` and add optional filter
  * Browse to specify container and folder to filter by
  * Review + add to review policy settings
  * Select `Add` to add new policy
  * JSON generated and viewed from _Code view_ tab
    ```JSON
    {
      "rules": [
        {
          "enabled": true,
          "name": "move-to-cool",
          "type": "Lifecycle",
          "definition": {
            "actions": {
              "baseBlob": {
                "tierToCool": {
                  "daysAfterModificationGreaterThan": 30
                }
              }
            },
            "filters": {
              "blobTypes": [
                "blockBlob"
              ],
              "prefixMatch": [
                "sample-container/log"
              ]
            }
          }
        }
      ]
    }
    ```
* From Azure CLI
  * First, write policy to a JSON file (i.e. above JSON saved in to a file called 'coolingPolicy.json')
  ```
  az storage account management-policy create \
  --account-name <storage-account>
  --policy @coolingPolicy.json \
  --resource-group <resource-group>
  ```
#### **Rehydrate blob data from archive tier**
* Blobs in Archive tier can not be read or modified because it is offline
  * Must be rehydrated (moved to Hot or Cool tier) to an online tier
* Rehydrating Options
  |Option|Instructions|
  |:--|:--|
  |Copy archived blob to an online tier|Rehydrate by copying to new blob in Hot or Cool tier with [Copy Blob](https://learn.microsoft.com/en-us/rest/api/storageservices/copy-blob) or [Copy Blob from URL](https://learn.microsoft.com/en-us/rest/api/storageservices/copy-blob-from-url) operation. **Recommened** for most scenarios|
  |Change blobs access tier to an online tier|Rehydrate by changing tier from Archive to Hot or Cool using [Set Blob Tier](https://learn.microsoft.com/en-us/rest/api/storageservices/set-blob-tier)|
* **Rehydration Priority**
  * Can set a priority for rehydration operation using `x-ms-rehydrate-priority` header on [Set Blob Tier](https://learn.microsoft.com/en-us/rest/api/storageservices/set-blob-tier) or **Copy Blob/Copy Blob from URL** operation.
  * Priority options
    |Priority|Description|
    |:--|:--|
    |Standard priority|Rehydration request will be processed in order it was received and may take up to 15 hours|
    |High priority|Request is prioritized over standard priority requests and may complete in under 1 hour for objects <10GB|
  * Check rehydration priority while operation is underway by calling [Get Blob Properties](https://learn.microsoft.com/en-us/rest/api/storageservices/get-blob-properties)
    * Returns `x-ms-hydrate-policy` header
      * Values are `High` or `Standard`
* **Copy an archived blob to an online tier**
  * Can use either **Copy blob** or **Copy blob from URL** operations
  * Copying Archive tier blob to online tier does not modify source blob
    * Must be copied to new blob with different name or different container
    * Cannot overwrite source blob by copying to same blob
  * Copying archived to online supported in same storage account only
    * Cannot copy archived blob to a destination blob that is also in archive tier
  * Blob copy operation behavior
    ||Hot tier source|Cool tier source|Archive tier source|
    |:--|:--|:--|:--|
    |Hot tier destination|Supported|Supported|Supported within same account. Requires blob rehydration|
    |Cool tier destination|Supported|Supported|Support within same account. Requires blob rehydration|
    |Archive tier|Supported|Supported|Unsupported|
* **Change a blob's access tier to an online tier**
  * Use **Set Blob Tier** to change blobs tier from archive to online tier
    * Can not be canceled once started
    * Blobs access tier shows as Archive until rehydration is complete
  * See [Rehydrate a blob by changing its tier](https://learn.microsoft.com/en-us/azure/storage/blobs/archive-rehydrate-to-online-tier#rehydrate-a-blob-by-changing-its-tier) for additional information
  > 🔴**CAUTION**</br>
  > Changing blobs tier does not affect _last modified time_. If a lifecycle management policy is in effect for the storage account, rehydrating blob with **Set Blob Tier**can result in a scenario where the lifecycle policy moves the blob back to archive after rehydration because last modified time is beyond threshold set in policy.
### **Work with Azure Blob storage**
#### **Explore Azure Blob storage client library**
* Azure Storage client libraries for .NET offer convenient interface for making calls to Azure Storage
  * Latest version is 12.x and is recommended for new applications
  * Classes in `Azure.Storage.Blobs`
    |Class|Description|
    |:--|:--|
    |`BlobClient`|Allows you to manipulate Azure Storage blobs|
    |`BlobClientOptions`|Provides client configuration options for connecting to Azure Blob Storage|
    |`BlobContainerClient`|Allows you to manipulate Azure Storage containers and their blobs|
    |`BlobServiceClient`|Allows you to manipulate Azure Storage service resources and blob containers. Storage account provides the top-level namespace for the Blob service.|
    |`BlobUriBuilder`|Provides convenient way to modify contents of a URI instance to point to different Azure Storage resources like an account, container, or blob|
#### **Exercise: Create Blob storage resources by using .NET client library**
* [Exercise link](https://learn.microsoft.com/en-us/training/modules/work-azure-blob-storage/3-develop-blob-storage-dotnet)
* Exercise shows how to
  * Create container
  * Upload blobs to container
  * List blobs in container
  * Download blobs
  * Delete a container
* **Setup** (From CLI)
  1. `az login`
  2. `az group create --location <myLocation> --name <uniqueName>`
  3. `az storage account create --resource-group <rgName> --name <storageName> --location <myLocation> --sku Standard_LRS`
  4. Get credentials for storage account
     1. Log in to Azure portal
     2. Navigate to newly created storage account
     3. **Security + networking** > **Access Keys** > **Connection string**
        1. Copy Key1
* **Prepare .NET project** (From CLI)
  1. `dotnet new console -n az204-blob`
  2. `cd az204-blob`
  3. `dotnet build`
  4. `mkdir data`
  5. `dotnet add package Azure.Storage.Blobs`
  6. `code Program.cs`
  7. Replace contents with following:
      ```C#
      using Azure.Storage.Blobs;
      using Azure.Storage.Blobs.Models;

      Console.WriteLine("Azure Blob Storage exercise\n");

      // Run the examples asynchronously, wait for the results before proceeding
      ProcessAsync().GetAwaiter().GetResult();

      Console.WriteLine("Press enter to exit the sample application.");
      Console.ReadLine();

      static async Task ProcessAsync()
      {
          // Copy the connection string from the portal in the variable below.
          string storageConnectionString = "CONNECTION STRING";

          // Create a client that can authenticate with a connection string
          BlobServiceClient blobServiceClient = new BlobServiceClient(storageConnectionString);

          // COPY EXAMPLE CODE BELOW HERE

      }
      ```
  8. Replace `"CONNECTION STRING"` with value copied from portal
  9. `dotnet build`
* **Create a container**
  * Steps to create a container
    1. Create instance of `BlobServiceClient`
    2. Call `CreateBlobContainerAsync`
       1. Call will fail if container already exists
    ```C#
    //Create a unique name for the container
    string containerName = "wtblob" + Guid.NewGuid().ToString();

    // Create the container and return a container client object
    BlobContainerClient containerClient = await blobServiceClient.CreateBlobContainerAsync(containerName);
    Console.WriteLine("A container named '" + containerName + "' has been created. " +
        "\nTake a minute and verify in the portal." + 
        "\nNext a file will be created and uploaded to the container.");
    Console.WriteLine("Press 'Enter' to continue.");
    Console.ReadLine();
    ```
* **Upload blobs to a container**
  * Following code snippet does following:
    * gets a reference to `BlobClient` by calling `GetBlobClient` on container created in previous section
    * Uploads selected local file to blob by calling `UploadAsync`
      * Creates blob is it doesn't already exist, overwrites if it does
    ```C#
    // Create a local file in the ./data/ directory for uploading and downloading
    string localPath = "./data/";
    string fileName = "wtfile" + Guid.NewGuid().ToString() + ".txt";
    string localFilePath = Path.Combine(localPath, fileName);

    // Write text to the file
    await File.WriteAllTextAsync(localFilePath, "Hello, World!");

    // Get a reference to the blob
    BlobClient blobClient = containerClient.GetBlobClient(fileName);

    Console.WriteLine("Uploading to Blob storage as blob:\n\t {0}\n", blobClient.Uri);

    // Open the file and upload its data
    using (FileStream downloadFileStream = File.OpenWrite(downloadFilePath))
        {
            await download.Content.CopyToAsync(downloadFileStream);
            downloadFileStream.Close();
        }

    Console.WriteLine("\nThe file was uploaded. We'll verify by listing" + 
            " the blobs next.");
    Console.WriteLine("Press 'Enter' to continue.");
    Console.ReadLine();
    ```
* **List blobs in a container**
  * List blobs by using `GetBlobsAsync` method
    ```C#
    // List blobs in the container
    Console.WriteLine("Listing blobs...");
    await foreach (BlobItem blobItem in containerClient.GetBlobsAsync())
    {
        Console.WriteLine("\t" + blobItem.Name);
    }

    Console.WriteLine("\nYou can also verify by looking inside the " + 
            "container in the portal." +
            "\nNext the blob will be downloaded with an altered file name.");
    Console.WriteLine("Press 'Enter' to continue.");
    Console.ReadLine();
    ```
* **Download blobs**
  * Download blobs by using `DownloadAsync` method
    ```C#
    // Download the blob to a local file
    // Append the string "DOWNLOADED" before the .txt extension 
    string downloadFilePath = localFilePath.Replace(".txt", "DOWNLOADED.txt");

    Console.WriteLine("\nDownloading blob to\n\t{0}\n", downloadFilePath);

    // Download the blob's contents and save it to a file
    BlobDownloadInfo download = await blobClient.DownloadAsync();

    using (FileStream downloadFileStream = File.OpenWrite(downloadFilePath))
    {
        await download.Content.CopyToAsync(downloadFileStream);
    }
    Console.WriteLine("\nLocate the local file in the data directory created earlier to verify it was downloaded.");
    Console.WriteLine("The next step is to delete the container and local files.");
    Console.WriteLine("Press 'Enter' to continue.");
    Console.ReadLine();
    ```
* **Delete a container**
  * Delete container by using `DeleteAsync` method
    ```C#
    // Delete the container and clean up local files created
    Console.WriteLine("\n\nDeleting blob container...");
    await containerClient.DeleteAsync();

    Console.WriteLine("Deleting the local source and downloaded files...");
    File.Delete(localFilePath);
    File.Delete(downloadFilePath);

    Console.WriteLine("Finished cleaning up.");
    ```
* **Run the code**
  * `dotnet build`
  * `dotnet run`
* **Cleanup Resources**
  * `az group delete --name <rgName> --no-wait`
#### **Manage container properties and metadata by using .NET**
* Blob containers support system properties and user-defined metadata
  |||
  |:--|:--|
  |**System Properties**|Exist on each blob storage resource. Some can be read or set, while others are read-only. Under the covers, some system properties correspond to certain standard HTTP headers. The Azure Storage client library for .NET maintains these properties for you|
  |**User-defined metadata**|Consists of one or more name-value pairs that you specify for a Blob storage resource. Can use metadata to store additonal values with the resource. Metadata values are for your own purposes only and do not affect how the resource behaves|
* Metadata name/value pairs are valid HTTP headers
  * Should adhere to all restrictions governing HTTP headers
  * Must be valid HTTP header names and valid C# identifiers
  * May contain only ASCII characters
  * Should be treated as case-sensitive
  * Non-ASCII characters should be Base64-Encoded or URL-Encoded
* **Retrieve container properties**
  * Call one of following methods on `BlobContainerClient` class
    * `GetProperties()` 
    * `GetPropertiesAsync()`
    ```C#
    private static async Task ReadContainerPropertiesAsync(BlobContainerClient container)
    {
        try
        {
            // Fetch some container properties and write out their values.
            var properties = await container.GetPropertiesAsync();
            Console.WriteLine($"Properties for container {container.Uri}");
            Console.WriteLine($"Public access level: {properties.Value.PublicAccess}");
            Console.WriteLine($"Last modified time in UTC: {properties.Value.LastModified}");
        }
        catch (RequestFailedException e)
        {
            Console.WriteLine($"HTTP error code {e.Status}: {e.ErrorCode}");
            Console.WriteLine(e.Message);
            Console.ReadLine();
        }
    }
    ```
* **Set and retrieve metadata**
  * Can specify metadata as one or more name-value pairs on a blob container or resource
  * To set, add name-value pairs to an `IDictionary` then call one of the following methods of `BlobContainerClient` class 
    * `SetMetadata()`
    * `SetMetadataAsync()`
  * To get, call one of following methods of `BlobContainerClient` class
    * `GetProperties()`
    * `GetPropertiesAsync()`
  * Metadata must conform to naming conventions for C# identifiers
    * Names preserve case with which they were created
    * Case-insensitive when set or read
    * If 2+ metadata headers with same name are submit for a resource, Blob storage comma-separates and concatenates the two, returns HTTP response code `200 (OK)`
  * Set metadata example
    ```C#
    public static async Task AddContainerMetadataAsync(BlobContainerClient container)
    {
        try
        {
            IDictionary<string, string> metadata = new Dictionary<string, string>();

            // Add some metadata to the container.
            metadata.Add("docType", "textDocuments");
            metadata.Add("category", "guidance");

            // Set the container's metadata.
            await container.SetMetadataAsync(metadata);
        }
        catch (RequestFailedException e)
        {
            Console.WriteLine($"HTTP error code {e.Status}: {e.ErrorCode}");
            Console.WriteLine(e.Message);
            Console.ReadLine();
        }
    }
    ```
  * Get metadata example
    ```C#
    public static async Task ReadContainerMetadataAsync(BlobContainerClient container)
    {
        try
        {
            var properties = await container.GetPropertiesAsync();

            // Enumerate the container's metadata.
            Console.WriteLine("Container metadata:");
            foreach (var metadataItem in properties.Value.Metadata)
            {
                Console.WriteLine($"\tKey: {metadataItem.Key}");
                Console.WriteLine($"\tValue: {metadataItem.Value}");
            }
        }
        catch (RequestFailedException e)
        {
            Console.WriteLine($"HTTP error code {e.Status}: {e.ErrorCode}");
            Console.WriteLine(e.Message);
            Console.ReadLine();
        }
    }
    ```
#### **Set and retrieve properties and metadata for blob resources by using REST**
* Containers and blob support custom metadata, represented as HTTP headers
  * Metadata headers can be set on a request that creates a new container or blob resource, or on a request that explicitly creates a property on an existing resource
* **Metadata header format**
  * Format of headers is `x-ms-meta-name:string-value`
    * Beginning with `verion 2009-09-19`, metadata names must adhere to naming rules for C# identifiers
  * Names are case-insensitive
    * Names preserve case that they were created with, but are case-insensitive when set or read
  * If 2+ metadata headers with same name are submit for a resource, the Blob service returns a `400 (Bad Reuquest)`
  * Total size of all metadata pairs can be up to 8KB in size
* **Operations on Metadata**
  * Can be retrieved or set directly on blob or container resource without returning or altering content of resource
  * Can only be read or written in full; partial updates not supported
    * Overwrites any existing metadata values for that resource
* **Retrieving properties and metadata**
  * GET and HEAD operations both retrieve metadata headers for container or blob
    * Returns headers ONLY
    * No response body

    |Object|URL syntax|
    |:--|:--|
    |Container|`GET/HEAD https://myaccount.blob.core.windows.net/mycontainer?restype=container`
    |Blobl|`GET/HEAD https://myaccount.blob.core.windows.net/mycontainer/myblob?comp=metadata`

  * PUT operations set metadata headers for container or blob
    * Overwrites existing metadata on resource
    * PUT without any headers clears all existing metadata on resource
    
    |Object|URL syntax|
    |:--|:--|
    |Container|`PUT https://myaccount.blob.core.windows.net/mycontainer?comp=metadata&restype=container`|
    |Blob|`PUT https://myaccount.blob.core.windows.net/mycontainer/myblob?comp=metadata`
* **Standard HTTP properties for containers and blobs**
  * Containers and blobs support certain standard HTTP properties
    * Properties and metadata are represented as headers
    * Difference between them is in the naming convention
      * Metadata headers: `x-ms-meta-<name>`
      * HTTP headers: use standard http header names as specified in _Header Field Definitions_ of section 14 of HTTP/1.1 protocol spec
  * Standard HTTP headers supported
    |Storage Type|Headers|
    |:--|:--|
    |Container|`ETag`</br>`Last-Modified`|
    |Blobs|`ETag`</br>`Last-Modified`</br>`Content-Length`</br>`Content-Type`</br>`Content-MD5`</br>`Content-Encoding`</br>`Content-Language`</br>`Cache-Control`</br>`Origin`</br>`Range`|

## **Develop solutions that use Azure Cosmos DB**
### **Explore Azure Cosmos DB**
#### **Identify key benefits of Azure Cosmos DB**
* Fully managed NoSQL database designed for 
  * low latency
  * elastic scalability of throughput
  * well-defined semantics for data-consistency
  * high-availbility
* **Key benefits of global distribution**
  * multi-master replication protocol suuports writes and reads in every region
  * Multi-master replication protocol also enables
    * Unlimited elastic write and read scalability
    * 99.9999% read/write availability all around world
    * Guaranteed read/write served in less than 10ms at 99th percentile
  * App can perform near real-time read/write against all regions chosen for DB
    * Cosmos DB internally handles data replication between regions with desired consistency level guarantees
  * Running DB in multiple regions increases availability of DB
    * If one region is unavailable, other regions automatically handle app requests
  * 99.9999% read/write availability for multi-region DBs
#### **Explore the resource hierarchy**
* Cosmos DB account is fundamental unit of global distribution and high availability
* Contains unique DNS name
* Manage account through Azure Portal, Azure CLI, or by using different language-specific SDKs
* Can add/remove Azure regions to account any time
* **Elements in an Azure Cosmos DB Account**
  * Cosmos DB Container is the _fundamental unit of scalability_
    * Virtually unlimited throughput (RU/s) and storage
    * Tansparently partitioned using your specified logical partition key
  * Can create _Max of 50_ Azure Cosmos DB accounts under Azure subscription
  * Hierarchy of different entities in Azure Cosmos DB Account
    ![cosmosdb-hierarchy](https://learn.microsoft.com/en-us/training/wwl-azure/explore-azure-cosmos-db/media/cosmos-entities.png)
* **Azure Cosmos DB databases**
  * Can create one or multiple Azure Cosmos DBs under your account
  * A database is analagous to a namespace
  * DB is a _unit of management_ for a set of Azure Cosmos DB containers
* **Azure Cosmos DB Containers**
  * _Unit of scalability_ for _provisioned throughput_ and _storage_
  * A _container_ is horizontally partitioned and then replicated across multiple regions
  * Items added to container are automatically grouped in to logical partitions and then distributed across physical partitions based on partition key
  * Throughput on container is evenly distributed across physical partitions
  * When creating a container, configure throughput to one of following modes:
    |Mode|Description|
    |:--|:--|
    |Dedicated provisioned throughput|Throughput is provisioned on a container is exclusively reserved for that container and it is backed by the SLAs|
    |Shared provisioned throughput|These containers share the provisioned throughput with the other containers in the same database (excluding containers that have been configured with dedicated provisioned throughput). In other words, the provisioned throughput on the database is shared among all the "shared throughput" containers|
  * Container is a schema-agnostic container of items
    * Items in a container can have arbitrary schemas
    * By default, all items added to a container are automatically indexed without requiring explicit index or schema management
* **Azure Cosmos DB Items**
  * Depending on which API is used, an item can represent:
    * document in a collection
    * row in a table
    * node or edge in a graph
#### **Explore consistency levels**
* Cosmos DB has 5 consistency levels ranging from `Strong Consistency` to `Eventual Consistency`
  ![availability-performance-tradeoffs](https://learn.microsoft.com/en-us/training/wwl-azure/explore-azure-cosmos-db/media/five-consistency-levels.png)
* Consistency levels (strongest to weakest)
  * Strong
  * Bounded Staleness
  * Session
  * Consistent Prefix
  * Eventual
* Consistency levels are region-agnostic
  * Guaranteed for all operations
* Read consistency applies to a single read operation scoped within a partition-key range or a logical partition
  * Can be issued by a remote client or stored procedure
#### **Choose the right consistency level**
Each consistency level provides precise availability and performance tradeoffs and is backed by comprehensive SLAs
* **Configure the default consistency level**
  * Can configure consistency level on Azure Cosmos DB account any time
    * Applies to all Azure Cosmos DB databases and containers under account
    * All reads/queries issued against container/DB use specified consistency level by default
* Read consistency applies to a single read operation scoped within a logical partition
  * Can be issued by remote client or stored procedure
* **Guarantees associated with consistency levels**
  * Azure Cosmos DB guarantees 100% of reads meet consistency guarantee for the consistency level chosen
  * Precise definitions of the five consistency levels in Azure Cosmos DB using TLA+ spec language are provided in [azure-cosmos-tla](https://github.com/Azure/azure-cosmos-tla) GitHub repo
* **Strong Consistency**
  * Offers linearizability guarantee
    * Refers to service requests concurrently
  * Reads are guaranteed to return most recent committed version on an item
    * Client never sees uncommitted or partial writes
  * Always guaranteed to read the latest committed write
* **Bounded staleness consistency**
  * Reads are guaranteed to honor the consistent-prefix guarantee
  * Reads might lag behind writes by at most "K" versions (K = updates) of an item or by "T" time interval, which ever is reached first
  * When choosing bounded staleness, staleness can be configured in two ways
    * Number of versions (K) of the item
    * Time interval (T) reads might lag behind writes
  * For single region account, minimum value of K = 10 write ops, T = 5 seconds
  * For multi-region accounts, minimum value of K = 100,000 write ops, T = 300 seconds
* **Session consistency**
  * In a single client session reads are guaranteed to honor consistent-prefix, monotonic reads, monotonic writes, read-your-writes, and write-follows-read guarantees
  * Assumes a single "writer" session or sharing session token for multiple writers
* **Consistent Prefix consistency**
  * Updates made as single document writes see eventual consistency
  * Updates made as a batch within a transaction are returned to the transaction in which they were committed
  * Write operations within a transaction of multiple documents are always visible together
  * Example:
    * Assume 2 write ops are performed on documents Doc1 and Doc2,within transactions T1 and T2
      * When client performs read in any replica, user will see either `{Doc1 V1, Doc2 V1}` or `{Doc1 V2, Doc2 V2}`, but never `{Doc1 V1, Doc2 V2}` for the same read or query
* **Eventual Consistency**
  * No odering guarantee for reads
  * In absence of any further writes, replicas eventually converge
  * Weakest consistency level
    * Client may read values that are older than the ones it had read before
  * Ideal for ordering doesn't matter
    * count of retweets, likes, non-threaded comments
#### **Explore supported APIs**
* Azure Cosmos DB offers multiple DB APIs
  * Azure Cosmos DB for:
    * NoSQL
    * MongoDB
    * PostgreSQL
    * Apache Cassandra
    * Table
    * Apache Gremlin
  * By using these APIs, can model real-world data using documents, key-value, graph, and column-family data models
* **Considerations when choosing API**
  * API for NoSQL is native to Azure Cosmos DB
  * API for MongoDB, PostgreSQL, Cassandra, Gremlin, and Table implement the wire protocol of open-source DB engines
    * Best suited for
      * Have an existing MongoDB, PostgreSQL, Cassandra, or Gremlin apps
      * Don't want to rewrite entire data access layer (DAL)
      * Want to use open-source developer ecosystem, client-drivers, expertise, and resources for your database
* **API for NoSQL**
  * Stores data in document format
  * Offers best end-to-end experience
    * Full control over interface, service, and SDK client libs
  * New features first rolled out to API for NoSQL accounts
  * Provides support for querying items using SQL syntax
* **API for MongoDB**
  * Stores data in a document structure via BSON format
  * Compatible with MongoDB wire protocol
    * Does not use any native MongoDB related code
  * Want to use broader MongoDB exosystem and skills without compromising on CosmosDB features
* **API for PostgreSQL**
  * Managed service for running PostgreSQL at any scale, with the [Citus open source](https://github.com/citusdata/citus) superpower of distributed tables
  * Stores data on a single node, or distributed in a multi-node configuration
* **API for Apache Cassandra**
  * Stores data in column-oriented schema
  * Highly distributed, horizontally scaling approach to storing large volumes of data while offering flexible approach to a solumn-oriented schema
  * Wire protocol compatible with native Apache Cassandra
* **API for Apache Gremlin**
  * Stores data as edges and vertices
    * Allows users to make graph queries
  * Use for scenarios:
    * Involving dynamic data
    * Data with complex relations
    * Data that is too complex to be modeled with relational databases
    * Want to use existing Gremlin ecosystem and skills
* **API for Table**
  * Stores data in key/value format
  * If currently using Azure Table storage, may see limitations in latency, scaling, throughput, global distribution, index management, low query performance
    * API for Table overcomes these limitations and it's recommended to migrate app if want to use benefits of Azure Comsos DB
  * Only supports OLTP scenarios
#### **Discover request units**
* Pay for throughput you provision and the storage consumed per hour
* Throughput must be provisioned to ensure sufficient system resources are available
* Cost of ops are normalized and expressed as _request units_ (RU/s)
  * RU represents system resources such as CPU, IOPS, and memory required to perform DB op
* Cost to do a point read (fetch single item by ID and partition key) for a 1 KB item is 1 RU
![high-level-ru](https://learn.microsoft.com/en-us/training/wwl-azure/explore-azure-cosmos-db/media/request-units.png)
* Type of Azure Cosmos DB account being used determines way consumed RUs get charged

  |Mode|Cost Description|
  |:--|:--|
  |Provisioned throughput mode|Provision number of RUs for app on a per-second basis in increments of 100 RUs/second. To scale provisioned throughput for app, increase or decrease number of RUs at any time. Can amke changes programatically or by using Portal. Can configure at container and database level|
  |Serverless mode|Don't have to provision any throughput. Get billed for amount of request units consumed by DB operations at end of billing period|
  |Autoscale mode|Automatically and instantly scale throughput based on usage. Mode is well suited for mission-critical workloads that have variable or unpredictable traffic patterns, and require SLAs on high performance and scale|
#### **Exercise: Create Azure Cosmos DB resources by using Azure Portal**
* See [Exercise](https://learn.microsoft.com/en-us/training/modules/explore-azure-cosmos-db/8-create-cosmos-db-resources-portal) to create and provision Azure Cosmos DB using Portal.
### **Implement Partitioning in Azure Cosmos DB**
#### **Explore Partitions**
* Items in a container are divided into distinct subsets called _logical partitions_
  * _Logical Partitions_ are formed based on value of a _partition key_ associated with each item in a container
  * All items in a logical partition have same partition key value
  * Example: 
    * Container holds items. 
    * Each item has unique value for `UserID`
    * If `UserID` serves as partition key for items in container and there are 1000 unique `UserId` values, 1,000 logical partitions are created for container
* In addition to a partition key that determines item's logical partition, each item in a container has an _item ID_ which is unique within a logical partition
  * Item's `index` = `partition key` in combination with `item id` 
* Partition key is important decision as it affects apps performance
* **Logical Partitions**
  * Consists of items that have the same partition key
    * For example, if a container has data about food nutrition and all items contain a `foodGroup` property, the `foodGroup` property can be used as parition key
    * Groups of items with specific values for `foodGroup` form distinct logical partitions
  * Define scope of database transactions
  * can update items within a logical partition by using a transaction with snapshot isolation
  * New items that are added create new logical partitions transparently
    * When data is deleted, logical partition is as well
* **Physical Partitions**
  * Container is scaled by distributing data and throughput across physical partitions
  * one or more logical parititions are mapped to a single physical partitition
    * Smaller containers generally have many logical partitions and only 1 physical partition
  * Internal implementation of the system and entirely managed by Azure Cosmos DB
  * Number of physical partitions depends on:
    * Number of throughput provisioned
      * Individual physical partitions can provide throughput up to 10,000 RUs)
      * Limit for physical partitions implies logical partitions also have a 10,000 RU/s limit
    * Total data storage
      * Each physical partition can store up to 50GB of data
  * Throughput provisioned for a container is divded evenly among physical partitions
    * Partition key that doesn't evenly distribute requests may receive too many requests directed at a small subset of the data and become "Hot"
      * "Hot" partitions lead to inefficent use of provisioned throughput and may lead to rate-limiting with higher costs
#### **Choose a partition key**
* Partition key has two components
  * `Partition key path`
    * accepts alphanumeric and underscore characters
    * Can use nested objects by using standard path notation (`/`)
  * `Partition key value`
    * Can be string or numeric types
* Can not change partition keys once selected
  * If need to change, create a new container and move data to it
* For all containers, partition key should:
  * Be a property whose value never changes
  * Have high cardinality (wide range of possible values)
  * Spread RU consumption and data storage evenly across all logical partitions
    * Ensures even distribution of consumption and storage across physical partitions
* **Partition keys for read-heavy containers**
  * Choose a partition key that appears frequently in query filters
    * Queries can be [efficiently routed to only relevant physical partitions](https://learn.microsoft.com/en-us/azure/cosmos-db/how-to-query-container#in-partition-query) by including partition key in filter predicate
  * Most workload requests are queries
    * Most queries have equality filter on same property
      * Good candidate for partition key
  * If container is small, probably don't need to worry about cross-partition queries
    * If it can grow to be large, make sure to pick a partition key that minimizes cross-partition queries
  * Container will require more than a few physical partitions if
    * Container will have >= 30,000 RUs provisioned
    * Container will store > 100GB of data
* **Using Item ID as partition key**
  * If container has a property that has a wide range of possible values, it is likely a great choice
  * For small read-heavy containers or write-heavy containers of any size, _item ID_ is great choice for partition key
  * _item ID_ is a good choice because:
    * wide range of possible values
    * Unique to each item
    * Easily do efficient point reads since item's parition key is always known
  * Considerations when choosing _item ID_ as partition key
    * Will become unique identifier throughout entire container
      * Cannot have items with duplicate _item ID_
    * Have a read-heavy container with a lot of physical partitions
    * Can't run stored procedures or triggers across multiple logical partitions
#### **Create a synthetic partition key**
Synthetic partition keys should be used when your container items do not have a candidate property
* **Concatenate multiple properties of an item**
  * Form a partition key using multiple property values into a single artifical `partitionKey`
  * Example:
    ```JSON
    {
      "deviceId": "abc-123",
      "date": 2018
    }
    ```
    ```JSON
    {
      "deviceId": "abc-123",
      "date": 2018,
      "partitionKey": "abc-123-2018" // deviceId + date
    }
    ```
  * In real-time scenarios, define client-side logic to concatenate values and insert the synthetic key into the items in your cosmos container
* **Use a partition key with a random suffix**
  * Append a random number at the end of partition key value
    * When distributed in this way, can perform parallel write operations across partitions
  * For example, if partition key represents a date, might choose a random number and concatenate it as a suffix to the date
    * Results in partition keys like `2023-01-18.2`, `2023-01-18.90`, etc...
  * Because partition key is randomized, write operations on container on each day are spread evenly across multiple operations
    * This method results in better parallelism and overall higher throughput
* **Use a partition key with pre-calculated suffixes**
  * Can greatly improve write throughput
    * Difficult to read specific item
  * Instead of using a randomly generated number to distribute items, use a number that is calculated based on something you want to query
    * For example, if item has VIN number (vehicle identification number) that is used in queries frequently, before writing item to container append the hash of the VIN to the date to create a unique key
      * Similar results produced by random suffix strategy but can easily read a particular item becuase the parition key can be calculated for a specific VIN
  * Benefit of this is that hot partition keys can be avoided
### **Work with Azure Cosmos DB**
#### **Explore Microsoft .NET SDK v3 for Azure Cosmos DB**
* Focuses on Azure Cosmos DB .NET SDK v3 for API for NoSQL (`Microsoft.Azure.Cosmos` nuget package)
* GitHub repo with examples: [azure-cosmos-dotnet-v3](https://github.com/Azure/azure-cosmos-dotnet-v3/tree/master/Microsoft.Azure.Cosmos.Samples/Usage)
* Because Azure Cosmos DB supports multiple API models, version 3 of SDK uses generic terms
  * Container: collection, graph, or table
  * Item: document, edge/vertex, row
    * content inside container
* **CosmosClient**
  * Creates new cosmos client with a connection string
  * Thread-safe
  * Recommended to maintin a single instance of `CosmosClient` for lifetime of application
    ```C#
    CosmosClient client = new CosmosClient(endpoint, key);
    ```
* **Database Examples**
  * **Create a database**
    * `CosmosClient.CreateDatabaseIfNotExistsAsync` creates DB if it doesn't exist
      * Only database `id` is used to verify
    ```C#
    DatabaseResponse databaseResponse = await client.CreateDatabaseIfNotExistsAsync(databaseId, 10_000);
    ```
  * **Read a database by ID**
    * Reads a DB from Azure Cosmos DB service an async operation
      ```C#
      DatabaseResponse readResponse = await database.ReadAsync();
      ```
  * **Delete a database**
    * Delete DB as async operation
      ```C#
      await database.DeleteAsync();
      ```
* **Container Examples**
  * **Create a container**
    * `Database.CreateContainerIfNotExistsAsync()` creates container if it doesn't exist
      * Only container `id` required
    ```C#
    ContainerResponse response = await database.CreateContainerIfNotExistsAsync(id: containerId, partitionKeyPath: partitionKey, throughput: 400);
    ```
  * **Get container by ID**
    ```C#
    Container container = database.GetContainer(containerId);
    ContainerProperties containerProps = await container.ReadContainerAsync();
    ```
  * **Delete a container**
    ```C#
    await database.GetContainer(containerId).DeleteContainerAsync();
    ```
* **Item Examples**
  * **Create an Item**
    * `Container.CreateItemAsync` creates an item
      * Must be JSON-serializable object that contains an `id` and `partitionKey`
    ```C#
    ItemResponse<SalesOrder> response = await container.CreateItemAsync(salesOrder, new PartitionKey(salesOrder.AccountNumber));
    ```
  * **Read an Item**
    * `Container.ReadItemAsync` to read an item
      * requires type to serialize item to, `id` property, and `partitionKey`
    ```C#
    string id = "[id]";
    string accountNumber = "[partition-key]";
    ItemResponse<SalesOrder> response = await container.ReadItemAsync(id, new PartitionKey(accountNumer));
    ```
  * **Query an Item**
    * `Container.GetItemQueryIterator` creates a query for items under a container using a SQL statement with parameterized values
      * returns `FeedIterator`
    ```C#
    QueryDefinition query = new QueryDefinition("select * from sales s where s.AccountNumber = @accountNumber")
    .WithParameter("@accountNumber", "123456789");

    FeedIterator<SalesOrder> resultSet = container.GetItemQueryIterator<SalesOrder>(query, requestOptions: {
      new QueryRequestOptions()
      {
        PartitionKey = new PartitionKey("123456789"),
        MaxItemCount = 1
      }
    });
    ```
#### **Exercise: Create resources by using the Microsoft .NET SDK 3**
* See [Exercise](https://learn.microsoft.com/en-us/training/modules/work-with-cosmos-db/3-exercise-work-cosmos-db-dotnet) to follow along
1. Connect to Azure: `az login`
2. Create resources in Azure
   1. `az group create --location <myLocation> --name <rgName>`
   2. `az cosmosdb create --name <myCosmosDbAccount> --resource-group <rgName>`
      1. stash `documentEndpoint` as it will be used later
   3. Retrieve primary key for account: `az cosmosdb keys list --name <myCosmosDbAccount> --resource-group <rgName>`
3. Create console application
   1. `md az204-cosmos`
   2. `cd az204-cosmos`
   3. `dotnet new console`
   4. `code . -r`
      1. `-r` flag opens folder without launching new vscode window
4. Add packages and build
   1. `dotnet add package Microsoft.Azure.Cosmos`
   2. Remove all code in Program.cs
   3. Add `using Microsoft.Azure.Cosmos;`
   4. Update _Program.cs_ with below code
      ```C#
      public class Program
      {
          // Replace <documentEndpoint> with the information created earlier
          private static readonly string EndpointUri = "<documentEndpoint>";

          // Set variable to the Primary Key from earlier.
          private static readonly string PrimaryKey = "<your primary key>";

          // The Cosmos client instance
          private CosmosClient cosmosClient;

          // The database we will create
          private Database database;

          // The container we will create.
          private Container container;

          // The names of the database and container we will create
          private string databaseId = "az204Database";
          private string containerId = "az204Container";

          public static async Task Main(string[] args)
          {
              try
              {
                  Console.WriteLine("Beginning operations...\n");
                  Program p = new Program();
                  await p.CosmosAsync();

              }
              catch (CosmosException de)
              {
                  Exception baseException = de.GetBaseException();
                  Console.WriteLine("{0} error occurred: {1}", de.StatusCode, de);
              }
              catch (Exception e)
              {
                  Console.WriteLine("Error: {0}", e);
              }
              finally
              {
                  Console.WriteLine("End of program, press any key to exit.");
                  Console.ReadKey();
              }
          }
          //The sample code below gets added below this line
      }
      ```
5. Add method below 'main' to instantiate `CosmosClient` and method to create container(s)
   ```C#
   public async Task CosmosAsync()
   {
       // Create a new instance of the Cosmos Client
       this.cosmosClient = new CosmosClient(EndpointUri, PrimaryKey);

       // Runs the CreateDatabaseAsync method
       await this.CreateDatabaseAsync();

       // Run the CreateContainerAsync method
       await this.CreateContainerAsync();
   }

   private async Task CreateContainerAsync()
   {
       // Create a new container
       this.container = await this.database.CreateContainerIfNotExistsAsync(containerId, "/LastName");
       Console.WriteLine("Created Container: {0}\n", this.container.Id);
   }
   ```
6. Build & Run
   1. `dotnet build`
   2. `dotnet run`
7. Cleanup
   1. `az group delete --name <rgName> --no-wait`
#### **Create stored procedures**
* Cosmos DB provides language-integrated, transactional execution of JavaScript that lets you write **procedures**, **triggers**, and **user-defined functions (UDF)**

* To call SPROC, trigger, or UDF, need to register it. 
* [How to work with SPROCs, trigger, and UDFs in Azure Cosmos DB](https://learn.microsoft.com/en-us/azure/cosmos-db/sql/how-to-use-stored-procedures-triggers-udfs)
* **Writing Stored Procedures**
  * Simple SPROC that returns _hello world_ response
    ```JavaScript
    var helloWorldStoredProc = {
        id: "helloWorld",
        serverScript: function () {
            var context = getContext();
            var response = context.getResponse();

            response.setBody("Hello, World");
        }
    }
    ```
    * `getContext()` returns a `context` object that provides access to allowed Cosmos DB operations and `request` and `response` objects
      * in this case, the `response` object is used to set body of response and send back to client
* **Create an item using stored procedure**
  * When item is created using a SPROC, the newly created items' ID is returned
  * Is an asynchronous operation and depends on JavaScript callbacks
    * Callback has two parameters:
      * error object in case operation fails
      * return value
    * In the callback, can either handle exception of throw an error
      * If no callback provided and an error is produced, Azure Cosmos DB runtime will throw an error
  ```JavaScript
  var createDocumentStoredProc = {
      id: "createMyDocument",
      body: function createMyDocument(documentToCreate) {
          var context = getContext();
          var collection = context.getCollection();
          var accepted = collection.createDocument(collection.getSelfLink(),
                documentToCreate,
                function (err, documentCreated) {
                    if (err) throw new Error('Error' + err.message);
                    context.getResponse().setBody(documentCreated.id)
                });
          if (!accepted) return;
      }
  }
  ```
* **Arrays as input aprameters for stored procedures**
  * SPROC input parameters are always sent as a string
    * To work around this, define a function within SPROC to parse string as an array
      ```JavaScript
      function sample(arr) {
          if (typeof arr === "string") arr = JSON.parse(arr);

          arr.forEach(function(a) {
              // do something here
              console.log(a);
          });
      }
      ```
* **Bounded execution**
  * All Cosmos DB operations must complete within a limited amount of time
  * SPROCs have a limited amount of time to run on server
  * All collection functions return a boolean that represents success or not
* **Transactions within stored procedures**
  * Can implement transactions on items within a container by using a SPROC
  * JS functions can implement a continuation-based model to batch or resume execution
  ![js-continuation](https://learn.microsoft.com/en-us/training/wwl-azure/work-with-cosmos-db/media/transaction-continuation-model.png)
#### **Create triggers and user-defined functions**
* Supports pre-triggers and post-triggers
  * pre-triggers executed _before_ modifying DB item
  * post-triggers executed _after_ modifying DB item
* Must befine each database operation that a trigger should execute on
* How to register and call a [pre-trigger](https://learn.microsoft.com/en-us/azure/cosmos-db/sql/how-to-use-stored-procedures-triggers-udfs#pre-triggers)/[post-trigger](https://learn.microsoft.com/en-us/azure/cosmos-db/sql/how-to-use-stored-procedures-triggers-udfs#post-triggers)
* **Pre-triggers**
  * Example below shows how a pre-trigger can be used to add a timestamp to an item that is being created if it doesn't exist
    ```JavaScript
    function validateToDoItemTimestamp() {
        var context = getContext();
        var request = context.getRequest();

        // item to be created in the current operation
        var itemToCreate = request.getBody();

        // validate properties
        if (!("timestamp" in itemToCreate)) {
            var ts = new Date();
            itemToCreate["timestamp"] = ts.getTime();
        }

        // update the item that will be created
        request.setBody(itemToCreate);
    }
    ```
  * pre-triggers can not have input parameters
  * Manipulates the request object of the request
  * Above example would be created with a `TriggerOperation` of `TriggerOperation.Create`
    * Would only apply to create operations
* **Post-Triggers**
  * Example queries for metadata item and updates it with details
    ```JavaScript
    function updateMetadata() {
      var context = getContext();
      var container = context.getCollection();
      var response = context.getResponse();

      // item that was created
      var createdItem = response.getBody();

      // query for metadata document
      var filterQuery = 'SELECT * FROM root r WHERE r.id = "_metadata"';
      var accept = container.queryDocuments(container.getSelfLink(), filterQuery,
          updateMetadataCallback);
      if(!accept) throw "Unable to update metadata, abort";

      function updateMetadataCallback(err, items, responseOptions) {
          if(err) throw new Error("Error" + err.message);
              if(items.length != 1) throw 'Unable to find metadata document';

              var metadataItem = items[0];

              // update metadata
              metadataItem.createdItems += 1;
              metadataItem.createdNames += " " + createdItem.id;
              var accept = container.replaceDocument(metadataItem._self,
                  metadataItem, function(err, itemReplaced) {
                          if(err) throw "Unable to update metadata, abort";
                  });
              if(!accept) throw "Unable to update metadata, abort";
              return;
          }
      }
    ```
  * Post-triggers run as part of same transaction
    * Failure in post-trigger causes transaction to fail
      * Anything committed will be rolled back
* **User-Defined Functions (UDF)**
  * UDFs would be used in a SPROC or a query
  * Example to calculate income tax for various brackets
    ```JavaScript
    function tax(income) {
      if(income == undefined)
          throw 'no input';

      if (income < 1000)
          return income * 0.1;
      else if (income < 10000)
          return income * 0.2;
      else
          return income * 0.4;
    }
    ```

## **Implement Infrastructure as a Service solutions (IaaS)**
### **Provision Virtual Machines in Azure**
#### **Explore Azure Virtual Machines**
* Flexibility of virtualization without physical hardware purchase/maintenance
  * Still requires maintenance - configuring, patching, software installation/updates
* Can be used in various ways
  |Usage|Description|
  |:--|:--|
  |Development and Test|Azure VMs offer a quick and easy way to create a computer with specific configurations required to code and test an application|
  |Applications in the cloud|Because demand for your app can fluctuate, may make sense to run it on a VM in Azure. Pay for extra VMs when needed, and shut them down when they're not|
  |Extended datacenter|VMs in Azure virtual network can easily be connected to your organization's network|
* **Design considerations for VM creation**
  |Consideration|Explanation|
  |:--|:--|
  |Availability|Azure supports a single instance VM SLA of 99.9% provided it is deployed with _premium storage for **all** disks_|
  |VM Size|Subscription has default quota limits in place. Current limit on a per subscription basis is 20VMs per region. Limits can be raised by filing a [support ticket requesting an increase](https://learn.microsoft.com/en-us/azure/azure-portal/supportability/regional-quota-requests)|
  |VM Image|Use your own or use image from Azure Marketplace. Can get list of images by running `az vm image list`. See [list popular images](https://learn.microsoft.com/en-us/azure/virtual-machines/linux/cli-ps-findimage#list-popular-images) for additional information|
  |VM Disks|Two components make up this area. Azure provides two types of disks:<br/></br>**Standard Disks**: Backed by HDDs, most cost-effective, ideal for dev/test.</br></br>**Premium Disks**: Backed by SSDs, high-performance and low-latency. Ideal for production workloads<br/></br>**Options for disk storage**</br></br>**Managed Disks**: Recommended disk storage model. Specify size <= 4TB. Azure creates and manages both disk and storage. No need to worry about storage account limits which makes this choice easier to scale out than unmanaged disks.</br></br>**Unmanaged Disks**: You're responsible for storage accounts that hold VHDs that correspond to VM disks. Pay for storage account rates for the amount of space used. Single storage account has fixed-rate limit of 20,000 I/O ops/second. Storage account is capable of supporting 40 standard VHDs at full utilization. Scaling out more disks requires mor storage accounts.|
* **Virtual machine extensions**
  * Windows VMs have extensions that give VM additional capabilities through post-deployment configurations and automated tasks. 
  * Common tasks that be completed using extensions
    |||
    |:--|:--|
    |Run custom scripts|Custom Script Extension helps configure workloads on VM by running your script when VM is provisioned|
    |Deploy and manage configurations|The PowerShell Desired State Configuration(DSC) Extension helpers set up DSC on a VM to manage configurations and environments|
    |Collect diagnostics data|Azure Diagnostics Extension helps configure VM to collect diagnostic data that can be used to monitor the health of application|
  * For Linux VMs, Azure supports [cloud-init](https://cloud-init.io/) across most Linux distros that support it and works with all major tooling like Ansible, Chef, SaltStack, and Puppet
#### **Compare Virtual Machine availability options**
* **Availability Zones**
  * Physically separate zone within an Azure region
    * 3 Availability Zones per supported Region
  * Is combination of a _fault domain_ and _update domain_
    * For example, 3 VMs across 3 zones
      * VM is distributed across 3 fault domains and 3 update domains
      * Azure recognizes this across the update domains to make sure VMs in different zones are not scheduled to update at the same time
  * High availability can be built in to app architecture by co-locatig compute, storage, networking, and data resources within the zone and replicating in other zones
  * _Availability Zones_ fall in to 2 categories
    |Category|Description|
    |:--|:--|
    |Zonal services|Resources is pinned to a specific zone (i.e. VMs, managed disks, standard IP addresses)
    |Zone-redundant services|When Azure platform replicates automatically across zones (i.e. zone-redundant storage, SQL)|
* **Availability Sets**
  * Logical grouping of VMs
  * Allows Azure to understand how app is built to provide redundancy and availability
  * Availability set composed of two additional groupings that protect against hardware failures and safely allow updates
    * Fault Domains (FDs)
    * Update Domains (UDs)
* **Fault Domains**
  * Logical grouping of hardware that share common power source and network switch
    * Think of a server rack in an on-prem solution
  * When creating VM, Azure automatically distributes VM across Fault Domain
  * Limits potential for
    * hardware failures
    * network outages
    * power interruptions</br>
    ![fault-domain](https://learn.microsoft.com/en-us/training/wwl-azure/provision-virtual-machines-azure/media/virtual-machine-fault-domains.png)
* **Update Domains**
  * logical group of underlying hardware
  * When VMs are created within _availability set_, Azure automatically distributes VM across update domains
    * Ensures updates do not take down app for Azure platform periodic maintenance
  * Only 1 update domain is rebooted at a time
* **Virtual Machine Scale Sets (VMSS)**
  * Create and manage group of load balanced VMs
  * Basically [Autoscale](#explore-autoscale-best-practices) for VMs
  * Additional info on VMSS can be found [here](https://learn.microsoft.com/en-us/azure/virtual-machine-scale-sets/overview?context=/azure/virtual-machines/context/context)
    * Key benefits of using VMSS
      * Easy to create and manage multiple VMs
      * High-availability and application resiliency
      * Allows app to automatically scale as demand changes
      * Works at large-scale
        * upto 1,000 VM instances for standard marketplace images through Azure Compute Gallery (formerly known as Shared Image Gallery)
* **Load Balancer**
  * Combine [Azure Load Balancer](https://learn.microsoft.com/en-us/azure/load-balancer/load-balancer-overview) with availability zone or availability set to get the most application resiliency
  * Is a Layer-4 (TCP,UDP) load balancer
    * Monitors given port on each VM and distributes traffic to an operational VM
  * Must define a front-end IP that contains 1+ public IPs
    * Allows load balancer and applications to be accessible over internet
  * VMs connect to internet using virtual NIC
    * To distribute traffic, load balancer has a back-end IP address pool that contains v-NICs connected to load balancer
  * Can define rules for ports and protocols that map to VM to control traffic flow
#### **Determine appropriate virtual machine size**
* Best way to decide VM size is to understand type of workload VM needs to run
* Workload options are classified as follows
  |VM Type|Description|
  |:--|:--|
  |General Purpose|Balanced CPU-to-memory ratio. Ideal for development and testing, small-medium databases and low-medium traffic web servers|
  |Compute Optimized|High CPU-to-memory ratio. For medium traffic web servers, network appliances, btach processes, and app servers|
  |Memory Optimized|High memory-to-CPU ratio. Great for relational DB servers, medium-large caches, and in-memory analytics|
  |Storage Optimized|High disk throughput and IO. Ideal for big data, NoSQL DBs, data warehousing, and large OLTP DBs|
  |GPU|Specialized VMs targeting heavy graphic rendering and video editing, as well as model training and inferencing (ND) with deep learning. Single or multi-gpu options.|
  |High Performance Compute|Fastest and most powerful CPU VM. Optional high-throughput network interfaces (RDMA)|
* Can resize VM anytime as long as the current hardware configuration allows for it
  * provides agile and elastic approach to VM management
  * If stop and deallocate VM, can select any size available in region since VM is removed from cluster it was running on
  > 🔴**CAUTION**</br>
  > When resizing production VMs they will be rebooted automatically which may cause temporary outage and change some configuration settings such as IP address
* Additional Resources
  * [Linux pricing](https://azure.microsoft.com/pricing/details/virtual-machines/#Linux)
  * [Windows pricing](https://azure.microsoft.com/pricing/details/virtual-machines/Windows/#Windows)
  * [VM size avaiability by region](https://azure.microsoft.com/regions/services/)
#### **Exercise: Create a VM by using the Azure CLI**
* Exercise goals:
  * Create RG and VM
  * Install web server
  * View web server in action
  * Clean up resources
1. Login to Azure: `az login`
2. Create RG and VM
   1. `az group create --name az-204-vm-rg --location <myLocation>`
   2. ```bash
      az vm create \
        --resource-group az204-vm-rg \
        --name az204vm \
        --image UbuntuLTS \
        --generate-ssh-keys \
        --admin-user az204admin \
        --public-ip-sku Standard
      ```
       * by default, only SSH connections are opened when Linux VM is created in Azure
3. Install webserver on VM
   1. `az vm open-port --port 80 --resource-group az204-vm-rg --name az204vm`
   2. `ssh az204admin@<publicIpAddress>`
   3. `sudo apt-get -y update`
   4. `sudo apt-get -y install nginx`
4. Open a web browser and navigate to the public ip address of the created VM, a 'Welcome to nginx' web page should display
5. Clean up resources
   1. `az group delete --name az204-vm-rg --no-wait`
### **Create and Deploy Azure Resource Manager Templates (ARM)**
#### **Explore Azure Resource Manager**
* When Azure Resource Manager receives request from Azure tools, APIs, SDKs, or Resource Manager, it authenticates and authorizes the request
  * Resource Manager sends request to the Azure servie which takes the requested action
* ARMs role in handling Azure requests
  ![arm-role-hl](https://learn.microsoft.com/en-us/training/wwl-azure/create-deploy-azure-resource-manager-templates/media/consistent-management-layer.png)
* **Why choose Azure Resource Manager templates**
  |Advantage|Explanation|
  |:--|:--|
  |Declarative syntax|ARM templates can create and deploy entire infrastructures decalaratively. i.e. VMs, network infra, storage, compute, etc...|
  |Repeatable results|Repeatedly deploy your infrastructure throughout deployment lifecycle and have confidence resources are deployed in a consistent manner. _Templates are idempotent_, meaning, deploy the same template many times and get same result. Can develop template that represents desired state, rather than developing lots of separate templates to represent updates|
  |Orchestration|Azure handles the complexity of ordering operations. Resource Manager orchestrates deployment of interdependent resources so they're created in correct order. Will deploy in parallel when possible to reduce deployment time. Single command to deploy template|
* **Template File**
  * Can write template expressions that extend capabilities of JSON
    * These expressions make use of Resource Manager [functions](https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/template-functions)
  * Templates have the following sections:
    |Section|Description|
    |:--|:--|
    |Parameters|Provide values during deployment that allow the same template to be used with different environments
    |Variables|Define values that are reused in templates; can be constructed from parameters|
    |User-defined Functions| Create customized functions that simplify your template|
    |Resources|Specify resources to deploy|
    |Outputs|Return values from deployed resources|
#### **Deploy multi-tiered solutions**
* With Resource Manager, can create a template in JSON that defines infrastructure and configuration of Azure solution
  * This approach allows a repeatable and consistent deployment solution throughout its lifecycle
* When a template is deployed, Resource Manager converts the template in to REST API operations
  * Example: ARM Template to create a storage account
    ```JSON
    "resources": [
      {
        "type": "Microsoft.Storage/storageAccounts",
        "apiVersion": "2019-04-01",
        "name": "mystorageaccount",
        "location": "westus",
        "sku": {
          "name": "Standard_LRS"
        },
        "kind": "StorageV2",
        "properties": {}
      }
    ]
    ```
    Is converted to
    ```
    PUT
    https://management.azure.com/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Storage/storageAccounts/mystorageaccount?api-version=2019-04-01
    REQUEST BODY
    {
      "location": "westus",
      "sku": {
        "name": "Standard_LRS"
      },
      "kind": "StorageV2",
      "properties": {}
    }
    ```
    * API version that is set in the `apiVersion` property is the API version for the REST operation. This ensures that template will continue to work if a new version is released
* Deploy templates using any of the following methods:
  * Azure Portal
  * Azure CLI
  * PowerShell
  * REST API
  * Button in GitHub repo
  * Azure Cloud Shell
* **Defining multi-tiered templates**
  * How templates and resource groups are defined are up to individual
    * For example, can deploy a 3-tier application through a single template to a single resource group if you want to
      ![three-tier-arm](https://learn.microsoft.com/en-us/training/wwl-azure/create-deploy-azure-resource-manager-templates/media/three-tier-template.png)
  * Can define multiple templates to be used in a 'parent' template
    * i.e. define Storage template, VM template, Network template, etc...
    ![master-template](https://learn.microsoft.com/en-us/training/wwl-azure/create-deploy-azure-resource-manager-templates/media/nested-tiers-template.png)
  * ARM analyzes dependencies to ensure resources are created in correct order
    * For example, if a resource relies on another resource (VM needing storage account), set a dependency
      * See [MS Learn ARM Resource Dependency](https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/resource-dependency)
  * Can also use templates for updates to infrastructure
    * For example, can add a resource to solution and add configuration rules for existing resources
      * If resources do not exist, they are created. If they do exist, they are updated
  * Resource Manager procides extensions for additional secnarios (i.e. installing software)
    * If configuration management service already in place, can continue working with that service by using extensions
* **Share Templates**
  * Can share templates with other users in organization.
  * [Template specs](https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/template-specs) enable you to store a template as a resource type
    * Can then use RBAC to manage access to the template spec
      * Read access users and see and deploy the template, but not modify
#### **Explore conditional deployment**
* Conditionally deploy a resource in an ARM template using `condition` element
  * `condition` value resolves to true/false
    * When true, resource is created. Otherwise, it isn't
    * Can only be applied to the entire resource
  > 🔵**NOTE**</br>
  > Conditional deployment does not cascade to [child resources](https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/child-resource-name-type). To conditionally deploy a resource and its child resources, same `condition` needs to be applied to each resource type
* **New or Existing Resource**
  * Can use `condition` to deploy a new or use an existing resource
  * Example: Use condition to deploy a new storage account or use existing storage account.
    ```JSON
    {
      "$schema": "https://schema.management.azure.com/schemas/2019-04-01/deploymentTemplate.json#",
      "contentVersion": "1.0.0.0",
      "parameters": {
        "storageAccountName": {
          "type": "string"
        },
        "location": {
          "type": "string",
          "defaultValue": "[resourceGroup().location]"
        },
        "newOrExisting": {
          "type": "string",
          "defaultValue": "new",
          "allowedValues": [
            "new",
            "existing"
          ]
        }
      },
      "functions": [],
      "resources": [
        {
          "condition": "[equals(parameters('newOrExisting'), 'new')]",
          "type": "Microsoft.Storage/storageAccounts",
          "apiVersion": "2019-06-01",
          "name": "[parameters('storageAccountName')]",
          "location": "[parameters('location')]",
          "sku": {
            "name": "Standard_LRS",
            "tier": "Standard"
          },
          "kind": "StorageV2",
          "properties": {
            "accessTier": "Hot"
          }
        }
      ]
    }
    ```
    * Example uses `newOrExisting` as a condition in the `resources` section
* **Runtime Functions**
  * If `reference` or `list` functions are used with a resource that is conditionally deployed, the function is evaluated even if resource isn't deployed
    * This can lead to errors if the resource does not exist
  * Use the `if` function to make sure function is only evaluated for conditions when resource is deployed
  * Set a resource as dependent on conditional resource just like any other resource
    * When conditional resource isn't deployed, ARM removes it from required dependencies
#### **Set the correct deployment mode**
* When deploying resources, specify if it is incremental or complete update
  * Default mode is incremental
* Resource Manager tries to create all resources in template for both modes
  * If resource exists and settings unchanged, no action is taken
  * If property changes in resource, the reouse is updated
  * Attempting to change location or type of existing resource results in error
    * Deploy a new resource with location or type desired
* **Complete Mode**
  * Resource Manager deletes resources that exist in RG that aren't specified in template
  * If template includes a resource that isn't deployed because `condition` is false
    * `API version < 2019-05-10`, resource is _**not**_ deleted
    * `API version >= 2019-05-10`, resource is deleted
    * Latest versions of Azure PoSH and CLI delete the resource
  * Careful using `copy loops` with complete mode
    * Resource not specified in template after resolving copy loop are deleted 
* **Incremental Mode**
  * Resource manager leaves _unchanged_ resources that exist in RG but aren't specified in template
  * Redeploying an existing resource
    * must specify _all_ properties, not just ones being updated
      * if left out, they are overwritten
* **Example Result**
  * Difference between `incremental` and `complete` modes
    |Resource Group contains|Template contains|Incremental Result|Complete Result|
    |:--|:--|:--|:--|
    |Resource A|Resource A|Resource A|Resource A|
    |Resource B|Resource B|Resource B|Resource B|
    |Resource C|Resource D|Resource C|Resource D|
    |||Resource D|
* **Set Deployment Mode**
  * With PowerShell, use `Mode` parameter
    * ```POWERSHELL
      New-AzResourceGroupDeployment `
      -Mode Complete `
      -Name ExampleDeployment `
      -ResourceGroupName ExampleResourceGroup `
      -TemplateFile C:\templates\storage.json
      ```
  * With Azure CLI, use `mode` parameter
    * ```
      az deployment group create \
        --mode Complete \
        --name ExampleDeployment \
        --resource-group ExampleResourceGroup \
        --template-file storage.json
      ```
#### **Exercise: Create and deploy ARM templates by using VS Code**
1. Open VS Code
2. Create new file named _azuredeploy.json_
3. enter `arm` in file and select `arm!` from autocomplete
   ![arm-autocomplete](https://learn.microsoft.com/en-us/training/wwl-azure/create-deploy-azure-resource-manager-templates/media/template-start.png)
   1. File should look similar to
      ```JSON
      {
        "$schema": "https://schema.management.azure.com/schemas/2019-04-01/deploymentTemplate.json#",
        "contentVersion": "1.0.0.0",
        "parameters": {},
        "functions": [],
        "variables": {},
        "resources": [],
        "outputs": {}
      }
      ```
4. Add resource to template
   1. in `resources` section type `storage`
   2. select `arm-storage` from autocomplete
   3. `resources` block should be similar to
      ```JSON
      "resources": [{
          "name": "storageaccount1",
          "type": "Microsoft.Storage/storageAccounts",
          "apiVersion": "2019-06-01",
          "tags": {
              "displayName": "storageaccount1"
          },
          "location": "[resourceGroup().location]",
          "kind": "StorageV2",
          "sku": {
              "name": "Premium_LRS",
              "tier": "Premium"
          }
      }],
      ```
5. Add parameters to template
   1. Place cursor in `parameters` block, press enter, type `"` and select `new-parameter` from snippet
   2. Update name of param to `storageAccountName`
   3. Update description to `Storage Account Name`
   4. Add both `minLength` and `maxLength` to parameter and provide appropriate values
      1. `minLength` = 3
      2. `maxLength` = 24
   5. `parameters` should look to similar to
      ```JSON
      "parameters": {
          "storageAccountName": {
              "type": "string",
              "metadata": {
                  "description": "Storage Account Name"
              },
              "minLength": 3,
              "maxLength": 24
          }
      },
      ```
6. Update name property of storage resource to use parameter
   1. in `resources` block, delete `storageaccount1`, leave `""`
   2. enter `[` to see ARM template functions, select `parameters`
   3. add `()` at end of `parameters`
   4. select `storageAccountName` from pop-up
      1. if parameter list does not display, enter `'` in `()` to display parm list
  5. `resources` section should be similar to
      ```JSON
      "resources": [{
          "name": "[parameters('storageAccountName')]",
          "type": "Microsoft.Storage/storageAccounts",
          "apiVersion": "2019-06-01",
          "tags": {
              "displayName": "storageaccount1"
          },
          "location": "[resourceGroup().location]",
          "kind": "StorageV2",
          "sku": {
              "name": "Premium_LRS",
              "tier": "Premium"
          }
      }],
      ```
* **Create a Parameter file**
  * Allows you store environment-specific parameter values and pass them in as a group at deployment time
    * Useful when multiple environments are in play (i.e. dev, stage, prod, etc...)
  1. in _azuredeploy.json_, open **Command Palette**
  2. enter `parameter`
  3. select **Azure Resource Manager Tools:Select/Create Parameter File**
  4. select **New**
  5. select **All Paramters**
  6. edit `value` parameter and type name that meets naming requirements
  7. _azuredeployment.parameters.json_ should look similar to
    ```JSON
    {
        "$schema": "https://schema.management.azure.com/schemas/2019-04-01/deploymentParameters.json#",
        "contentVersion": "1.0.0.0",
        "parameters": {
            "storageAccountName": {
                "value": "az204storageacctarm" 
            }
        }
    }
    ```
* **Deploy the template**
  1. `az login`
  2. `az group create --name az204-arm-rg --location <myLocation>`
  3. `az deployment group create --resource-group az204-arm-rg --template-file azuredeploy.json --parameters azuredeploy.parameters.json`
  4. `az storage account show --resource-group az204-arm-rg --name <myStorageAccount>`
* **Clean up resources**
  * `az group delete --name az204-arm-rg --no-wait`
### **Manage Container Images in Azure Container Registry (ACR)**
Use ACR service with existing container development/deployment pipelines, or use ACR Tasks to build container images in Azure. Build on demand, or automated builds with triggers such as source code commits and base image updates
#### **Discover the Azure Container Registry (ACR)**
* **Use Cases**
  * Pull images from Azure container registry to various deployment targets
    * **Scalable orchestration systems** that manage containerized applications across clusters of hosts, including Kubernetes, DC/OS, and Docker Swarm
    * **Azure services** that support building and running applications at scale, includeing Azure Kubernetes Service (AKS), App Service, Batch, Service Fabric, and others
  * Can also push to container registry as part of container dev workflow
    * For example, target container registry from CI tool such as Azure Piplines or Jenkins
  * Configure ACR Tasks to automatically rebuild images when base images are updated, or automate image buils when team commits to a Git repo
  * Create multi-step tasks to automate build, test, and patching multiple container images in parallel in the cloud
* **Azure Container Registry service tiers**
  * Multiple service tiers
  * Predictable pricing and several options for aligning to capacity and usage patterns of private Docker registry in Azure
  
    |Tier|Description|
    |:--|:--|
    |Basic|Cost-optimized entry point for devs learning about ACR. Same capabilities as Standard and Premium (such as Azure AD, auth integration, image deletion, and webhooks). Storage and image throughput designed for lower throughput|
    |Standard|Same as basic but with increased included storage and image throughput. Generally satisfy most production scenarios|
    |Premium|Highest amout of included storage and concurrent ops, enabling high-volume scenarios. Adds geo-replication for managing single registry across multiple regions, content trust for image tag signing, and private link with private endpoints to restrict access to registry|
* **Supported images and artifacts**
  * Each image is a read-only snapshot of Docker-compatible container
  * Supports Windows and Linux images
  * ACR also stored related content formats such as [Helm charts](https://learn.microsoft.com/en-us/azure/container-registry/container-registry-helm-repos) and images built to the [Open Container Initiative (OCI) Image Format Specification](https://github.com/opencontainers/image-spec/blob/master/spec.md)
* **Automated Image Builds**
  * use ACR Tasks to streamline building, testing, pushing, and deploying images in Azure
  * Configure build tasks to automate container OS and framework patching pipeline, and build automatically when team commits code
#### **Explore storage capabilities**
* All tiers benefit from advanced Azure storage features like encryption-at-rest for image data security and geo-redundancy for image data protection
  |Capability|Description|
  |:--|:--|
  |Encryption-at-rest|All images in registry are encrypted at rest. Encrypts before storing and decrypts on-the-fly when requested|
  |Regional storage|ACR stores data in region where registry is created. All regions **except** Brazil South and Southeast Asia, Azure may store registry data in a paired region in same geography. in Brazil South and Southeast Asia, data always confined to region.</br></br>Regional outages may render registry data unavailable. Can enable geo-replication to have resiliency|
  |Zone redundancy|_Premium_ service tier only. Uses Azure _availability zones_ to replicate registry to a minimum of 3 separate zones in each enabled region|
  |Scalable storage|ACR allows you to create as many repos, images, layers, or tags as needed, up to registry [storage limit](https://learn.microsoft.com/en-us/azure/container-registry/container-registry-skus#service-tier-features-and-limits)|
  > 🔵**NOTE**</br>
  > High number of repos and tags can cause performance issues. Periodically delete unused repos, tags, and images. Deleted registry resources can not be recovered
#### **Build and manage containers with tasks**
ACR Tasks is a suit of features within an ACR. Provides cloud-vased container image building for platforms including Linux, Windows, and ARM, and can automate OS and framework patching for Docker containers. ACR Tasks enables automated builds triggered by code updates, container base image updates, or timers.
* **Task scenarios**
  * **Quick Task**
    * Build and push single container image to a container registry on-demand, in Azure, without needing a local Docker Engine installation
    * Think `docker build` and `docker push` in the cloud
  * **Automatically triggered tasks**
    * Enable on or more _triggers_ to build an image
      * Source code updates
      * Base image updates
      * Schedule based
  * **Multi-step task**
    * Extend single image build-and-push capability of ACR Tasks with multi-step, multi-container-based workflows
* **Quick Task**
  * Before committing first line of code, ACR Tasks's quick task feature can provide integrated development experience by offloading container image builds to Azure
  * Can verify automated build definitions and catch potential issues before committing code
  * Uses familiar `docker build` format
    * `az acr build` command in Azure CLI
      * Takes a context (set of files to build), sends to ACR Tasks, and by default, pushes build image to its registry upon completion
* **Trigger task on source code update**
  * Trigger container build or multi-step task when code is committed
    * Or PR is made or updated to public or private repo in GitHub or DevOps
  * Configure a build task with Azure CLI command `az acr task create` by specifying Git repo, (optionally) branch, and Dockerfile
    * When code is updated in repo, ACR Tasks-created webhook trigger build of container image defined in repo
* **Schedule a task**
  * Schedule a task by setting up on ore more timer triggers
  * Useful for running container workloads on defined schedule, running maintenance ops, or tests on images
* **Multi-step tasks**
  * Defined in [YAML file](https://learn.microsoft.com/en-us/azure/container-registry/container-registry-tasks-reference-yaml)
    * Specify individual build/push ops for container images and other artifacts
  * Can define execution of 1+ containers
    * Each step using container as execution environment
  * For example, create multi-step task to automate:
    * Build web app image
    * Run web app image
    * Build web app test image
    * Run web app test container, which runs tests against running app container
    * If tests pass, build Helm chart archive package
    * Perform `helm upgrade` using new Helm chart archive package
#### **Explore elements of a Dockerfile**
* Must understand Dockerfile structure to create custom containers
* Following aspects of image are defined
  * Base or parent image used to create new image
  * Commands to update base OS and install additional software
  * Build artifacts to include, such as developed application
  * Service to expose, such as storage and network configuration
  * Command to run when container is launched
* Example Dockerfile for creating Docker image for ASP.NET Core site
  ```DOCKER
  # Step 1: Specify the parent image for the new image
  FROM ubuntu:18.04

  # Step 2: Update OS packages and install additional software
  RUN apt -y update &&  apt install -y wget nginx software-properties-common apt-transport-https \
    && wget -q https://packages.microsoft.com/config/ubuntu/18.04/packages-microsoft-prod.deb -O packages-microsoft-prod.deb \
    && dpkg -i packages-microsoft-prod.deb \
    && add-apt-repository universe \
    && apt -y update \
    && apt install -y dotnet-sdk-3.0

  # Step 3: Configure Nginx environment
  CMD service nginx start

  # Step 4: Configure Nginx environment
  COPY ./default /etc/nginx/sites-available/default

  # STEP 5: Configure work directory
  WORKDIR /app

  # STEP 6: Copy website code to container
  COPY ./website/. .

  # STEP 7: Configure network requirements
  EXPOSE 80:8080

  # STEP 8: Define the entry point of the process that runs in the container
  ENTRYPOINT ["dotnet", "website.dll"]
  ```
  * `ENTRYPOINT` indicates which process will execute once container is run from an image
* [Dockerfile Reference](https://docs.docker.com/engine/reference/builder/)
#### **Exercise: Build and run a container image by using Azure Container Registry (ACR) Tasks**
1. Log in to Azure or use Azure CLI tools `az login`
2. `az group create --name az204-acr-rg --location <myLocation>`
3. ```
   az acr create \
    --resource-group az204-acr-rg \
    --name <myContainerRegistry> \
    --sku Basic
   ```
4. Create or navigate to a local directory for Dockerfile creation
   1. `cd dockerExample` or `mkdir dockerExample && cd dockerExample`
5. `echo FROM mcr.microsoft.com/hello-world > Dockerfile`
6. ```
   az acr build \ 
    --image sample/hello-world:v1 \
    --registry <myContainerRegistry> \
    --file Dockerfile
   ```
7. Verify result: `az acr repository list --name <myContainerRegistry> --output table`
8. List tags 
   ```
   az acr repository show-tags \
    --name <myContainerRegistry> \
    --repository sample/hello-world \
    --output table
    ```
9. Run image in ACR
   ```
   az acr run \
    --regitry <myContainerRegistry> \
    --cmd '$Regitry/sample/hello-world:v1' /dev/null
   ```
   1.  `cmd` runs container in its default configuration
       1.  Also supports additional `docker run` parameters or other `docker` commands
10. Cleanup resources: `az group delete --name az204-acr-rg --no-wait`
### **Run Container Images in Azure Container Instances (ACI)**
#### **Explore Azure Container Instances (ACI)**
* Great solution for scenarios that can operate in isolated containers, including simple apps, task automation, and build jobs
  |Benefit||
  |:--|:--|
  |Fast Startup|ACI can start containers in Azure in seconds, no need to provision and manage VMs|
  |Container access|ACI enables exposing container groups directly to internet with an IP address and fully qualified domain name (FQDN)|
  |Hypervisor-level security|Isolate app as it would be in VM|
  |Customer data|ACI service stored minimum customer data required to ensure container groups are running as expected|
  |Custom sizes|Provides optimum utilization by allowing exact specifications of CPU cores and memory|
  |Persistent storage|Mount Azure Files shares directly to a container to retrieve and persist state|
  |Linux and Windows|Schedule both containers using the same API|
* When you need full container orchestration, including service discovery across multiple containers, autoscaling, coordinated app updates, it is recommended to use [Azure Kubernetes Service (AKS)](https://learn.microsoft.com/en-us/azure/aks/)
* **Container groups**
  * Top-level resource in ACIs is _container group_
    * Collection of containers that scheduled on same host machine
  * Containers in group share lifecycle, resources, local network, and storage columns
    * Similar to _pod_ in Kubernetes
  * Example container group with multiple containers
    ![container-group-example](https://learn.microsoft.com/en-us/training/wwl-azure/create-run-container-images-azure-container-instances/media/container-groups-example.png)
  > 🔵**NOTE**</br>
  > Multi-container groups are currently only supported with Linux containers. For Windows containers, ACI only supports deployment of single instance.
* **Deployment**
  * Two common ways to deploy multi-container groups
    * Resource Manager templates
      * When additional Azure resources are needed. For example, Azure File Shares
    * YAML file
      * When deployment only includes container instances
* **Resource allocation**
  * ACIs allocate resources such as CPU, Memory, and optionally GPU (preview) to a container group by adding resource requests of the instances in the group
    * For example:
      * Container group with two instances, each requesting 1 CPU
        * Container group is allocated 2 CPUs
* **Networking**
  * Container groups share IP address and port namespace on that IP
  * Must expose a port on IP to expose container within a group to external clients
    * Port mapping not supported
  * Containers in a group can reach each other via loalhost on teh ports they have exposed
    * Do not need to be exposed externally on groups IP
* **Storage**
  * Can specify external volumes to mount within a container group
  * Can map volumes to specific paths within individual containers in a group
  * Supported volumes:
    * Azure File Share
    * Secret
    * Empty directory
    * Cloned git repo
* **Common scenarios**
  * Multi-container groups are useful in cases where you want to divide a single functional task into small number of container images
    * Images can be delivered by different teams and have separate resource requirements
  * Example usages:
    * Container serving web app and container pulling latest content from source control
    * An app container and a logging container.
      * logging container collects logs and metrics output by main app and writes them to long-term storage
    * App container and a monitoring container
      * Monitoring container periodically makes a request to app to ensure it's running and responding correctly, raises alert if it's not
    * Front-end container and back-end container
      * Front-end may serve web app, and back-end running service to retrieve data
#### **Exercise: Deploy a container instance by using the Azure CLI**
* Log in to Azure portal, or fireoff a CLI and `az login`
1. `az group create --name az204-aci-rg --location <myLocation>`
2. `DNS_NAME_LABEL=aci-example-$RANDOM`
   1. For use later when exposing container to internet
3. ```
   az container create --resource-group az204-ci-rg \
    --name mycontainer \
    --image mcr.microsoft.com/azuredocs/aci-helloworld \
    --ports 80 \
    --dns-name-label $DNS_NAME_LABEL \
    --location <myLocation>
   ```
   1. `$DNS_NAME_LABEL` specifies DNS name
   2. `mcr.microsoft.com/azuredocs/aci-helloworld` is docker image that runs basic Node.js web app
   3. Container instance is now running
4. ```
   az container show \
    --resource-group az204-aci-rg \
    --name mycontainer \
    --query "{FQDN:ipAddress.fqdn,ProvisioningState:provisioningState}"
    --out table
   ```
   1. Output
      ```
      FQDN                                    ProvisioningState
      --------------------------------------  -------------------
      aci-wt.eastus.azurecontainer.io         Succeeded
      ```
5. Cleanup: `az group delete --name az204-aci-rg --no-wait`
#### **Run containerized tasks with restart policy**
* Ease and speed of deploying containers in ACI provides compelling platform for executing run-once tasks
  * build, test, and image rendering; for example
* Configurable restart policy allows you to specify that containers are stopped when processes are completed
  * Only billed for resources consumed while container is running
* **Container restart policy**
  * When a container group is created in ACI, can specify 1 of 3 policy settings:
    |Restart policy|Description|
    |:--|:--|
    |`Always`|Containers in container group are always restarted. **default** policy when no policy is specified|
    |`Never`|Containers in container group never restarted. Run at most once|
    |`OnFailure`|Containers in container group are restarted only when process executed in container fails (non-zero exit code). Containers run at least 1 time|
* **Specify restart policy**
  * Specify a `--restart-policy` parameter when calling `az container create`
    ```
    az container create \
      --resource-group myResourceGroup \
      --name mycontainer \
      --image mycontainerimage \
      --restart-policy OnFailure
    ```
* **Run to completion**
  * ACI starts container, stops it when app or script exist.
  * When ACI restart policy is `Never` or `OnFailure`, containers status is set to **Terminated**
#### **Set environment variables in container instances**
* Setting variables allows dynamic configuration of app or script run by container
  * similar to `--env` command-line argument in `docker run`
* Supports secure values for secrets in both Windows and Linux containers
* Example:
  * Assumes CLI in Bash or Cloud Shell
    * For windows CMD, replace `'` with `"`
    ```
    az container create \
      --resource-group myResourceGroup \
      --name mycontainer2 \
      --image mcr.microsoft.com/azuredocs/aci-wordcount:latest \
      --restart-policy OnFailure \
      --environment-variables 'NumWords'='5' 'MinLength'='8' \
    ```
* **Secure Values**
  * Objects with secure values intended to hold sensitive info like passwords or keys for app
    * Using Secure Values for environment variables is safer and more flexible than including it in container's image
  * Environment variables with secure values aren't visible in container's properties
    * Values can be accessed only from within container
  * Set secure variable by specifying `secureValue` instead of `value` for variable's type
  * Example
    ```YAML
    apiVersion: 2018-10-01
    location: eastus
    name: securetest
    properties:
      containers:
      - name: mycontainer
        properties:
          environmentVariables:
            - name: 'NOTSECRET'
              value: 'my-exposed-value'
            - name: 'SECRET'
              secureValue: 'my-secret-value'
          image: nginx
          ports: []
          resources:
            requests:
              cpu: 1.0
              memoryInGB: 1.5
      osType: Linux
      restartPolicy: Always
    tags: null
    type: Microsoft.ContainerInstance/containerGroups
    ```
  * To deploy container group with YAML
    * `az container create --resource-group myResourceGroup --file secure-env.yaml`
#### **Mount an Azure file share in Azure Container Instances**
* By default, ACIs are stateless
* Must mount a volume from an external store to persist state
* Can mount an Azure file share created with Azure Files
  * Azure Files is fully managed file shares in cloud
  * Accessible via industry standard SMB protocol
* **Limitations**
  * Can only mount azure Files shares to Linux containers
  * Azure file share volume mount requires linux container running as _root_
  * Azure File share colume mounts are limited to CIFS support
* **Deploy container and mount volume**
  * Specify the share and volume mount point when you create a container with `az container create`
    ```
    az container create \
      --resource-group $ACI_PERS_RESOURCE_GROUP \
      --name hellofiles \
      --image mcr.microsoft.com/azuredocs/aci-hellofiles \
      --dns-name-label aci-demo \
      --ports 80 \
      --azure-file-volume-account-name $ACI_PERS_STORAGE_ACCOUNT_NAME \
      --azure-file-volume-account-key $STORAGE_KEY \
      --azure-file-volume-share-name $ACI_PERS_SHARE_NAME \
      --azure-file-volume-mount-path /aci/logs
    ```
    * `--dns-name-label` must be unique in azure region
* **Deploy container and mount volume - YAML**
  * Can deploy container group and mount volume in container with Azure CLI and a YAML template
    * YAML template preferred method when deploying container groups consisting of multiple containers
  * Example template defines container group with one container created with `aci-hellofiles` image. Container mounts Azure file share _acishare_ created previously as a volume
    ```YAML
    apiVersion: '2019-12-01'
    location: eastus
    name: file-share-demo
    properties:
      containers:
      - name: hellofiles
        properties:
          environmentVariables: []
          image: mcr.microsoft.com/azuredocs/aci-hellofiles
          ports:
          - port: 80
          resources:
            requests:
              cpu: 1.0
              memoryInGB: 1.5
          volumeMounts:
          - mountPath: /aci/logs/
            name: filesharevolume
      osType: Linux
      restartPolicy: Always
      ipAddress:
        type: Public
        ports:
          - port: 80
        dnsNameLabel: aci-demo
      volumes:
      - name: filesharevolume
        azureFile:
          sharename: acishare
          storageAccountName: <Storage account name>
          storageAccountKey: <Storage account key>
    tags: {}
    type: Microsoft.ContainerInstance/containerGroups
    ```
* **Mount multiple volumes**
  * To mount multiple volumes in a container instance, must deploy using ARM template or YAML
    * Provide share details and define volumes by populating `volumes` array in `properties` section of template
  * Example: Assume two file shares _share1_ and _share2_ are created in storage account _myStorageAccount_
    ```JSON
    "volumes": [{
      "name": "myvolume1",
      "azureFile": {
        "shareName": "share1",
        "storageAccountName": "myStorageAccount",
        "storageAccountKey": "<storage-account-key>"
      }
    },
    {
      "name": "myvolume2",
      "azureFile": {
        "shareName": "share2",
        "storageAccountName": "myStorageAccount",
        "storageAccountKey": "<storage-account-key>"
      }
    }]
    ```
  * For each container in container group that needs a mounted volume, populate the `volumeMounts` array in `properties` section of container definition.
    ```JSON
    "volumeMounts": [{
      "name": "myvolume1",
      "mountPath": "/mnt/share1/"
    },
    {
      "name": "myvolume2",
      "mountPath": "/mnt/share2/"
    }]
    ```
## **Implement user authentication and authorization**
### **Explore the Microsoft Identity platform**
#### **Explore the Microsoft Identity platform**
* Helps devs build apps that lets users authenticate using Microsoft identities or social accounts
* Provides authorized access to own APIs or Microsoft APIs like Microsoft Graph
* Components that make up Microsoft identity platform
  * **OAuth 2.0 and OpenID Connect standard-compliant authentication service** enabling developers to authenticate several identity types:
    * Work or school accounts, provisioned through Azure AD
    * Personal MS account, like Skype, XBox, and Outlook.com
    * Social or local accounts, by using Azure AD B2C
  * **Open-source libraries**
    * MSAL and support for other standards-compliant libraries
  * **Application management portal**
    * Registration and configuration experience in Azure portal, along with other Azure management capabilities
  * **Application configuration API and PowerShell**
    * Programmatic configuration of apps through Microsoft Graph API and PowerShell so DevOps tasks can be automated
* Offers integration of modern innovations in identity and security space like passwordless authentication, step-up authentication, and Conditional Access
  * Apps integrated with Microsoft identity platform natively take advantage of these innovations
#### **Explore service principals**
* To delegate Identity and Access Management functions to Azure AD, app must be registered with Azure AD tenant
* When app is registered with Azure AD, an identity configuration is created for it allowing it to integrate with Azure AD
* When registering app, must choose whether it is:
  * **Single-Tenant** - only accessible in your tenant
  * **Multi-Tenant** - accessible in other tenants
* If you register app in portal
  * application object (globally unique instance of app) and service principal object are automatically created in home tenant
  * Also have globally unique ID for app (the app or client ID)
  * Can then add secrets or certificates and scopes to make app work
    * Customize branding of app in sign-in dialog, and more
  > 🔵**NOTE**</br>
  > Can also create service principal objects in a tenant using PowerShell, Azure CLI, Microsoft Graph, and other tools
* **Application object**
  * Azure AD application is defined by its one and only application object
    * Resides in Azure AD tenant where app was registered
      * Known as applications _home_ tenant
  * Application object is used as template or blueprint to create one or more service principal objects
    * Service principal is created in every tenant where application is used
  * Describes 3 aspects of an application
    * How service can issue tokens in order to access application
    * Resource application might need to access
    * Actions application can take
  * Microsoft Graph [Application entity](https://learn.microsoft.com/en-us/graph/api/resources/application) defines schema for an application object's properties
* **Service principal object**
  * Entity that requires access to Azure AD secured tenant but be represented by a security principal
    * **User principal** for users
    * **Service principal** for applications
  * Defines access policy and permissions for user/application in Azure AD tenant
    * Enables core features such as authentication of user/app and authorization during resource access
  * 3 types of service principal
    |Type|Description|
    |:--|:--|
    |Application|Local representation, or app instance, of global app object in single tenant or directory. Service principal is created in each tenant where application is used and references the globally unique app object. Service principal object defines what app can do in the specific tenant, who can access the app, and what resources the app can access|
    |Managed Identity|Service principal used to represent a [managed identity](https://learn.microsoft.com/en-us/azure/active-directory/managed-identities-azure-resources/overview). Provides identity for apps to use when connecting to resource that support Azure AD authentication. When managed identity is enabled, a service principal representing the managed identity is created in your tenant. Service principals representing managed identities can be granted access and permissions, but cannot be updated or modified directly|
    |Legacy|Represents a legacy app/app that was created before app registrations were introduced. A legacy service principal can have credentials, service principal names, reply URLs, and other properties an authorized user can edit, but does not have an associated app registration. Service principal can only be used in tenant where it was created|
* **Relationship between application objects and service principals**
  * Application object is the _global_ representation of application for use across all tenants
  * Service principal is _local_ representation for use in a specific tenant
  * Application object serves as template from which common and default properties are _derived_ for use in creating corresponding service principals
  * Application object has
    * 1:1 relationship with software app
    * 1:* relation with its corresponding service principal object(s)
  * Service principal must be created in each tenant where application is used, enabling it to establish an identity for sign-in and/or access tor esources being secured by the tenant
  * Single-tenant app has only one service principal (in its home tenant), create and consented for use during app registration
  * Multi-tenant application also has a service principal created in each tenant where a user from that tenant has consented
#### **Discover permissions and consent**
* Apps that integrate with Microsoft identity platform follow authorization model that gives users and admins control over how data can be accessed
* Microsoft identity platform implements [OAuth 2.0](https://learn.microsoft.com/en-us/azure/active-directory/develop/active-directory-v2-protocols)
  * OAuth 2.0 is method through which third-party apps can access web-hosted resources on behalf of a user
* Any web-hosted resource that integrates with Microsoft identity platform has a resource identifier, or _application ID URI_
* Example of MS web-hosted resources
  * Microsoft Graph: `https://graph.microsoft.com`
  * Microsoft 365 Mail API: `https://outlook.office.com`
  * Azure Key Vault: `https://vault.azure.net`
* Same is true for third-part resources that have integrated with Microsoft identity platform
  * Any of the resources can define set of permissions that can be used to divide functionality of resource in to smaller chunks
    * When chunked in to smaller permission sets, third-party apps can be built to request only permissions needed to perform their function
* In OAuth 2.0, these permission sets are called _scopes_
  * Often referred to as _permissions_
  * App requests permissions it needs by specifying permission in `scope` query parameter
  * Identity platform supports several well-defined [OpenID Connect scopes](https://learn.microsoft.com/en-us/azure/active-directory/develop/v2-permissions-and-consent#openid-connect-scopes) as well as resource-based permissions
* Apps most commonly request permissions by specifying scopes in requests to Microsoft Identity platform authorize endpoint
  * Some high-privilege permissions can be granted only through admin consent
    * Can be requested or granted using [administrator consent endpoint](https://learn.microsoft.com/en-us/azure/active-directory/develop/v2-permissions-and-consent#admin-restricted-permissions)
  > 🔵**NOTE** </br>
  > In requests to authorization, token or consent endpoints for Microsoft identity platform, if resource identitifier is omitted in scope parameter, the resource is assumed to be Microsoft Graph. For example, `scope=User.Read` is equivalent to `https://graph.microsoft.com/User.Read`
* **Premission Types**
  * Two types of supported permissions: _delegated_ and _application_ permissions
    |Type|Description|
    |:--|:--|
    |Delegated|Used by apps that a signed-in user present. For these apps, either the user or an admin consents to the permissions that the app requests. The app is delegated with the permission to act as a signed-in user when it makes calls to the target resource|
    |Application|Used by apps that run without a signed-in user present, for example, apps that run as background services or daemons. _**Only an admin can consent to application permissions**_|
* **Consent Types**
  * Applications in Microsoft identity platform rely on consent to gain access to necessary resources or APIs
  * Three consent types:
    * Static user consent
    * Incremental and dynamic user consent
    * Admin consent
* **Static User Consent**
  * Must specify all permissions it needs in apps configuration in Azure portal
  * Is user (or admin, as appropriate) has not granted consent for the app, then Microsoft identity platform will prompt user to provide consent
  * Enables admins to consent on behalf of all users in organization
  * Pros and Cons
    * Pro: Keeps code clean and simple
    * Con: App requests all permissisions ever needs when user's first sign-in. Can lead to long list of permissions that discourages end users from approving apps access
    * Con: App needs to know all resources it would ever access ahead of time
* **Incremental and Dynamic user consent**
  * Can request permissions incrementally instead
  * Ask for minimum set of permissions upfront and request more as customer uses additional app features
  * To do so, can specify scopes the app needs at anytime by includes the new scopes in the `scope` parameter when requesting an access token
  * Users are prompted for consent of new permissions if it has not already been given
  * _**Only applies to delegated permissions and not application permissions**_
  > 🟠**IMPORTANT**</br>
  > Dynamic consent can be convenient but presents a big challenge for permissions that require admin consent, since the admin consent experience doesn't know about those permissions at consent time. If you require admin privileged permissions or if your app uses dynamic consent, you must register all of the permissions in the Azure portal (not just a subset of permissions that require admin consent). This enabled tenant admins to consent on behald of all their users.
* **Admin consent**
  * Required when app needs access to certain high-privelege permissions.
  * Ensures admins have additional controls before authorizing apps or users to access highly privileged data from the org
  * Admin consent on bhealf of an org still requires the static permissions registered for the app.
    * Set these permissions for apps in app registration portal
    * Reduces cycles required by organization admin to set up application
* **Requesting individual user consent**
  * In OpenID Connect or OAuth 2.0 authorization request, app can request permissions it needs by using the `scope` query parameter
  * Example request
    ```
    GET https://login.microsoftonline.com/common/oauth2/v2.0/authorize?
    client_id=6731de76-14a6-49ae-97bc-6eba6914391e
    &response_type=code
    &redirect_uri=http%3A%2F%2Flocalhost%2Fmyapp%2F
    &response_mode=query
    &scope=
    https%3A%2F%2Fgraph.microsoft.com%2Fcalendars.read%20
    https%3A%2F%2Fgraph.microsoft.com%2Fmail.send
    &state=12345
    ```
  * `scope` is space-separated list of delegated permissions app is requesting
    * If requested permissions are not already consented or admin has not consented on behalf of org, user is asked to grant requested permissions
#### **Discover conditional access**
* Feature in Azure AD
* Enables devs and enterprise customers to protect services in multitude of ways including
  * [MFA](https://learn.microsoft.com/en-us/azure/active-directory/authentication/concept-mfa-howitworks)
  * Allowing only Intune enrolled devices to access specific services
  * Restricting user locations and IP ranges
* **How does conditional access impact an app?**
  * In general, it doesn't
  * Only certain cases when app indirectly, or silently, requests token for service does an app require code changes to handle Conditional Access challenges
    * May be as simple as performing interactive sign-in request
  * Following scenarios require code to handle Conditional Access challenges
    * Apps performing the on-behalf-of flow
    * Apps accessing multiple services/resources
    * SPAs using MSAL.js
    * Web apps calling a resource
  * For app to continue functioning if new policy is applied, implement challenge handling
* **Conditional Access Examples**
  * Building a single-tenant iOS app and apply a conditional access policy. App signs in a user and doesn't request access to an API. When user signs in, the policy is automatically invoked and the user needs to perform MFA
  * Building an app that uses a middle-tier service to access a downstream API. An enterprise customer at the company using this app applies a policy to the downstream API. When an end user signs in, the app requests access to the middle tier and sends the token. The middle tier performs on-behalf-of flow to request access to the downstream API. At this point, a claims "challenge" is presented to the middle-tier. The middle-tier sends the challnege back to the app, which needs to comply with the Conditional Access policy
### **Implement authentication by using the Microsoft Authentication Library**
#### **Explore the Microsoft Authentication Library**
Microsoft Authentication Library (MSAL) can be used to provide secure access to Microsoft Graph, other Microsoft APIs, third-party web APIs, or your web API. MSAL supports many different application architectures and platforms includes .NET, JavaScript, Java, Python, Android, and iOS.

MSAL gives many ways to get tokens, with a consistent API for a number of platforms. Using MSAL provides the following benefits:
  * No need to directly use OAuth libraries or code against the protocol in app
  * Acquires tokens on behalf of a user or on behalf of an app
  * Maintains a token cache and refreshes tokens for you when they are close to expiring. Don't need to handle token expiration on your own.
  * Helps specify which audience you wnat your app to sign in
  * Helps set up app from configuration files
  * Helps troubleshoot app by exposing actionable exceptions, logging, and telemetry
* **Application Types and Scenarios**
  * Using MSAL, a token can be acquired from a number of app types: web apps, web APIs, SPAs (JavaScript), mobile and native apps, and daemons and server-side apps
  * Supports following platforms and frameworks
    |Library|Supported platforms and frameworks|
    |:--|:--|
    |[MSAL for Android](https://github.com/AzureAD/microsoft-authentication-library-for-android)|Android|
    |[MSAL Angular](https://github.com/AzureAD/microsoft-authentication-library-for-js/tree/dev/lib/msal-angular)|SPAS with Angular and Angular.js frameworks|
    |[MSAL for iOS and macOS](https://github.com/AzureAD/microsoft-authentication-library-for-objc)|iOS and macOS|
    |[MSAL Go (preview)](https://github.com/AzureAD/microsoft-authentication-library-for-go)|Windows, macOS, Linux|
    |[MSAL Java](https://github.com/AzureAD/microsoft-authentication-library-for-java)|Windows, macOS, Linux|
    |[MSAL.js](https://github.com/AzureAD/microsoft-authentication-library-for-js/tree/dev/lib/msal-browser)|JavaScript/TypeScript frameworks such as Vue.js, Ember.js, or Durandal.js|
    |[MSAL.NET](https://github.com/AzureAD/microsoft-authentication-library-for-dotnet)|.NET framework/Core, Xamarin Android/iOS, UWP|
    |[MSAL Node](https://github.com/AzureAD/microsoft-authentication-library-for-js/tree/dev/lib/msal-node)|Web apps with Express, desktop apps with Electron, Cross-platform console apps|
    |[MSAL Python](https://github.com/AzureAD/microsoft-authentication-library-for-python)|Windows, macOS, Linux|
    |[MSAL React](https://github.com/AzureAD/microsoft-authentication-library-for-js/tree/dev/lib/msal-react)|SPAs with React and React-based libraries (Next.js, Gatsby.js)|
* **Authentication flows**
  * Some different authentication flows provided by MSAL. Flows can be used in variety of different scenarios
    |Flow|Description|
    |:--|:--|
    |Auth code|Native web apps securely obtain token in the name of user|
    |Client creds|Service apps run without user interaction|
    |On-behalf-of|App calls a service/web API, which in turn calls Microsoft Graph|
    |Implicit|Used in browser-based applications|
    |Device code|Enables sign-in to a device by using another device that has a browser|
    |Integrated Windows|Windows computers silently acquire access token when they are domain joined|
    |Interactive|Mobile and desktop applications call Microsoft Graph in name of a user|
    |Username/Password|Application signs in a user by using their username and password|
* **Public client, and confidential client applications**
  * Security tokens can be acquired by multiple types of applications
    * Typically separated into the following 2 categories; each used with different libraries and objects
    * **Public client applications**
      * Apps that run on devices, desktops, or in a browser.
      * Not trusted to safely keep app secrets, so only access web APIs on behalf of user
      * Support only public client flows
      * Don't have client secrets
    * **Confidential client applications**
      * Apps that run on servers (web apps, APIs, service/daemon apps)
      * Considered difficult to access, are capable of keeping app secrets
      * Can hold configuration-time secrets
      * Each instances of client has distinct configuration (including clientID and client secret)
#### **Initialize client applications**
* With MSAL.NET 3.x, recommended way to instantiate an app is by using application builders `PublicClientApplicationBuilder` and `ConfidentialClientApplicationBuilder`
  * Offer mechanisms to configure app from code, config file, or both
* Must first register app so it can be integrated with MS Identity platform
  * May need:
    * client ID (a GUID)
    * Identity provider URL (named the instance) and sign-in audience for app
      * Collectively know as the _authority_
    * Tenant ID if writing line of business (LoB) app solely for organization
      * AKA _single-tenant_ app
    * App secret or certificate (X509Certificate2) if it's a confidential client app
    * Web apps, and sometimes for public client apps (particularly when app needs to use a broker), have to set the `redirectUri` for identity callback with security tokens
* **Intializing public and confidential client apps from code**
  * Code to instantiate a public client app, signing-in users in the Microsoft Azure public cloud, with their work and school accounts, or personal MS account
    ```C#
    IPublicClientApplication app = PublicClientApplicationBuilder.Create(clientId).Build()
    ```
  * Similarly, following code instantiates confidential app (web app located at https://myapp.azurewebsites.net) handling tokens from users in Azure, with their work, school, or personal MS accounts. App is identified with identity provider by sharing a client secret
    ```C#
    string redirectUri = "https://myapp.azurewebsites.net";
    IConfidentialClientApplication app = ConfidentialClientApplicationBuilder.Create(clientId)
      .WithClientSecret(clientSecret)
      .WithRedirectUri(redirectUri)
      .Build();
    ```
* **Builder modifiers**
  * a number of `.With` methods can be applied as modifiers (for example, `.WithAuthority`, and `.WithRedirectUri`)
    * `.WithAuthority` modifier
      * Sets app default authority to an Azure AD authority, with possibility of choosing Azure Cloud, the audience, the tenant (tenant ID or domain name), or providing directly the authority URL
        ```C#
        var clientApp = PublicClientApplicationBuilder.Create(clientId)
          .WithAuthority(AzureCloudInstance.AzurePublic, tenantId)
          .Build()
        ```
    * `.WithRedirectUri` modifier
      * Overrides default redirect URI. In the case of public apps, is useful for scenarios that require a broker
        ```C#
        var clientApp = PublicClientApplicationBuilder.Create(clientId)
          .WithAuthority(AzureCloudInstance.AzurePublic, tenantId)
          .WithRedirectUri("https://localhost")
          .Build()
        ```
* **Modifiers Common to Public and Confidential Client apps**
  |Modifier|Description|
  |:--|:--|
  |`.WithAuthority()`|Sets app default authority to Azure AD, with possibility of choosing the Azure Cloud, audience, tenant (tenant ID or domain name), or providing directly the authority URI|
  |`.WithTenantId(string tenantId)`|Override tenant ID or tenant description|
  |`.WithClientId(string)`|Overrides client ID|
  |`.WithRedirectUri(string redirectUri)`|Overrides default redirect URI. In case of public client apps, this will be sueful for scenarios requiring a broker|
  |`.WithComponent(string)`|Sets name of library using MSAL.NET (for telemetry reasons)|
  |`.WithDebugLoggingCallback()`|If called, application will call `Debug.Write` simply enabling debugging traces|
  |`.WithLogging()`|If called, app will call a callback with debugging traces|
  |`.WithTelemetry(TelemetryCallback callback)`|Sets the delegate used to send telemetry|
* **Modifiers specific to confidential client apps**
  |Modifier|Description|
  |:--|:--|
  |`.WithCertificate(X509Certificate2 cert)`|Sets the certificate identifying the application with Azure AD|
  |`.WithClientSecret(string clientSecret)`|sets client secret (app password) identifying the application with Azure AD|
#### **Exercise: Implement interactive authentication by using MSAL.NET**
* **Register new application**
  1. Sign in to portal
  2. Search for and select Azure Active Directory
  3. Under **Manage > App Registrations > New registration**
  4. When _Register an application_ page appears, enter apps registration information
      |Field|Value|
      |:--|:--|
      |Name|`az204appreg`|
      |Supported account types|Select _Accounts in this organizational directory only_|
      |Redirect URI (optional)|Select _Public client/native (mobile & desktop)_ and enter `http://localhost` in box to the right|
  5. Select _Register_
* **Set up console app**
  1. open VS code and open the terminal
  2. `md az204-auth`
  3. `cd az204-auth`
  4. `dotnet new console`
  5. `code . -r`
  6. `dotnet build`
  7. `dotnet add package Microsoft.Identity.Client`
  8. open _Program.cs_ and add `using` statements
      ```C#
      using System.Threading.Tasks;
      using Microsoft.Identity.Client;
      ```
  9. Update `Main` method to be async
      ```C#
      public static async Task Main(string[] args)
      ```
* **Add code for interactive authentication**
  1. Copy Application (client) and Directory (tenant) IDs from portal and store in variables
      ```C#
      private const string _clientId = "APP_CLIENT_ID";
      private const string _tenantId = "DIRECTORY_TENANT_ID";
      ```
  2. Use `PublicClientApplicationBuilder` class to build out auth context
      ```C#
      var app = PublicClientApplicationBuilder
        .Create(_clientId)
        .WithAuthority(AzureCloudInstance.AzurePublic, _tenantId)
        .WithRedirectUri("http://localhost")
        .Build();
      ```
     1. `.Create` creates a `PublicClientApplicationBuilder` from a Client ID
     2. `.WithAuthority` adds a known Authority corresponding to an ADFS server. In the code we're specifying the Public cloud, and using the tenant for the app we registered
* **Acquire a token**
  * When app was registered, it automatically generated an API permission `User.Read` for Microsoft Graph. We'll use that permission to acquire a token.
  1. Set permission scope for token request. (added below `PublicClientApplicationBuilder`)
    ```C#
    string[] scopes = { "user.read" };
    ```
  2. Add code to request token and write result to console
    ```C#
    AuthenticationResult result = await app.AcquireTokenInteractive(scopes).ExecuteAsync();
    Console.WriteLine($"Token: {result.AccessToken}");
    ```
* **Run the Application**
  * With everything in place and the app building, run it.
    * `dotnet build`
    * `dotnet run`
  * Should be prompted with a 'Permissions requested'
  * Console should list the retrieved token
### **Implement shared access signatures**
#### **Discover share access signatures**
* Signed URI that points to one or more storage resources
  * Includes token and special set of query parms
* Signature is constructed from SAS parameters and signed with key used to create the SAS
* **Types of Shared Access Signatures (SAS)**
  |||
  |:--|:--|
  |User delegation SAS|SAS secured with Azure AD creds and also by the permissions specified for the SAS. A user delegation SAS applies to Blob storage only|
  |Service SAS|Secured with the storage account key/ A service SAS delegates access to a resource in the following Azure Storage services: Blob, Queue, Table, or Azure Files|
  |Account SAS|Secured with storage account key. Account SAS delegates access to resources in one or more of the storage services. All of the operations available via a service or user delegation SAS are also avaiable via an account SAS|
  > 🔵**NOTE** <br/>
  > MS recommends using Azure AD credentials when possible as a security best practice, rather than using the account key, which can be more easily compromised. When app designed requires SAS for access to Blob storage, use Azure AD credentials to create a [user delegation SAS](https://learn.microsoft.com/en-us/rest/api/storageservices/create-user-delegation-sas) when possible for superior security
* **How SAS Works**
  * Need 2 components for SAS to access Azure Storage
    * URI to the resource to access
    * SAS token created to authorize access to the resource
  * Example URI:
    ```
    https://medicalrecords.blob.core.windows.net/patient-images/patient-116139-nq8z7f.jpg?sp=r&st=2020-01-20T11:42:32Z&se=2020-01-20T19:42:32Z&spr=https&sv=2019-02-02&sr=b&sig=SrW1HZ5Nb6MbRzTbXCaPm%2BJiSEn15tC91Y4umMPwVZs%3D
    ```
    * URI components explained
      |Component|Description|
      |:--|:--|
      |`sp=r`|Controls access rights.</br>`a` = add</br>`c` = create</br>`d` = delete</br>`l` = list</br>`r` = read</br>`w` = write</br>`sp=acdlrw` grants all available rights|
      |`st=2020-01-20T11:42:32Z`|Date/time when access starts|
      |`se=2020-01-20T19:42:32Z`|Date/time when access ends. Example grants 8 hours of access|
      |`sv=2019-02-02`|Version of storage API to use|
      |`sr=b`|Kind of storage being accessed, `b` = blob|
      |`sig=SrW1HZ5Nb6MbRzTbXCaPm%2BJiSEn15tC91Y4umMPwVZs%3D`|The cryptographic signature|
* **Best Practices**
  * Best practices to reduce potential risks of using SAS
    * Always use HTTPS
    * User delegation SAS is the most secure SAS. Use it whenever possible because it removes the need to store your storage account key in code. Must use Azure AD to manage credentials. May not be possible for your solution.
    * Set expiration to the smallest useful value. Is SAS key becomes compromised, it can be exploited only for a short period of time.
    * Apply rule of minimum-required privileges. Only grant access that's required. Generally, read-only access is sufficient.
    * Some situations where SAS isn't the correct solution. When there's an unacceptable risk of using SAS, create a middle-tier service to manager users and their access to storage.
  * Most flexible and secure way to use a service or account SAS is to associate the SAS tokens with a stored access policy
#### **Choose when to use shared access signatures**
* Use a SAS when you want to provide secure access to resources in storage account to any client who does not otherwise have permissions to use those resources.
  * Common use case is when users need to read/write to storage account
* When storage account stores user data, there are two typical design patterns
  1. Clients upload and download data via a front-end proxy service, which performs authentication. The front-end proxy service has the advantage of allowing validation of business rules, but for large amounts of data or high-volume transactions, creating a service that can scale to demand may be expensive or difficult.
   ![design-pattern-1](https://learn.microsoft.com/en-us/training/wwl-azure/implement-shared-access-signatures/media/storage-proxy-service.png)
  2. Lightweight service authenticates the client as needed and then generates a SAS. Once the client application receives the SAS, they can access storage account resources directly with the permissions defined by the SAS and for interval allowed by the SAS. The SAS mitigates the need for routing all data through a front-end proxy service.
   ![design-pattern-2](https://learn.microsoft.com/en-us/training/wwl-azure/implement-shared-access-signatures/media/storage-provider-service.png)
* Many real-world services may use a hybrid of these two approaches. For example, some data might be processed and validated via the front-end proxy, while other data is saved and/or read directly using SAS
* Additionally, SAS is required to authorize access to the source object in a copy operation in certain scenarios:
  |Scenario|Solution|
  |:--|:--|
  |Copy blob to another blob in a different storage account|Use SAS to authorize access to the source blob. Optionally use a SAS to authorize access to the destination blob as well|
  |Copy a file to a different storage account|Must use SAS to authorize access to the _source_ file. Optionally use a SAS to authorize access to the destination file as well|
  |Copy blob to file, or file to blob|Must use a SAS to authorize access to the _source_ object, even if the source and destination objects reside in within the same storage account|
#### **Explore stored access policies**
* Stored access policy provides additional level of control over service-level SAS's on server side
  * Groups shared access signatures and provides additional restrictions for bound by the policy
  * Can use policy to change start time, expiry time, permissions, or revoke it after issuance
* Storage resources supporting Stored Access Policies
  * Blob containers
  * File shares
  * Queues
  * Tables
* **Creating a stored access policy**
  * Consists of _start time_, _expiry time_, and _permissions_ for signature
  * Can specify all parameters on signature URI and none in Stored Access Policy
  * Can specify all parameters on stored access policy
  * _**Can not**_ specify a given parameter on both the SAS token and the stored access policy
  * To create or modify a stored access policy, call `Set ACL` operation for the resource with a request body that specifies the terms of the access policy
    * [Set Container ACL](https://learn.microsoft.com/en-us/rest/api/storageservices/set-container-acl)
    * [Set Queue ACL](https://learn.microsoft.com/en-us/rest/api/storageservices/set-queue-acl)
    * [Set Table ACL](https://learn.microsoft.com/en-us/rest/api/storageservices/set-table-acl)
    * [Set Share ACL](https://learn.microsoft.com/en-us/rest/api/storageservices/set-share-acl)
  * Request body includes a unique signed identifier of your choosing, upto 64 characters, and the optional parameters of the access policy
  > 🔵**NOTE** <br/>
  > When establishing stored access policy on container, queue, table, or share, it may take up to 30 seconds to take effect. Requests may fail with a `403 Forbidden` until it is active. Table entity range restrictions (`startpk`, `startrk`, `endpk`, `endrk`) cannot be specified in a stored access policy
  * .NET example of creating stored access policy
    ```C#
    BlobSignedIdentifier identifier = new BlobSignedIdentifier
    {
      Id = "storead access policy identifier",
      AccessPolicy = new BlobAccessPolicy
      {
        ExpiresOn = DateTimeOffset.UtcNow.AddHours(1),
        Permissions = "rw"
      }
    };

    blobContainer.SetAccessPolicy(permissions: new BlobSignedIdentifier[] { identifier });
    ```
  * Azure CLI example of creating stored access policy
    ```
    az storage container policy create \
      --name <stored access policy identifier> \
      --container-name <containerName> \
      --start <start time UTC datetime> \
      --permissions <(a)dd, (c)reate, (d)elete, (l)ist, (r)ead, (w)rite> \
      --account-key <storage account key> \
      --account-name <storage account name>
    ```
* **Modifying or revoking stored access policy**
  * Can modify parameters of stored access policy by calling the ACL operation for the resource type and replace the existing policy.
    * For example, to remove write permissions, overwrite currently policy with a read-only policy
  * To revoke
    * Delete the stored access policy
    * Rename it by changing the signed identifier
      * Breaks the associations between any existing signatures and the stored access policy
    * Change expiry time to a value in past
      * Causes any associated signatures to expire
  * Deleting/modifying stored access policy immediately affects all of the SAS associated with it
  * To remove a single access policy
    * Call the resources `Set ACL` operation with the signed identifiers you wish to maintain
  * To remove all access policies from resource, call `Set ACL` with an empty body
### **Explore Microsoft Graph**
#### **Discover Microsoft Graph**
* Is a gateway to data intelligent in Microsoft 365
* Provides unified programmability model that can be used to access "tremendous" amount of data in Microsoft 365, Windows 10, and Enterprise Mobility + Security
  ![ms-365-platform](https://learn.microsoft.com/en-us/training/wwl-azure/microsoft-graph/media/microsoft-graph-data-connectors.png)
* 3 main concepts facilitate access and flow of data
  * Microsoft Graph API offers a single endpoint `https://graph.microsoft.com`
    * Can use REST APIs or SDKs to access endpoint
    * Includes powerful set of service that manage user and device identity, access, compliance, security, and helper protect orgs against data leakage or loss
  * [Microsoft Graph connectors](https://learn.microsoft.com/en-us/microsoftsearch/connectors-overview) work in the incoming direction, _**delivering data external to the Microsoft cloud into Microsoft Graph services and applications**_
    * Connectors exist for many data sources such as Box, Drive, Jira, Salesforce
  * [Microsoft Graph Data Connect](https://learn.microsoft.com/en-us/graph/overview#access-microsoft-graph-data-at-scale-using-microsoft-graph-data-connect) provides a set of tools to streamline secure and scalable _**delivery of Microsoft Graph data to popular Azure data stores**_
    * Cached data serves as data sources for Azure development tools that you can use to build intelligent applications
#### **Query Microsoft Graph by using REST**
* After registering app and gettting authentication tokens for a user or service, you can make requests to the Microsoft Graph API
* Defines most resources, methods, and enumerations in OData namespace, `microsoft.graph`, in the [Microsoft Graph metadata](https://learn.microsoft.com/en-us/graph/traverse-the-graph#microsoft-graph-api-metadata)
* A few API sets are defined in their sub-namespaces, such as the [call records API](https://learn.microsoft.com/en-us/graph/api/resources/callrecords-api-overview) which defines resources like [callRecord](https://learn.microsoft.com/en-us/graph/api/resources/callrecords-callrecord) in `microsoft.graph.callRecords`
* Unless explicitly specified in the corresponding topic, assume types, methods, and enumerations are part of the `microsoft.graph` namespace
* **Call a REST API method**
  * To read from or write to a resource, construct a request that looks like the following
    * `{HTTP method} https://graph.microsoft.com/{version}/{resource}?{query-parameters}`
      * Parameter definitions
        * `{HTTP method}` The http method used on request
        * `{version}` Version of MS Graph API app is using
        * `{resource}` Resource in MS Graph that you're referencing
        * `{query-parameters}` Optional OData query options or REST method parameters that customize response
  * Response is returned that includes
    * `status code` HTTP status code indicating success or failure
    * `Response message` Data that was requested. Can be empty
    * `netLink` If request returns a lot of data, need to page through it by using the URL returned in `@odata.nextLink`
* **HTTP Methods**
  * MS Graph supports the following HTTP Methods
    |Method|Description|
    |:--|:--|
    |GET|Read data from resource|
    |POST|Create new resource or perform action|
    |PATCH|Update resource with new values|
    |PUT|Replace resource with new one|
    |DELETE|Remove resource|
  * `GET` and `DELETE` does not require a request body
  * `POST`, `PATCH`, `PUT` requires a JSON formatted request body that contains additional information such as the values for properties of the resource
* **Version**
  * MS Graph supports 2 versions: `v1.0` and `beta`
  * `v1.0` includes generally available APIs, use in production
  * `beta` includes APIs currently in preview. Recommended to only use in development. <span style="color:red">do not use in production</span>
* **Resource**
  * Can be an entity or complex type, commonly defined with properties
  * Entities differ in complex types by _always_ including an `id` property
  * Your URL will include the resource you are interacting with in the request
    * `me`, `user`, `group`, `drive`, and `site`
  * Top-level resources often include _relationships_, which can be used to access other resources
    * For example: `me/messages`, `me/drive`
  * Can also interact with resources using _methods_
    * For example, to send an email: `me/sendMail`
  * Each resource may have different permission requirements
    * Often need a higher level of permissions to create/update a resource than to read it
* **Query Parameters**
  * Can be OData system query options, or other strings that a method accepts to custome its response
  * Can use optional OData system query options to:
    * include more/less properties than default response
    * filter response for items that match a custom query
    * provide another parameter for a method
  * Example filtering results to only those with `emailAddress` property of `jon@contoso.com`
    * `GET https://graph.microsoft.com/v1.0/me/messages?filter=emailAddress eq 'jon@contoso.com'`
* **Additional Resources**
  * Tools to build and test requests using Microsoft Graph APIs
    * [Graph Explorer](https://developer.microsoft.com/graph/graph-explorer)
    * [Postman](https://www.getpostman.com/)
#### **Query Microsoft Graph by using SDKs**
* Microsoft Graph SDKs designed to simplify building high-quality, efficient, and resilient apps that access MS Graph
  * SDKs include 2 components: service library and core library
    * Service library contains models and request builders generated from MS Graph metadata to provide a rich, strongly-typed, and discoverable experience
    * Core library provides a set of features that enhance working with all MS Graph services
      * Embedded support for:
        * Retry handling
        * Secure redirects
        * Transparent authentication
        * Payload compression
      * Support for common tasks such as paging through collections and creating batch requests
* **Install the Microsoft Graph SDK**
  * Included in the following NuGet packages
    * [Microsoft.Graph](https://github.com/microsoftgraph/msgraph-sdk-dotnet) - Contains models and request builders for accessing `v1.0` endpoint with the Fluent API. Has dependency on Microsoft.Graph.Core
    * [Microsoft.Graph.Beta](https://github.com/microsoftgraph/msgraph-beta-sdk-dotnet) - Contains models and request builders for accessing `beta` endpoint with the Fluent API. Has dependency on Microsoft.Graph.Core.
    * [Microsoft.Graph.Core](https://github.com/microsoftgraph/msgraph-sdk-dotnet) - Core library for making calls to MS Graph
    * [Microsoft.Graph.Auth](https://github.com/microsoftgraph/msgraph-sdk-dotnet) - Package provides an authentication scenario-based wrapper of MSAL for use with MS Graph SDK
* **Create a Microsoft Graph client**
  * Can use a single client instance for lifetime of app
  * In the following example:
    * Shows how to create MS Graph client
    * Authentication provider handles token acquisition
      * Different app providers support different client scenarios, for additional details about options and scenarios, see [Choose an Authentication Provider](https://learn.microsoft.com/en-us/graph/sdks/choose-authentication-providers)
    ```C#
    // Build client application
    IPublicClientApplicationBuilder clientApp = 
      PublicClientApplicationBuilder
        .Create("clientAppId")
        .Build();

    // Create authentication provider by passing in a client app and graph scopes
    DeviceCodeProvider authProvider = new DeviceCodeProvider(clientApp, graphScopes);

    // Create new instance of GraphServiceClient with auth provider
    GraphServiceClient graphClient = new GraphServiceClient(authProvider);
    ```
* **Read information from Microsoft Graph**
  * To read info, first need to create a request object and run the `GET` method on the request
    ```C#
    // GET https://graph.microsoft.com/v1.0/me
    var user = await graphClient.Me.Request().GetAsync();
    ```
* **Retrieve list of entities**
  * Retrieving a list of entities is similar to a single entity except there are number of other options for configuring the request
    * `$filter` query parm can be used to reduce result set to only rows that match provided condition
    * `$orderBy` provides list of entities sorted by specific properties
    ```C#
    // GET https://graph.microsoft.com/v1.0/me/messages?$select=subject,sender&$filter=<some condition>&orderBy=<some property>
    var messages = await graphClient.Me.Messages
        .Request()
        .Select(x => new {
          x.Subject,
          x.Sender
        })
        .Filter("<filter condition>")
        .OrderBy("<some property>")
        .GetAsync();
    ```
* **Delete an entity**
  * Delete requests are constructed in the same way as GETs, but use `DeleteAsync()` instead
    ```C#
    // DELETE https://graph.microsoft.com/v1.0/me/message/{message-id}
    string messageId = "...";
    var message = await graphClient.Me
      .Messages[messageId]
      .Request()
      .DeleteAsync();
    ```
* **Create an entity**
  * SDKs that support Fluent API, new items can be added to collections with the `Add` method.
  * Template-based SDKs, the request object exposes a `post` method
    ```C#
    // POST https://graph.microsoft.com/v1.0/me/calendars
    var calendar = new Calendar
    {
      Name = "Volunteer"
    };

    var newCalendar = await graphClient.Me
      .Calendars
      .Requests()
      .AddAsync(calendar);
    ```
* **Additional Resources**
  * [Microsoft Graph REST API v1.0 Reference](https://learn.microsoft.com/en-us/graph/api/overview)
#### **Apply best practices to Microsoft Graph**
* **Authentication**
  * App will need to acquire an OAuth 2.0 access token and present it to MS Graph in either of the following:
    * HTTP _Authorization_ request header, as a _Bearer_ token
    * Graph client constructor, when using MS Graph client library
  * Use the [MSAL](https://learn.microsoft.com/en-us/azure/active-directory/develop/active-directory-v2-libraries) library to acquire the access token to MS Graph
* **Consent and Authorization**
  * **Use least privilege**
    * Only request perms that are required, and only when needed
    * For APIs the application calls check the permissions section in the method topics. For example, see [creating a user](https://learn.microsoft.com/en-us/graph/api/user-post-users) and choose the least privileged permissions
  * **Use correct permission type based on scenarios**
    * If building an interactive app where a signed in user is present, application should use _delegated_ permissions
    * If app runs without a signed in user (background service, daemon), app should use the application permissions
    > 🔴**CAUTION**
    > Using app permissions for interactive scenarios can put application at compliance and security risk. Verify user privileges to ensure they can't access privileged info or are able to circumnavigate policies configured by admins
  * **Consider the end user and admin experience**
    * Consider who will be consenting to the application, either end users or admins, and configure app to [request permissions appropriately](https://learn.microsoft.com/en-us/azure/active-directory/develop/v2-permissions-and-consent)
    * Ensure that you understand the difference between [static, dynamic, and incremental consent](https://learn.microsoft.com/en-us/azure/active-directory/develop/v2-permissions-and-consent#consent-types)
  * **Consider multi-tenant applications** Expect customers to have various application and consent controls in different states. For example:
    * Tenant admins can disable the ability for end users to consent to applications. In this case, an admin would need to consent on behalf of their users
    * Tenant admins can set custom authorization policies such as blocking users from reading other user's profiles, or limiting self-service group creation to a limited set of users. In this case, your application should expect to handle a `403 Forbidden` response when acting on behalf of user
* **Handle responses effectively**
  * 🟠**IMPORTANT** practices to follow to ensure app behaves reliably and predictably for end users
    * **Pagination**
      * When querying resource collections, should expect MS Graph will return the result set in multiple pages
      * App should _always_ handle possibility that the responses are paged in nature, and use the `@odata.nextLink` property to obtain the next paged set of results until all pages are read
      * Final page will not contain `@odata.nextLink`
    * **Evolvable Enumerations**
      * Adding members to existing enums can break apps already using these enums
      * Evolvable enums is a mechanism that MS Graph API uses to add new memebrs to existing enumerations without causing a breaking change for applications
      * GET operations return only known members for properties of evolvable enum types and app needs to handle only the known members
        * If designing to handle unknown members, opt-in to receive those memeber by using an HTTP `Prefer` request header
* **Storing data locally**
  * App should ideally make calls to MS Graph to retrieve data in real time as necessary
  * Only cache or store data locally if necessary for specific scenario, and if that scenario is covered by your terms of use and privacy policy, and does not violate [Microsoft APIs Terms of Use](https://learn.microsoft.com/en-us/legal/microsoft-apis/terms-of-use?context=/graph/context)
  * Should implement retention and deletion policies
## **Implement Secure Cloud Solutions**
### **Implement Azure Key Vault**
#### **Explore Azure Key Vault**
* Supports 2 types of containers: vaults and managed hardware security modules(HSM) pools
* Supports storing:
  * Software and HSM-backed keys
  * Secrets
  * Certificates
* Managed HSM pools only support HSM-backed keys
* Helps solve the following problems:
  * **Secrets Management**
    * Azure KV can be used to securely store and tightly control access to tokens, passwords, certificates, API keys, and other secrets
  * **Key Management**
    * Azure KV can be used as a Key Management solution
  * **Certificate Management**
    * Azure KV is a service that lets you easily provision, manage, and deploy public and private SSL/TSL certificates for use with Azure and internal connected resources
* 2 tiers available
  |Tier|Description|
  |:--|:--|
  |Standard|Encrypts with a software key|
  |Premium|Includes HSM-protected keys
* See [Azure Key Vault pricing](https://azure.microsoft.com/pricing/details/key-vault/) page for differences and costs
* **Key benefits of using Azure Key Vault**
  * **Centralized application secrets**
    * Centralized storage of secrets provides control over distribution
    * Apps can securely access info they by using URIs
    * URIs allow apps to retrieve specific versions of a secret
  * **Secure store secrets and keys**
    * Access requires authentication and authorization
    * Authentication done via Azure AD
    * Authorization done via Azure RBAC or Key Vault access policy
      * Azure RBAC used when dealing with management of vaults
      * Key Vault access policy used when attempting to access data stored in a vault
  * **Monitor access and use**
    * Can monitor activity by enabling logging for vaults
      * Secure logs by restricting access
      * If desired, delete old logs
      * Can be configured to
        * Archive to storage account
        * Stream to event hub
        * Send logs to Azure Monitor logs
  * **Simplified administration of application secrets**
    * Security information must: be secured, follow a life cycle, be highly available
      * Key vault simplifies meeting these requirements by
        * Removing need for in-house knowledge of Hardware Security Modules
        * Scaling up on short notice to meet orgs needs
        * Replicating contents of Key Vault in a region to a secondary region
          * Data replication ensures high availability
          * Takes away need of any action by an admin to trigger failover
        * Provide standard Azure admin options via portal, Azure CLI, PowerShell
        * Automate certain tasks on certificates purchased from public CAs, such as enrollment and renewal
#### **Discover Azure Key Vault best practices**
* Azure KV is a tool for securely storing and accessing secrets
* A vault is a logical group of secrets
* **Authentication**
  * 3 ways to authenticate to Key Vault
    1. **Managed Identities for Azure resources**
        * When deploying VM in Azure, can assign an identity to VM that has access to Key Vault
        * Can also assign identities to other Azure resources
        * Benefit of this approach is that the app or service isn't managing rotation of the first secret
          * Azure automatically rotates service principal client secret associated with the identity
        * _Recommend approach as a best practice_
    2. **Service principal and certificate**
        * Can use a service principal and associated cert that has access to KV
          * Not recommended approach because app owner/dev is responsible for rotating certs
    3. **Service Principal and secret**
        * Can use a service principal and secret to authenticate to KV, but isn't recommended
          * Hard to automatically rotate the bootstrap secret that's used to authenticate to KV
* **Encryption of data in transit**
  * Azure KV enforces TLS protocol
  * Clients negotiate a TLS connection with Azure KV
  * TLS provides
    * Strong authentication
    * Message privacy
    * Integrity
      * enabling detection of message tampering, interception, and forgery
    * Interoperability
    * Algorithm flexibility
    * Ease of deployment and use
  * Perfect Forward Secrecy (PFS) protects connections between customers' client systems and Microsoft cloud service by unique keys
  * Connections use RSA-based 2048-bit encryption key lengths
* **Azure KV best practices**
  |||
  |:--|:--|
  |Use separate KVs|Use a vault per app environment (dev, stage, prod). Helps you not share secrets across environments and reduces attack surface in event of breach|
  |Control access to KV|Allow only authorized apps/persons access|
  |Backup|Create regular backups of vault on update/delete/create of objects within vault|
  |Logging|Be sure to turn on logging and alerts|
  |Recovery options|Turn on [soft-delete](https://learn.microsoft.com/en-us/azure/key-vault/general/soft-delete-overview) and purge protection if you want to guard against force deletion of secrets|
#### **Authenticate to Azure Key Vault**
* Authentication with KV works in conjunction with Azure AD
* Applications have two ways to obtain a service principal
  * Enable a system-assigned **managed identity** for the app
    * With managed identity, Azure internally manages the apps service principal and automatically authenticates the app with other Azure services
    * Available to apps deployed to a variety of services
  * If unable to use managed identity
    * Register app with Azure AD tenant
      * Creates a second application object that identifies the app across all tenants
  > 🔵**NOTE**</br>
  > Recommended to use system-assigned managed identity
* **Authentication to Key Vault in app code**
  * KV SDK is using Azure Identity client library which allows seamless authentication to Key Vault across environments with the same code
  * Azure Identity client libraries
    |Language|Information|
    |:--|:--|
    |.NET|[Azure Identity SDK .NET](https://learn.microsoft.com/en-us/dotnet/api/overview/azure/identity-readme)|
    |Python|[Azure Identity SDK Python](https://learn.microsoft.com/en-us/python/api/overview/azure/identity-readme)|
    |Java|[Azure Identity SDK Java](https://learn.microsoft.com/en-us/java/api/overview/azure/identity-readme)|
    |JavaScript|[Azure Identity SDK JavaScript](https://learn.microsoft.com/en-us/javascript/api/overview/azure/identity-readme)|
* **Authentication to KV with REST**
  * Access tokens must be sent to service using HTTP Authorization header
    ```
    PUT /keys/MYKEY?api-version=<api_version> HTTP/1.1
    Authorization: Bearer <access_token>
    ```
  * If access token is not supplied (or accepted) a `401 Unauthorized` response is returned to client and `WWW-Authenticate` header will be included
    ```
    401 Not Authorized
    WWW-Authenticate: Bearer authorization="...", resource="..."
    ```
    * `WWW-Authenticate` header params are
      * `authorization`: Address of OAuth2 authorization service that me be used to obtain an access token for the request
      * `resource`: name of resource (`https://vault.azure.net`) to use in authorization request
* **Additional Resources**
  * [Azure Key Vault developer's guide](https://learn.microsoft.com/en-us/azure/key-vault/general/developers-guide)
  * [Azure Key Vault availability and redundancy](https://learn.microsoft.com/en-us/azure/key-vault/general/disaster-recovery-guidance)
#### **Exercise: Set and retrieve a secret from Azure Key Vault using Azure CLI**
* The following steps will create a key vault and add/retrieve a secret
1. Define variables for reuse
   1. `myKeyVault=az204vault-$RANDOM`
   2. `myLocation=<myLocation>`
2. `az group create --name az204-vault-rg --location $myLocation`
3. `az keyvault create --name $myKeyVault --resource-group az204-vault-rg --location $myLocation`
4. Add a password as a secret
   1. `az keyvault secret set --vault-name $myKeyVault --name "ExamplePassword" --value "exampleValue"`
5. Retrieve the secret
   1. `az keyvault secret show --name "ExamplePassword" --vault-name $myKeyVault`
6. cleanup
   1. `az group delete --name az204-vault-rg --no-wait`
### **Implement Manged Identities**
#### **Explore managed identities**
* Managed identities provide an identity for apps to use when connecting to resources that support Azure AD
* Apps may use managed identity to object Azure AD tokens
  * App may use managed identity to access Key Vault
* **Types of managed identities**
  * **System-assigned managed identity**
    * Enabled directly on an Azure service instance
    * When identity is enabled, Azure create an identity for the instance int he Azure AD tenant that's trusted by the subscription instance
    * After identity is created, creds are provisioned onto the instance
    * Lifecycle is directly tied to the Azure service instance it's enabled on
    * If instance deleted, so is system-assigned managed identity
  * **User-assigned managed identity**
    * Created as standalone Azure resource
    * Through the create process, an identity for the instance is created in Azure AD tenant that's trusted by subscription in use
    * Can be assigned to 1+ Azure service instances
    * Managed separately from Azure service instance to which it's assigned
  * Managed identities are a special service principal type
    * Locked and only to be used with Azure resources
    * Deleting managed identity removes corresponding service principal
* **Characteristics of managed identities**
  |Characteristic|System-assigned|User-assigned|
  |:--|:--|:--|
  |Creation|Created as part of an Azure resource (i.e. AZ VM, AZ App Service)|Created as stand-alone Azure resource|
  |Lifecycle|Shared lifecycle with Azure resource that managed dientity is created with. When parent resource deleted, managed identity is deleted|Independent lifecycle. Must be explcitily deleted|
  |Sharing across Azure resources|Cannot be shared, only associated with a single Azure resource|Can be shared, the same user-assigned managed identity can be associated with more than one Azure resource|
* **When to use managed identities**
  * Can use managed identities if you want to build an app using AZ App Services that access Azure Storage without having to manage credentials
  ![overview-manged-identities](https://learn.microsoft.com/en-us/training/wwl-azure/implement-managed-identities/media/managed-identities-use-case.png)
* **What Azure services support managed identities?**
  * Managed identities for Azure resources can be used to authenticate to serevices that support Azure AD authentication
  * Remaining modules will use Azure VMs in the examples, but same concepts and similar actions can be applied to any resource in Azure that supports Azure AD authentication.
  * [Azure services that support managed identities](https://learn.microsoft.com/en-us/azure/active-directory/managed-identities-azure-resources/managed-identities-status)
#### **Discover managed identities authentication flow**
* **How a _system-assigned_ managed identity owrks with an Azure VM**
  1. Azure Resource Manager receives a request to enable system-assigned managed identity on VM
  2. ARM creates a service principal in Azure AD for the identity of the VM. The service principal is created in Azure AD tenant that's trusted by the subscription
  3. ARM configures the identity on the VM by updating the Azure instance Metadat Service identity endpoint with the service principal client ID and certificate
  4. After VM has an identity, use the service principal information to grant the VM access to Azure resources. To call ARM, use RBAC in Azure AD to assign the appropriate role to the VM service principal. To call Key Vault, grant your code access ot the specific secret or key in KV
  5. Code that's running on the VM can request a token from the Azure Instance Metadata service endpoint, accessible only from within the VM: `169.254.169.254/metadata/identity/oauth2/token`
  6. Call is made to Azure AD to request access token by using client ID and certificate configured in step 3. Azure AD returns a JWT access token
  7. Code sends access token on a call to a service that supports Azure AD authentication
* **How a _user-assigned_ managed identity works with an Azure VM**
  1. ARM receives a request to create a user-assigned managed identity
  2. ARM creates a service principal in Azure AD for the user-assigned managed identity. Service principal created in Azure AD tenant that's trusted by subscription
  3. ARM receives a request to configure use-assigned managed identity on a VM and updates the Azure Instance Metadata Service identity endpoint with the user-assigned managed identity service principal client ID and certificate
  4. After the user-assigned managed identity is created, use the service principal information to grant the identity access ot Azure resources. To call ARM, use RBAC in Azure AD to assign appropriate role to the service principal of the user-assigned identity. To call KV, grant your code access to specific secret or KV
  5. Code that's running on the VM can request a token from the Azure Instance Metadata Service identity endpoint, accessible only from within VM: `http://169.254.269.254/metadata/identity/oauth2/token`
  6. Call is made to Azure AD to request access token by using the client ID and certificate. Azure AD returns a JWT access token
  7. Code sends the access token on a call to a service that supports Azure AD authentication
#### **Configure managed identities**
* Can configure a managed identity during, or after, the creation of a resource
* **System-assigned managed identity**
  * To create, or enable, a VM resource with system-assigned managed identity your account needs the **Virtual Machine Contributor** role assignment
    * No additional Azure AD role assignments are required
* **Enable system-assigned managed identity during creation of an Azure VM**
  ```
  az vm create \
    --resource-group <myResourceGroup> \
    --name <vmName> \
    --image wind2016datacenter \
    --generate-ssh-keys \
    --assign-identity \
    --role contributor \
    --scope mySubscription \
    --admin-username <adminUser> \
    --admin-password <adminPassword>
  ```
* **Enable system-assigned managed identity on an existing Azure VM**
  * `az vm identity assign -g <myResourceGroup> -n <myVM>`
* **User-assigned managed identity**
  * To assign user-assigned managed identity to a VM at creation, your account needs **Virtual Machine Contributor** _and_ **Managed Identity Operator** roles
  * Two-step process
    * Create user-assigned identity
    * Assign identity to a VM
* **Create a user-assigned identity**
  * Create using `az identity create`
  * `az identity create -g <myResourceGroup> -n <myVM>`
* **Assign a user-assigned managed identity during creation of an Azure VM**
  ```
  az vm create \
    --resource-group <myResourceGroup> \
    --name <vmName> \
    --image UbuntuLTS \
    --admin-username <username> \
    --admin-password <password> \
    --assign-identity <userAssignedIdentityName> \
    --role <role> \
    --scope <subscription>
  ```
* **Assign a user-assigned managed identity to an existing Azure VM**
  ```
  az vm identity assign \
    -g <myResourceGroup> \
    -n <myVM> \
    --identities <userAssignedIdentity>
  ```
* **Azure SDKs with managed identities for Azure resources support**
  |SDK|Sample|
  |:--|:--|
  |.NET|[Manage resource from a virtual machine enabled with managed identities for Azure resources enabled](https://github.com/Azure-Samples/aad-dotnet-manage-resources-from-vm-with-msi)|
  |Java|[Manage storage from a virtual machine enabled with managed identities for Azure resources](https://github.com/Azure-Samples/compute-java-manage-resources-from-vm-with-msi-in-aad-group)|
  |Node.js|[Create a virtual machine with system-assigned managed identity enabled](https://azure.microsoft.com/resources/samples/compute-node-msi-vm/)|
  |Python|[Create a virtual machine with system-assigned managed identity enabled](https://azure.microsoft.com/resources/samples/compute-python-msi-vm/)|
  |Ruby|[Create Azure virtual machine with an system-assigned identity enabled](https://github.com/Azure-Samples/compute-ruby-msi-vm/)|
#### **Acquire an acess token**
* A client app can request managed identities for Azure resources app-only access token for accessing a given resource
  * Token based on managed identities for Azure resources service principal
* No need for client to register itself to obtain an access token under its own service principal
  * Token is suitable for use as a bearer token in service-to-service calls requiring client credentials
> 🟠**IMPORTANT**</br>
> All sample code/script assumes client is running on a VM with managed identities for Azure resources
* **Acquire a token**
  * Fundamental interface for token acquisition is based on REST
    * Means its accessible to any client app running that can make HTTP REST calls
    * Similar to Azure AD programming model except client uses an endpoint on the VM versus an Azure AD endpoint
  * `GET 'http://169.254.169.254/metadata/identity/oauth2/token?api-version=2018-02-01&resource=https://management.azure.com/' HTTP/1.1 Metadata: true`
    |Element|Description|
    |:--|:--|
    |`GET`|HTTP verb|
    |`http://169.254.169.254/metadata/identity/oauth2/token`|Managed identities for Azure resources endpoint for the Instance Metadata Service|
    |`api-version`|Query string parameter indicating API version of the IMDS endpoint|
    |`resource`|Query string parameter indicating the App ID URI of the target resource. Also appears in the `aud` (audience) claim of the issued token. Example requests a token to access ARM, which has an App ID URI of `https://management.azure.com/`|
    |`Metadata`|HTTP request header field, required by managed identities for Azure resources as a mitigation against Server Side Request Forgery (SSRF) attack. Value must be set to `true`, all lowercase|
  * Sample Response
    ```JSON
    HTTP/1.1 200 OK
    Content-Type: application/json
    {
      "access_token": "eyJ0eXAi...",
      "refresh_token": "",
      "expires_in": "3599",
      "expires_on": "1506484173",
      "not_before": "1506480273",
      "resource": "https://management.azure.com/",
      "token_type": "Bearer"
    }
    ```
* **Get a token using C#**
  ```C#
  using System;
  using System.Collections.Generic;
  using System.IO;
  using System.Net;
  using System.Web.Script.Serialization; 

  // Build request to acquire managed identities for Azure resources token
  HttpWebRequest request = (HttpWebRequest)WebRequest.Create("http://169.254.169.254/metadata/identity/oauth2/token?api-version=2018-02-01&resource=https://management.azure.com/");
  request.Headers["Metadata"] = "true";
  request.Method = "GET";

  try
  {
      // Call /token endpoint
      HttpWebResponse response = (HttpWebResponse)request.GetResponse();

      // Pipe response Stream to a StreamReader, and extract access token
      StreamReader streamResponse = new StreamReader(response.GetResponseStream()); 
      string stringResponse = streamResponse.ReadToEnd();
      JavaScriptSerializer j = new JavaScriptSerializer();
      Dictionary<string, string> list = (Dictionary<string, string>) j.Deserialize(stringResponse, typeof(Dictionary<string, string>));
      string accessToken = list["access_token"];
  }
  catch (Exception e)
  {
      string errorText = String.Format("{0} \n\n{1}", e.Message, e.InnerException != null ? e.InnerException.Message : "Acquire token failed");
  }
  ```
* **Token caching**
  * Managed identities for Azure resources subsystem caches tokens, but also recommended to implement token caching in code
  * As a result, should prepare for scenarios where the resource indicates that the token is expired
  * On-the-wire calls to Azure AD result only when
    * Cache miss occurs due to no token in managed identities for Azure resources subsystem cache
    * Cached token is expired
* **Retry guidance**
  * Retry if receiving `404`, `429`, or `5xx` error code
  * Throttling limits apply to number of calls made to IMDS endpoint
    * Will return `429 Too Many Requests` when throttling is active
### **Implement Azure App Configuration**
#### **Explore the Azure App Configuration service**
* Use App Configuration to store all settings for application and secure their access in one place
* Offers following benefits
  * Fully managed service that can be set up in minutes
  * Flexible key representations and mappings
  * Tagging with labels
  * Point-in-time replay of settings
  * Dedicated UI for feature flag management
  * Comparison of two sets of configuration on custom defined dimensions
  * Enhanced security through Azure-managed identities
  * Complete data encryption, at-rest or in-transit
  * Native integration with popular frameworks
* App Configuration complements Azure Key Vault. Easier to implement following scenarios
  * Centralize management and distribution of hierarchical configuration data for different environments and geographies
  * Dynamically change application settings without the need to redeploy or restart an app
  * Control feature availability in real-time
* **Use App Configuration**
  * Easiest way is to add an App Configuration store to application through a client library provided by Microsoft
    |Language/Framework|How to connect|
    |:--|:--|
    |.NET Core/ASP.NET Core|App Configuration provider for .NET core|
    |.NET Framework/ASP.NET|App Configuration builder for .NET|
    |Java Spring|App Configuration client for Spring Cloud|
    |Others|App Configuration for REST API|
#### **Create paired keys and values**
* App Configuration stores configuration data as Key-Value pairs
* **Keys**
  * Common practice to store keys into a hierarchical namespace by using a character delimiter such as `/` or `:`
  * App Configuration treats keys as a whole and does not parse keys to figure out how their names are structured or enforce any rule on them
  * _**Case-sensitive**_, unicode-based strings.
    * Keys _app1_ and _App1_ are distinct in App Configuration store
    * Some frameworks handle configuration keys case-insensitively
  * Can use any unicode character in key name
    * Except `*`, `,`, and `\`
      * If required, escape it using `\`
  * Combined size limit of 10,000 character on K-V pair
* **Design key namespaces**
  * Two general approaches to naming keys used for configuration data
    * Flat
    * Hierarchical
      * Offers number of advantages
        * Easier to read
        * Easier to manage
          * key name hierarchy represents logical groups of configuration data
        * Easier to use
          * Simpler to write a pattern-match query for keys in a hierarchical structure that retrieves only a portion of configuration data
  * **Hierarchical examples**
    * Based on component services
      ```
      AppName:Service1:ApiEndpoint
      AppName:Service2:ApiEndpoint
      ```
    * Based on deployment regions
      ```
      AppName:Region1:DbEndpoint
      AppName:Region2:DbEndpoint
      ```
* **Label Keys**
  * Key values can be assigned a label attribute
  * Labels are used to differentiate key values with the same key
  * Example: A key app1 with labels A and B forms two separate keys in an App Configuration store
  * Common use is to specify environments for the same key
    ```
    Key = AppName:DbEndpoint & Label = Test
    Key = AppName:DbEndpoint & Label = Staging
    Key = AppName:DbEndpoint & Label = Production
    ```
* **Version key values**
  * Not versioned autoamtically when modified
  * Use labels to create multiple versions of a key value
* **Query key values**
  * Each key value is uniquely identitifed by _key_ + _label_ (null by default)
  * Query App Configuration store by specifying a pattern
  * App Configuration returns all key values that match the pattern and their corresponding values and attributes
* **Values**
  * Unicode strings
  * Optional user-defined content type
    * Use this to store information (i.e. encoding scheme)
  * Encrypted at rest and in transit
  * App Configuration is not a replacement for Azure Key Vault
    * _**Do not**_ store app secrets in it
#### **Manage application features**
* Feature management is modern software-development practice for decoupling feature releases from deployments and enables quick changes to feature availability on demand
  * Uses _feature flags_ (aka _feature toggles_, _freature switches_, etc..)
* **Basic Concepts**
  * **Feature Flag**
    * Variable with binary state
    * Has associated code blocks
      * Run only if feature flag is in desired state
  * **Feature manager**
    * Application package that handles the lifecycle of all feature flags in an app
    * Typically provides additional functionality, such as caching feature flags and updating their state
  * **Filter**
    * Rule for evaluating state of a feature flag
    * User group, service, browser type, geographic location, and time window are all examples of a filter
  * Effective implementation of feature management consists of at least 2 components working in concert
    * App that makes use of feature flags
    * Separate repo that stores feature flags and current their state
* **Feature flag usage in code**
  * Feature flags are basically `if/else` statements
    ```C#
    if(featureFlag)
    {
      // ... do this ...
    }
    else
    {
      // don't
    }
    ```
  * Feature flag can be set statically: `bool featureFlag = true`
  * Can evaluate flag state based on rules: `bool featureFlag = isBetaUser()`
* **Feature flag declaration**
  * Each flag has two parts
    1. Name
    2. List of 1+ filters to evaluate if flag is on/off
  * Filters are evaluated in order, if filter results in flag being on, other conditions are not evaluated
    * If all filters are checked and none are true, the flag is off
  * Feature manager supports _appsettings.json_ as a configuration source for feature flags
    ```JSON
    "FeatureManagement": {
        "FeatureA": true, // Feature flag set to on
        "FeatureB": false, // Feature flag set to off
        "FeatureC": {
            "EnabledFor": [
                {
                    "Name": "Percentage",
                    "Parameters": {
                        "Value": 50
                    }
                }
            ]
        }
    }
    ```
* **Feature flag repository**
  * To effectively use feature flags, they need to be externalized from the app
  * Azure App Configuration is designed to be a centralized repo for feature flags
    * Use it to define different kinds of feature flags and manipulate states quickly and confidently
  * Can use App Configuration libraries to access feature flags from app
#### **Secure app configuration data**
* Will learn how to secure apps configuration data by using
  * Customer-managed keys
  * Private endpoints
  * Managed identities
* **Encrypt configuration data by using customer-managed keys**
  * Azure App Configuration encrypts all sensitive information at rest using a 256-bit AES encryption key provided by MS
  * Every App Configuration instance has its own encryption key
  * When customer-managed key capability is enabled
    * App Configuration uses managed identity assigned to App Configuration instance to authenticate with Azure AD
    * Managed identity then calls Azure Key Vault and wraps the App Configuration instances encryption key
    * Wrapped encryption key is then stored and the unwrapped encryption key is cached within App Configuration for 1 hour
      * Refreshes every hour
* **Enabled cusomter-managed key capability**
  * Components required to successfully enable customer-managed keys in Azure App Configuration
    * Standard tier Azure App Configuration
    * Azure Key Vault with soft-delete and purge-protection enabled
    * RSA or RSA-HSM key within the KV
      * Key must not be expired
      * Must be enabled
      * Must have both wrap and unwrap capabilities
  * Once above is configured, two additional steps remain
    * Assign a managed identity to Azure App Configuration instance
    * Grant the identity `GET`, `WRAP`, and `UNWRAP` permissions in the target Key Vault's access policy
* **Use private endpoints for Azure App Configuration**
  * Can use private endpoints for App Configuration to allow clients on a VNet to securely access data over a private link
  * Private endpoint using an IP from the VNet address space for you App COnfiguration store
  * Network traffic between clients on the VNet and App Configuration store tracerses over VNet using a private link on the MS backbone network, eliminating exposure to public internet
  * Using private endpoints for App Configuration enables you to
    * Secure app configuration details by configuring the firewall to block all connections to App Configuration on the public endpoint
    * Increate security for VNet ensuring data doesn't escape from the VNet
    * Securely connect to App Configuration from on-prem networks that connect tot he VNet using VPN or ExpressRoutes with private-peering
* **Private endpoints for App Configuration**
  * When creating private endpoint, must specify App Configuration store to which it connects
  * Need a separate private endpoint for each App Configuration store
  * Azure relies on DNS resolution to route connections from the VNet to the configuration store over a private link
    * Can find connection strings in portal by selecting _**App Configuration store > Settings > Access Keys**_
* **DNS changes for private endpoints**
  * When creating private endpoints
    * DNS CNAME record for configuration store is updated to an alias in a subdomain with the prefix `privatelink`
    * Azure also create a [private DNS zone](https://learn.microsoft.com/en-us/azure/dns/private-dns-overview) corresponding to the `privatelink` subdomain with a DNS A resource record
  * When resoling the endpoint URL from within the VNet hosting the private endpoint, it resolves to the private endpoint of the store
  * Outside of the VNet, the endpoint URL resolves to the public endpoint
    * Creating a private endpoint disables the public endpoint
* **Managed identities**
  * Managed identity from Azure AD allows App Configuration to easily access other Azure AD resources (i.e. Key Vault)
    * Identity is managed by Azure
    * Does not require secret privisioning or rotation
  * App can be granted two types of identities
    * System-assigned identity
      * tied to configuration store
      * If configuration store is deleted, so is identity
      * App Configuration can only have 1 system-assigned identity
    * User-assigned identity
      * Standalone azure resource that can be assigned to configuration store
      * Configuration store can have multiple user-assigned identities
* **Add a system-assigned identity**
  * To set up a managed identity using the Azure CLI, use `az appconfig identity assign` against an existing App Configuration store
  * Example
    ```
    az appconfig identity assign \
      --name myTestAppConfigStore \
      --resource-group myResourceGroup
    ```
* **Add a user-assigned identity**
  * Requires that you create the identity and then assign its resource identitifier to your store
  * Example
    ```
    az identity create \
      --resource-group myResourceGroup \
      --name myUserAssignedIdentity

    az appconfig identity assign \
      --name myAppConfigStore \
      --resource-group myResourceGroup \
      --identities /subscriptions/[subscription id]/resourcegroups/myResourceGroup/providers/Mucrosoft.ManagedIdentity/useAssignedIdentities/myUserAssignedIdentity
    ```
## **Implement API Management**
### **Explore API Management**
#### **Discover API Management Service**
* API Management provides core functionality to ensure a successful API program through
  * Developer engagement
  * Business insights
  * Analytics
  * Security
  * Protection
* Each API consists of 1+ operations, and each API can be added to 1+ products
  * To use an API, devs subscribe to a product that contains the API, and then call the APIs operations
* System is made up of following components
  * **API Gateway** is endpoint that
    * Accepts API calls and routes them to backend
    * Verifies API keys, JWT tokens, certs, and other credentials
    * Enforces usage quotas and rate limits
    * Transforms API on the fly without code modifications
    * Caches backend responses where set up
    * Logs call metadata for analytics
  * **Azure Portal** is administrative interface where you set up your API program. Use it to:
    * Define or import API schema
    * Package APIs in to products
    * Set up policies like quota or transformations on APIs
    * Get insights from analytics
    * Manage users
  * **Developer Portal** serves as main web presence for devs where they can
    * Read API documentation
    * Try out an API via an interactive console
    * Create an account and subscribe to get API keys
    * Access analytics on their own usage
* **Products**
  * How APIs are surfaced to developers
  * _Products_ in API Management have one or more APIs
    * Are configured with
      * title
      * description
      * and terms of use
  * Can be _**Open**_ or _**Protected**_
    * _Protected_ must be subscribed to before use
  * Subscription approval configured at product level and can either require an admin approval or be auto-approved
* **Groups**
  * Used to manage visibility of products to developers
  * API Management has the following immutable system groups
    |||
    |:--|:--|
    |Administrators|Azure subscription admins are part of this group. Admins manage API Management service instances; creating the APIs, operations, and products.|
    |Developers|Authenticated developer portal users fall into this group. Developers are the customers that build applications using your APIs. Developers are granted access to the developer portal and build applications that call the operations of an API|
    |Guests|Unauthenticated developer portal users. Can be granted certain read-only access, such as the ability to view APIs but not call them|
* **Developers**
  * Represent the user accounts in an API Management service
  * Can be created or invited by admins
  * Is a member of 1+ groups
  * Can subscribe to the products that grant visibility to those groups
* **Policies**
  * Allow Azure portal to change behavior of teh API through configuration
  * Collection of stataements that are executed sequentially on the request or response of an API
  * Popular statements include
    * Conversion from XML to JSON
    * Call rate limiting
    * Many other policies available
* **Developer Portal**
  * Where developers can learn about the API
  * Can view/call operations, and subscribe to products
  * Prospective customers can visit the developer portal, view APIs and operations, and sign up
  * URL for dev portal is located in API Management service instance
#### **Explore API Gateways**
* An _API Gateway_ can help address the following:
  * How does a client know what endpoints to call?
  * What happend if new service is introduced, or existing services are refactored?
  * How do services handle SSL termination, authentication, etc...?
  ![api-gateway](https://learn.microsoft.com/en-us/training/wwl-azure/explore-api-management/media/api-gateway.png)
* API Gateway sits between clients and services
  * Acts as reverse proxy, routing requests from clients to services
  * May perform various cross-cutting tasks; i.e. authentication, SSL termination, and rate limiting
* If you don't deploy an API Gateway, clients must send requests directly to front-end services
  * Presents potential problems with exposing services
    * Complex client code, client must keep track of multiple endpoints and handle failures in a resilient way
    * Coupling between client and backend
      * Client must know how individual services are decomposed
    * Single operation may require calls to multiple services
    * Each public-facing service must handle concerns such as: authentication, SLL, client rate limiting
    * Services must expose client friendly protocol (HTTP, WebSockets) limiting the choice of protocols
    * Potential attack surface and must be hardened
* API Gateway helps address above issues by decoupling clients from services
  * Can perform a number of different functions, and can be grouped into the following design patterns
    |Pattern||
    |**Gateway Routing**|Use gateway as reverse proxy to route requests to one or more backend services, using Layer-7 routing. Gateway provides a single endpoint for clients, and helper to decouple clients from services|
    |**Gateway Aggregation**|Aggregate multiple individual requests in to a single request. This pattern applies when a single operation requires calls to multiple backend services. Client sends one request to the gateway, gateway dispatches requests to the various backend services, then aggregates results and sends back to client. Helpers reduce the chattiness between client and backend|
    |**Gateway Offloading**|Use gateway to offload functionality from individual services to the gateway. Particularly, cross-cutting concerns. Can be useful to consolidate these functions into one place, rather than making every service responsible for implementing them.
* Some functionality that can be offloaded to a gateway
  * SSL termination
  * Authentication
  * IP allow/block list
  * Client rate limiting
  * Logging and monitoring
  * Response caching
  * GZIP compression
  * Servicing static content
#### **Explore API Management Policies**
* Azure API Management policies are a powerful capability of the system that allow the publisher to change the behavior of an API through configuration
  * Are a collection of Statements executed sequentially on the request or response
* Policies applied at the gateway
  * Can change inbound/outbound request/response
* Policy expressions can be used as attribute values or text values in any of the API Management policies, unless speficied otherwise
* **Understanding policy configuration**
  * XML document that describes a sequence of inbound/outbound statements
  * Configuration is divided into `inbound`, `backend`, `outbound`, and `on-error`
    ```XML
    <policies>
      <inbound>
        <!-- statements to be applied to the request go here -->
      </inbound>
      <backend>
        <!-- statements to be applied before the request is forwarded to 
            the backend service go here -->
      </backend>
      <outbound>
        <!-- statements to be applied to the response go here -->
      </outbound>
      <on-error>
        <!-- statements to be applied if there is an error condition go here -->
      </on-error>
    </policies>
    ```
  * Error during processing of a request will cause remaining `inbound`, `backend`, and `outbound` sections to be skipped and execution jumps to `on-error` section
    * Can review error by using `context.LastError` property, inspect and customize the error response using the `set-body` policy and configure what happens if an error occurs
* **Examples**
  * **Apply policies specified at different scopes**
    * If policy configured at global level and a policy configured for an API, when the API is used, both policies are applied.
    * API Management allows for deterministic ordering of combined policy statements via the base element
      ```XML
      <policies>
        <inbound>
            <cross-domain />
            <base />
            <find-and-replace from="xyz" to="abc" />
        </inbound>
      </policies>
      ```
    * In above policy definition, `cross-domain` statement would execute before any higher policies which would in turn, be followed by the `find-and-replace` policy
* **Filter response content**
  * Example policy demonstrates how to filter data elements from response payload based on product associated with the request
    * Assumes response content is JSON formatted and contains root-level properties named "minutely", "hourly", "daily", "flags"
    ```XML
    <policies>
      <inbound>
        <base />
      </inbound>
      <backend>
        <base />
      </backend>
      <outbound>
        <base />
        <choose>
          <when condition="@(context.Response.StatusCode == 200 && context.Product.Name.Equals("Starter"))">
            <!-- NOTE that we are not using preserveContent=true when deserializing response body stream into a JSON object since we don't intend to access it again. See details on https://learn.microsoft.com/azure/api-management/api-management-transformation-policies#SetBody -->
            <set-body>
              @{
                var response = context.Response.Body.As<JObject>();
                foreach (var key in new [] {"minutely", "hourly", "daily", "flags"}) {
                response.Property (key).Remove ();
              }
              return response.ToString();
              }
        </set-body>
          </when>
        </choose>    
      </outbound>
      <on-error>
        <base />
      </on-error>
    </policies>
    ```
#### **Create advanced policies**
* Reference for following API Management policies
  |Policy|Description|
  |:--|:--|
  |Control flow|Conditionally policy statements based on boolean evaluation|
  |Forward request|Forwards request to backend service|
  |Limit concurrency|Prevents enclosed policies from executing by more than the specified number of requests at a time|
  |Log to Event Hub|Sends messages in the specified format to an Event Hub defined by a Logger entity|
  |Mock response|Aborts pipeline execution and returns mocked response directly to caller|
  |Retry|Retries execution of enclosed policy statements, if and until the condition is met. Execution will repeat at the specified time intervals and up to the specified retry count|
* **Control flow**
  * The `choose` policy applies enclosed policy statements based on evaluation of boolean expression. Similar to `if-then-else` or `switch` statement
  ```XML
  <choose>
    <when condition="Boolean expression | Boolean constant">
        <!— one or more policy statements to be applied if the above condition is true  -->
    </when>
    <when condition="Boolean expression | Boolean constant">
        <!— one or more policy statements to be applied if the above condition is true  -->
    </when>
    <otherwise>
        <!— one or more policy statements to be applied if none of the above conditions are true  -->
    </otherwise>
  </choose>
  ```
  * Must contain at least one `<when>...</when>` statement
  * `<otherwise>` is optional, executed if all `<when>`s are false
  * Conditions in `<when>...</when>` are evaluated in order of appearance
* **Forward request**
  * `forward-request` policy forwards incoming request to backend service specified in request context
  * Backend service URL is specified in API settings, can be changed using the set backend service policy
  * Removing `forward-request` policy results in requests not being forwarded and policies in outbound section are evaluated immediately upon successful completion of inbound policies
  ```XML
  <forward-request timeout="time in seconds" follow-redirects="true|false"/>
  ```
* **Limit concurrency**
  * `limit-concurrency` policy prevents enclosed policies from executing by more than the specified number of requests at any time
    * Returns `429 Too Many Requests` if exceeded
  ```XML
  <limit-concurrency key="expression" max-count="number">
        <!— nested policy statements -->
  </limit-concurrency>
  ```
* **Log to Event Hub**
  * `log-to-eventhub` policy sends messages in specified format to event hub defined by a Logger entity
  * Used for saving select request/response context information for online/offline analysis
  ```XML
  <log-to-eventhub logger-id="id of the logger entity" partition-id="index of the partition where messages are sent" partition-key="value used for partition assignment">
  Expression returning a string to be logged
  </log-to-eventhub>
  ```
* **Mock response**
  * `mock-response` is used to mock APIs and operations
    * Aborts normal pipeline execution and returns mocked response
    * Prefers response content examples when available
    * Generates sample responses from schemas, when schemas are provided and examples are not
      * If neither found, empty response returned
  ```XML
  <mock-response status-code="code" content-type="media type"/>
  ```
* **Retry**
  * `retry` policy executes child policies once and then retries their execution until retry `condition` becomes `false` or retry `count` is exhausted
  ```XML
  <retry
    condition="boolean expression or literal"
    count="number of retry attempts"
    interval="retry interval in seconds"
    max-interval="maximum retry interval in seconds"
    delta="retry interval delta in seconds"
    first-fast-retry="boolean expression or literal">
        <!-- One or more child policies. No restrictions -->
  </retry>
  ```
* **Return response**
  * `return-response` policy aborts pipeline execution and return either a default of custom response
    * Default is `200 OK` with no body
    * Custom response can be specified via a content variable or policy statements
    * If both are provided, response contained within context variable is modified by the policy statements before being returned
  ```XML
  <return-response response-variable-name="existing context variable">
    <set-header/>
    <set-body/>
    <set-status/>
  </return-response>
  ```
* **Additional Resources**
  * [API Management Policies](https://learn.microsoft.com/en-us/azure/api-management/api-management-policies)
  * [Error handling in API Management Policies](https://learn.microsoft.com/en-us/azure/api-management/api-management-error-handling-policies)
#### **Secure APIs by using subscriptions**
* When publishing APIs through API Management, it's easy and common to secure access to them by using subscription keys
* Subscribers must include valid subscription key in HTTP requests when they make calls to secured APIs
* Subscription is required to get a subcscription key
  * Subscription is named container for subscription keys
> 🔵**NOTE**</br>
> API management supports securing access to APIs using OAuth 2.0, Client certs, and IP allow listing
* **Subscriptions and Keys**
  * Subscription key is unique auto-generated key that can be passed in headers of client request or as a query string parameter
    * Is directly related to a subscription, which can be scoped to different areas
  * Subscriptions give granular control over permissions and policies
  * 3 main subscription scopes
    |Scope|Details|
    |:--|:--|
    |All APIs|Applies to every APU accesible from gateway|
    |Single API|Scope applies to a single imported API and all of its endpoints|
    |Product|Collection of one or more APIs that you configure in API Management. Can assign APIs to more than one product. Products can have different access rules, usage quotas, and terms of use|
  * Every subscription has 2 keys, and keys can be revoked/regenerated any time
  * For products where subscriptions are enabled
    * Clients must supply key in every request
    * Devs can obtain a key by submitting a subscription request
      * If request is approved, must send the dev the subscription key
        * Preferably in a secure manner
          * _**Core part of API Management workflow**_
* **Call an API with the subscription key**
  * Apps must include valid key in all HTTP requests made to protected API endpoints
    * Can be passed in headers, or in url as query string
    * **Default _header_ name** is `Ocp-Apim-Subscription-Key`
    * **Default _query string_** is `subscription-key`
  * To test API calls, can use the Developer Portal, Curl, Postman, etc...
    * Example of Developer portal
      ![dev-portal-api](https://learn.microsoft.com/en-us/training/wwl-azure/explore-api-management/media/key-header-portal.png)
    * Curl header example: `curl --header "Ocp-Apim-Subscription-Key: <key>" https://<apim gateway>.azure-api.net/api/path`
    * Curl query param example: `curl https://<apim gateway>.azure-api.net/api/path?subscription-key=<key>`
  * If `Ocp-Apim-Subscription-Key` or `subscription-key` is not provided a `401 Unauthorized` is returned
#### **Secure APIs by using certificates**
* Certificates can be used to provide TLS mutual authentication between client and API Gateway
* Can configure API Management gateway to allow only requests with certificates containing a specific thumbprint
  * **Authorization** at the gateway is handled through `inbound` policies
* **TLS Client Authentication**
  * API Management gateway can inspect certificate contained within the client request and check for
    |Property|Description|
    |:--|:--|
    |**Certificate Authority(CA)**|Only allow certs signed by a particular CA|
    |**Thumbprint**|Allow certs containing a specific thumbprint|
    |**Subject**|Only allow certs with specific subject|
    |**Expiration Date**|Only allow unexpired certs|
  * Properties are not mutually exclusive and be mixed to form custom policy requirements
  * Client certs are signed to ensure that they are not tampered with
    * Verify certificate comes from client and not imposter in the following 2 common ways
      * Check who issued the cert
        * If issuer was a cert authority that you trust, you can use the certificate.
        * Can configure the trusted certificate authorities in Azure portal to automate this process
      * If issued by a partner, verify it came from them
        * For example, if they deliver a cert in person, you can be sure of its authenticity
          * Known as 'self-signed certificates'
* **Accepting client certificates in the Consumption tier**
  * Consumption tier in APIM is designed to conform with serverless design principles
  * If building APIs using serverless technology (i.e. Azure Functions), this tier is a good fit
  * Must explicitly enable use of client certs, which can be done in the _**Custom domains**_ page of the API Management service
  ![client-cert-apim-svc](https://learn.microsoft.com/en-us/training/wwl-azure/explore-api-management/media/configure-request-certificates.png)
* **Certificate Authorization Policies**
  * Create these policies in the `inbound` section of the policy file
    ![apim-svc-cert-policy](https://learn.microsoft.com/en-us/training/wwl-azure/explore-api-management/media/inbound-policy.png)
* **Check thumbprint against certificates uploaded to API Management**
  * In above example, only a single thumbprint would work, so only 1 cert would be validated
  * Typically each customer or partner would pass a different cert with a different thumbprint
    * To enable this scenario, obtain certs from partners and use the **Client certificates** page in Azure portal to upload them to API Management resource, then add below code to policy
      ```XML
      <choose>
        <when condition="@(context.Request.Certificate == null || !context.Request.Certificate.Verify()  || !context.Deployment.Certificates.Any(c => c.Value.Thumbprint == context.Request.Certificate.Thumbprint))" >
            <return-response>
                <set-status code="403" reason="Invalid client certificate" />
            </return-response>
        </when>
    </choose>
      ```
* **Check Issuer and Subject of a client cert**
  ```XML
  <choose>
    <when condition="@(context.Request.Certificate == null || context.Request.Certificate.Issuer != "trusted-issuer" || context.Request.Certificate.SubjectName.Name != "expected-subject-name")" >
        <return-response>
            <set-status code="403" reason="Invalid client certificate" />
        </return-response>
    </when>
  </choose>
  ```
#### **Exercise: Create a backend API**
* Learn how to
  * Create an API Management instance
  * Import an API
  * Configure backend settings
  * Test API
1. Set variables in console for reuse, APIM name must be globally unique
   ```
   myApiName=az204-apim-$RANDOM
   myLocation=<myLocation>
   myEmail=<myEmail>
   ```
2. Create resource group
   ```
   az group create --name az204-apim-rg --location $myLocation
   ```
3. Create APIM instance using `az apim create`
   ```
   az apim create -n $myApiName \
    --location $myLocation \
    --publisher-email $myEmail \
    --resource-group az204-apim-rg \
    --publisher-name AZ204-APIM-Exercise \
    --sku-name Consumption
   ```
4. Import a backend (by importing and publishing an OpenAPI specification)
   1. In Azure Portal, search for and select **API Management services**
   2. On **API Management** screen, select API Management service instance that was created above
   3. Select **APIs** in **API Management service** navigation pane
      ![apim-apis-pane](https://learn.microsoft.com/en-us/training/wwl-azure/explore-api-management/media/select-apis-navigation-pane.png)
   4. Select **OpenAPI** from list and select **Full** in pop-up
      ![open-api-full](https://learn.microsoft.com/en-us/training/wwl-azure/explore-api-management/media/create-api.png)
   5. Use values in below table to fill out fields
      |Setting|Value|Description|
      |:--|:--|:--|
      |OpenAPI Specification|`https://conferenceapi.azurewebsites.net?format=json`|References the service implementing the API, requests are forwarded to this address. Most of the nevessary information in the form is automatically populated after this is entered|
      |Diplay name|_Demo Conference API_|Name that is displayed in developer portal|
      |Name|_demo-conference-api_|Providers unique name for API|
      |Description|Automatically populated|Provide an optional description of the API|
      |API URL suffix|_conference_|Suffix is appended to the base URL for the API management service. API Management distringuishes APIs by their suffix and therefore must be unique for every API for a given publisher|
5. Configure backend settings</br>
   _Demo Conference API_ is created and a backend needs to be specified
   1. Select **Settings** in balde to right and enter `https://conferenceapi.azurewebsites.net/` in **Web service URL** field
   2. If checked, uncheck **Subscription required**
      ![apim-settings](https://learn.microsoft.com/en-us/training/wwl-azure/explore-api-management/media/api-settings-backend.png)
   3. **Save**
6. Test the API</br>
   API has now been imported and backend configured, time to test
   1. Select **Test**
   2. Select **GetSpeakers**. Page only shows **Query parameters** and **Headers**, if any. The `Ocp-Apim-Suscription-Key` is filled automatically for subscription key associated to API
   3. **Send**
   4. Backend responds with `200 OK` and some data
7. Clean up: `az group delete --name az204-apim-rg --no-wait`
## **Develop Event-Based Solutions**
### **Explore Azure Event Grid**
#### **Explore Azure Event Grid**
* Event Hubs is an eventing backplane that enables _event-driven, reactive programming_
  * Pub-sub model
    * Publishers emit events with no expectation how they are handled
    * Subscribers decide which events they want to handle
* Support for built-in events coming from Azure
  * Also supports own custom events using _custom topics_
* Event Grid connector sources and handlers (not comprehensive)
  ![event-grid-conns-hndlrs](https://learn.microsoft.com/en-us/training/wwl-azure/azure-event-grid/media/functional-model.png)
* **Concepts in Azure Event Grid**
  |Concept|Description|
  |:--|:--|
  |Events|What happened|
  |Event Sources|Where event took place|
  |Topics|Endpoint where publishers send events|
  |Event subscriptions|Endpoint or built-in mechanism to route events, sometimes to more than one handler. Subscriptions are also used by handlers to intelligently filter incoming events|
  |Event handlers|App or service reacting to the event|
* **Events**
  * Smallest amount of information that fully describes something that happened in the system
  * Has common information like: _event source_, _event time_, _unique identitifier_
  * Every event has specific information about relevant only to the specific event type
    * An event about a new file created in Azure Storage has details about the file, such as `lastModifiedTime`
    * Event Hubs event has URL of the capture
* **Event Sources**
  * Where the event happens
  * Each event source is related to 1+ event types
  * For example
    * Azure Storage is the event source for blob created events
    * IoT Hub is event source for device created events
    * Your app is the vent source for custom events that you define
  * _Responsible for sending events to Event Grid_
* **Topics**
  * Event Grid Topic provides an endpoint for the source to send events to
  * Publisher creates the event grid topic
    * Decides whether an event source needs 1 or more topic
  * Used for a collection of related events
  * To response to events, subscriber decides which topics to subscribe to
    |Topic Type|Description|
    |:--|:--|
    |**System Topics**|Built-in topics provided by Azure Services.</br>Don't see system topics in Azure Subscription, owned by publisher</br>To subscribe, provide info about resource to receive events from, if you have access to the resource, you can subscribe to its events|
    |**Custom Topics**|App and third-party topics. When you create or are assigned a custom topic, they are visible in Azure Subscription|
* **Event Subscriptions**
  * Tells Event Grid which events on a topic you're interested in receiving
  * When creating a subscription, you provide an endpoint for handling the event
  * Can filter events send to the endpoint
    * Filter by _event type_ or _subject pattern_
  * Set expiration for event subscriptions that are only needed for a limited time and you don't need to worry about cleaning up those subscriptions
* **Event Handlers**
  * Place where event is sent
  * Event Grid supports several handler types
    * Can use a supported Azure service
    * Can use own webhook
  * HTTP Webhook events are retried until handler returns `200 OK`
  * For Azure Storage Queue, events are retried until Queue service successfully proccess the message push to the queue
#### **Discover event schemas**
* Events _**consist of 4 required string properties**_
  * Common to all events from any publisher
  * Data object has properties specific to each publisher
  * _System topics_, the properties are specific to the resource provider, such as Azure Storage or Azure Event hubs
* Sources send events to Azure Event Grid in an array, which can contain several event objects
  * Array max size is 1MB
    * Each event is limited to 1MB
    * A `413 Payload Too Large` response is returned if size limit is exceeded
* Operations are charged in 64KB increments
  * Events over 64KB incurs operation charges as though they were multiple events
    * For example: 130KB event would incur charges for 3 separate events
* Event Grid sends events to publishers in an array that has a single event
* JSON schema for Event Grid event and each Azure publishers data payload can be found  in [Event Schema store](https://github.com/Azure/azure-rest-api-specs/tree/master/specification/eventgrid/data-plane)
* **Event Schema**
  * All event publishers use the following properties
    ```JSON
    [
      {
        "topic": string,
        "subject": string,
        "id": string,
        "eventType": string,
        "eventTime": string,
        "data":{
          object-unique-to-each-publisher
        },
        "dataVersion": string,
        "metadataVersion": string
      }
    ]
    ```
* **Event Properties**
  * All events have the top-level data
    |Property|Type|Required|Description|
    |:--|:--|:--|:--|
    |topic|string|No. If not included, Event Grid will stamp onto the event. If included, must match the Event Grid topic Azure Resource Manager ID exactly|Full resource path to the event source. Not writeable. Event Grid provides this value|
    |subject|string|Yes|Publisher-defined path to the event subject|
    |eventType|string|Yes|Generated event time based on providers UTC time|
    |id|string|Yes|Unique identifier for the event|
    |data|object|No|Event data specific to resource provider|
    |dataVersion|string|No. If not included, will be stamped with empty value|Schema version of the data object. Publisher defines schema version|
    |metadataVersion|string|No. If not included, Event Grid will stamp onto the event. If included, must match the Event Grid Schema `metadataVersion` exactly (currently, only `1`)|The schema version of the event metadata. Event Grid defines the schema of the top-level properties. Event Grid provides this value|
  * For custom topics, event publisher determines data object
    * Top-level data should have the same fileds as standard resource-defined events
  * When publishing events to custom topics, create subjects for your events that make it easy for subscribers to know whether they're interesting in the event
  * Subscribers use _subject_ to filter and route events
    * Consider providing the path for where event happened, so subscribers can filter by segments on that path
      * For example: If providing three segment path like `/A/B/C` in the subject
        * Subscribers could filter on `/A` to get broad set of events (i.e. `/A/B/E`, `/A/Z/C`, etc...)
        * Others could filter on `/A/B` to get narrower set
  * Sometimes your subject needs more detail about what happened
    * For example, the **Storage Accounts** publisher provides the subject `/blobServices/default/containers/<container-name>/blobs/<file>` when a file is added to a container.
      * A subscriber could filter by the path `/blobServifces/default/containers/testcontainer` to get all events for `testcontainer`, but not other containers
    * Can filter or route by suffix as well, i.e. only work with txt files, use a `.txt` filter
* **CloudEvents v1.0 Schema**
  * Azure Event Grid naticely supports events in the JSON implementation of `CloudEvents v1.0` and HTTP protocol binding
    * CloudEvents is an open specification for describing event data
  * Simplifies interoperability by providing a common event schema for publishing and consuming cloud based events
  * Schema allows for 
    * Uniform tooling
    * Standard ways of routing & handling events
    * Universal ways of deserializing outer event schema
  * Example Blob Storage event in CloudEvents format
    ```JSON
    {
        "specversion": "1.0",
        "type": "Microsoft.Storage.BlobCreated",  
        "source": "/subscriptions/{subscription-id}/resourceGroups/{resource-group}/providers/Microsoft.Storage/storageAccounts/{storage-account}",
        "id": "9aeb0fdf-c01e-0131-0922-9eb54906e209",
        "time": "2019-11-18T15:13:39.4589254Z",
        "subject": "blobServices/default/containers/{storage-container}/blobs/{new-file}",
        "dataschema": "#",
        "data": {
            "api": "PutBlockList",
            "clientRequestId": "4c5dd7fb-2c48-4a27-bb30-5361b5de920a",
            "requestId": "9aeb0fdf-c01e-0131-0922-9eb549000000",
            "eTag": "0x8D76C39E4407333",
            "contentType": "image/png",
            "contentLength": 30699,
            "blobType": "BlockBlob",
            "url": "https://gridtesting.blob.core.windows.net/testcontainer/{new-file}",
            "sequencer": "000000000000000000000000000099240000000000c41c18",
            "storageDiagnostics": {
                "batchId": "681fe319-3006-00a8-0022-9e7cde000000"
            }
        }
    }
    ```
  * [CloudEvents fields, types, and definitions](https://github.com/cloudevents/spec/blob/v1.0/spec.md#required-attributes)
  * Headers values for events delivered in CloudEvents scehma and Event Grid schema are the same exception for `content-type`
    * `content-type` header for CloudEvents is `"content-type":"application/cloudevents+json; charset=utf-8"`
    * For Event Grid schema, it is `"content-type":"application/json; charset=utf-8"`
  * Can use Event Grid for both I/O of events in CloudEvents schema
  * Can use CloudEvents for system events, like Blob Storage events and IoT Hub events, and custom events.
    * Can also transform these events on the wire back and forth
#### **Explore event delivery durability**
* Event Grid provides durable delivery
* Attempt to deliver each event at least once for each matching subscription immediately
* If subscriber endpoint doesn't acknowledge receipt of an event, or there is a failure, Event Grid retries based on fixed retry schedule and policy
* By default, Event Grid delivers one event at a time to the subscriber, and payload is an array with a single event
> 🔵**NOTE**</br>
> Event Grid **does not guarantee** order of event delivery, so subscribers may receive them out of order
* **Retry Schedule**
  * When event delivery fails, Event grid decides:
    * Should it retry delivery
    * Dead-letter the event
    * Drop event based on type of error
  * If error returned by subscribed endpoint is a configuration-related error that can't be fixed with retries, EventGrid will either dead-letter the event or drop it (if dead-lettering is not configured)
  * Retries do not occur if endpoints produce the following errors
    |Endpoint Type|Error Codes|
    |:--|:--|
    |Azure Resources|400 Bad Request, 413 Rquest Entity Too Large, 403 Forbidden|
    |Webhook|400 Bad Request, 413 Request Entity Too Large, 403 Forbidden, 404 Not Found, 401 Unauthorized|
  * If error returned by subscribed andpoints is not in above list, Event Grid waits 30 seconds for a response after delivering a message
    * If endpoint hasn't responded in this time, message is queued for retry
      * Uses exponential backoff retry policy for event delivery
    * If endpoint responds with-in 3 minutes, Event Grid will attempt to remove the vent from the retry queue on a best effort basis but duplicates may still be received
  * Event Grid adds small randomization to all retry steps and may opportunistically skip certain retries if an endpoint is consistently unhealthy, down for long period of time, or appears to be overwhelmed
* **Retry Policy**
  * Can customize retry plicy when creating event subscription by using the following 2 configurations
    * Events will be dropped if either of the limits of the retry policy is reached
      * **Maximum number of attempts** - Integer value between 1 and 30, default is 30
      * **Event time-to-live (TTL)** - Integer value between 1 and 1440, default is 1440
  * CLI example for settting max attempts
    ```
    az eventgrid event-subscription create \
      -g <eventGrid_resoure_group> \
      --topic-name <topic_name> \
      --name <event_subscription_name> \
      --endpoint <endpoint_URL> \
      --max-delivery-attempts 18
    ```
* **Output Batching**
  * Can configure Event Grid to use batch events for delivery
    * Improves HTTP performance in high-throughput scenarios
  * Turned off by default
  * Can be turned on per-subscription via Portal, CLI, PoSH, or SDKs
  * 2 settings
    * **Max events per batch**
      * Maximum number of events Event Grid will deliver per batch
      * Doesn't delay delivery of events if fewer events are available
      * Integer value between 1 and 5000
    * **Perferred batch size in KB**
      * Target celing for batch size
      * May exceed limit if single event is larger than preferred size
        * i.e. if configured for a max of 4KB, and a 10KB event comes in, the 10KB event will be sent as its own batch
* **Delayed Delivery**
  * If endpoint experiences delivery failures, Event Grid will begin delaying delivery and retry of events to that endpoint
    * For example, if the first 10 events sent to endpoint fail, Event Grid assumes endpoint is experiencing issues and will delay all subsequent retries and new deliveries
      * Can be up to several hours
  * Functional purpose of delayed delivery is to protect unhealthy endpoints and the Event Grid system
    * With out back-off and delayed delivery, Event Grid's retry policy and volume capabilities can easily overwhelm a system
* **Dead-letter events**
  * If unable to deliver an event with-in a specified time period or number of retries, Event Grid can send the event to a storage account
    * Known as dead-lettering
  * Dead-lettering (if configured) occurs when
    * Event isn't delivered within the TTL period
    * Number of retries is exceeded
  * If dead-lettering is not configured, events are dropped
  * Requires a storage account specified when creating event subscription
  * `400 Bad Request` and `413 Request Entity Too Large` are automatically dead-lettered
  * 5-minute delay between last attempt to deliver an event and when it is delivered to dead-letter location
    * Intended to reduce number of Blob storage ops
    * if dead-letter location unavailable for 4 hours, event is dropped
* **Custom delivery properties**
  * Event subscriptions allow you to set up HTTP headers that are included in delivered events
  * Can set up to 10 headers when creating an event subscription
    * Limited to <= 4096 bytes per header
  * Supported on events with following destination
    * Webhooks
    * Azure Service Bus topics and queues
    * Azure Event hubs
    * Relay Hybrid Connections
  * Before setting Dead-letter location, must have a storage account with a container. Endpoint is provided for this container when creating the event subscription
#### **Control access to events**
* Event Grid uses RBAC to control level of access and allowed management operations
* **Built-in Roles**
  |Role|Description|
  |:--|:--|
  |Event Grid Subscription Reader|Lets you read Event Grid event subscriptions|
  |Event Grid Subscription Contributor|Lets you manage Event Grid event subscription operations|
  |Event Grid Contributor|Lets you create and manage Event Grid resources|
  |Event Grid Data Sender|Lets you send events to Event Grid topics|
  * Event Grid Subscription Reader and Event Grid Subscription Contributor roles are for managing event subscriptions
    * Important when implementing event domains because they giver users permissions they need to subscribe to topics in event domain
    * Focused on event subscriptions and don't grant access for actions such as creating topics
  * Event Grid Contributor role allows you to create and manage Event Grid resources
* **Permissions for Event Subscriptions**
  * If using event handler that isn't a Webhook (i.e. event hub or queue storage), you need _write_ access to that resource
  * Must have **Microsoft.EventGrid/EventSubscriptions/Write** permission on the event source
    * Need this permission you're writing a new subscription at the scope of the resource
  * Required resource differs based on whether you're subscribing to a system topic or custom topic
    |Topic Type|Description|
    |:--|:--|
    |System Topics|Need permission to write a new event subscription at the scope of the resource publishing the event. The format of the resource is: `/subscriptions/{subscription-id}/resourceGroups/{resource-group-name}/providers/{resource-provider}/{resource-type}/{resource-name}`|
    |Custom Topics|Need permission to write a new event subscription at the scope of the event grid topic. The format of the resource is: `/subscriptions/{subscription-id}/resourceGroups/{resource-group-name}/providers/Microsoft.EventGrid/topics/{topic-name}`|
#### **Receive events by using webhooks**
* Webhooks on of may ways to receive events from Azure Event Grid
* When new event is ready, Event Grid service POSTs an HTTP request to the configured endpoint with the event in the request body
* Requires proof that you own the webhook endpoint before Event Grid will deliver events to it
* Azure infrastructure automatically handles validation for:
  * Azure Log Apps with Event Grid Connector
  * Azure Automation via Webhook
  * Aure Functions with Event Grid Trigger
* **Endpoint validation with Event Grid events**
  * If using any other endpoint than the previously mentioned 3, such as an HTTP trigger based AZ function, endpoint code needs to participate in validation handshake with Event Grid
  * Two ways of validating the subscription:
    * **Synchronous handshake**
      * At time of event subscription, Event Grid sends a subscription validation event to your endpoint. The schema of this event is similar to any other Event Grid event. The data portion of the event includes a `validationCode` property. Application verified that the validation request is for an expected event subscription, and returns the validation code in the response synchronously. This handshake mechanisk is supported in all Event Grid versions
    * **Asynchronous handshake**
      * In certain cases, you can't return the ValidationCode in response synchronously. For example, if you use a third-party service (i.e. Zapier or IFTTT), you can't programmatically respond with the validation code
  * Starting with version `2018-05-01-preview`, Event Grid supports a manual validation handshake
    * If creating an event subscription with an SDK or toll that uses API version 2018-05-01-preview or later, Event Grid sends a `validationUrl` property in the data portion of the subscription validation event
    * To complete handshake, find URL in data and perform GET request
  * `validationUrl` is valid for 5 minutes
    * During this time _provisioning state_ of the event subscription is `AwaitingManualAction`
    * If manual validation not completed with-in the time frame, _provisioning state_ is set to `Failed`
      * Have to create event subscription again before starting manual validation
  * Authentication mechanism requires webhook endpoint returns a `200 OK` response before being put in manual validation mode
  > 🔵**Note**</br>
  > Using self-signed certificates for validation is not supported. Use a signed certificate from a commercial certificate authority instead.
#### **Filter events**
* When creating event subscription, you have 3 options for filtering
  * Event types
  * Subject begins with or ends with
  * Advanced fields and operators
* **Event type filtering**
  * All event types for the event source are sent to the endpoint by default
  * For example, can get notified of updates to your resources, but not notified for other operations like deletions
    * In this case, filter by `Microsoft.Resources.ResourceWriteSuccess` event type
  * Provide array with event types for specify `All` to get all event type for the event source
  * JSON syntax for filtering by event type:
    ```JSON
    "filter": {
      "includedEventTypes": [
        "Microsoft.Resources.ResourceWriteFailure",
        "Microsoft.Resources.ResourceWriteSuccess"
      ]
    }
    ```
* **Subject Filtering**
  * For simple subject filtering, specify starting or ending vlaue for the subject
    * For example, specify `.txt` to only get events related to .txt files
    * Or, to get notified on all events in a container, specify container path (i.e. `blobServices/default/containers/testcontainer`)
  * JSON syntax for filtering by subject
    ```JSON
    "filter": {
      "subjectBeginsWith": "/blobServices/default/containers/mycontainer/log",
      "subjectEndsWith": ".jpg"
    }
    ```
* **Advanced Filtering**
  * To filter by values in data fields and specify a comparison operator, use the advanced filtering option `advancedFilters`
    * Must specify:
      * Operator type - type of comparison
      * Key - field in event data that is used. Can be number, bool, string
      * value(s) - value(s) to compare to key
  * Example advanced filter JSON
    ```JSON
    "filter": {
      "advancedFilters": [
        {
          "operatorType": "NumberGreaterThanOrEquals",
          "key": "Data.Key1",
          "value": 5
        },
        {
          "operatorType": "StringContains",
          "key": "Subject",
          "values": ["container1", "container2"]
        }
      ]
    }
    ```
#### **Exercise: Route custom events to web endpoint by using Azure CLI**
* Exercise goals:
  * Enable Event Grid resource provider
  * Create custom topic
  * Create message endpoint
  * Subscribe to a custom topic
  * Send event to custom topic
1. **Create resource group**
   1. Launch cloud shell ([https://shell.azure.com](https://shell.azure.com)) > **Bash**
      ```BASH
      let rNum=$RANDOM*$RANDOM
      myLocation=<myLocation>
      myTopicName="az204-egtopic-${rNum}"
      mySiteName="az204-egsite-${rNum}"
      mySiteUrl="https://${mySiteName}.azurewebsites.net"

      az group create \
        --name az204-evgrid-rg \
        --location $myLocation
      ```
2. **Create custom topic**
   1. Create custom topic by using `az eventgrid topic create`
      ```BASH
      az eventgrid topic create \
        --name $myTopicName \
        --location $myLocation \
        --resource-group az204-evgrid-rg
      ```
3. **Create a message endpoint**
   * Need to create an endpoint for event message before subscribing to custom topic
      * Example below uses pre-built web app that displays event messages
        * Solution includes App Service plan, App Service web app, and source code from GitHub
   1. Create message endpoint
      ```BASH
      az deployment group create \
        --resource-group az204-evgrid-rg \
        --template-uri "https://raw.githubusercontent.com/Azure-Samples/azure-event-grid-viewer/main/azuredeploy.json" \
        --parameters siteName=$mySiteName hostingPLanName=viewerhost
      
      echo "Your web app URL: ${mySiteUrl}
      ```
4. **Subscribe to custom topic**
   * Subscribe to event grid topic to tell Event Grid which events you want to track and where to send the tracked events
   * Subscribe to custom topic using `az eventgrid event-subscription create`
    ```BASH
    endpoint="${mySiteUrl}/api/updates"
    subId=$(az account show --subscription "" | jq -r '.id')

    az eventgrid event-subscription create \
      --source-resource-id "/subscriptions/$subId/resourceGroups/az204-evgrid-rg/providers/Microsoft.EventGrid/topics/$myTopicName"
      --name az204ViewerSub \
      --endpoint $endpoint
    ```
5. **Send event to custom topic**
   1. Retrieve URL and key for custom topic
      ```BASH
      topicEndpoint=$(az eventgrid topic show --name $myTopicName -g az204-evgrid-rg --query "endpoint" --output tsv)
      key=$(az eventgrid topic key list --name $myTopicName -g az204-evgrid-rg --query "key1" --output tsv)
      ```
   2. Create event data to send
      ```BASH
      event='[ {"id": "'"$RANDOM"'", "eventType": "recordInserted", "subject": "myapp/vehicles/motorcycles", "eventTime": "'`date +%Y-%m-%dT%H:%M:%S%z`'", "data":{ "make": "Contoso", "model": "Monster"},"dataVersion": "1.0"} ]'

      curl -X POST -H "aeg-sas-key: $key" -d "$event" $topicEndpoint
      ```
6. Clean up resource: `az group delete --name az204-evgrid-rg --no-wait`
### **Explore Azure Event Hubs**
#### **Discover Azure Event Hubs**
* Event Hubs represent the "front door" for an event pipeline, often called an _event ingestor_ in solution architectures
* Component that sits between publishers and consumers to decouple production of event stream from consumption of those events
* Provides unified streaming platform with time retention buffer
  |Feature|Description|
  |:--|:--|
  |Fully managed PaaS|Event Hubs is a fully managed PaaS with little configuration or management overhead. Event Hubs for Apache Kafka ecosystems gives you PaaS Kafka experience with having to manage, configure, or run your clusters|
  |Real-time and batch processing|Event Hubs uses a partitioned consumer model, enabling multiple applications to process the stream concurrently and letting you control the speed of processing|
  |Scalable|Scaling options, like Auto-inflate, scale the number of throughput units to meet your usage needs|
  |Rich ecosystem|Event Hubs for Apache Kafka ecosystems enables Apache Kafka (1.0 and later) clients and applications to talk to Event hubs. Do not need to set up, configure, and manage your own Kafka clusters|
* **Key Concepts**
  * Event Hubs client
    * Primary interface for devs interacting with Event Hubs client library. Many different Event Hub clients, each dedicated to specific use of Event Hubs, such as publishing or consuming events
  * Event Hubs producer
    * Type of client that serves as a source of telemetry data, diagnostics info, usage logs, or other log data, as part of an embedded device solution, mobile device app, game title running on a console or other device, some client or server based business solution, or a web site.
  * Event Hubs consumer
    * Client that reads information from Event Hub and allows processing of it. May also involve distribution or storage of information in raw or transformed fasion. Are often robust and high-scale platform infrastructure parts with built-in analytics capabilities, like Azure Stream Analytics, Apache Spark
  * Partition
    * Ordered sequence of events that is held in an Event Hub.
    * Means of data organization associated with the parallelism required by event consumers. Azure Event Hubs provides message streaming through a partitioned consumer pattern in which each consumer only reads a specific subset, or partition, of the message stream.
    * Newly received events are added to end of sequence.
    * Number of partitions is specified at Event Hub creation time and can not be changed
    * Consumer Group
      * View of an entire Event Hub
      * Enable multiple consuming applications to each have a separate view of the event stream, and to read the stream independently at their own pace and from their own position
      * Limited to 5 concurrent readers on a partition per consumer group
        * _Recommended there is only ever 1 active consumer for a given partition and consumer group pairing_
        * Multiple reader on same partition will receive duplicate events
    * Event Receivers
      * Entity that reads event data from Event Hubs
      * All consumers connect via _AMQP 1.0_ session
      * Events delivered through a session as they become available
      * All Kafka consumers connect via _Kafka protocol 1.0_ and later
    * Throughput units/Processing units
      * Pre-purchased units of capacity that control throughput capacity of Event Hubs
  
  ![event-hub-stream-proc-arch](https://learn.microsoft.com/en-us/training/wwl-azure/azure-event-hubs/media/event-hubs-stream-processing.png)
#### **Explore Event Hubs Capture**
* Can automatically capture streaming data in Event Hubs in Azure Blob storage or ADLS account of your choice
  * Added flexibility of specifying a time or size interval
* Setting up capture is fast, has no administrative costs to run it, and scales automatically with Event Hubs _throughput units in standard tier_ and _processing units in premium tier_ 
* Capture enables you to process real-time and batch-based pipelines on the same stream
  ![event-hub-capture](https://learn.microsoft.com/en-us/training/wwl-azure/azure-event-hubs/media/event-hubs-capture.png)
* **How Event Hubs Capture works**
  * Event Hubs is a time-retention durable buffer for telemetry ingress, similar to a distributed log
  * Key to scaling is the partitioned consumer model
    * Each partition is an independent segment of data and is consumed independently
  * Based on the configurable retention period, data is aged off so event hub never gets "too full"
  * Event Hubs Capture enables you to specify your own Azure Blob storage account and container, or ADLS account, which are used to store the captured data
    * Storage account and Event Hub can be in different regions
  * Captured data is written in Apache Avro format
    * a compact, fast, binary format that provides rich data structurs with inline schema
    * Widely used in Hadoop ecosystem, Stream Analytics, and Azure Data Factory
* **Capture Windowing**
  * Can configure a window to control capturing
  * Is a minimum size and time configuration with a "first wins policy"
    * First trigger encountered causes a capture operation
  * Each partition capture independently and writes a completed blobk blob at the time of capture, name for the time at which the capture interval was encountered.
  * Storage naming convention: `{Namespace}/{EventHub}/{PartitionId}/{Year}/{Month}/{Day}/{Hour}/{Minute}/{Second}`
    * Date values are left padded with a 0. i.e. 01/02/23/01/30/55
* **Scaling to throughput units**
  * Event Hubs traffic is controlled by throughput units
  * Throughput unit allows 
    * Ingress: 1MB/second or 1000 events/second
    * Egress: 2MB/second or 2000 events/second
  * Standard Event Hubs can be configured with 1-20 throughput units
    * Can purchase more with quota increase support request
  * Usage is throttled if throughput is exceeded
  * Event Hubs Capture copies data directly from internal Event Hubs storage, bypassing egress throughput unit quotas
    * Saves egress for processing readers, such as Stream Analytics or Spark
  * Once Capture is configured, it runs automatically when the first event is sent, and continues running
    * Event Hubs writes an empty file when no data is present, providing a predictable cadence and marker that can feed your batch processors
#### **Scale your processing application**
* To scale event processing application, run multiple instances of the app and have it balance the load among themselves
* In older versions, `EventProcessorHost` allowed you to balance the load between multiple instances of your program and checkpoint events when receiving
  * Newer verions (5.0+), `EventProcessorClient` (.NET/Java), or `EventHubConsumerClient` (Python and JavaScript) allows you to do the same
> 🔵**NOTE**</br>
> Key to scale for Event Hubs is the idea of partitioned consumers. In contrast to the competing consumers pattern, the _partitioned consumer pattern_ enables high scale by removing the contention bottleneck and facilitating end-to-end parallelism
* **Example scenario**
  * COnsider a home security company that monitors 100,000 homes. Every minute, data is received from various sensors such as motion detector, door/window open sensor, glass break detector, etc... Company provides a web site for residents to monitor the activity of their home in near real time
  * Each sensor pushes data to an event hub. The event hub is configured with 16 partitions. On the consuming end, you need a mechanism that can read these events, consolidate them, and dump the aggregate to a storage blob, which is then projected to a user-friendly web page
  * When designing the consumer in a distributed environment, the scenario must handle the following requirements
    |Scenario|Handling|
    |:--|:--|
    |Scale|Create multiple consumers, with each consumer taking ownership of reading from a few Event Hubs partitions|
    |Load balance|Increate/reduce consumers dynamically. For example, when a new sensor type is added, the number of events increase. In this case, the operator (human) increases the number of consumer instances. Then, the pool of consumers can rebalance the number of partitions they own, to share the load with the newly added consumers|
    |Seamless resume on failures|If a consumer (consumer A) fails, then other consumers can pick up the partitions owned by consumer A and continue. Also, the continuation point, called a _checkpoint_ or _offset_ should be at the exact point at which consumer A failed, or slightly before that.|
    |Consume events|While previous 3 points deail with management of the consumer, there must be code to consume the events and do something useful with it. For example, aggregate it and upload to blob storage.
* **Event Processor or Consumer Client**
  * Don't need to build own solution to meet these requirements. Azure Event Hubs SDKs provider this functionality.
    * In .NET or Java SDKs, use `EventProcessorClient`
    * In Python or JavaScript, use `EventHubConsumerClient`
  * _Recommended_ to use event processor client for reading and processing events in production scenarios.
    * Clients can work cooperatively within the context of a consumer group for a given event hub
    * Clients will automatically manage distribution and balancing of work as instances become available/unavailable for the group
* **Partition Ownership Tracking**
  * Event processor instance typically owns and processes events from one or more partititions
    * Evenly distributed among all active event processor isntances associated with an event hub and consumer group combination
  * Event processors are given a unique identifier and claims ownership of partitions by adding or updating an entiry in the checkpoint store
    * All instances communicate with this store periodically to update its own processing state as well as to learn about other active instances
      * Data is used to balance load among active processors
* **Receive messages**
  * When creating an event processor, you specify the functions that will process events and errors
  * Each call to the function that processes events delivers a single event from a specific partition
    * Your responsibility to handle this event
    * Need to write code to handle retry logic
      * Must take care with poisoned messages
  * Should be relatively fast, in other words, don't do a bunch of complicated and time consuming processing
  * If there is a need to write to storage and do some routing, best to use 2 consumer groups and 2 event processors
* **Checkpointing**
  * Process by which an event processor marks or commits the position of the last auccessfully processed event within a partition
    * Typically done with the function that processes the events and occurs on a per-partition basis within a consumer group
  * If event processor disconnects from a partition, another instance can resume processing the partition at the checkpoint
    * When processor connects, it passes the offset to the event hub to specify the location at which to start reading
    * Can use _checkpointing_ to both mark events as "complete" by downstream apps, and to provide resiliency when an event processor goes up
      * Can return older data by specifying an earlier offset than the checkpoint
* **Thread safety and processor instances**
  * By default, function that processes events is called sequentially for a give partiton
  * Subsequent events and calls to this function from the same partition queue behind up behind the scenes as the event pump continues to run in the background on other threads
  * Events from different partitions can be processed concurrently and any shared state that is accessed across partitions have to be synchronized
#### **Control access to events**
* Azure Event Hubs support both Azure AD and SAS to handle both authentication and authorization
* Following builtin roles are available
  |Role|Description|
  |:--|:--|
  |[Azure Event Hubs Data Owner](https://learn.microsoft.com/en-us/azure/role-based-access-control/built-in-roles#azure-event-hubs-data-owner)|Use this role to give _complete access_ to Event Hubs resources|
  |[Azure Event Hubs Data Sender](https://learn.microsoft.com/en-us/azure/role-based-access-control/built-in-roles#azure-event-hubs-data-sender)|Give _send access_ to Event Hubs resources|
  |[Azure Event Hubs Data Receiver](https://learn.microsoft.com/en-us/azure/role-based-access-control/built-in-roles#azure-event-hubs-data-receiver)|Give _receiving access_ to Event Hubs resources|
* **Authorize access with Managed Identities**
  * To authorize request to Event Hubs service from managed identity in your app, you need to configure Azure RBAC for the managed identity
  * When Azure role is assigned to managed identity, the managed identity is granted access to Event Hubs data at the appropriate scope
* **Authorize access with MS Identity Platform**
  * Key advantage of using Azure AD with Event Hubs is that your credentials no longer need to be stored in code
    * Instead, can request an OAuth 2.0 token from MS Identity Platform
  * Azure AD authenticates the security principal (user, group, or service principal) running the app
  * If Authentication succeeds, AAD returns the access token to the application and the app can use the token to authorize requests to Azure Event Hubs
* **Authorize access to Event Hubs publisher with SAS**
  * Event publisher defines a virtual endpoint for an Event Hub
  * Publisher can only send messages to an event hub and _can not_ receive messages
  * Event Hub typically employs one publisher per client
    * All messages sent to any publisher of an Event hub are enqueued within that event hub
  * Publishers enable fine-grained access control
  * Each Event Hub client is assigned a unique token which is uploaded to the client
    * Client that holds the token can only send to the one publisher
    * If multiple clients share the same token, then each of them shares the publisher
  * All tokens are assigned with SAS keys
    * Typically, all tokens are signed with the same key
    * Clients are not aware of the key, preventing clients from manufacturing tokens
    * Clients operate on the same tokens until the token expires
* **Authorize access to Event Hubs consumers with SAS**
  * To authenticate back-end applications that consume the data generated by Event Hubs producers, Event hubs token authentication requires clients to either have the `manage` rights or the `listen` priveleges assigned to its Event Hubs namespace or event hub instance or topic
  * Data is consumed from Event Hubs using consumer groups
  * SAS policy gives you granular scope
    * Applied only at entity level and not at consumer level
      * Privileges defined at namespace level or event hub instance or topic level applies to consumer groups of that entity
#### **Perform common operations with the Event Hubs client library**
* Contains examples of common operations you can perform with Event Hubs SDK (`Microsoft.Azure.EventHubs`)
* **Inspect an Event Hub**
  * Many operations take place within the scope of a specific partition
    * Because partitions are owned by the Event hub, their names are assigned at time of creation.
    * Query Event Hub using one of the Event Hub clients to see what partitions are available
  ```C#
  var connectionString = "<connection string for event hubs namespace>";
  var eventHubName = "<name of event hub>";

  await using(var producer = new EventHubProducerClient(connectionString, eventHubName))
  {
    string[] partitionIds = await producer.GetPartitionIdsAsync();
  }
  ```
* **Publish events to an Event Hub**
  * In order to publish events, need to create `EventHubProducerClient`
  * Producers publish events in braches and may request a specific partition, or allow Event Hubs service to decide which partition events should be published to.
    * _Recommended_ to use automatic routing when publishing events that need to be highly available or when data should be distributed evenly among partitions
  ```C#
  var connectionString = "<connection string for event hubs namespace>";
  var eventHubName = "<name of event hub>";

  await using(var producer = new EventHubProducerClient(connectionString, eventHubName))
  {
    using EventDataBatch eventBatch = await producer.CreateBatchAsync();
    eventBatch.TryAdd(new EventData(new BinaryData("first")));
    eventBatch.TryAdd(new EventData(new BinaryData("second")));

    await producer.SendAsync(eventBatch);
  }
  ```
* **Read events from an Event Hub**
  * To read events from an Event Hub, need to create an `EventHubConsumerClient` for given consumer group
  * When Event Hub is created, it provides a default consumer group that can be used to get started with exploring Event Hubs
  > 🔵**NOTE**</br>
  > Important to note this approach to consuming is intended to improve the experience of exploring the Event Hubs client library and prototyping. It is recommended that it not be used in production scenarios. For production, we recommend using the [Event Processor Client](https://github.com/Azure/azure-sdk-for-net/blob/main/sdk/eventhub/Azure.Messaging.EventHubs.Processor), as it provides more robust and performant experience.
  ```C#
  var connectionString = "<connection string for event hub namespace>";
  var eventHubName = "<event hub name>";
  // Only use this for prototyping and general testing
  // Not to be used in production scenarios
  string consumerGroup = EventHubConsumerClient.DefaultConsumerGroup;

  await using(var consumer = new EventHubConsumerClient(consumerGroup, connectionString, eventHubName))
  {
    using var cancellationSource = new CancellationTokenSource();
    cancellationSource.CancelAfter(TimeSpan.FromSeconds(45));
    await foreach(PartitionEvent receivedEvent in consumer.ReadEventAsync(cancellationSource.Token))
    {
      // At this point, the loop will wait for events to be available 
      // in the Event Hub. When available, the loop will iterate with
      // the event that was received. Because no maximum wait time was
      // specified, loop will wait forever unless cancellation is
      // requested using the cancellation token
    }
  }
  ```
* **Read events from an Event Hub partition**
  * To read from specific partition, consumer needs to specify where in the event stream to begin receiving events; in this example, it's focused on reading all published events for the first partition of the Event Hub
  ```C#
  var cancellationSource = new CancellationTokenSource();
  cancellationSource.CancelAfter(TimeSpan.FromSeconds(45));
  
  var storageConnectionString = "<storage account conn string>";
  var blobContainer = "<name of blob container>";

  var eventHubConnectionString = "<connection string for event hub namespace>";
  var eventHubName = "<event hub name>";
  var consumerGroup = "<name of event hub consumer group>";

  Task processEventHandler(ProcessEventArgs eventArgs) => Task.CompletedTask;
  Task processErrorHandler(ProcessErrorEventArgs eventArgs) => Task.CompletedTask;

  var storageClient = new BlobContainerClient(storageConnectionString, blobContainerName);
  var processor = new EventProcessorClient(storageClient, consumerGroup, eventHubsConnectionString, eventHubName);

  processor.ProcessEventAsync += processEventHandler;
  processor.ProcessErrorAsync += processErrorHandler;

  await processor.StartProcessingAsync();
  try
  {
    // The processor performs its work in the background; block 
    // until cancellation to allow processing to take place
    await Task.Delay(Timeout.Infinite, cancellationToken.Source);
  }
  catch(TaskCanceledException)
  {
    // Expected when delay is canceled
  }

  try
  {
    await processor.StopProcessingAsync();
  }
  finally
  {
    // To prevent leaks, handlers should be removed when processing
    // is complete
    processor.ProcessEventAsync -= processEventHandler;
    processor.ProcessErrorAsync -= processErrorHandler;
  }
  ```
## **Develop message-based solutions**
* Azure supports 2 types of queue mechanisms _Service Bus queues_ and _Storage queues_
#### **Choose a message queue solution**
* Storage Queues and Service Bus queues have slightly different feature sets
  * Can choose both if want to
* **Consider using Service Bus Queues when:**
  * Solution needs to receive messages without having to poll
    * Can be achieved in Service Bus qeueues using long-polling to receive operation using TCP-based protocols that SB supports
  * Solution requires the queue to provide guaranteed FIFO delivery
  * Solution needs to support automatic duplicate detection
  * Want application to process messages as parallel long-running streams (messages are associated with a stream using teh _session ID_ property on the message)
    * In this model, each node in consuming application competes for streams, as opposed to messages
      * When a stream is given to a consuming node, the node can examine the state of the application stream state using transactions
  * Solution requires transactional behavior and atomicity when sending/receiving multiple messages from a queue
  * Application handles messages that can exceed 64KB, but wont approach the 256KB limit
* **Consider using Storage queues when:**
  * Application must store > 80GB of messages in a queue
  * Application wants to track progress for processing a message in the queue
    * Useful if the worker processing a message crashes
      * Another worker can then use that information to continue from where the prior worker left off
    * Require server side logs of all of the transactions executed against your queues
#### **Explore Azure Service Bus**
* Azure Service Bus is fully managed enterprise integration message broker
  * Decouples apps and services
  * Data transferred using _messages_
    * container decorated with metadata and contains data
    * Can be any kind of information, including structure data encoded with common formats (i.e. JSON, XML, Apache Avro, plain text, etc...)
* Common messaging scenarios:
  * _Messaging_ - Transfer business data
  * _Decouple applications_ - Improve reliability and scalability of apps and services
    * App and service do not have to be online at the same time
  * _Topics and Subscriptions_ - Enable 1:n relationships between publishers and subscribers
  * _Message sessions_ - Implement workflows that require message ordering or message deferral
* **Service Bus Tiers**
  * _Standard_ and _Premium_ tiers
  * High-level differences between the two
    |Premium|Standard|
    |:--|:--|
    |High throughput|Variable throughput|
    |Predictable performance|Variable latency|
    |Fixed pricing|Pay-as-you-go variable pricing|
    |Ability to scale workload up and down|N/A|
    |Message size up to 100MB|Message size upto 256KB|
* **Advanced Features**
  |Feature|Description|
  |:--|:--|
  |Message sessions|Create FIFO guaranteee. Manage sessions enable exclusive, ordered handling of unbounded sequences of related messages|
  |Autoforwarding|Chains a queue or subscription to another queue or topic that is in the same namespace|
  |Dead-letter queue|Holds messages that can't be delivered to any receiver|
  |Scheduled delivery|Submit messages to queue or topic for delayed processing|
  |Message deferral|Queue or subscription client can defer retrieval of message until later time. Message remains in queue or subscription but is set aside|
  |Batching|Client-side batching enables queue or topic client to delay sending message for a certain period of time|
  |Transactions|Groups 2+ operations into an _execution scope_. Service Bus supports grouping operations against a single messaging entity within the scope of a single transaction. A message entity can be a queue, topic, or subscription|
  |Filtering and actions|Subscribers can define which messages they want to receive from a topic. Messages are specified in form of one or more named subscription rules|
  |Autodelete on idle|Enables you to specify an idle interval after which a queue is automatically deleted. Min duration is 5 minutes|
  |Duplicate detection|Error could cause client to have a doubt about the outcome of a send operation. Duplicate detection enables the sender to resend the same message, or for the queue or topic to discard any duplicate copies|
  |Security protocols|SB supports security protocols such as SAS, RBAC and Managed identities for Azure resources|
  |Geo-disaster recovery|Enables data processing to continue operating in a different region or datacenter|
  |Security|SB supports standard AMQP 1.0 and HTTP/REST protocols|
* **Compliance with standards and protocols**
  * Primary wire protocol for SB is [Advanced Messaging Queuing Protocol (AMQP) 1.0](https://learn.microsoft.com/en-us/azure/service-bus-messaging/service-bus-amqp-overview)
    * An open ISO/IEC standard
  * Allows customers to write apps that work against Service Bus and on-premises brokers such as ActiveMQ or RabbitMQ
    * [AMQP protocol guide](https://learn.microsoft.com/en-us/azure/service-bus-messaging/service-bus-amqp-protocol-guide) provides detailed information if you want to build this abstraction
  * _Service Bus Premium_ is fully compliant with Java/Jakarta EE [Java Message Service (JMS) 2.0](https://learn.microsoft.com/en-us/azure/service-bus-messaging/how-to-use-java-message-service-20) API
* **Client Libraries**
  * Azure SDK supported Service Bus client libraries
    * [Azure Service Bus for .NET](https://learn.microsoft.com/en-us/dotnet/api/overview/azure/service-bus)
    * [Azure Service Bus libraries for Java](https://learn.microsoft.com/en-us/java/api/overview/azure/servicebus)
    * [Azure Service Bus provider for Java JMS 2.0](https://learn.microsoft.com/en-us/azure/service-bus-messaging/how-to-use-java-message-service-20)
    * [Azure Service Bus Modules for JavaScript and TypeScript](https://learn.microsoft.com/en-us/javascript/api/overview/azure/service-bus)
    * [Azure Service Bus libraries for Python](https://learn.microsoft.com/en-us/python/api/overview/azure/servicebus)
#### **Discover Service Bus queues, topics, and subscriptions**
* **Queues**
  * FIFO message delivery with 1+ competing consumers
  * Messages stored durably in queue to producers (senders) and consumers (receivers) so they don't have to process messages concurrently
  * **Load-leveling**
    * Send/Receive messages at different rates
    * Intermediating message producers and consumers means consuming application only has to handle average load instead of peak load
  * Can create using:
    * Portal
    * PoSH
    * CLI
    * ARM Templates
  * Send/receive using clients written in C#, Java, Python, and JavaScript
* **Receive Modes**
  * Can Specify 2 different modes _**Receive and delete**_ or _**Peek lock**_
  * **Received and delete**
    * Simplest mode
    * When request received from consumer, message is marked as being consumed and returned to consumer
    * For scenarios where application can tolerate not processing a message if failure occurs
      * For example if app requests a message and then crashes, the message is marked as consumed and when the app up comes up continues processing the next message and original is skipped
  * **Peek lock**
    * Receive operation becomes two-stage
      * Find next message to consume, lock it, and return to application
      * After processing of message is finished by consumer, makes request to SB to complete second stage which marks the message as being consumed
    * If unable to process the message, consumer can request SB to **abandon** the message
      * SB unlocks the message and makes it available to consumers again
    * Locks have a **timeout**
      * If lock expires, SB unlocks message and makes it available to consumers
* **Topics and Subscriptions**
  * Provide a 1:* communication in pub/sub pattern
  * Useful for scaling to large number of consumers
  * Each published message is made available to each subscription registered topic
    * Publisher sends message to a topic where 1+ subscribers receive a copy of the message, depending on filter rules
  * Publishers send messages to a topic the same way they would to a queue
  * **Topic** subscription resembles a virtual queue that receives copies of messages sent to the topic
  * Consumers receive messages from a subscrtiption identically to the way they receive messages from a queue
  * Creating a topic is similar to creating a queue
* **Rules and Actions**
  * Can configure subscriptions to find messages that have specific properties and make modifications to the property
  * While SB subscriptions see all messages sent to a topic, you can only copy a subset of the messages to a virtual subscription queue
  * **filter actions**
    * A filter expression that is supplied when creating a subscription and operates on the properties of the message
      * Can be both system properties (i.e. Label) and custom app properties
      * SQL filter expression is optional
        * Without the SQL filter expression, any filter action defined on a subscription will be done on all messages for the subscription
#### **Explore Service Bus message payloads and serialization**
* Messages carry payload and metadata
  * Metadata in form of key-value pairs
    * Describes payload and gives handling instructions to SB and apps
  * Object model of SB clients for .NET and Java reflect abstract SB message structure
    * Mapped to and from wire protocols SB supports
* SB Message consists of a binary payload (handled in any form on service-side) and 2 sets of properties
  * _Broker Properties_ are predefined by the system
    * Control message level functionality inside broker or map to common standardized metadata items
  * _User Properties_ are a collection of key-value pairs defined and set by the application
* **Message routing and correlation**
  * Subset of _broker properties_ are used to help route messages to particular destinations
    * `To`
    * `ReplyTo`
    * `ReplyToSessionId`
    * `MessageId`
    * `CorrelationId`
    * `SessionId`
  
    |Scenario|Broker Properties/Description|
    |:--|:--|
    |Simple Request/Reply|Publisher sends message, expects reply.</br>To receive reply, publishers owns a queue into which it expects replies to be delivered, and is found in `ReplyTo` property of outbound message. When consumer responds, copies `MessageId` into `CorrelationId` of reply message and delivers message to destination indicated by `ReplyTo`. One message can yield many replies depending on app context|
    |Multicast Request/Reply|Publisher sends message to a topic and multiple subscribers eligible to consume message. Each subscriber might respond as previously described. Pattern is used in discovery or roll-call scenarios and respondent typically identifies itself with a _user property_ or inside the payload. If `ReplyTo` points to a topic, discovery responses can be distributed to an audience|
    |Multiplexing|Session feature enables multiplexing of streams of related messages through a single queue or subscription such that each session (or group) or related messages, identified by `SessionId` values, are routed to a specific receiver while the receiver holds the lock on the session. [Additional sessions information](https://learn.microsoft.com/en-us/azure/service-bus-messaging/message-sessions)|
    |Multiplexed Request/Reply|Allows several publishers to share a reply qeueue. By setting `ReplyToSessionId`, publisher can instruct consumer(s) to copy that value into the `SessionId` property of the reply message. Publishing queue or topic does not need to be session-aware. Publisher can specifically wait for a session with the given `SessionId` to arrive on the queue by conditionally accepting a session receiver|
  * Routing inside SB can be realized using auto-forward chaining and topic subscription rules
    * Routing across namespaces can be done using Azure LogicApps
  * The `To` property is reserved for future use and may be interpreted by the broker with a specially enabled feature in the future
  * Routing should be implemented with _user properties_ and not lean on the `To` property
* **Payload Serialization**
  * When in transit or inside of SB, payload always opaque binary block
  * `ContentType` enables apps to describe the payload
    * Must be a MIME content-type description according to [IETF RFC2045](https://www.rfc-editor.org/rfc/rfc2045)
      * i.e. `application/json;charset=utf-8`
  * Unlike Java and .NET Standard variants, .NET Framework versoin of SB API supports creating `BrokeredMessage` instances by passing arbitrary .NET objects into the CTOR
  * Protocol handling
    * Legacy SBMP protocol
      * Objects are serialized using default binary serializer, or serializer that is externally supplied
    * AMQP protocol
      * Object serialized into an AMQP object
        * Received can retrieve objects with `GetBody<T>()`
      * Objects are serialized into an AMQP graph of `ArrayList` and `IDictionary<string,object>` objects
        * Any AMQP client can decode them
  * Apps can take explicit control over object serialization and turn object graphs into streams before including them into a message, an do the reverse on the receiver side.
    * Yields interoperable results
  * AMQP binary serialization is tied to AMQP messaging ecosystem and HTTP clients will have difficulty decoding the payloads
#### **Exercise: Send and receive message from a Service Bus queue by using .NET**
* Goals of Exercise
  * Create DB namespace and queue using Azure CLI
  * Create .NET Core console app to send set of messages to queue
  * Create .NET Core console app to receive messages from queue
* Notes:
  * Example will be broken in to sections, code styling and language should indicate whether action is in Azure CLI or in *.cs file
  * Assumes you're logged in to Azure
* **Create Azure Resources**
  ```BASH
  myLocation=<myLocation>
  myNamespaceName=az204svcbus$RANDOM

  # Create resource group
  az group create --name az204-svcbus-rg --location $myLocation

  # Create service bus namespace
  az servicebus namespace create \
    --resource-group az204-svcbus-rg \
    --name $myNamespaceName \
    --location $myLocation

  # Create service bus queue
  az servicebus queue create \
    --resource-group az204-svcbus-rg \
    --namespace-name $myNamespaceName \
    --name az204-queue
  ```
* Get the SAS key for `RootManageSharedAccessKey`
* **Create console app and send messages to queue**
  ```BASH
  dotnet new console
  dotnet add package Azure.Messaging.ServiceBus
  code Program.cs
  ```
  ```C#
  // Add using statements
  using System.Threading.Tasks;
  using Azure.Messaging.ServiceBus;

  static string connString = "<namespace connection string>";
  static string queueName = "az204-queue";
  static ServiceBusClient client;
  static ServiceBusSender sender;
  private const int numOfMessages = 3;

  static async Task Main()
  {
    // Create client and sender
    client = new ServiceBusClient(connString);
    sender = client.CreateSender(queueName);
    
    // Create a batch
    using ServiceBusMessageBatch messageBatch = await sender.CreateMessageBatchAsync();
    for(int i = 0; i <= numOfMessages; i++)
    {
      if(!messageBatch.TryAddNew(new ServiceBusMessage($"Message {i}")))
      {
        throw new Exception($"Exception {i} has occurred.");
      }
    }

    try
    {
      //Use producer client to send batch of messages to SB queue
      await sender.SendMessagesAsync(messageBatch);
      Console.WriteLine($"A batch of {numOfMessages} messages published to queue");
    }
    finally
    {
      await sender.DisposeAsync();
      await client.DisposeAsync();
    }

    Console.WriteLine("Press any key to exit...");
    Console.ReadKey();
  }
  ```
  ```
  dotnet build
  dotnet run
  ```
* **Update project to receive messages from queue**
  ```
  code Program.cs
  ```
  ```C#
  // Add static property to global vars
  static ServiceBusProcessor processor;

  ... Main method ...
  
  // Add new methods
  static async Task MessageHandler(ProcessMessageEventArgs args)
  {
    string body = args.Message.Body.ToString();
    Console.WriteLine($"Received: {body}");
    await args.CompleteMessageAsync(args.Message);
  }

  static Task ErrorHandler(ProcessErrorEventArgs args)
  {
    Console.WriteLine(args.Exception.ToString());
    return Task.CompletedTask;
  }

  // Update Main to read messages from queue
  static async Task Main()
  {
    client = new ServiceBusClient(connString);
    processor = client.CreateProcessor(queueName, new ServiceBusProcessorOptions());

    try
    {
      processor.ProcessMessageAsync += MessageHandler;
      processor.ProcessErrorAsync += ErrorHandler;
      await processor.StartProcessingAsync();
      Console.WriteLine("Wait for a minute then press any key to exit...");
      Console.ReadKey();
      
      Console.WriteLine();
      Console.WriteLine("Stopping receiver...");
      await processor.StopProcessingAsync();
      Console.WriteLine("Stopped receiving messages...");
    }
    finally
    {
      await processor.DisposeAsync();
      await client.DisposeAsync();
    }
  }
  ```
  ```
  dotnet build
  dotnet run
  ```
  * Cleanup resources `az group delete --name az204-svcbus-rg --no-wait`
#### **Explore Azure Qeueue Storage**
* Service for storing large numbers of messages
* Queue message size can be _upto_ 64KB
* Contains the following components
  ![az-queue-strg-comps](https://learn.microsoft.com/en-us/training/wwl-azure/discover-azure-message-queue/media/queue-storage-service-components.png)
  |||
  |:--|:--|
  |URL Format|`https://<storageAccount>.queue.core.windows.net/<queue>`|
  |Storage account|All access is done through a storage account|
  |Queue|Contains set of messages. Queue name _must_ be all lowercase|
  |Message|Any format upto 64KB in size. Version >= 2017-07-29, max TTL can be any positive integer; -1 to set message to never expire. If TTL is omitted, default is 7 days|
#### **Create and manage Azure Queue Storage and messages by using .NET**
* Examples rely on the following .NET NuGet packages
  |Package|Description|
  |:--|:--|
  |[Azure.Core](https://www.nuget.org/packages/azure.core/)|Share primitives, abstractions and helpers|
  |[Azure.Storage.Common](https://www.nuget.org/packages/azure.storage.common/)|Provides infrastructure shared by other Azure Storage client libs|
  |[Azure.Storage.Queues](https://www.nuget.org/packages/azure.storage.queues/)|Enables working with Azure Queue Storage|
  |[System.Configuration.ConfigurationManager](https://www.nuget.org/packages/system.configuration.configurationmanager/)|Provides access to configuration files for client|
* **Create Queue service client**
  ```C#
  QueueClient client = new QueueClient(connectionString, queueName);
  ```
* **Create a Queue**
  ```C#
  string connString = ConfigurationManager.AppSettings["StorageConnectionString"];
  QueueClient client = new QueueClient(connString, queueName);
  client.CreateIfNotExists();
  ```
* **Insert a message into a queue**
  ```C#
  string connString = ConfigurationManager.AppSettings["StorageConnectionString"];
  var qClient = new QueueClient(connString, queueName);
  qClient.CreateIfNotExists();
  if(qClient.Exists())
  {
    qClient.SendMessage(message);
  }
  ```
* **Peek at next message**
  ```C#
  string connString = ConfigurationManager.AppSettings["StorageConnectionString"];
  var qClient = new QueueClient(connString, queueName);
  if(qClient.Exists())
  {
    PeekedMessage[] peekedMessages = qClient.PeekMessages();
  }
  ```
* **Change contents of queued message**
  ```C#
  string connString = ConfigurationManager.AppSettings["StorageConnectionString"];
  var qClient = new QueueClient(connString, queueName);
  if(qClient.Exists())
  {
    QueueMessage[] message = qClient.ReceiveMessages();
    qClient.UpdateMessage(
      message[0].MessageId,
      message[0].PopReceipt,
      "Updated contents",
      TimeSpan.FromSeconds(60.0) // Make it invisible for another 60s
    );
  }
  ```
* **Dequeue next message**
  ```C#
  string connString = ConfigurationManager.AppSettings["StorageConnectionString"];
  var qClient = new QueueClient(connString, queueName);
  if(qClient.Exists())
  {
    QueueMessage[] message = qClient.ReceiveMessages();
    Console.WriteLine($"Deqeued message: {message[0].Body}");
    qClient.DeleteMessage(message[0].MessageId, message[0].PopReceipt);
  }
  ```
* **Get Queue length**
  ```C#
  var qClient = new QueueClient(connString, queueName);
  if(qClient.Exists())
  {
    QueueProperties properties = qClient.GetProperties();
    var messageCount = properties.ApproximateMessagesCount;
    Console.WriteLine($"Number of messages in queue: {messageCount}");
  }
  ```
* **Delete a queue**
  ```C#
  if(qClient.Exists())
  {
    qClient.Delete();
  }
  ```
## **Instrument solutions to support monitoring and logging**
### **Monitor app performance**
#### **Explore Azure Monitor**
* Comprehensive solution for collecting, analyzing, and acting on telemetry from cloud and on-prem environments
  ![az-monitor-highlvl](https://learn.microsoft.com/en-us/training/wwl-azure/monitor-app-performance/media/azure-monitor-overview2.png#lightbox)
* **What data does Azure Monitor collect**
  * Metrics, Logs, Distributed traces are commonly referred to as the Three Pillars of Observability
    |Pillar|Description|
    |:--|:--|
    |Metrics|Numerical values that describe some aspect of a system in a particular point in time. Collected at regular intervals and are identified with a timestamp, name, value, and 1+ defining labels|
    |Logs|Events that occurred in a system. Can contain different kinds of data and may be structured or free-form text with a timestamp|
    |Distributed traces|Series of related events that follow a user request through a distributed system|
    |Changes|Series of events that occur in Azure App and Resources. Change Analysis tracks changes and is a subscription-level observability tool that's built on the power of Azure Resource Graph|
* **Insights and Curated Visualizations**
  * Some resource providers have a _curated visualization_ that gives a customized monitoring experince for a particular service or set of services
  * Larger scalable curated visualizations are know as _insights_ and are marked with that name in the documentation and Azure portal
    * Some examples of insights
      |Insight|Description|
      |:--|:--|
      |Application Insights|Monitors availability, performance, and usage of web apps whether hosted in cloud or on-prem. Enables diagnosing errors without waiting for a user to report on them|
      |Container Insights|Monitors performance of container workloads that are deployed to managed Kubernetes clusters hosted on AKS and ACI. Gives performance visibility by collecting metrics from controllers, nodes, and containers that are available in Kubernetes through Metrics API. Container logs are also collected|
      |VM Insights|Monitors Azure VMs at scale. Analyzes performance and health of Windows and Linux VMs and identifies their different processes and interconnected dependencies on external processes|
#### **Explore Application Insights**
* Application Insights is an extension of Azure Monitor and provides _Application Performance Monitoring_ (aka APM) features
* **App Insights feature overview**
  |Feature|Description|
  |:--|:--|
  |Live Metrics|Observe activity from deployed app in real time with no effect on host|
  |Availability|Probe app external endpoints to test overall availability and responsiveness over time|
  |GitHub or Azure DevOps integration|Create GitHub or Azure DevOps work items in context of App Insights data|
  |Usage|Reveals which features are popular with users and how users interact and use your app|
  |Smart Detection|Provides automatic failure and anomaly detection through proactive telemetry analysis|
  |Application Map|High-level top-down view of application architecture and at-a-glance visual references to component health and responsiveness|
  |Distributed Tracing|Search and visualize an end-to-end flow of a given execution or transaction|
* **What App Insights monitors**
  * App insights collects Metrics and app Telemetry data, which describe application activities and health, as well as trace logging data
  * **Request rates, response times, and failure rates**
    * Find which pages are most popular, at what times of day, and where users spend most time
    * See what pages perform best
    * If response times/failure rates increase with requests, potentially a resourcing problem
  * **Dependency Rates, response times, and failure rates**
    * Determine if external services are slowing you down
  * **Exceptions**
    * Analyze aggregated statistics, or pick specific instances and drill into the stack trace and related requests
    * Both browser and server exceptions are reported
  * **Page views and load performance**
    * Reported by users' browser
  * **AJAX calls** from webpages
    * Rates, response times, failure rates
  * **User and Session counts**
  * **Performance counter**
    * From Windows or Linux server machines, such as CPU, memory, network usage, etc...
  * **Host diagnostics**
    * From Docker or Azure
  * **Diagnostic trace logs** from app
    * Correlate trace events with requests
  * **Custom events and metrics**
    * Written by you in client or server code to track business events such as items sold or games won
* **Getting started with Application Insights**
  * Service hosted within Azure where telemtry is sent for analysis/presentation
  * _Basic_ pricing plan has no charge until app has grown to have substantial usage
  * Ways to get started monitoring and analyzing app performance
    * **At run time**
      * Instrument web app on server. Ideal for apps already deployed. Avoids any update to code
    * **At Development time**
      * Add app insights to code. Allows customization of telemetry collection and send more telemetry
    * **Instrument web pages** for page view, AJAX, and other client-side telemetry
    * **Analyze mobile app usage** by integrating with Visual Studio App Center
    * **Availability tests** - ping website regularly from our servers
  * **App Insights Sampling**
    * _Adaptive sampling_
      * Enabled by default is ASP.NET/CORE SDKS and in Azure Functions
    * Fixed-rate sampling
      * Available in recent versions of App Insights SDKs for .NET/CORE, Java (Agent and SDK), JavaScript, and python
    * Ingestion sampling
      * Works on App Insights service endpoint
        * Only available when no other sampling is active
    * **Sampling types and availability by SDK/app type**
      * [Sampling Overview](https://learn.microsoft.com/en-us/azure/azure-monitor/app/sampling?tabs=net-core-new)
       
      |App Insights SDK|Adaptive Sampling Supported|Fixed-rate Sampling Supported|Ingestion Sampling Supported|
      |:--|:--|:--|:--|
      |ASP.NET|Yes (on by default)|Yes|Only if no other sampling is active|
      |ASP.NET Core|Yes (on by default)|Yes|Only if no other sampling is active|
      |Azure Functions|Yes (on by default)|No|Only if no other sampling is in effect|
      |Java|No|Yes|Only if no other sampling is in effect|
      |JavaScript|No|Yes|Only if no other sampling is in effect|
      |NodeJS|No|Yes|Only if no other sampling is in effect|
      |Python|No|Yes|Only if no other sampling is in effect|
      |All others|No|No|Yes|

#### **Discover log-based metrics**
* Let you analyze health or monitored apps, create dashboards, and configure alerts
* _2 types of metrics_
  * **Log-based metrics** behind the scene are translated into [Kusto queries](https://learn.microsoft.com/en-us/azure/kusto/query/) from stored events
    * Have more dimensions making them ideal for data analysis and ad-hoc diagnostics
  * **Standard metrics** are stored as pre-aggregated time series
    * Have better performance at query time
    * Ideal for dashboarding and real-time alerting
  * Use [namespace selector](https://learn.microsoft.com/en-us/azure/azure-monitor/essentials/metrics-getting-started#create-your-first-metric-chart) to switch between log-based and standard metrics in [metrics explorer](https://learn.microsoft.com/en-us/azure/azure-monitor/essentials/metrics-getting-started)
* **Log-based metrics**
  * Can use SDK to emit events manually or rely on automatic collection of events from auto-instrumentation
  * App Insights backend stores all collected events as logs
    * Blade in Azure portal acts as an analytical and diagnostic tool for visualizing event-based data from logs
  * Using logs to retain complete set of events can bring great analytical and diagnostic value
    * For example
      * Can get exact request count of specific URL with the number of distinct users who made the calls
      * Get detailed diagnostic traces, including exceptions and dependency calls for any user session
  * For scenarios where collecting all events me be impractical, App Insights implements several telemetry volume reduction techniques
    * Sampling and filtering reduce number of collected and stored events
    * Reducing number of stored events also lowers accuracy of metrics in query-time aggregations of events stored in logs
* **Pre-aggregated Metrics**
  * Not stored as individual events with lots of properties
  * Stored as pre-aggregated time series with key dimensions only
    * Makes new metrics superior at query time
      * Data retrieved fater with less compute power
    * Enables new scenarios such as near real-time alerting on dimensions of metrics, more responsive dashboards, and more
  > 🟠**IMPORTANT**</br>
  > Both, log-based and pre-aggregated metrics coexist in App Insights. To different the two, in App Insights UX the pre-aggregated metrics are called _Standard metrics (preview)_ while traditional metrics from events are named _Log-based metrics_
  * Newer SDKs ([Application Insights 2.7+](https://www.nuget.org/packages/Microsoft.ApplicationInsights/2.7.2)) pre-aggregate metrics during collection
    * Applies to [standard metrics sent by default](https://learn.microsoft.com/en-us/azure/azure-monitor/essentials/metrics-supported#microsoftinsightscomponents) so accuracy not affected by sampling or filtering
    * Also applies to custom metrics sent using [GetMetric](https://learn.microsoft.com/en-us/azure/azure-monitor/app/api-custom-events-metrics#getmetric) resulting in less data ingestion and lower cost
  * Older SDKs or Browser instrumentation that don't implement pre-aggregation, App Insights backend still populates new metrics by aggregating the events received by App Insights event collection endpoint
    * Still benefit from pre-aggregated metrics, better performance, and support of near real-time dimensional alerting
  * Collection endpoint pre-aggregates events before ingestion sampling, which means [ingestion sampling](https://learn.microsoft.com/en-us/azure/azure-monitor/app/sampling) never impacts accuracy of pre-aggregated metrics regardless of SDK version
#### **Instrument an app for monitoring**
* Enabled through Auto-Instrumentation (agent) or by adding App Insights SDK to app code
* **Auto-instrumentation**
  * _Preferred_ method
  * No developer investment and eliminates future overhead related to updating SDKs
  * Only need to enable; and potentially configure agent; which will collect telemetry automatically
  * List of supported services changes frequently, check [here](https://learn.microsoft.com/en-us/azure/azure-monitor/app/codeless-overview#supported-environments-languages-and-resource-providers) for list of what is supported
* **Enabling via App Insights SDKs**
  * Need to install App Insights SDK when
    * Require custom events/metrics
    * Require control over flow of telemetry
    * Auto-instrumentation isn't available
  * To use SDK, install small instrumentation package in to app and then instrument web app, background components, and JavaScript in web pages
    * Don't have to be hosted in Azure
    * Instrumentation monitors app and directs telemetry to App Insights resource by using unique token
  * Distributed tracing natively supported in .NET/Core, Java, Node.js, and JavaScript
  * Manually track with call to `TrackDependency` on `TelemetryClient`
* **Enable via OpenCensus**
  * App Insights supports distributed tracing through OpenCensus.
    * An open source, vendor-agnostic, single distribution of libraries to provide metrics collection and distributed tracing for services
  * Enables distributed tracing with popular technologies like Redis, Memcached, or MongoDB
#### **Select an availability test**
* Can set up recurring tests to monitor availability and responsiveness
* App Insights sends requests to app at regular intervals from points around the world
  * Can alert if app isn't responding or responds slowly
* Can be set up for any HTTP/S endpoint accessible from public internet
  * Doesn't need to be an app you own, can also be set up to test external API dependencies
* Create up to 100 availability tests per App Insights resource
* _3 types of availability tests_
  * [URL ping test (classic)](https://learn.microsoft.com/en-us/azure/azure-monitor/app/monitor-web-app-availability)
    * Simple test created through portal to validate endpoint is responding and measure performance associated with response.
    * Can set custom success criteria coupled with more advanced features; i.e. parsing dependent requests and retries
  * [Standard test (Preview)](https://learn.microsoft.com/en-us/azure/azure-monitor/app/availability-standard-tests)
    * Single request similar to URL ping
    * Includes SSL cert validity, proactive lifetime check, HTTP request verb, custom headers, custom data
  * [Custom TrackAvailability test](https://learn.microsoft.com/en-us/azure/azure-monitor/app/availability-azure-functions)
    * Custom application to run availability tests
    * Use `TrackAvailability()` to send results to App Insights
    * Use if multiple requests, or authentication tests are required
  > 🟠**IMPORTANT**</br>
  > **URL ping test** relies on DNS infrastructure of public internet to resolve domain names of the tested endpoints. If using a private DNS, must ensure the public domain name servers can resolve every domain name of your test. When not possible, can use **TrackAvailability tests**
#### **Troubleshoot app performance by using Application Map**
* Helps spot performance bottlenecks or failure hotspots across all components of distributed app
* Nodes on map represent app component or dependency
  * Has health KPI and alerts status
* Can click through any component for more detailed diagnostics, such as App Insights events
* Components are independently deployable parts of distributed/microservices app
  * Devs and ops teams have code-level visibility or access to telemetry granted by app components
    * Components are different from "observed" external dependencies such as SQL, EventHubs, etc... which team may/may not have access to
    * Components run on any number of server/role/container instances
    * Components can be separate App Insights instrumentation keys (even if subscriptions are different) or different roles reporting to a single App Insights instrumentation key. Preview map experience shows components regardless of how they are set up
* App Map finds components by following HTTP dependency calls made between servers with App Insights SDK installed
* When first loading app map, set of queries is triggered to discover components related to this component
* Clicking "Update map components" refreshes map with all discovered components until that point
* If all components are roles in a single App Insights resource, discovery is not required</br>
  ![app-map-example](https://learn.microsoft.com/en-us/training/wwl-azure/monitor-app-performance/media/application-map.png)
* Clicking on a component shows related insights and allows you to navigate to performance and failure triage experience
  ![app-map-triage](https://learn.microsoft.com/en-us/training/wwl-azure/monitor-app-performance/media/application-map-component.png)
## **Integrate caching and content delivery within solutions**
### **Develop for Azure Cache for Redis**
#### **Explore Azure Cache for Redis**
* Provides an in-memory data store based on the [Redis](https://redis.io/) software
* Improves scalability and performance of an app that uses backend data stores heavily
* Able to process large volumes of application requests by keeping frequently accessed data in the server memory
* Brings critical low-latency, high-throughput data storage solution to modern apps
* Azure Cache for Redis offers both as managed service:
  * Redis Open-Source (OSS Redis)
  * Redis Labs (commercial product)
* Provides secure and dedicated Redis service instances and full Redis API compatibility
* **Key Scenarios**
  * Azure Cache for Redis improves app performance by supporting common app architectures
    |Pattern|Description|
    |:--|:--|
    |Data cache|DBs are often too large to load directly into cache. It's common to use the [cache-aside](https://learn.microsoft.com/en-us/azure/architecture/patterns/cache-aside) pattern to load data into the cache only as needed. When system makes change to data, system can also update the cache, which is then distributed to other clients|
    |Content cache|Many web pages are generated from templates that use static content such as headers, footers, banners. Static items shouldn't change often. Using an in-memory cache provides quick access to static content compared to backend datastores|
    |Session store|Pattern is commonly used with shopping carts and other user history data that a web app may associate with user cookies. Storing too much in a cookie can have negative performance impacts as cookie size grows and is passed and validated with every request. Typical solution uses the cookie as a key to query the data in a database. Using an in-memory cache, like Azure Cache for Redis, to associate information with a user is much faster than interacting with a full relational DB|
    |Job and Message queuing|Apps often add tasks to a queue when operations associated with the request take time to execute. Longer running operations are queued to be processed in sequence, often by another server. This method of deferring work is called _task queuing_|
    |Distributed transactions|Apps sometimes require a series of commands against a backend data-store to execute as a single atomic operation. All commands must succeed, or all must be rolled back. Azure Cache for Redis supports executing a batch of commands as a single [transaction](https://redis.io/topics/transactions|
* **Service Tiers**
  * Azure Cache for Redis is available in the following tiers
    |Tier|Description|
    |:--|:--|
    |Basic|An OSS Redis cache running on a single VM. Tier has no SLA and is ideal for development/test and non-critical workloads|
    |Standard|OSS Redis cache running on two VMs in a replicated region|
    |Premium|High-performance OSS Redis cache. Offers higher throughput, lower latency, better availability, and more features. Premium caches are deployed on more power VMs compared to VMs for Basic or Standard cache tiers|
    |Enterprise|High-performance caches powered by Redis Labs' Redis Enterprise software. Tier supports Redis modules including RediSearch, RedisBloom, and RedisTimeSeries. Offers higher availability than Premium tier|
    |Enterprise Flash|Cost-effective large caches powered by Redis Labs' Redis Enterprise software. Tier extends Redis data storage to non-volatile memory, wich is cheaper than DRAM on a VM. Reduces overall per-GB memory cost|
#### **Configure Azure Cache for Redis**
* Can create Redis cache using Portal, Azure CLI, Azure PoSH
* **Create and Configure Azure Cache for Redis instance**
  * There are many params that need to be decided to configure cache properly for your purposes
* **Name**
  * Globally unique name
  * Used to generate public-facing URL to connect and communicate with service
  * Between 1 and 63 characters, letters, numbers, and '-'.
* **Location**
  * Need to decide where Redis cache will be physically located by selecting Azure region
  * Place cache instance and application in same region
  * If connecting to cache outside of Azure, select a location near app hosting location
* **Pricing Tier**
  * 3 Pricing tiers available for an Azure Cache for Redis
    * Basic
      * For development/testing
      * Single server
      * 53GB of memory
      * Upto 20,000 simultaneous connections
      * No SLA
    * Standard
      * Supports replication
      * SLA
      * 2 servers
      * Same memory and connection limit as Basic
    * Premium
      * Enterprise tier
      * Standard tier + persistence, clustering, scale-out support
      * 530GB of memory
      * Upto 40,000 simultaneous connections
  * Control amount of cache memory on each tier by selecting cache level
    * Basic/Standard: C0-C6
    * Premium: P0-P4
  * _Recommended_ to use Standard or Premium tiers for production
  * _Premium Tier_ 
    * allows you to persist data in two ways to provide DR
      * RDB persistence takes a periodic snapshot and can rebuild cache using snapshot in case of failure
      * AOF persistence saves every write operation to a log that is saved at least once/second. Creates larger files but has less data loss than RDB.
    * Virtual Network support
      * Can deploy to a VNet in the cloud
        * Cache available only to other VMs and apps in same VNET
      * Higher-level of security when service and cache both hosted in Azure, or are connected through Azure VNET VPN
    * Clustering support
      * Can implement clusting to automatically split dataset among multiple nodes
      * To implement clustering
        * Specify number of shards to maximum of 10
        * Cost incurred is cost of original node * number of shards
          * For example, cost of node is $10,000, have 4 shards, total cost is $40,000
* **Accessing the Redis Instance**
  * Redis has a CLI tool for interacting with Azure Cache for Redis as a client
    * Availabe for download at [Redis CLI tools for Windows](https://github.com/MSOpenTech/redis/releases/)
  * Redis supports a set of known commands
    * Typically issues as `COMMAND parm1 parm2 parm3...`
  * Common commands that can be used
    |Command|Description|
    |:--|:--|
    |`ping`|Ping the server. Returns "PONG"|
    |`set [key] [value]`|Set key/value in cache. Returns OK on success|
    |`get [key]`|Gets value from the cache|
    |`exists [key]`|Returns '`' if **key** exists in cache, '0' otherwise|
    |`type [key]`|Returns type associated to value of given key|
    |`incr [key]`|Increment value associated to **key** by 1; value must be integer or double. Returns new value|
    |`incrby [key] [amount]`|Increment value by `[amount]`. Must be integer or double. Returns the new value.|
    |`del [key]`|Deletes value associated with key|
    |`flushdb`|Delete _all_ keys and values in DB|
  * Example of a command
    ```
    > set somekey somevalue
    OK
    > get somekey
    "somevalue"
    > exists somekey
    (string) 1
    > del somekey
    (string) 1
    > exists somekey
    (string) 0
    ```
* **Adding an expiration time to values**
  * When TTL elapses, the key is automatically deleted
  * TTL Expiration notes
    * Expirations can be set using seconds or millisecond precision
    * Expire time resolution is always 1 ms
    * Information about expires are replicated and persisted on disk
      * Time virtually passes when Redis server remains stopped
  * Expiration example
    ```
    > set counter 100
    OK
    > expire counter 5
    (integer) 1
    > get counter
    100
    ... wait ...
    > get counter
    (nil)
    ```
* **Accessing Redis cache from a client**
  * Clients need: host name, port, and access key
    * Can be retrieve from Portal through _Settings > Access Keys_ page
  * Host name is public internet address of the cache, which was created using the name of cache
    * For example: `sportsresults.redis.cache.windows.net`
  * Access key acts as a password for cache
    * 2 keys are created: primary and secondary
    * Whoever has a key can perform any operation on the cache
#### **Interact with Azure Cache for Redis by using .NET**
* Popular client for interacting with Redis: `StackExchange.Redis`
* **Connecting to Redis Cache with StackExchange.Redis**
  * Need: host address, port number, and access key
    * Azure offers a connection string some Redis clients which bundles all this together into a single string
    * Will look similar to the following (with `cache-name` and `password-here` fields filled)
      ```
      [cache-name].redis.cache.windows.net:6380,password=[password-here],ssl=True,abortConnection=false
      ```
      * `abortConnection` allows a connection to be created even if server is unavailable at the moment
      * `ssl` ensures communication is encrypted
  * [Optional parameters](https://github.com/StackExchange/StackExchange.Redis/blob/master/docs/Configuration.md#configuration-options) that can be appended to configure the client library
* **Creating a connection**
  * Main connection object in _StackExchange.Redis_ is `StackExchange.Redis.ConnectionMultiplexer` class
    * Optimized to manage connections efficiently and intended to be kept around while access to the cache is needed (Singleton?)
  * Can create a `ConnectionMultiplexer` instance using static `ConnectionMultiplexer.Connect` or `ConnectionMultiplexer.ConnectAsync`
    * Passing in either a connection string or a `ConfigurationOption` object
  * Example
    ```C#
    using StackExchange.Redis;
    ...
    var connectionString = "<redis connection string>";
    var redisConnection = ConnectionMultiplexer.Connect(connectionString);
    ```
  * `ConnectionMultiplexer` gives access to Redis to perform various operations. 3 Primary things may want to to are
    * Access a Redis DB
    * Make use of pub/sub features of Redis (out of scope)
    * Access individual server for maintenance or monitoring
* **Accessing a Redis DB**
  * Redis database is represented by the `IDatabase` type
    ```C#
    IDatabase db = redisConnection.GetDatabase();
    ```
  * The returned `IDatabase` object is lightweight and does not need to be kept alive
  * `IDatabase` allows you to execute methods to interact with the cache
    * Have synchronous and asynchronous methods
  * Example storing/retreiving key/value in cache
    ```C#
    bool wasSet = db.StringSet("favorite:flavor", "i-love-rocky-road");
    string setValue = db.StringGet("favorite:flavor");
    ```
* **Getting and Setting binary values**
  * Redis key/values are binary safe
  * Implicit conversion operators exist to work with `byte[]` naturally
    ```C#
    byte[] key = ...;
    byte[] value = ...;
    db.StringSet(key, value);

    byte[] key = ...;
    byte[] value = db.StringGet(key);
    ```
  * `StackExchange.Redis` represents keys using `RedisKey` type, and `RedisValue` type for values
    * Class has implicit conversions to and from both `string` and `byte[]` allowing both text and binary keys\values to be used without complication
* **Other common properties**
  * `IDatabase` includes several other methods including methods to work with hashes, lists, sets, and ordered sets
  * Common ones that work with single keys
    |Method|Description|
    |:--|:--|
    |`CreateBatch`|Creates group of operations that will be sent to server as a single unit, but not necessarily processed as a unit|
    |`CreateTransaction`|Creates group of operations that will be sent to server as single unit and processed on server as single unit|
    |`KeyDelete`|Delete key/value|
    |`KeyExists`|Returns whether given key exists in cache|
    |`KeyExpire`|Sets TTL on key|
    |`KeyRename`|Renames a key|
    |`KeyTimeToLive`|Returns TTL for key|
    |`KeyType`|Returns string representation of type of value stored at key. Different types returns are: string, list, zset and, hash
  * [Read source code](https://github.com/StackExchange/StackExchange.Redis/blob/master/src/StackExchange.Redis/Interfaces/IDatabase.cs) for full list
* **Executing other commands**
  * `IDatabase` has an `Execute` and `ExecuteAsync` method which can be used to pass textual commands to Redis server
    ```C#
    var result = db.Execute("ping");
    Console.WriteLine(result.ToString()); // displays: PONG
    ```
  * `Execute` and `ExecuteAsync` return a `RedisResult` which is a data holder that includes two properties
    * `Type` - returns a `string` indicating type of the result
    * `IsNull` - true/false to detect when result is `null`
  * Use `ToString()` on `RedisResult` to get actual return value
  * Can use `Execute` or `ExecuteAsync` to perform any supported commands
    * For example, to get all clients connected to cache ("CLIENT LIST")
      ```C#
      var result = await db.ExecuteAsync("client", "list");
      Console.WriteLine($"Type = {result.Type}");
      Console.WriteLine($"Result = {result}");
      ```
      * Example output
        ```
        Type = BulkString
        Result = id=9469 addr=16.183.122.154:54961 fd=18 name=DESKTOP-AAAAAA age=0 idle=0 flags=N db=0 sub=1 psub=0 multi=-1 qbuf=0 qbuf-free=0 obl=0 oll=0 omem=0 ow=0 owmem=0 events=r cmd=subscribe numops=5
        id=9470 addr=16.183.122.155:54967 fd=13 name=DESKTOP-BBBBBB age=0 idle=0 flags=N db=0 sub=0 psub=0 multi=-1 qbuf=0 qbuf-free=32768 obl=0 oll=0 omem=0 ow=0 owmem=0 events=r cmd=client numops=17
        ```
* **Storing more complex values**
  * Redis is oriented around binary safe strings, but you can cache off object graphs by serializing them to a textual format (i.e. XML/JSON)
  * For example, serialize a class into a string and back
    ```C#
    public class GameStat
    {
        public string Id { get; set; }
        public string Sport { get; set; }
        public DateTimeOffset DatePlayed { get; set; }
        public string Game { get; set; }
        public IReadOnlyList<string> Teams { get; set; }
        public IReadOnlyList<(string team, int score)> Results { get; set; }

        public GameStat(string sport, DateTimeOffset datePlayed, string game, string[] teams, IEnumerable<(string team, int score)> results)
        {
            Id = Guid.NewGuid().ToString();
            Sport = sport;
            DatePlayed = datePlayed;
            Game = game;
            Teams = teams.ToList();
            Results = results.ToList();
        }

        public override string ToString()
        {
            return $"{Sport} {Game} played on {DatePlayed.Date.ToShortDateString()} - " +
                  $"{String.Join(',', Teams)}\r\n\t" + 
                  $"{String.Join('\t', Results.Select(r => $"{r.team } - {r.score}\r\n"))}";
        }
    }

    ...

    var stat = new GameStat("Soccer", new DateTime(2019, 7, 16), "Local Game", 
                new[] { "Team 1", "Team 2" },
                new[] { ("Team 1", 2), ("Team 2", 1) });

    string serializedValue = Newtonsoft.Json.JsonConvert.SerializeObject(stat);
    bool added = db.StringSet("event:1950-world-cup", serializedValue);

    ...
    var result = db.StringSet("event:2019-local-game");
    var stat = Newtonsoft.Json.JsonConvert.DeserializeObject<GameStat>(result.ToString());
    Console.WriteLine(stat.Sport);
    ```
* **Cleaning up the connection**
  * Once done with the Redis connection, can call `Dispose` on the `ConnectionMultiplexer`
    * Close all connections and shutdown communication to server
    ```C#
    redisConnection.Dispose();
    redisConnection = null;
    ```
#### **Exercise: Connect an app to Azure Cache for Redis by using .NET Core**
* Goals of the example
  * Create new Redis Cache instance using Azure CLI Commands
  * Create .NET Core app to add and retrieve values from cache using `StackExchange.Redis`
1. Create Azure Resources
   1. `az group create --name az204-redis-rg --location <myLocation>`
   2. ```
      redisName=az204redis$RANDOM
      az redis create \
        --location <myLocation> \
        --name $redisName \
        --sku Basic \
        --vm-size c0
      ```
   3. In Portal navigate to new Redis Cache just created and select _Settings > Access keys_ and copy the _Primary connection string (StackExchange.Redis)_ for use later
2. Create console app
   1. `dotnet new console -o RedisCache`
   2. `dotnet add package StackExchange.Redis`
   3. Open _Program.cs_ and add using statements
      ```C#
      using StackExchange.Redis;
      using System.Threading.Tasks;
      ```
   4. Add relevant code
      ```C#
      static string connectionString = "[redis-connection-string]";
      static async Task Main(string[] args)
      {
        using(var cache = ConnectionMultiplexer.Connect(connectionString))
        {
          IDatabase db = cache.GetDatabase();

          // Execute a ping test
          var result = await db.Execute("ping");
          Console.WriteLine($"PING = {result.Type} : {result}");

          // Call StringSetAsync to set key test:key value to 100
          bool setVaue = await db.StringSetAsync("test:key", "100");
          Console.WriteLine($"SET: {setValue}");

          // Get the value of the recently added key
          bool getValue = await db.StringGetAsync("test:key");
          Console.WriteLine($"GET: {getValue}");
        }
      }
      ```
   5. Build and run:
      1. `dotnet build`
      2. `dotnet run`
3. Cleanup resources: `az group delete -n az204-redis-rg --no-wait`
### **Develop for storage on CDNs**
#### **Explore Azure Content Delivery Networks (CDNs)**
* Azure CDN offers developer a global solution for rapidly delivering high-bandwidth content to users by caching their content at strategically placed physical nodes across the world.
  * Can accelerate dynamic content by leveraging varios network optimizations using _CDN POPs (Point of Presence)_
    * For example, route optimization to bypass Border Gateway Protocols (BGP)
* Benefits of Azure CDN
  * Better performance and improved user experience
    * Especially when multiple round-trips are required to load content
  * Large scaling to better handle instantaneous high loads
  * Distribution of user requests and serving of content directly from edge servers so less traffic is sent to the origin server
* **How Azure CDNs work**
  ![cdn-high-level](https://learn.microsoft.com/en-us/training/wwl-azure/develop-for-storage-cdns/media/azure-content-delivery-network.png)
  * Requests by a user are cached on POP edge servers and subsequent requests from other users will receive the cached assets
    * Assets in the POP edge servers are cached until the TTL in the header expires
      * If no expiration provided, default is 7 days
* **Requirements**
  * Must create at least 1 CDN profile
    * Collection of CDN endpoints
  * Each CDN endpoint represents a specific configuration of content deliver behavior and access
  * To organize CDN endpoints by internet domain, web app, or other criteria, can use multiple profiles
  * Because [Azure CDN pricing](https://azure.microsoft.com/pricing/details/cdn/) is applied at CDN profile level, must create multiple CDN profiles if you want to use a mix of pricing tiers
* **Limitations**
  * Each Azure subscription has default limits for the following resources
    * Number of CDN profiles that can be created
    * Number of endpoints that can be created in a CDN profile
    * Number of custom domains that can be mapped to an endpoint
  * [CDN Limits](https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/azure-subscription-service-limits#content-delivery-network-limits)
* **Azure CDN Products**
  * Azure CDN includes 4 products
    * Azure CDN Standard from Microsoft
    * Azure CDN Standard from Akamai
    * Azure CDN Standard from Verizon
    * Azure CDN Premium from Verizon
#### **Control cache behavior on Azure Content Delivery Networks**
* Because cached data becomes stale, it is important for any caching mechanism to control when content is refreshed
  * Cached resources are not compared to version on origin server
    * As long as it is considered to "fresh" is assumed the most recent/current version
      * Fresh is defined as the resource age being less than period defined in cache setting
* **Controlling caching behavior**
  * Azure CDNS provide 2 mechanisms for caching files
    * These settings depend on the selected tier
  * _Azure CDN Standard for Microsoft_ are set at endpoint level and provide 3 configuration values
  * Other tiers provide additional configuration options, which include
    |Option|Description|
    |:--|:--|
    |Caching Rules|Caching rules can be either global (apply to all content from specified endpoint) or custom. Custom rules apply to specific paths and file extensions|
    |Query string caching|Query string caching enables you to configure how Azure CDN responds to a query string. Query string caching has no effect on files that can't be cached|
  * With Azure CDN Standard for Microsoft tier, caching rules are as simple as teh following 3 options
    * _Ignore query strings_
      * Default mode
      * CDN POP simply passes the request and any query strings directly to origin server on the first request and caches the asset.
        * New requests for same asset will ignore any query strings until TTL expires
    * _Bypass caching for query strings_
      * Each query request from client is passed directly to origin server with no caching
    * _Cache every unique URL_
      * Every time a request is made with a unique URL, the URL is passed to origin server and the response is cached with its own TTL
        * This is inefficient when each request is a unique URL as the cache-hit ratio becomes low
  * To change settings, _Endpoint pane > Caching rules > Select caching option > Save_
* **Caching and TTL**
  * If website published through Azure CDN, files on the site are cached until TTL expires
    * `Cache-Control` header in HTTP response from origin server determines TTL duration
  * If you don't see a TTL on a file, Azure CDN sets a default
    * Default values:
      * Generalized web delivery optimizations: 7 days
      * Large file optimizations: 1 day
      * Media streaming optimizations: 1 year
* **Content Updating**
  * Under normal operation, Azure CDN edge node will serve an asset unitl its TTL expires
  * Edge note reconnects to origin server when TTL expires and client makes a request to the same asset
  * To ensure users always receive the latest version of an asset, consider including a version string in the asset URL
    * Causes CDN to retrieve new asset immediately
  * Can purge cached content from edge nodes
    * May want to do this when publishing a new version of a web app or to replace out-of-date assets
  * Can purge in many ways:
    * On an endpoint by endpoint basis,, or all endpoints simultaneously should you want to update everything on your CDN at once
    * Specify a file, by including the path to that file or all assets on the selected endpoint by checking the **Purge All** checkbox in Azure portal
    * Based on wildcard (`*`) or under the root (`/`)
  * Azure CLI provides special `purge` verb that will unpublish cached assets from an endpoint
    * Useful in scenarios where large amount of data is invalidated 
    * Must specify either a file path, a wildcard directory, or both
      ```BASH
      az cdn endpoint purge \
        --content-paths '/css/*' '/js/app.js' \
        --name ContosoEndpoint \
        --profile-name DemoProfile \
        --resource-group ExampleGroup
      ```
  * Can also preload assets into an endpoint
    * Useful when app creates a large number of assets and want to improve user experience by prepopulating cache before any actual requests
      ```BASH
      az cdn endpoint load \
        --content-paths '/img/*' '/js/module.js'
        --name ContosoEndpoint \
        --profile-name DemoProfile \
        --resource-group ExampleGroup
      ```
* **Geo-filtering**
  * Enabled you to allow or block content in specific countries/regions, based on country/region code
  * _Azure CDN Standard for Microsoft tier_ only allow or block the entire site
  * _Verizon_ or _Akamai_ tiers, can set up restrictions on directory paths
#### **Interact with Azure CDNs by using .NET**
* Can use Azure CDN Library for .NET to automate creation and management of CDN profiles and endpoints
* `Microsoft.Azure.Management.Cdn.Fluent` NuGet package
* **Create a CDN Client**
  ```C#
  ...
  CdnManagementClient cdn = new CdnManagementClient(new TokenCredentials(authResult.AccessToken))
  {
    SubscriptionId = subscriptionId
  };
  ...
  ```
* **List CDN Profiles and Endpoints**
  * Method lists all profiles and endpoints in resource group
    * If it find a match for the profile and endpoint names specified in constants, makes a nore of it for later to avoid creating duplicates
  ```C#
  private static void ListProfilesAndEndpoints(CdnManagementClient cdn)
  {
    var profileList = cdn.Profiles.ListByResourceGroup(resourceGroupName);
    profileList.ForEach((Profile)profile => 
    {
      Console.WriteLine($"CDN Profile {profile.Name}");
      if(profile.Name.Equals(profileName, StringComparison.OrdinalIgnoreCase))
      {
        profileExists = true;
      }

      Console.WriteLine("Endpoints:");
      var endpoints = cdn.Endpoints.ListByProfile(profile.Name, resourceGroupName);
      endpoints.ForEach((Endpoint)endpoint => 
      {
        Console.WriteLine($"{endpoint.Name}, {endpoint.HostName}");
        if(endpoint.Name.Equals(StringComparison.OrdinalIgnoreCase))
        {
          endpointExists = true;
        }
      });
      Console.WriteLine();
    });

  }
  ```
* **Create CDN Profiles and Endpoints**
  * Create an Azure CDN Profile
    ```C#
    private static void CreateCdnProfile(CdnManagementClient cdn)
    {
      if(profileAlreadyExists)
      {
        // Check if profile already exists
      }
      else
      {
        // Create new profile
        ProfileCreateParameters profileParms = new ProfileCreateParameters()
        {
          Location = resourceLocation,
          Sku = new Sku(SkuName.StandardVerizon)
        };
        cdn.Profiles.Create(profileName, profileParms, resourceGroupName);
      }
    }
    ```
  * After `Profile` is created, need to create an `Endpoint`
    ```C#
    private static void CreateCdnEndpoint(CdnManagementClient cdn)
    {
      if(endpointAlreadyExists)
      {
        // Check if endpoint already exists
      }
      else
      {
        EndpointCreateParameters endpointParms = new EndpointCreateParameters()
        {
          Origins = new List<DeepCreatedOrigin>() 
          { 
            new DeepCreatedOrigin("Contoso", "www.contoso.com")
          },
          IsHttpAllowed = true,
          IsHttpsAllowed = true,
          Location = resourceLocation
        };
        cdn.Endpoints.Create(endpointName, endpointParms, profileName, resourceGroupName);
      }
    }
    ```
* **Purge an Endpoint**
  * Purge content from an endpoint
    ```C#
    private static void PromptPurgeCdnEndpoint(CdnManagementClient cdn)
    {
      if(PromptUser($"Purge CDN Endpoint {endpointName}?"))
      {
        Console.WriteLine($"Purging endpoint {endpointName}. Pease wait...");
        cdn.Endpoints.PurgeContent(resourceGroup, profileName, endpointName, new List<string>() { "/*" });
        Console.WriteLine("Purge complete");
        Console.WriteLine();
      }
    }
    ```