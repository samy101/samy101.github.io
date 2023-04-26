---
layout: page
title: Energy Anomaly Detection
description: Large-scale Anomaly Detection (LEAD) dataset and techniques.
github: https://github.com/samy101/anomaly_detection
img: /assets/img/anomaly.png
importance: 1
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0 text-center">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/anomaly_example.png' | relative_url }}" alt="" title="Anomaly Example"/>
    </div>
</div>
<div class="caption">
    An example anomaly in the hourly electricity readings from an office building.
</div>

<h4>Kaggle Competition: Large-scale Energy Anomaly Detection (LEAD)</h4>
<div class="row">
    <div class="col-sm mt-3 mt-md-0 text-center">
		<a href="https://www.kaggle.com/competitions/energy-anomaly-detection" target="_blank">
			<img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/lead_competition.png' | relative_url }}" alt="" title="LEAD competition"/>
		</a>
    </div>
</div>
<br>
Buildings consume approximately one-third of the total energy around the world. It is estimated that more than 20% of this energy is wasted due to equipment failure, aging, misconfiguration, and human-related errors. This wasteful use of energy can be identified and prevented using a data-driven analytical technique known as anomaly or outlier detection. Modern buildings are densely equipped with smart energy meters, which periodically generate a massive amount of time-series data yielding a few million data points every day. This data can be leveraged to identify anomalies present in the energy consumption profiles, which is a big step towards saving energy and achieving global sustainability.

In this competition, data scientists were challenged to develop accurate models to identify abnormal energy usage instances (point anomaly) in year-long hourly smart electricity meter time series. The provided dataset is the extended version of the dataset used in the ASHRAE - Great Energy Predictor III competition after carefully annotating each data point of electricity meters from approximately 400 commercial buildings.

**Competition website:** [Kaggle](https://www.kaggle.com/competitions/energy-anomaly-detection){:target="_blank" rel="noopener"}<br>
**Winnning solution:** [Kaggle notebook](https://www.kaggle.com/code/patrick0302/2-anomaly-detection-features-csv-revised-lgb){:target="_blank" rel="noopener"}<br>
**Code:** [Kaggle notebooks](https://www.kaggle.com/competitions/energy-anomaly-detection/code){:target="_blank" rel="noopener"}<br>

<hr>

<h4> LEAD1.0: a large-scale annotated dataset for energy anomaly detection in commercial buildings </h4>
Modern buildings are densely equipped with smart energy meters, which periodically generate a massive amount of time-series data yielding a few million data points every day. This data can be leveraged to discover the underlying load and infer their energy consumption patterns, inter-dependencies on environmental factors, and the building's operational properties. Furthermore, it allows us to simultaneously identify anomalies present in the electricity consumption profiles, which is a big step towards saving energy and achieving global sustainability. However, to date, the lack of large-scale annotated energy consumption datasets hinders the ongoing research in anomaly detection. We contribute to this effort by releasing a carefully annotated version of a publicly available ASHRAE Great Energy Predictor III data set containing 1,413 smart electricity meter time series spanning over one year. In addition, we benchmark the performance of eight state-of-the-art anomaly detection methods on our dataset and compare their performance.

**Team:** Manoj Gulati (SMU) and Pandarasamy Arjunan (BEARS)<br>
**Code:** [GitHub](https://github.com/samy101/lead-dataset){:target="_blank" rel="noopener"}<br>
<hr>

<h4> Multi-User Energy Consumption Monitoring and Anomaly Detection with Partial Context Information </h4>
Anomaly detection is an important problem in building energy management in order to identify energy theft and inefficiencies. However, it is hard to differentiate actual anomalies from the genuine changes in energy consumption due to seasonal variations and changes in personal settings such as holidays. One of the important drawbacks of existing anomaly detection algorithms is that various unknown context variables, such as seasonal variations, can affect the energy consumption of users in ways that appear anomalous to existing time series based anomaly detection algorithms.In this project, we have developed a system for monitoring the energy consumption of multiple users within a neighborhood and a novel algorithm for detecting anomalies by combining data from multiple users. For each user, the neighborhood is defined as the set of all other users that have similar characteristics (function, location or demography), and are therefore likely to react and consume energy in the similar way in response to the external conditions. The neighborhood can be predefined based on prior customer information, or can be identified through an analysis of historical energy consumption. The proposed algorithm works as a two-step process. In the first step, the algorithm periodically computes an anomaly score for each user by just considering their own energy consumption and variations in the consumption of the past. In the second step, the anomaly score for a user is adjusted by analyzing the energy consumption data in the neighborhood. The collation of data within the neighborhood allows the proposed algorithm to differentiate between these genuine effects and real anomalous behavior of users. Unlike multivariate time series anomaly detection algorithms, the proposed algorithm can identify specific users that are exhibiting anomalous behavior. The capabilities of the algorithm are demonstrated using several year-long real-world data sets, for commercial as well as residential consumers.

**Team:** Pandarasamy Arjunan (IIIT-Delhi), Harshad D Khadilkar (IBM Research, Bangalore), Tanuja Ganu (IBM Research, Bangalore), Zainul M Charbiwala (IBM Research, Bangalore), Dr. Amarjeet Singh (IIIT-Delhi), and Dr. Pushpendra Singh (IIIT-Delhi)<br>
**Code:** [GitHub](https://github.com/samy101/anomaly_detection){:target="_blank" rel="noopener"}<br>
<hr>

<br>
**Publications:** 
<div class="publications">
  {% bibliography -f papers -q @*[title=Trimming outliers using trees: winning solution of the large-scale energy anomaly detection (LEAD) competition]* %}
  {% bibliography -f papers -q @*[title=LEAD1.0: a large-scale annotated dataset for energy anomaly detection in commercial buildings]* %}
  {% bibliography -f papers -q @*[title=Multi-User Energy Consumption Monitoring and Anomaly Detection with Partial Context Information]* %}
</div>