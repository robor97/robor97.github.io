---
layout: post
title: "What Platform Engineering means to me"
categories: cohort4
author:
- Matt Lumb
- Cohort 4
meta: "PE"
---

## What is Platform Engineering?

In this age of digital transformation, companies are continually looking to innovate to gain a competitive advantage. One way to gain a competitive advantage is to have an efficient mechanism for deploying & operating applications in production that enables teams to provide features to end-users faster. To achieve that, many companies realized that it helps to have a dedicated team that builds & maintains a common platform and constantly looks to innovate how applications are deployed and operated in Production. This practice of creating a common platform as a product is called Platform Engineering. See below my definition of Platform Engineering:

Platform Engineering is a practice of building and operating a common platform as a product for technology teams. It reduces time to market and complexity by providing self-service deployments for infrastructure and application and ease of operating applications in production. The team building and operating the common platform constantly innovates and provides best practices implementation, tools, and automation.

The application development teams and other technology teams are still responsible for building, deploying, and operating their applications, but they use the platform in a self-service manner to help simplify things for them.

## Example of a typical platform...

Platforms will be different based on your organization’s needs, but I wanted to explain how a typical platform looks. In diagram #1 below, the platform is self-service where its customers use it for features like Self-service pipelines, Infrastructure Provisioning, Container Platform, Monitoring, Identity Management, Log Aggregation, etc. 

## Diagram 1: Example of a Platform

Platform Engineering Team
The team that builds and operates the common platform is usually called “Platform Engineering Team,” but as mentioned in the caution at the top, it might make sense to call it something else depending on your situation. One of the DevOps movement’s key aspects is to remove silos in organizations by enabling collaboration between various teams(devs, ops, security, compliance, etc.). Making sure that this team does not become another silo is essential.

See below, an example elevator pitch that explains what a typical Platform Engineering Team would do.

For Application Development, Information Security, Compliance, and Infrastructure Teams (Customers)
Who Need to deploy & operate applications in Production (Goal)
We Are Providing Scalable, Secure, Reusable and Self Service Platform (Solution)
That can enable out of the box complex deployments & operations using industry best practices (Key Outcome)
Which is declarative, extendable & a comprehensive plug & play solution (Key Differentiator)
So that they get a competitive advantage by reducing Time to Market & Complexity (Value)

Who are the customers?
The platform’s customers are other technology teams like Application Development, Information Security, Operations, Compliance, Infrastructure, etc. These are typically internal technology teams within the company, but I can see Platform Engineering being used with external teams too.

When is it useful?
Cross-functional teams where each team manages its infrastructure, application, and operations stack are still highly recommended as they are the most effective way to deliver software. Still, there are cases where PE is useful. See below cases where I have seen Platform Engineering being useful.

Want a dedicated team focused on constant innovation of how applications are deployed and operated in production
One of the Platform Engineering team’s key responsibilities is to constantly innovate and improvise on how applications are deployed & operated in production to give a competitive advantage to the technology teams that consume the Platform. The team is constantly experimenting with & learning new practices, technologies, and tools. They work closely with their customers to then implement and provide new features/improvements.

Want application teams to focus on building the business features for end-users
Many companies don’t realize that even with cloud deployments, there is a lot of work needed for deploying complex applications to production. Other than the platform features mentioned in diagram #1 above, things like secrets management, compliance as code, etc. are usually needed that require knowledge of tools/best practices and extensive work. If you want application teams to focus on building the business features for end-users and not worry about automation and tooling for infrastructure and application, having a common platform is useful.

Aligning how various teams deploy and operate applications across the organization
There is a benefit to aligning how teams deploy and operate applications across the organization. This doesn’t mean that different teams don’t use other practices, tools, and technologies but making some common stuff available to teams easily helps.

Teams lack the skills to self-manage deployment and operations
If the technology teams lack the skills to self-manage deployment and operations, having a separate team with the right skills helps provide them what they need to deploy and operate applications in production.

When starting a greenfield application 
Creating a temporary Platform Engineering team is also helpful when you start a greenfield application and want to have a “Walking Skeleton” with a tiny implementation of the application with end to end function including building, deploying, and operating the application in production. Once you achieve the walking skeleton, you disband the PE team, and the other technology teams own the platform.

Note: Be careful not just to renaming an existing team (operations or release management team) to the Platform engineering team without adopting the principles and practices.

Challenges with Platform Engineering
I have worked with various organizations of different sizes and domains to build a common platform as a product. See below some of the challenges I have seen while doing that.

#### Avoid creating another silo
As mentioned above, one of the DevOps movement’s critical aspects is to reduce silos between various teams. Creating another team sounds like the opposite of that, and you should be careful about not creating another silo.

#### Tackling Knowledge silos within the team
We talked about avoiding silos between teams above, but how about silos within the team. PE team usually works with a lot of different programming languages, tools, and techniques that change frequently. Due to these reasons, I have seen silos being created within the team. One of the classic examples is that only 1 of the team members knows how a certain part of the platform works. 

#### Building the right features
I have seen this as a challenge for most PE teams since they are usually dealing with various stakeholders from various teams, so defining and prioritizing features is not straightforward. This team often becomes a catch-all for anything that doesn’t fall under the other technology teams.

#### Being Agile
Since the features this team works on are more technical as the customers are technical teams, I have seen PE teams struggle with using Agile principles and practices. 

#### Embracing rapid adoption
As the practices, technologies, and tools used by the PE team change frequently, the team needs to embrace rapid adoption, which can be challenging as the team members need to continually keep learning and keep their customers updated & educated on the changes.

