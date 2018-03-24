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

You will learn how to:
- make decisions to use one pattern against the other,
- changed architecture, culture and process over time to respond to new requirements,
- make a foundation for successful digitalization.

The ultimate goal is to deliver better software faster. Today, that invariably means continuous delivery – for an installed product – or continuous deployment for an -aaS product. [Read more ...](https://www.gitbook.com/read/book/ivans-innovation-lab/my-company)

This lab is a multi-repo version of the [lab (mono-repo version)](http://ivans-innovation-lab-monorepos.github.io/), and it represents its successor. We keep all our libraries and applications in a separate repos, and this make our build/deployment pipeline and release management more complicated then in a monorepo environemnt. On the other side it enables scaling of development and eliminates long-term commitment to a technology stack.

![Multirepo](https://github.com/ivans-innovation-lab/ivans-innovation-lab.github.io/raw/master/img/multirepo.png)
