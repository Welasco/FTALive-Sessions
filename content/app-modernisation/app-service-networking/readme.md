# App Service Networking

## Overview

In this session you will learn about the different ways you can secure Azure App Service from a networking perspective. The main focus of the session will be Azure App Service, but you will also be able to apply a lot of the concepts we cover to other Azure PaaS services.

### Agenda

- Out of the box networking behavior and available security options.
- Locking down inbound calls, conceptually and in practice.
- Locking down outbound calls, conceptually and in practice.
- Single tenancy (App Service Environment).

### Audience

This session is most useful for web application administrators and architects who want to be able to lock down the communication channels of web apps. Network admins can also benefit from this session to learn how PaaS networking differs from Infrastructure networking.

### Goals

In this session you will learn how to:

- Protect your web application with a Web Application Firewall (WAF) appliance.
- Securely connect to a backend database in your Azure or on-prem network.
- Route calls between web apps through your VNet.

## Resources

Please find the most relevant resources below to continue your learning after this session.

### Azure Architecture Center

- [Web app with private connectivity to Azure SQL database](https://docs.microsoft.com/azure/architecture/example-scenario/private-web-app/private-web-app)
- [Multi-region web app with private connectivity to database](https://docs.microsoft.com/azure/architecture/example-scenario/sql-failover/app-service-private-sql-multi-region)

### App Service

- [App Service networking features](https://docs.microsoft.com/azure/app-service/networking-features)
- [Regional VNet integration](https://docs.microsoft.com/azure/app-service/web-sites-integrate-with-vnet#regional-vnet-integration)
- [App Service private endpoints](https://docs.microsoft.com/azure/app-service/networking/private-endpoint)
- [Hybrid connections](https://docs.microsoft.com/azure/app-service/app-service-hybrid-connections)

### Web Application Firewall

- [Application Gateway overview](https://docs.microsoft.com/azure/application-gateway/overview)
- [Azure Front Door overview](https://docs.microsoft.com/azure/frontdoor/front-door-overview)
- [WAF overview](https://docs.microsoft.com/azure/web-application-firewall/overview)
- [Application Gateway integration with service endpoints](https://docs.microsoft.com/azure/app-service/networking/app-gateway-with-service-endpoints)
- [Allow only Front Door to access your backend](https://docs.microsoft.com/azure/frontdoor/front-door-faq#how-do-i-lock-down-the-access-to-my-backend-to-only-azure-front-door-)

### Azure SQL

- [How to set up Private Link for Azure SQL Database](https://docs.microsoft.com/azure/azure-sql/database/private-endpoint-overview#how-to-set-up-private-link-for-azure-sql-database)
- [Azure SQL Firewall](https://docs.microsoft.com/azure/azure-sql/database/firewall-create-server-level-portal-quickstart)

### Networking

- [Integrate Azure services with virtual networks for network isolation](https://docs.microsoft.com/azure/virtual-network/vnet-integration-for-azure-services)
- [Private link resources](https://docs.microsoft.com/azure/private-link/private-endpoint-overview#private-link-resource)
- [Virtual Network service endpoints](https://docs.microsoft.com/azure/virtual-network/virtual-network-service-endpoints-overview)
- [Azure Private Link frequently asked questions (FAQ)](https://docs.microsoft.com/azure/private-link/private-link-faq#what-is-the-difference-between-a-service-endpoints-and-a-private-endpoints)
