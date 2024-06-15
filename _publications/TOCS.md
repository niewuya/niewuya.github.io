---
title: "Optimizing resource management for shared microservices: a scalable system design"
collection: publications
permalink: /publication/Optimizing resource management for shared microservices a scalable system design
date: 2024-03-23
venue: 'ACM Transactions on Computer Systems'
# slidesurl: 'http://academicpages.github.io/files/slides2.pdf'
# paperurl: 'http://academicpages.github.io/files/paper2.pdf'
# citation: 'Your Name, You. (2010). &quot;Paper Title Number 2.&quot; <i>Journal 1</i>. 1(2).'
---

A common approach to improving resource utilization in data centers is to adaptively provision resources
based on the actual workload. One fundamental challenge of doing this in microservice management frameworks, however, is that different components of a service can exhibit significant differences in their impact
on end-to-end performance. To make resource management more challenging, a single microservice can be
shared by multiple online services that have diverse workload patterns and SLA requirements. We present an efficient resource management system, for guaranteeing SLAs with high
probability in shared microservice environments. 

<!-- Erms profiles microservice latency as a piece-wise linear function of the workload, resource usage, and interference. Based on this profiling, Erms builds resource scaling models to optimally determine latency targets for microservices with complex dependencies. Erms also
designs new scheduling policies at shared microservices to further enhance resource efficiency. Experiments
across microservice benchmarks as well as trace-driven simulations demonstrate that Erms can reduce SLA
violation probability by 5× and more importantly, lead to a reduction in resource usage by 1.6×, compared to
state-of-the-art approaches. -->