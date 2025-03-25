---
layout: page
title: Infrared Thermography
description: Infrared Thermography (IRT) for city-scale building diagnostics and energy auditing.
img: /assets/img/ir-residential.png
importance: 3
---

<h3>Operational characteristics of residential air conditioners with temporally granular remote thermographic imaging</h4>

<br>
<div class="row">
    <div class="col-sm mt-3 mt-md-0 text-center">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/ir-data-collection.png' | relative_url }}" alt="" title="Data collection setup"/>
    </div>
</div>
<div class="caption">
    Infrared data collection setup.
</div>
Collecting accurate information about the operational characteristics of buildings is essential for many performance analyses including energy auditing and benchmarking. While most of the existing solutions involve manual inspection of building premises, surveys, or in-situ sensor deployment, these techniques are intrusive and/or time-intensive, limiting their applicability at larger, city-level spatial scales. Complementing these solutions, we present a wide-area infrared thermography (IRT) based system for measuring a building’s operational characteristics remotely in a non-intrusive and scalable way, and we describe the image capture, processing pipeline, and preliminary results from an initial deployment of this system focusing on the operational characteristics of air-conditioning units. The data collection consisted of infrared imaging of a residential building for 50 days at continuous 10-second intervals. The infrared brightness variations of exterior split air-conditioners fixtures were extracted for each image, and operational attributes were then extracted from the resultant time series. Using state-based change point detection methods to determine times at which air-conditioners are operational, our preliminary analysis focuses on phenomenological patterns of activity with two main findings. First, we demonstrate our ability to determine the operational characteristics of air-conditioners and in particular the fact that they exhibit two distinct modes: continuous operation and cycling behavior. Second, we find that the fraction of "on" time spent in the cycling mode is characteristically longer for lower external temperatures, consistent with the hypothesis that the cycling mode represents a reaching of set temperature. Finally, we outline future research directions and challenges in leveraging IRT for behavioral studies of cooling system use and proactive assessment of air-conditioners towards the development of scalable virtual energy auditing.

<div class="row">
    <div class="col-sm mt-3 mt-md-0 text-center">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/ir_analysis.png' | relative_url }}" alt="" title="IR analysis"/>
    </div>
</div>
<div class="caption">
    Infrared data analysis to extract AC usage.
</div>

**Team:** Pandarasamy Arjunan, Gregory Dobler (University of Delaware, USA), Kyungmin Lee (University of Delaware, USA),  Filip Biljecki (NUS), Clayton Miller (NUS), and Kameshwar Poolla (UC Berkeley)
<hr>

<h4>Longitudinal thermal imaging for scalable non-residential HVAC and occupant behaviour characterization</h4>

<br>
<div class="row">
    <div class="col-sm mt-3 mt-md-0 text-center">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/ir_nus1.png' | relative_url }}" alt="" title="Data collection setup at NUS"/>
    </div>
</div>
<div class="caption">
    Infrared observatory system at NUS.
</div>

This work presents a study on the characterization of the air-conditioning (AC) usage pattern of non-residential buildings from longitudinal thermal images collected at the urban scale. The operational pattern of two different air-conditioning systems (water-cooled systems operating on a pre-set schedule and window AC units operated by the occupants) are studied from the thermal images. It is observed that for the water-cooled system, the difference between the rate of change of the window and wall temperature can be used to extract the operational pattern. While, in the case of the window AC units, wavelet transform of the AC unit temperature is used to extract the frequency and time domain information of the AC unit operation. The results of the analysis are compared against the indoor temperature sensors installed in the office spaces of the building. This forms one of the first few studies on the operational behavior of HVAC systems for non-residential buildings using the longitudinal thermal imaging technique. The output from this study can be used to better understand the operational and occupant behavior, without requiring to deploy a large array of sensors in the building space.

**Team:** Vasantha Ramani (BEARS), Miguel Martin (BEARS), Pandarasamy Arjunan (BEARS), Adrian Chong (NUS), Kameshwar Poolla (UC Berkeley), and Clayton Miller (NUS)
<hr>

<h4>Semantic segmentation of longitudinal thermal images for identification of hot and cool spots in urban areas
</h4>

<br>
<div class="row">
    <div class="col-sm mt-3 mt-md-0 text-center">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/ir_segmentation.jpg' | relative_url }}" alt="" title="IR image segmentation"/>
    </div>
</div>
<div class="caption">
    Semantic segmentation of thermal images
</div>

This work presents the analysis of semantically segmented, longitudinally, and spatially rich thermal images collected at the neighborhood scale to identify hot and cool spots in urban areas. An infrared observatory was operated over a few months to collect thermal images of different types of buildings on the educational campus of the National University of Singapore. A subset of the thermal image dataset was used to train state-of-the-art deep learning models to segment various urban features such as buildings, vegetation, sky, and roads. It was observed that the U-Net segmentation model with ‘resnet34’ CNN backbone has the highest mIoU score of 0.99 on the test dataset, compared to other models such as DeepLabV3, DeeplabV3+, FPN, and PSPnet. The masks generated using the segmentation models were then used to extract the temperature from thermal images and correct for differences in the emissivity of various urban features. Further, various statistical measures of the temperature extracted using the predicted segmentation masks are shown to closely match the temperature extracted using the ground truth masks. Finally, the masks were used to identify hot and cool spots in the urban feature at various instances of time. This forms one of the very few studies demonstrating the automated analysis of thermal images, which can be of potential use to urban planners for devising mitigation strategies for reducing the urban heat island (UHI) effect, improving building energy efficiency, and maximizing outdoor thermal comfort.

**Team:** Vasantha Ramani (BEARS), Pandarasamy Arjunan (BEARS), Kameshwar Poolla (UC Berkeley), and Clayton Miller (NUS)
<hr>



**Publications:** 
<div class="publications">
  {% bibliography -f papers -q @*[title=Semantic segmentation of longitudinal thermal images for identification of hot and cool spots in urban areas]* %}
    {% bibliography -f papers -q @*[title=Longitudinal thermal imaging for scalable non-residential HVAC and occupant behaviour characterization]* %}
  {% bibliography -f papers -q @*[title=Operational characteristics of residential air conditioners with temporally granular remote thermographic imaging]* %}
</div>


