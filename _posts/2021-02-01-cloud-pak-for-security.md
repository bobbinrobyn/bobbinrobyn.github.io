---
layout: post
title: IBM Cloud Pak for Security
---

![IBM Cloud Pak for Security](/images/cp4s/homepage.png)
_Designing a unified platform for security tools that allow enterprises to surface threats across all their data sources and quickly respond_

## In a nutshell
IBM Cloud Pak for Security (CP4S) is a security platform that brings together a number of threat management security tools. With CP4S, enterprises have a one stop shop for their entire threat management workflow. The primary users of CP4S are security analysts, incident responders, threat hunters, and IT administrators. Another important category of users are internal; CP4S empowers app teams to easily onboard to the platform, and we also contribute significantly to IBM's Cloud Pak strategic initiative and all of its collaborators.

For the last year, I have led a team of designers to deliver new capabilities for Cloud Pak for Security platform that add functionality and improve the user experience. Below, I'll walk through the collaborative process for improving a user pain point while also adding functionality.


## Problem statement
A core value for CP4S is empowering application teams to easily onboard their app to the platform. Until recently, we could only support production-ready apps. For apps that wanted to release a preview or early release of some kind, they had to hack at the existing experience and make it work for a beta release. Each app went about differently, which was frustrating for them and a bad experience for end users.

Our app teams needed a programatic way to release an app or feature in beta, and our users needed to have appropriate expectations for using a beta app or feature. The entire experience needed to be designed, rather than mashed together without a lot of thought.


## Desired outcomes
- Create a formalized beta release governance plan
- Empower app teams to release beta features and apps
- Design a pattern to label beta features and apps


## My contributions & process
I led the design of the beta governance plan, and I oversaw a small team of designers who delivered the beta design pattern.

- Stakeholder interviews to gain domain knowledge and better understand pain points, by asking questions like:
  - What term will users be most familiar with to describe a pre-production release? 
  - What are our users' expectations for a beta release?
  - Should beta features and apps be opted into or out of by default?

- Created criteria to define a beta release versus a production release, as well as guidance to ensure the governance is applied consistently

- Aligned stakeholders around the final recommendation until it earned executive approval

- Communicated the new governance plan and design pattern for beta releases to app teams and offering managers


## Solution
The work is being delivered in phases. In the first phase, we have implemented an initial governance plan and launched three beta apps and features using the new design pattern. In a future phase, we will enhance the design pattern and included a feedback mechanism as part of the governance plan.

![Final design](/images/cp4s/beta1.png)
![Final design](/images/cp4s/beta2.png)
