---
layout: page
title: EnergyStar++
description: More accurate and explanatory building energy benchmarking
github: https://github.com/buds-lab/energystar-plus-plus
importance: 10
---

Building energy performance benchmarking has been adopted widely in the USA and Canada through the Energy Star Portfolio Manager platform. Building operations and energy management professionals have long used this simple 1–100 score to understand how their building compares to its peers. This single number is easy to use but is created by potentially inaccurate multiple linear regression (MLR) models and lacks much further information about why a building achieves that score. This paper proposes a methodology that enhances the existing Energy Star calculation method by increasing accuracy and providing additional model output processing to help explain why a building is achieving a particular score. Two new prediction models were proposed and tested: multiple linear regression with feature interactions (MLRi) and gradient boosted trees (GBT). Both models performed better than a baseline Energy Star MLR model as well as four baseline models from previous benchmarking studies. This paper shows that for six building types, on average, the third-order MLRi models achieved a 4.9% increase in adjusted R-squared and a 7.0% decrease in normalized root mean squared error (NRMSE) over the baseline MLR model. More substantially, the most accurate GBT models, on average, achieved a 24.9% increase in adjusted R-squared and a 13.7% decrease in NMRSE against the baseline MLR model. In addition, a set of techniques was developed to help determine which factors most influence a building’s energy use versus its peers using SHapley Additive exPlanation (SHAP) values. The SHAP force visualization, in particular, offered an accessible overview of the aspects of the building that influenced the score that even non-technical users can interpret. This methodology was tested on the 2012 Commercial Building Energy Consumption Survey (CBECS)(1,812 buildings) and public data sets from the energy disclosure programs of New York City (11,131 buildings) and Seattle (2,073 buildings).

<div class="row">
    <div class="col-sm mt-3 mt-md-0 text-center">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/energystarplusplus-force_lowerEUI.png' | relative_url }}" alt="" title="OpenBAN Architecture"/>
    </div>
</div>
<div class="caption">
    An example SHAP force plot reveals how each factor influences the building energy use.
</div>

**Team member:** Pandarasamy Arjunan<br>
**Advisors:** Kameshwar Poolla (UC Berkeley) and Clayton Miller (NUS)<br>
**Code:** [github](https://github.com/buds-lab/energystar-plus-plus){:target="_blank" rel="noopener"}<br>
**Publications:** 
<div class="publications">
  {% bibliography -f papers -q @*[title=EnergyStar++: Towards more accurate and explanatory building energy benchmarking]* %}
</div>


