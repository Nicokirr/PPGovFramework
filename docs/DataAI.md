---
title: Data and AI
permalink: /pillars/dataai/
excerpt: >
    Data Management defines and controls WHO can use WHICH data with low code tools.  
    This evolves over time following users and organization maturity or demand.
toc: true
---

Data Management defines and controls WHO can use WHICH data with low code tools.  
This evolves over time following users and organization maturity or demand

| Theme | Activity | **Why** you should work on this activity | **How** you can start |
| --- | --- | --- | --- |
| External data (standard) | Default Connectors | Create a **baseline** for data usage | Define **minimum viable list of connectors** that any citizen developer can use. |
| External data (standard) | Dataverse for Teams | Manage efficiently relational data | Detect usage of Dataverse for Teams, clean unused envs, and make sure environments are used for the right use cases by asking for business justification. |
| External data (premium) | Connectors to core business data | **Accelerate adoption** of low code for **critical business areas** | **Identify critical business** areas for your digital transformation, and based on tools and data they use regularly, identify a **set of connectors targeting this population**. Document requirements to use these connectors, and work with training & security teams to allow targeted users to use these connectors.|
| External data (premium) | Predefined groups of connectors | **Centralize** management of data connectivity | Define **groups of connectors** (built-in or custom) that share **similar level of maturity** and/or business understanding. Document, for each group, what are the prerequisites to use them (skills, responsibility, business knowledge, etc). This should be mapped with environment architecture, and training strategy. |
| External data (premium) | Custom management of connectors | **Decentralize** management of data connectivity | Have a process to **create custom connectors at scale**. (ex: solid APIM layer to expose your APIs to the platform in a secure & scalable way). Have a process to **manage custom DLP** to allow these connectors under specific requirements |
| External data (premium) | OnPrem Gateway management | Allow **OnPrem** connectivity | Sync with IT teams  (PowerBI, Azure, Data, etc)  to define a **common IT strategy for OnPrem data gateways** (ex : central vs local gateways, etc) |
| Power Platform data (premium) | Dataverse best practices | Define a **baseline** for **data structure**, and reduce potential **rework** | Document a first level of **best practices** for Dataverse (there are **things that cannot be changed** after creation : target them first when building these best practices : datamodel, table options, etc) |
| Power Platform data (premium) | Basic datamodel (V1) | Ensure **data structure consistency** across the company | Define a **core datamodel** that works best with most of your business scenarios. You should have capacity to **deploy automatically** this model to new environments |
| Power Platform data (premium) | CDM mapping with MDM (V2) | Progressively extend pre-built data model | Work with your data architecture team to understand the **Common Data Model (CDM)** and align it with your own data structure. Build a capacity to automatically deploy relevant items in selected environments. |
| Power Platform data (premium) | Extended datamodel (V3) | Progressively extend pre-built data model | Go beyond CDM data model to include **your own data structure** in Power Platform environments |
| Power Platform data (premium) | Low Code AI | Define a baseline for data structure, and reduce potential rework | Build a decision matric for AI (when to use AI Builder, Cognitive services, or custom AI models) |
