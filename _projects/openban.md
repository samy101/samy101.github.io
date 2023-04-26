---
layout: page
title: OpenBAN
description: An Open Building ANalytics Middleware for Smart Buildings
github: https://github.com/samy101/OpenBAN
img: /assets/img/openban-logo.png
importance: 101
---

Towards the realization of smart building applications, buildings are increasingly instrumented with diverse sensors and actuators. These sensors generate large volumes of data which can be analyzed for optimizing building operations. Many building energy management tasks such as energy forecasting, disaggregation, among others require complex analytics leveraging collected sensor data. While several standalone and cloud-based systems for archiving, sharing and visualizing sensor data have emerged, their support for analyzing sensor data streams is primitive and limited to rule-based actions based on thresholds and simple aggregation functions. We have developed OpenBAN, an open source sensor data analytics middleware for buildings, to make analytics an integral component of modern smart building applications. OpenBAN provides a framework of extensible sensor data processing elements for identifying various building context, which different applications can leverage. We validate the capabilities of OpenBAN by developing three representative real-world applications which are deployed in our test-bed buildings: (i) household energy disaggregation, (ii) detection of sprinkler usage from water meter data, and (iii) electricity demand forecasting. We also provide a preliminary system performance analysis of OpenBAN when deployed in the cloud and locally within a building.

<div class="row">
    <div class="col-sm mt-3 mt-md-0 text-center">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/openban.jpg' | relative_url }}" alt="" title="OpenBAN Architecture"/>
    </div>
</div>
<div class="caption">
    OpenBAN architecture shows the Aggregate-Analyze-Act pipeline of a building energy management application.
</div>

**Team members:** Pandarasamy Arjunan (IIIT-Delhi) and Kevin Ting (UCLA)<br>
**Advisors:** Prof. Mani B Srivastava (UCLA), Dr. Amarjeet Singh (IIIT-Delhi), and Dr. Pushpendra Singh (IIIT-Delhi)<br>
**Code:** [GitHub](https://github.com/samy101/OpenBAN){:target="_blank" rel="noopener"}<br>
**Publications:** 
<div class="publications">
  {% bibliography -f papers -q @*[title=OpenBAN: An Open Building ANalytics Middleware for Smart Buildings]* %}
</div>
