---
layout: post
title: IBM Cloud Identity
---

![Final designs for an IBM Cloud Identity feature I designed](/images/cloud-identity/final-design.png)

## In a nutshell
IBM Cloud Identity (CI) is an identity and access management tool that enables enterprises to securely manage users and their access to applications. The tool ensures that enterprises only allow applications to be accessed by users who are authenticated and authorized. This type of software tool is often considered a "necessary evil" –– it's usually not glamorous, but it is an essential part of an enterprise's security strategy. The primary users of CI are IT administrators on the configuration side, as well as employees and/or customers on the user-facing side. 

For the last year and a half, I have worked with a small team of designers to design several new capabilities for CI that add functionality and improve the user experience. Below, I'll walk through my process for designing one of these features to improve a major user pain point.


## Problem statement
A core feature of CI is the ability to configure and manage identity sources. Unfortunately, up to this point this only included cloud-based identity sources, not external (on-premises) identity sources. This meant that some of an enterprises's users were managed in CI, while others are managed elsewhere. It was a totally disconnected experience and a nightmare for IT admins. It also created the potential for duplicate users, mismatched entitlements, and other security gaps.

Our users needed to be able to create and manage all of their identity sources within IBM Cloud Identity (CI), including external identity sources. This would allow CI to be a true single source of truth from which an enterprise could manage all user authentication.


## Desired outcomes
- Easily connect an external identity source to CI
- Create a single place to configure and monitor all identity sources within CI
- Ability to authenticate and provision users from external identity sources


## My contributions & process
I led the design of this feature, and I worked with a visual designer and a team of developers to deliver the final designs.

- Stakeholder interviews to gain domain knowledge and better understand pain points, by asking questions like:
  - What should the user be able to do and accomplish with this new feature?
  - What does the user need to see in order to get through each step of a workflow? 
  - What are the pieces of this thing you want to build? What makes it all come together to be displayed to the user?

- Created content models to document the desired to-be state
![Content model for passthrough agents](/images/cloud-identity/content-model.png)

- Modeled the to-be user workflow and created initial prototypes, collaborating heavily with the dev team
![To-be user workflow](/images/cloud-identity/workflow.png)

- Validated content models and prototypes with stakeholders and users
![Using Slack to validate content model](/images/cloud-identity/slack-content-model.png)


## Solution
We delivered a simple solution for connecting external identity sources to CI and for monitoring all identity sources in a single location. We also provided a quick workflow for building the agents needed to authenticate and provision users from external identity sources. This dramatically reduces the workload for the IT admin and improves the security of enterprise user bases.

![Final design](/images/cloud-identity/final-design.png)
![Final design](/images/cloud-identity/final-design-2.png)
