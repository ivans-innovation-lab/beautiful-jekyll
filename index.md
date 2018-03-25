---
layout: page
title: Lab - Multirepos
subtitle: Architecture, culture and process
bigimg:
  - "/img/architecture.jpg" : "Architecture"
  - "/img/innovate.jpg" : "Innovate"
  - "/img/digital-transformation.jpg" : "Digital transformation"
---

The intention of this open lab is to build information system of a **fictitious company**. We are going to use different architectural and design patterns to support this.

This is a multi-repo version of the lab, and represents a successor of a mono-repo version. Within this version of the lab each project (app or lib) has its dedicated repository (one project = one repository).

Every project has a specific deployment pipeline. In addition, projects don't need to share the same dependencies any more. Hence, all projects are versioned with a concrete version numbers (not SNAPSHOT), and everyone can use any version. You have to deal with a private NPM (JavaScript) or Maven (Java) registry in order to share all versions of projects.

Some teams are writing successful applications leveraging libraries and at companies like Google and Facebook there is a long tradition of using mono-repos.

![Multirepo](https://github.com/ivans-innovation-lab/ivans-innovation-lab.github.io/raw/master/img/multirepo.png)


You will learn how to:
- make decisions to use one pattern against the other,
- changed architecture, culture and process over time to respond to new requirements,
- make a foundation for successful digitalization.

The ultimate goal is to deliver better software faster. Today, that invariably means continuous delivery – for an installed product – or continuous deployment for an -aaS product. [Read more ...](https://www.gitbook.com/read/book/ivans-innovation-lab/my-company)

