---
title: Measuring Success
description: How to set expectations and measure the success of platforms
weight: 7
---

<!-- ## <i class="fas fa-users"></i> People  -->
Having defined what platforms are and the values they intend to provide, let's
consider how to measure if a platform is providing those values. Notably, the
success of a platform is directly correlated to the success of products deployed
on it, and this in turn is largely dependent on user experiences with the
platform.

A platform's first value is to improve product delivery so platform success
metrics should reflect that. The DevOps Research and Assessment (DORA) metrics
suggested by Google provide a baseline and include:

- Frequency of updated deployments
- Lead time for introducing a change
- Rate of failure of newly-introduced changes
- Mean time to recovery from failed changes

And because a platform's success also depends on its users, platforms should
also measure users' experiences, including:

- Time for a new contributor to submit their first (or 10th!) PR
- Number of contributions from users, e.g. Backstage plugins, Crossplane
  compositions
- Number of projects which diverge from "golden paths" and provided capabilities
- Number of tickets opened related to platform capabilities
- Developer satisfaction in the enterprise
    - Net Promoter Score (NPS)
    - SPACE framework: https://queue.acm.org/detail.cfm?id=3454124