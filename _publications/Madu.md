---
title: "The Power of Prediction: Microservice Auto Scaling via Workload Learning"
collection: publications
permalink: /publication/The Power of Prediction Microservice Auto Scaling via Workload Learning
# excerpt: 'This paper is about the number 3. The number 4 is left for future work.'
date: 2022-09-01
venue: 'ACM SoCC'
# slidesurl: 'http://niewuya.github.io/files/slides3.pdf'
# paperurl: 'http://niewuya.github.io/files/paper3.pdf'
# citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---

When deploying microservices in production clusters, it is critical to automatically scale containers to improve cluster utilization and ensure service level agreements (SLA). Although reactive scaling approaches work well for monolithic architectures, they are not necessarily suitable for microservice frameworks due to the long delay caused by complex microservice call chains. In contrast, existing proactive approaches leverage end-to-end performance prediction for scaling, but cannot effectively handle microservice multiplexing and dynamic microservice dependencies.

In this paper, we present Madu, a proactive microservice auto-scaler that scales containers based on predictions for individual microservices. Madu learns workload uncertainty to handle the highly dynamic dependency between microservices. Additionally, Madu adopts OS-level metrics to optimize resource usage while maintaining good control over scaling overhead. Experiments on large-scale deployments of microservices in Alibaba clusters show that the overall predic- tion accuracy of Madu can reach as high as 92.3% on average, which is 13% higher than the state-of-the-art approaches. Furthermore, experiments running real-world microservice benchmarks in a local cluster of 20 servers show that Madu can reduce the overall resource usage by 1.7x compared to reactive solutions, while reducing end-to-end service latency by 50%.