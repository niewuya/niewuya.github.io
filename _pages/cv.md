---
layout: archive
# title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in University of Chinese Academy of Sciences, Sept. 2016 - Jan. 2023
* B.S. in Shenzhen University, Sept. 2012 - Jul. 2016

Work experience
======
* Jun. 2023 - Present: Postdoc in Yale University
  * Maintained the transparency for parallel computing across servers with cache coherence.
  * Designed an efficient memory management system for a distributed shared memory cluster and achieved high performance similar to distributed system.

* Apr. 2021 - May 2023: Research Assistant in University of Macau
  * Leveraged deep learning to predict workloads and their uncertainties, and designed a proactive auto-scaler for microservices.
  * Designed an efficient resource management system for guaranteeing SLAs in shared microservice.

* Nov. 2018 - Jan. 2023: Research Intern in Alibaba Cloud
  * Performed a solid analysis of large-scale deployments of microservices at Alibaba clusters.
  * Built a real prototype for microservices resource management and evaluated its efficiency in cloud.
  
Research Interests
======
* Distributed system, cloud computing, deep learning and operating system

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
<!-- Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->
  
Community Service
======
* Reviewer for IEEE Transactions on Parallel and Distributed Systems, Journal of Cloud Computing 
* TPC member for SmartData-2024, HDIS 2023 and 2022, IEEE ScalCom 2022
* Shadow PC for EuroSys 2023
