---
layout: page
title: Building Energy Benchmarking
description: More accurate and explanatory building energy benchmarking systems.
github: https://github.com/buds-lab/energystar-plus-plus
img: /assets/img/benchmarking.png
importance: 10
---

<h4>BEEM: Data-driven building energy benchmarking for Singapore</h4>
<div class="row">
    <div class="col-sm mt-3 mt-md-0 text-center">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/beem.png' | relative_url }}" alt="" title="beem"/>
    </div>
</div>
<div class="caption">
    BEEM benchmarking system for Singapore buildings.
</div>

Building energy use benchmarking is the process of measuring the energy performance of buildings relative to their peer group for creating awareness and identifying energy-saving opportunities. In this paper, we present the design and implementation of BEEM, a data-driven energy use benchmarking system for buildings in Singapore. The peer groups for comparison are established using a public energy disclosure data set. We use an ensemble tree algorithm for accurately modeling building energy use and for identifying the most influential factors. Our models reduce the prediction error from 24.39% to 6.04%, on average, when compared to the baseline linear regression models, which were used in the previous energy efficiency labeling program in Singapore, and outperforms ten other recent models. Using the prototype implementation of BEEM, we benchmarked three building types, office (290), hotel (203), and retail (125), and compared their rating. The code repository and the accompanying data set are released as an open-source project for community use.

**Team:** Pandarasamy Arjunan (BEARS), Kameshwar Poolla (UC Berkeley), and Clayton Miller (NUS)<br>
**Code:** [GitHub](https://github.com/samy101/BEEM){:target="_blank" rel="noopener"}<br>
<hr>


<h4>XENIA: eXplainable ENergy Informatics and Attributes for building energy benchmarking</h4>
<div class="row">
    <div class="col-sm mt-3 mt-md-0 text-center">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/xenia.png' | relative_url }}" alt="" title="xenia"/>
    </div>
</div>
<div class="caption">
    XENIA workflow from the original dataset to benchmarking and model explanation.
</div>
Benchmarking energy usage help identify operational and strategic best practices suitable for an establishment while creating awareness of energy consumption. Therefore in this work, we present XENIA, a data-driven energy benchmarking methodology for buildings in Singapore using a public dataset of building attributes. We develop an ensemble tree model to predict energy consumption using the building attributes as predictors. Symmetric mean absolute percentage error of these models for hotel and retail buildings is 5.15% and 5.02%, respectively. A benchmark grade is then assigned to each building using the actual and predicted energy consumption. To interpret the model, we provide a global explanation using the partial dependence function to show the effect of building attributes on energy consumption. For local explanation, i.e., for a specific building, we use the SHAP value to show the influence of each building attribute in the prediction model. The results for hotels and retail buildings show that change in AC and non-AC floor has the highest positive impact on energy consumption.
<hr>
**Team:** Kevin Joshi (IIT Bombay), Arnab Jana (IIT Bombay), Pandarasamy Arjunan (IIT Bombay), and Krithi Ramamritham (IIT Bombay)<br>
**Code:** [GitHub](https://github.com/kevinjoshi9888/xenia-benchsys22){:target="_blank" rel="noopener"}<br>
<hr>


<h4>EnergyStar++: Towards more accurate and explanatory building energy benchmarking</h4>
Building energy performance benchmarking has been adopted widely in the USA and Canada through the Energy Star Portfolio Manager platform. Building operations and energy management professionals have long used this simple 1–100 score to understand how their building compares to its peers. This single number is easy to use but is created by potentially inaccurate multiple linear regression (MLR) models and lacks much further information about why a building achieves that score. This paper proposes a methodology that enhances the existing Energy Star calculation method by increasing accuracy and providing additional model output processing to help explain why a building is achieving a particular score. Two new prediction models were proposed and tested: multiple linear regression with feature interactions (MLRi) and gradient boosted trees (GBT). Both models performed better than a baseline Energy Star MLR model as well as four baseline models from previous benchmarking studies. This paper shows that for six building types, on average, the third-order MLRi models achieved a 4.9% increase in adjusted R-squared and a 7.0% decrease in normalized root mean squared error (NRMSE) over the baseline MLR model. More substantially, the most accurate GBT models, on average, achieved a 24.9% increase in adjusted R-squared and a 13.7% decrease in NMRSE against the baseline MLR model. In addition, a set of techniques was developed to help determine which factors most influence a building’s energy use versus its peers using SHapley Additive exPlanation (SHAP) values. The SHAP force visualization, in particular, offered an accessible overview of the aspects of the building that influenced the score that even non-technical users can interpret. This methodology was tested on the 2012 Commercial Building Energy Consumption Survey (CBECS)(1,812 buildings) and public data sets from the energy disclosure programs of New York City (11,131 buildings) and Seattle (2,073 buildings).
<hr>
<div class="row">
    <div class="col-sm mt-3 mt-md-0 text-center">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/energystarplusplus-force_lowerEUI.png' | relative_url }}" alt="" title="OpenBAN Architecture"/>
    </div>
</div>
<div class="caption">
    An example SHAP force plot reveals how each factor influences the building energy use.
</div>

**Team:** Pandarasamy Arjunan (BEARS), Kameshwar Poolla (UC Berkeley), and Clayton Miller (NUS)<br>
**Code:** [GitHub](https://github.com/buds-lab/energystar-plus-plus){:target="_blank" rel="noopener"}<br>

<hr>
**Publications:** 
<div class="publications">
  {% bibliography -f papers -q @*[title=XENIA: eXplainable ENergy Informatics and Attributes for building energy benchmarking]* %}
  {% bibliography -f papers -q @*[title=BEEM: Data-driven building energy benchmarking for Singapore]* %}
  {% bibliography -f papers -q @*[title=EnergyStar++: Towards more accurate and explanatory building energy benchmarking]* %}
</div>


