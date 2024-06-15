---
title: "Characterizing Microservice Dependency and Performance: Alibaba Trace Analysis"
collection: publications
permalink: /publication/Characterizing Microservice Dependency and Performance Alibaba Trace Analysis
# excerpt: 'This paper is about fixing template issue #693.'
date: 2021-02-23
venue: 'ACM SoCC'
# paperurl: 'http://academicpages.github.io/files/paper3.pdf'
# citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---

Loosely-coupled and light-weight microservices running in containers are replacing monolithic applications gradually. Understanding the characteristics of microservices is critical to make good use of microservice architectures. However, there is no comprehensive study about microservice and its related systems in production environments so far. 

In this paper, we present a solid analysis of large-scale deployments of microservices at Alibaba clusters. Our study focuses on the characterization of microservice dependency as well as its runtime performance. We conduct an in-depth anatomy of microservice call graphs to quantify the difference between them and traditional DAGs of data-parallel jobs. In particular, we observe that microservice call graphs are heavy-tail dis- tributed and their topology is similar to a tree and moreover, many microservices are hot-spots. We reveal three types of meaningful call dependency that can be utilized to optimize microservice designs. Our investigation on microservice run- time performance indicates most microservices are much more sensitive to CPU interference than memory interfer- ence. To synthesize more representative microservice traces, we build a mathematical model to simulate call graphs. Ex- perimental results demonstrate our model can well preserve those graph properties observed from Alibaba traces.