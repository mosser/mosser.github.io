---
title: "Research Interests"
permalink: /research/
author_profile: true
---

<div style="float:right; margin-bottom: 1em; margin-left: 1em;">
  <img src="/images/teacher.png" />
</div>

My overall research goal is to properly understand "software composition" (_i.e._, the opposite side of the "separation of concerns" – SoC – coin) and how practitioners use it. Since the defence of my Ph.D. in 2010, I obtained results dedicated to software composition and its application to a given application domain, namely cyber-physical systems. In addition, I also contributed to software engineering in general, focusing on modelling and variability management at a large scale.

### Current research interests (2022 - ...)

- **Lightweight Safety Models**: Safety models such as assurance cases require specific expertise, and are usually not mastered by _regular_ software engineers. By working on justification models (and developping the [jPipe](https://github.com/ace-design/jpipe) platform), I am exploring how to bring safety-related expertise to non-safety-critical domains, such as machine learning pipelines or CI/CD systems in DevOps environments.

- **Requirements Engineering**: I am interested in understandign how engineers capture requirements, from agile user stories to more formal models. As requirements eventually confilct wit each other, my effort is focused here on how to capture decisions and trade-offs related to solving such conflicts, and how to maintain these decisions over time. 

- **Language Server Protocols**: in the past 10 years, a lot of my research effort involved the developement of so-called domain-specific languages (DSL). I am now interested in trying to abstract recurring elements to provide easier support for the edition of such DSLs/

### Previous research interests (until 2022)

- **Microservice Architectures**: Decomposing distributed systems into microservices often creates more issues than it was supposed to solve. I am interested in observing how developers maintain and evolve such systems and providing tools to support such tasks at scale. We have curated a list of 13 open-sources microservice architectures that we are currently studying.

- **Software composition abstractions**: I focused my efforts on defining composition operators while measuring the benefits of introducing software composition in various application domains (_e.g._, graph databases, kernel development, micro-services deployment, business processes). Classical software composition approaches rely on total ordering. I proposed strategies that free the software developer from identifying an application order when composing artifacts, depending on algebraic properties such as commutativity. 

- **Software Modelling and Variability Management**: Considering software modelling, I applied _Model-Driven Engineering_ (MDE) approaches to variability management in various domains such as modelling languages, business processes or continuous integration. My other contributions to variability management were focused on managing large-scale software product lines, leading to the registration of a French patent. I have also dedicated efforts in my research contributions to teaching software modelling and variability management. Since 2018, I am also involved in an initiative targeting the improvement of MDE teaching.

- **Cyber-Physical Systems (CPSs)**: In this domain, I focused my effort on defining model-based composition operators dedicated to data collection policies and large-scale sensor networks. These operators allow one to reuse an existing network by deploying new applications on top of it instead of building a new sensor network from scratch. This is very important in the context of Smart Cities, for example.

- **Source Code Analysis & Merging**: When talking about software development, "_code is the truth_" at the end of the day. I am interested in developing source code analysis techniques that can help software developers when working on large pieces of software. In this context, my current playground is to experiment with new source code merging algorithms and provide static analysis to understand better how software compilers (e.g., LLVM) work.

- **Scalable Software Development**: This dimension covers my work on DevOps, considering that making software development scalable is not all about technical work. It also covers requirements engineering and human aspects. I am particularly interested in linking requirements to development, build and deployment artifacts in this context. I am also investigating how NLP techniques can improve how requirements can be used in such a context.
