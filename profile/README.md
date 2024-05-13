## Introduction :deciduous_tree:
The ClimaTree project is a Masters in Environmental Data Science capstone project at the Bren School of Environmental Science & Management (UCSB)

Faculty Advisor and Client: [Dr. Joan Dudney](https://joandudney.com)

The team consists of [Rosemary Juarez](https://github.com/rosemaryjuarez), [Briana Barajas](https://github.com/briana-barajas), [Fletcher McConnell](https://github.com/fletcher-m) and [Vanessa Salgado](https://github.com/Vanessa-Salgado). 

Primary Contributor / Client: Dr. Joan Dudney 

Other Contributors: Dr. Robert Heilmeyer, Dr. Frances C. Moore

## Project Summary :evergreen_tree:
Forests cover approximately 30% of Earth’s land surface, absorb more carbon than all other terrestrial ecosystems, and provide trillions of dollars’ worth of ecosystem services. However, these crucial ecosystems are becoming increasingly vulnerable to a changing climate. A widespread assumption underlying the mapping of forest vulnerability has been that forests are most sensitive to drought and climate change in hot, dry regions. New data contradicts this assumption and suggests that forests in regions of a mild climate may be the most vulnerable to climate change. This could mean that current global vegetation models greatly underestimate the effects of climate change on forests. Furthermore, current research has largely been done on a global, aggregate scale. Althought this is helpful for so many ways, it is not particularly helpful for land managers to use for decision-making. Through this project, the capstone team will use spatial analysis to map and assess the validity of the two hypotheses, both among distinct species and within each species range. We created two types of maps: one to display tree sensitivity to water availability and the other to predict future tree growth, given predicted changes in water availability. We developed a shiny app that combines this information on an easily accessible and user-friendly platform. These deliverables will help public and private stakeholders identify species and regions of highest risk so that they can develop the most effective conservation and management strategies. 


## Project Objective :seedling:
The objective of this project is to generate species-level sensitivity and vulnerability maps for most sampled (ITRDB) and threatened tree species that capture exposure and sensitivity to illustrate adaptive and spatial variation in response to climate change and predict future tree growth. 

Our initial goals:
* Design a new workflow from a global to species level analysist to analyze sensitivity and vulnerability of trees to decreased water availability  
* Create accurate risk maps for vulnerable species of trees :earth_americas:
* Develop a shiny app that summarizes our findings on an easily accessible and user-friendly platform :computer:

## Repository Structure
```
ClimaTree
├── climatree_mapping_repository
│   ├── 1_climate_niche.R
│   ├── 2_plot_level_regression.R
│   ├── 3_run_regressions.R
│   ├── 4_sens_predictions.R
│   ├── 5_mapping.R
│   ├── main.R
│   └── prep_scripts
│       ├── 2_spp_list.R
│       └── create_top_species.R
└── climatree-shiny-dev
    └── shinydashboard
        ├── global.R
        ├── server.R
        └── ui.R
```



















<!---
Directions:
Update GitHub organization & team management plan
Update:

Your GitHub organization’s landing page to include the project summary you submitted a on week 2. 

Delete all the repositories, issues, and projects from today’s demo sessions.

Your team management plan sections V and VI to include the GitHub tools we covered today (if your team will use them - highly encouraged!).

Create a skeleton of repositories, some issues and milestones, and a project to track the bigger steps of your Approach & Methods section.
-->
