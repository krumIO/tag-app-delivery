---
title: How to Contribute
linkTitle: "Contribute"
toc_hide: true
menu:
  main:
    weight: 30
description: Welcome! The Platforms working group is part of CNCF App Delivery - Technical Advisory Group.
---

## Introduction

TAG App Delivery focuses on enabling projects and initiatives related to delivering cloud-native applications, including building, deploying, managing, and operating them. The TAG produces guidance for and gathers feedback from cloud app users and developers and provides guidance and coordination to CNCF projects in the TAG's technical domains.

The Platforms working group aims to provide guidance 

We want to educate and inform users with effective and practical guidance to help them understand the cloud native ecosystem. We do this by collaborating with groups inside and outside the CNCF.

We work to engage with CNCF projects at sandbox, incubating, and graduated level to ensure effective and accurate representation within assets, as well as CNCF Technical Advisory Groups. We also provide a vendor neutral forum for validation, discussion and feedback.
As you get started, you are in the best position to give us feedback on areas where the working group needs help. This includes:

- Gaps in our documentation
- Working to define new artifacts
- Engaging with TAGs and SIGs within the CNCF and its projects

## Contributing to the Website

We use [Hugo](https://gohugo.io/) to format and generate this website, the
[Docsy](https://github.com/google/docsy) theme for styling and site structure,
and [Netlify](https://www.netlify.com/) to manage the deployment of the site.
Hugo is an open-source static site generator that provides us with templates,
content organisation in a standard directory structure, and a website generation
engine. You write the pages in Markdown (or HTML if you want), and Hugo wraps
them up into a website.

All submissions, including submissions by project members, require review. We
use GitHub pull requests for this purpose. Consult
[GitHub Help](https://help.github.com/articles/about-pull-requests/) for more
information on using pull requests.

### Setting up a local instance

Install a local copy of this website with these instructions. Note you must have [npm](https://www.npmjs.com/) and [Hugo](https://gohugo.io/) installed.

```
git clone https://github.com/cncf/tag-app-delivery.git
cd tag-app-delivery
git submodule update --init --recursive
cd website
npm install
```

You can then run the site using `hugo server`.
