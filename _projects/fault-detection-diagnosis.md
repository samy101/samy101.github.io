---
layout: page
title: Fault Detection and Diagnosis (FDD)
description: Data-driven fault detection and diagnosis (FDD) for chiller systems.
img: /assets/img/chiller.png
importance: 2
---


<h4>Explainable AI for Chiller Fault-Detection Systems: Gaining Trust and Human Connect</h4>
<div class="row">
    <div class="col-sm mt-3 mt-md-0 text-center">
		<img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/xai-workflow.png' | relative_url }}" alt="" title="XAI-FDD workflow"/>
    </div>
</div>
<div class="caption">
    XAI-FDD workflow.
</div>

<br>
Chillers are energy-intensive, prone-to-faults components used for space cooling in buildings.  Data-driven Fault Detection and Diagnosis (DD-FDD) are widely used for chillers. However, field personnel are often not confident in DD-FDD mainly because no explanation is given for the results. EXplainable Artificial Intelligence (XAI)  can help bridge this gap. We investigate XAI-FDD's role in building trust in DD-FDD. We examine use-cases for XAI-FDD on a building in Singapore having 6 chillers.

**Team:** Seshadhri Srinivasan (GE Global Research), Pandarasamy Arjunan (BEARS), Baihong Jin (UC Berkeley), Alberto L. Sangiovanni-Vincentelli (UC Berkeley), Zuraimi Sultan (BEARS), and Kameshwar Poolla (UC Berkeley)

<hr>

<h4> Causal 1-D convolutional neural networks based chiller fault detection and diagnosis </h4>
Modern buildings are densely equipped with smart energy meters, which periodically generate a massive amount of time-series data yielding a few million data points every day. This data can be leveraged to discover the underlying load and infer their energy consumption patterns, inter-dependencies on environmental factors, and the building's operational properties. Furthermore, it allows us to simultaneously identify anomalies present in the electricity consumption profiles, which is a big step towards saving energy and achieving global sustainability. However, to date, the lack of large-scale annotated energy consumption datasets hinders the ongoing research in anomaly detection. We contribute to this effort by releasing a carefully annotated version of a publicly available ASHRAE Great Energy Predictor III data set containing 1,413 smart electricity meter time series spanning over one year. In addition, we benchmark the performance of eight state-of-the-art anomaly detection methods on our dataset and compare their performance.

**Team:** Pandarasamy Arjunan (BEARS), Seshadhri Srinivasan (GE Global Research), and Kameshwar Poolla (UC Berkeley)
<hr>

<br>
**Publications:** 
<div class="publications">
  {% bibliography -f papers -q @*[title=Causal 1-D convolutional neural networks based chiller fault detection and diagnosis]* %}
  {% bibliography -f papers -q @*[title=Explainable AI for chiller fault-detection systems: gaining human trust]* %}
</div>