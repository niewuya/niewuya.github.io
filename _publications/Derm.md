---
title: "Derm: SLA-aware Resource Management for Highly Dynamic Microservices"
collection: publications
permalink: /publications/Derm SLA-aware Resource Management for Highly Dynamic Microservices
# excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2024-08-01
venue: 'ISCA'
# slidesurl: 'http://niewuya.github.io/files/slides1.pdf'
# paperurl: 'http://niewuya.github.io/files/paper1.pdf'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

Ensuring efficient resource allocation while provid- ing service level agreement (SLA) guarantees for end-to-end (E2E) latency is crucial for microservice applications. Although existing studies have made significant contributions towards achieving this objective, they primarily concentrate on static graphs. However, microservice graphs are inherently dynamic during runtime in production environments, necessitating more effective and scalable resource management solutions.

In this paper, we present Derm, a new resource management system designed for microservice applications with highly dynamic graphs. Our principal finding is that prioritizing different microservice graphs can lead to a substantial reduction in resource allocation. To take advantage of this opportunity, we develop three main components. The first is a performance model that describes uncertainties of microservice latency through a conditional exponential distribution. The second is a probabilistic quantification of the dynamics of microservice graphs. The third is an optimization method for adjusting the resource allocation of microservices to minimize resource usage. We evaluate Derm in our cluster using real microservice benchmarks and production traces. The results highlight that Derm reduces the resource usage by 68.4% and lowers SLA violation probability by 6.7×, compared to existing approaches.