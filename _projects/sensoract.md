---
layout: page
title: SensorAct
description: A Decentralized and Extensible Middleware for Smart Buildings
github: https://github.com/iiitd-ucla-pc3
img: /assets/img/sensort-logo.png
importance: 102
---

The archaic centralized software systems, currently used to manage buildings, make it hard to incorporate advances in sensing technology and user-level applications, and present hurdles for experimental validation of open research in building information technology. Motivated by this, we — a transnational collaboration of researchers engaged in development and deployment of technologies for sustainable buildings — have developed SensorAct, an open-source federated middleware incorporating features targeting three specific requirements: (i) Accommodating a richer ecosystem of sensors, actuators, and higher level third-party applications (ii) Participatory engagement of stakeholders other than the facilities department, such as occupants, in setting policies for management of sensor data and control of electrical systems, without compromising on the overall privacy and safety, and (iii) Flexible interfacing and information exchange with systems external to a building, such as communication networks, transportation system, electrical grid, and other buildings, for better management, by exploiting the teleconnections that exist across them. SensorAct is designed to scale from small homes to network of buildings, making it suitable not only for production use but to also seed a global-scale network of building testbeds with appropriately constrained and policed access. We have deployed SensorAct in diverse settings across India and United States and implemented multiple third party applications using SensorAct APIs.

<div class="row">
    <div class="col-sm mt-3 mt-md-0 text-center">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/sensoract.jpg' | relative_url }}" alt="" title="OpenBAN Architecture"/>
    </div>
</div>
<div class="caption">
    Tiered architecture of SensorAct, Virtual Personal Device Servers (VPDS) and Broker components.
</div>

**Team members:** Pandarasamy Arjunan (IIIT-Delhi), Haksoo Choi (UCLA), Manaswi Saha (IIIT-Delhi), Nipun Batra (IIIT-Delhi), and Manoj Gulati (IIIT-Delhi)<br>
**Advisors:** Prof. Mani B Srivastava (UCLA), Dr. Amarjeet Singh (IIIT-Delhi), and Dr. Pushpendra Singh (IIIT-Delhi)<br>
**Code:** [GitHub](https://github.com/iiitd-ucla-pc3){:target="_blank" rel="noopener"}<br>
**Publications:** 
<div class="publications">
  {% bibliography -f papers -q @*[title=SensorAct: A Decentralized and Scriptable Middleware for Smart Energy Buildings]* %}
  {% bibliography -f papers -q @*[title=Sensoract: Design and implementation of fine-grained sensing and control sharing in buildings]* %}
  {% bibliography -f papers -q @*[title=SensorAct: A Privacy and Security Aware Federated Middleware for Building Management]* %}
</div>