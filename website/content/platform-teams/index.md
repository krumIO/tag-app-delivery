---
title: Platform Teams
description: The makeup of Platform teams, and how to enable them.
weight: 4
---

<!-- ## <i class="fas fa-users"></i> People  -->
## Attributes of platform teams

Platform teams are responsible for the interfaces to and experiences with
platform capabilities - like Web portals, custom APIs, and golden path
templates. On one hand, platform teams work with those teams implementing
infrastructure and supporting services to define consistent experiences; on
the other, they work with product and user teams to gather feedback and ensure
those experiences meet requirements.

Following are jobs a platform team should be responsible for:

1. Research platform user requirements
1. Manage and develop interfaces for capabilities and services - portals, APIs,
   docs and templates, CLIs
1. Market, evangelize and advocate for platform usage

Most importantly, platform teams must learn about the requirements of platform
users \[1\] to inform and continuously improve capabilities and interfaces offered
by their platform. Ways to learn about user requirements include user
interviews, interactive hackathons, issue trackers and surveys, and direct
observation of usage through observability tools. For example, a platform team
could publish a form for users to submit feature requests; and conduct periodic
roadmap meetings to share upcoming features and gather feedback.

A platform team doesn't necessarily run compute, network, storage or other
services. Rather they own the interfaces \[2\] (GUI, CLI, API) and user
experiences with those services. For example, a Web portal page might describe
and even offer a button to provision an identity for an app; while the
implementation of that capability might be via a cloud-hosted identity service.
A platform team owns the web page and user-facing API, but not necessarily the
implementation.

Earlier it was stated that a platform should be treated as a product.
Specifically, the platform should be continuously improved based on user
requirements and optional to use (see: platform attributes #1 and #8). While
research and design is one side of product delivery, the other side is marketing
and advocacy \[3\]. If the platform is truly being built to user requirements,
people should be excited to use the provided capabilities. Some ways a platform
team can help adoptions is through internal marketing activities including
delivering department wide announcements, sharing engaging demos, and welcoming
questions during regular office hours. The key here is to meet users where they
are, and bring them on the journey to engage with and benefit from the platform.

## Enabling platform teams

It is clear from these challenges that platform teams are faced with a number of
diverse responsibilities which lead to cognitive load. Just as with their
application team counterparts, this challenge grows with the number and diversity
of users and teams they need to support.

It is important to focus the platform team's energy on the experience and
capabilities that are unique to their specific business. Ways to reduce load on
the platform team include the following:

1. Use implementations from managed service providers where reasonable
1. Leverage open source frameworks and toolkits for creating docs, templates and
   compositions for application team use
1. Ensure platform teams are staffed appropriately for their domain and number
   of customers