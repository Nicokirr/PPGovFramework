---
title: Technical Guidance
permalink: /techguidance/
excerpt: >
    Tech guidance ensures Technical best practices are followed across the platform, with a goal to reduce efforts to create and maintain low code items.
toc: true
---

Tech guidance ensures Technical best practices are followed across the platform, with a goal to reduce efforts to create and maintain low code items.

| Theme | Activity | **Why** you should work on this activity | **How** you can start |
| --- | --- | --- | --- |
| Architecture | Env archi guidance citizen | Clarify **citizen** access to different environments | Define rules to create environments for citizen developers. As environments are related to connector control through DLP, a good approach is to have at least one environment per citizen dev maturity / training. |
| Architecture | Env archi guidance pro dev | Clarify **pro dev** access to different environments | Define rules to create environments for pro developers. To avoid governance challenges within an environment, it is currently recommended to have few environments dedicated for each “pro dev” team. Define when projects should use mutualized environments, and based on which criteria. |
| Architecture | Dev best practices | **Ensure similar dev patterns** are used across Power Platform items to **ease maintenance & support** | Define guidelines such as naming conventions, ways to structure apps & flows. You can leverage [PowerApps Canvas app coding standards and guidelines](https://aka.ms/powerappscanvasguidelines) |
| Tools | Expertise as a service | Use central technical expertise to coach other developers | Have a catalog of expertise services to help citizen developers build their app in the right way (architecture workshop, design review, etc) |
| Tools | DevTools | Ensure similar CI/CD patterns across dev teams | Define how to build CI/CD pipelines in your company context (source code repository) |
| Tools | Component & template catalog | **Accelerate** build by citizens. **Increase capabilities** offered to citizens. Homogenize theming and UX | Create a library of components to ease most common scenarios. This can be low code components (headers, footers, nav menus, etc.) as well as coded components (PCF : often used to expand platform capabilities for core business scenarios) |
| Capabilities | Engineering roadmap | Maximize value of platform evolution | Review regularly release notes (twice a year) and analyze benefits based on your usage, needs, and requirements. |
