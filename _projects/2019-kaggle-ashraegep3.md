---
layout: page
title: ASHRAE - Great Energy Predictor III
description: A Kaggle competition to generate crowd-sourced energy prediction models.
github: https://github.com/buds-lab/ashrae-great-energy-predictor-3-overview-analysis
importance: 1
---

In late 2019, ASHRAE hosted the Great Energy Predictor III (GEPIII) machine learning competition on the Kaggle platform. This launch marked the third energy prediction competition from ASHRAE and the first since the mid-1990s. In this updated version, the competitors were provided with over 20 million points of training data from 2,380 energy meters collected for 1,448 buildings from 16 sources. This competition’s overall objective was to find the most accurate modeling solutions for the prediction of over 41 million private and public test data points. The competition had 4,370 participants, split across 3,614 teams from 94 countries who submitted 39,403 predictions. In addition to the top five winning workflows, the competitors publicly shared 415 reproducible online machine learning workflow examples (notebooks), including over 40 additional, full solutions. The most popular and accurate machine learning workflows used large ensembles of mostly gradient boosting tree models, such as LightGBM. Similar to the first predictor competition, preprocessing of the data sets emerged as a key differentiator.

<!-- I am one of the core members of the  technical committee and co-led the data preparation and model prototyping process, and validated the winning solutions.-->

**Competition website:** [Kaggle](https://www.kaggle.com/c/ashrae-energy-prediction){:target="_blank" rel="noopener"}<br>
**Code:** [Overview of analysis of data about the competition](https://github.com/buds-lab/ashrae-great-energy-predictor-3-overview-analysis){:target="_blank" rel="noopener"} and [Top 5 winning solutions](https://github.com/buds-lab/ashrae-great-energy-predictor-3-solution-analysis){:target="_blank" rel="noopener"}<br>
**Dataset:** [The Building Data Genome 2 (BDG2) - extended version](https://github.com/buds-lab/building-data-genome-project-2){:target="_blank" rel="noopener"}<br>
**Video:** [An overview of the competition from the ASHRAE 2020 Online Conference](https://www.youtube.com/watch?v=xqtBVy5cZgA&feature=youtu.be){:target="_blank" rel="noopener"}

**Publications:** 
<div class="publications">
  {% bibliography -f papers -q @*[title=The ASHRAE Great Energy Predictor III competition: Overview and results]* %}
  {% bibliography -f papers -q @*[title=The Building Data Genome Project 2: Hourly energy meter data from the ASHRAE Great Energy Predictor III competition]* %}
</div>


