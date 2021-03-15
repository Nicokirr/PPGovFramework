---
title: Security
permalink: /docs/security/
excerpt: >
    Security ensures a controlled and managed usage of the platform, protecting company data.
toc: true
---

Security ensures a controlled and managed usage of the platform, protecting company data

| Theme | Activity | WHY its important | HOW you can start |
| --- | --- | --- | --- |
| Platform | Platform validation | Allow **basic & controlled** usage of Power Platform in the company | **Validate O365** usage in default environment **for all**. Implement a **DLP** in default env and any new environment (except env managed), that **enforce the default** list established by the data stream. **Configure tenant** (trial access, environment creation, resource allocation, etc.) |
| Platform | Connector security assessment & rating | Allow **more connectivity** while staying in **control** | Define a **criticity scale** for connectors with generic criterias (for example, authentication mechanism used). Then map connectors on this scale. Regularly review the mapping (for new, custom and updated connectors). |
| Compliance | Compliance guidance | Manage apps based on **criticity** | Define **criticity scale** with criterias (ie : use of personal or sensitive data, number of users, impact on business if app does not work,  …). Define **control processes** based on app criticity. (ex: low criticity : fully automated, medium : manual review before go live, high : regular reviews). Define do’s and don’ts in regards of security (consent management for example). |
| Compliance | Compliance reviews | **Ensure** the right level of **security** for each app | Map app **criticity scale** with existing **security service offers**. This may result in internal “certification” of some applications, or even development teams to scale. |
| Identity | Security group self service | Ease **access management** to low code resources | Build tools to allow users to create and manage their own groups. **Sync with O365 team** to check how business users can manage groups. |
| Identity | Policy for external identity | Allow processes that include **external users** (providers, partners, customers, subcontractors, etc) | **Sync with AzureAD teams**. Regarding AzureAD : Define how **external authentication** should be managed. Can makers leverage **guest access** ? Regarding external identity management : Can external users authenticate with **external providers** ? (Google, Facebook, etc). |
