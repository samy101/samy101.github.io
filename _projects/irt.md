---
layout: page
title: Infrared Thermography (IRT)
description: Infrared Thermography (IRT) for city-scale building diagnostics and energy auditing.
img: /assets/img/ir-residential.png
importance: 10
---

Collecting accurate information about the operational characteristics of buildings is essential for many performance analyses including energy auditing and benchmarking. While most of the existing solutions involve manual inspection of building premises, surveys, or in-situ sensor deployment, these techniques are intrusive and/or time-intensive, limiting their applicability at larger, city-level spatial scales. Complementing these solutions, we present a wide-area infrared thermography (IRT) based system for measuring a building’s operational characteristics remotely in a non-intrusive and scalable way, and we describe the image capture, processing pipeline, and preliminary results from an initial deployment of this system focusing on the operational characteristics of air-conditioning units. The data collection consisted of infrared imaging of a residential building for 50 days at continuous 10-second intervals. The infrared brightness variations of exterior split air-conditioners fixtures were extracted for each image, and operational attributes were then extracted from the resultant time series. Using state-based change point detection methods to determine times at which air-conditioners are operational, our preliminary analysis focuses on phenomenological patterns of activity with two main findings. First, we demonstrate our ability to determine the operational characteristics of air-conditioners and in particular the fact that they exhibit two distinct modes: continuous operation and cycling behavior. Second, we find that the fraction of "on" time spent in the cycling mode is characteristically longer for lower external temperatures, consistent with the hypothesis that the cycling mode represents a reaching of set temperature. Finally, we outline future research directions and challenges in leveraging IRT for behavioral studies of cooling system use and proactive assessment of air-conditioners towards the development of scalable virtual energy auditing.

<div class="row">
    <div class="col-sm mt-3 mt-md-0 text-center">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/ir-data-collection.png' | relative_url }}" alt="" title="Data collection setup"/>
    </div>
</div>
<div class="caption">
    Infrared data collection setup.
</div>

**Team member:** Pandarasamy Arjunan<br>
**Advisors:** Kameshwar Poolla (UC Berkeley) and Clayton Miller (NUS)<br>
**Publications:** 
<div class="publications">
  {% bibliography -f papers -q @*[title=Operational characteristics of residential air conditioners with temporally granular remote thermographic imaging]* %}
</div>


