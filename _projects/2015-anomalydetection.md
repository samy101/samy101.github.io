---
layout: page
title: Anomaly Detection
description: Multi-User Energy Consumption Monitoring and Anomaly Detection with Partial Context Information
github: https://github.com/samy101/anomaly_detection
importance: 100
---

Anomaly detection is an important problem in building energy management in order to identify energy theft and inefficiencies. However, it is hard to differentiate actual anomalies from the genuine changes in energy consumption due to seasonal variations and changes in personal settings such as holidays. One of the important drawbacks of existing anomaly detection algorithms is that various unknown context variables, such as seasonal variations, can affect the energy consumption of users in ways that appear anomalous to existing time series based anomaly detection algorithms.In this project, we have developed a system for monitoring the energy consumption of multiple users within a neighborhood and a novel algorithm for detecting anomalies by combining data from multiple users. For each user, the neighborhood is defined as the set of all other users that have similar characteristics (function, location or demography), and are therefore likely to react and consume energy in the similar way in response to the external conditions. The neighborhood can be predefined based on prior customer information, or can be identified through an analysis of historical energy consumption. The proposed algorithm works as a two-step process. In the first step, the algorithm periodically computes an anomaly score for each user by just considering their own energy consumption and variations in the consumption of the past. In the second step, the anomaly score for a user is adjusted by analyzing the energy consumption data in the neighborhood. The collation of data within the neighborhood allows the proposed algorithm to differentiate between these genuine effects and real anomalous behavior of users. Unlike multivariate time series anomaly detection algorithms, the proposed algorithm can identify specific users that are exhibiting anomalous behavior. The capabilities of the algorithm are demonstrated using several year-long real-world data sets, for commercial as well as residential consumers.


**Team member**: Pandarasamy Arjunan (IIIT-Delhi)<br>
**Advisors:** Harshad D Khadilkar (IBM Research, Bangalore), Tanuja Ganu (IBM Research, Bangalore), Zainul M Charbiwala (IBM Research, Bangalore), Dr. Amarjeet Singh (IIIT-Delhi), and Dr. Pushpendra Singh (IIIT-Delhi)<br>
**Code:** [github](https://github.com/samy101/anomaly_detection){:target="_blank" rel="noopener"}<br>
**Publications:** 
<div class="publications">
  {% bibliography -f papers -q @*[title=Multi-User Energy Consumption Monitoring and Anomaly Detection with Partial Context Information]* %}
</div>