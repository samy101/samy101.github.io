---
layout: page
title: EnergyStar++
description: Towards more accurate and explanatory building energy benchmarking
github: https://github.com/buds-lab/energystar-plus-plus
importance: 1
---

Building energy performance benchmarking has been adopted widely in the USA and Canada through the Energy Star Portfolio Manager platform. Building operations and energy management professionals have long used this simple 1–100 score to understand how their building compares to its peers. This single number is easy to use but is created by potentially inaccurate multiple linear regression (MLR) models and lacks much further information about why a building achieves that score. This paper proposes a methodology that enhances the existing Energy Star calculation method by increasing accuracy and providing additional model output processing to help explain why a building is achieving a particular score. Two new prediction models were proposed and tested: multiple linear regression with feature interactions (MLRi) and gradient boosted trees (GBT). Both models performed better than a baseline Energy Star MLR model as well as four baseline models from previous benchmarking studies. This paper shows that for six building types, on average, the third-order MLRi models achieved a 4.9% increase in adjusted R-squared and a 7.0% decrease in normalized root mean squared error (NRMSE) over the baseline MLR model. More substantially, the most accurate GBT models, on average, achieved a 24.9% increase in adjusted R-squared and a 13.7% decrease in NMRSE against the baseline MLR model. In addition, a set of techniques was developed to help determine which factors most influence a building’s energy use versus its peers using SHapley Additive exPlanation (SHAP) values. The SHAP force visualization, in particular, offered an accessible overview of the aspects of the building that influenced the score that even non-technical users can interpret. This methodology was tested on the 2012 Commercial Building Energy Consumption Survey (CBECS)(1,812 buildings) and public data sets from the energy disclosure programs of New York City (11,131 buildings) and Seattle (2,073 buildings).

Highlights
 - More accurate and explanatory models are proposed for building energy benchmarking.
 - A gradient boosted model shows a 13.7% decrease in error over Energy Star.
 - The first use of explanatory methods (XAI) in energy use benchmarking.
 - Application to over 15,000 buildings and released the code as open-source.