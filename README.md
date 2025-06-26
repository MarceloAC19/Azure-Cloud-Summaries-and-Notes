# Summaries-and-notes-on-Azure-Cloud
*Made for a DIO bootcamp*

# Cloud Computing

## What is the Cloud?
A service based on the use of servers for storage, data processing, networking, and other functionalities. These servers can be public, private, or hybrid.

## Types of Cloud
### • Private Cloud
This is an environment created in the company's own datacenter, operating independently and exclusively.
**Advantages:** Complete control over data and security.
**Disadvantage:** The company is fully responsible for the maintenance and updating of hardware.

### • Public Cloud
These are environments created to meet the needs of various companies and users, belonging to cloud service providers.
**Advantages:** Ease of adding and removing applications, no server setup costs, and payment based only on the tools used.
**Disadvantage:** Complete dependency on third parties.

### • Hybrid Cloud
This is a combination of the two cloud types, making information storage more flexible and facilitating the management of sensitive data.
**Advantages:** Storage flexibility, high control over information, and security.
**Disadvantages:** Management complexity.

## Expenses
### • CapEx
This refers to capital expenditures, related to the physical infrastructure for server setup. The costs decrease over time.

### • OpEx
This refers to operational expenditures, such as products and services necessary for server hosting. Billing is immediate.

## Benefits of the Cloud
### • High Availability
This is the guarantee that the service will be available regardless of unforeseen events. Microsoft Azure fits this characteristic, as it guarantees uptime according to the applied service through SLAs (Service Level Agreements).

### • Scalability
This refers to the necessary adjustments to meet demand, allowing for an increase in resources to handle growth. If demand decreases, it is also possible to reduce resources, since payment is based on consumption in public servers.

### • Elasticity
This refers to the abrupt expansion of resources to cover high demand for only a specific period. As soon as the demand decreases, the additional resources are removed.

### • Reliability
As a result of its decentralized design, the cloud becomes a reliable and resilient infrastructure. It is possible to deploy resources in various regions around the planet, ensuring the security and continuity of services, even in the event of a failure in one region.

### • Predictability
This is the ability to forecast performance and costs, ensuring stability in the services provided and allowing for better planning of the resources used. The Microsoft Azure Well-Architected Framework provides guidelines to optimize performance and spending, ensuring that services are delivered efficiently and within the planned budget.

### • Security
The cloud offers tools that allow for greater control and protection over resources. Security follows a shared responsibility model, where the provider ensures the security of the physical infrastructure and networks, while the customer must correctly configure security policies, identity management, and access control.

### • Governance
This refers to the application of auditing and compliance practices to ensure that resources follow corporate standards. Governance involves continuous monitoring to ensure compliance with regulatory standards and internal policies. Additionally, management tools allow for the automation of applying patches and updates, ensuring systems are always protected against vulnerabilities.

### • Manageability
This refers to the ability to efficiently manage resources in the cloud. This allows for everything from automatic scaling of resource deployment to administration through different interfaces, such as a web portal, CLI, APIs, and PowerShell. Tools like Azure Monitor and Azure Automation help predict future needs and apply proactive measures to ensure operational efficiency.
