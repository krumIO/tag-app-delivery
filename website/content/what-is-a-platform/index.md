---
title: What is a Platform?
description: A Platform brings together technologies and teams to achieve business outcomes
weight: 2
---

<!-- ## <i class="fas fa-users"></i> People  -->

At its more basic, a platform is an **integrated product** developed by a 
platform engineering team that is custom built and composed of supporting 
capabilities and services designed to reduce the cognitive load and burden 
experienced by **internal** stakeholders of an enterprise organization 
while still safely shipping software at speed [[4]]. 

Note that while internal stakeholders typically refer to developers, they can 
refer to DevOps, SREs, FinOps, Customer Success, and anyone who is responsible 
for software delivery and cloud native infrastructure in an enterprise organization. 

Platforms have become a key focus in cloud-native computing, which typically
separates supporting capabilities from application-specific logic more than
previous paradigms. In such environments resources like Kubernetes clusters, 
databases and object stores, message queues and brokers, observability collectors
and dashboards,user directories and authentication systems, task runners and reconcilers and
more are managed independently and integrated into applications running in
containers and machines. However, this has introduced its own set of challenges as 
developers for example are having to spend more time learning about infrastructure 
instead of focusing on software and app delivery.

Therefore, the goal of the platform is to truly drive
organizational efficiency and productivity by empowering internal stakeholders to 
focus on their key responsibilities while giving them the tools and self-service 
necessary to drive their day to day work. For developers for example, this could mean
having the ability to deploy self-service environments for application development without 
the overhead of understanding infrastructure components. Or for FinOps, this could
mean being able to define chargeback rules without understanding getting too in depth of 
how the metrics are actually collectedfrom cloud-native infrastructure. 

Therefore according to Martin Fowler[[2]], **"a digital platform is a foundation of self-service APIs, tools, services, 
knowledge and support which are arranged as a compelling internal product."**

It is key to note that a platform is bespoke to an organization, supporting 
a unique set of users and business needs. Therefore, platforms are not to be confused 
as just an Internal Developer Portal (IDP) or Service Catalog [[5]]. While those interfaces 
can certainly be helpful for many organizations, ultimately platform engineering teams
need to take a platform as product approach and think deeply about the business objectives 
of their organizations. At its very basic level, a platform could simply be a place where 
users go for basic actions like user management, technical docs, or incident management if that 
is what is most needed.
 
However, just like any product, a platform can evolve over time to meet more complex needs of an organization. 
For example, some example use cases an enterprise can meet with a platform include the following:

1. Developers of products or services can automatically request a complete 
   development environment to support iterative research and development of new 
   features. This includes spaces in relevant services such as Kubernetes clusters, 
   task runners and artifact storage, membership in designated teams, and publication of connection 
   info such as URLs and secrets.
1. Engineering Teams and SRE Teams have a central location for observability where infrastructure
	and services can be onboarded into a single observability platform. 
	This allows for a consistent approach to observability while giving developers 
	an easy interface to be able to do this for any app or cloud service.
1. Operators of third-party products and services can automatically provision 
   spaces and supporting services to deploy and use those third-party products and 
   services
   
Therefore, It is recommended that platform engineering teams start with the thinnest viable platform (TVP) [[6]], 
which is very similar to the concept of an MVP - solve
for the key needs of your organization with the most basic and continue to evolve your platform just like 
any other product. 

By offering consistent experiences for individual and/or scenario-oriented sets 
of capabilities, platforms make it easy for their users to deliver valuable products.

[1]: https://www.atlassian.com/devops/frameworks/team-topologies
[2]: https://martinfowler.com/articles/talk-about-platforms.html
[3]: https://thenewstack.io/platform-as-a-product-true-devops/
[4]: https://thenewstack.io/platform-engineering-in-2023-doing-more-with-less/
[5]: https://thenewstack.io/platform-engineering-is-not-about-building-fancy-uis/
[6]: https://teamtopologies.com/key-concepts-content/what-is-a-thinnest-viable-platform-tvp