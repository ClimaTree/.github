# Mapping Tree Species Drought Sensitivity Under Climate Change
## Introduction :deciduous_tree:
The ClimaTree project is a [Masters in Environmental Data Science capstone project](https://bren.ucsb.edu/projects?f%5B0%5D=project-program%3A63) at the Bren School of Environmental Science & Management (UCSB)

Faculty Advisor and Client: [Dr. Joan Dudney](https://joandudney.com)

The team consists of [Rosemary Juarez](https://github.com/rosemaryjuarez), [Briana Barajas](https://github.com/briana-barajas), [Fletcher McConnell](https://github.com/fletcher-m) and [Vanessa Salgado](https://github.com/Vanessa-Salgado). 

Primary Contributor / Client: Dr. Joan Dudney 

Other Contributors: Dr. Robert Heilmeyer, Dr. Frances C. Moore

## Project Summary :evergreen_tree:
Forests cover approximately 30% of Earth’s land surface, absorb more carbon than all other terrestrial ecosystems, and provide trillions of dollars’ worth of ecosystem services. However, these crucial ecosystems are becoming increasingly vulnerable to a changing climate. Though many studies document higher drought sensitivity in drier regions, some studies suggest trees may be even more drought sensitive in wet regions. To reconcile these contradictory results, this capstone project conducted a species-level sensitivity analysis to test whether there is strong variation in tree vulnerability to climate change across species’ ranges. Specifically, the capstone team used spatial analysis to map and assess the sensitivity of the 26 most dominant tree species in the International Tree-Ring Databank. The species-specific maps displayed tree sensitivity to declines in water availability (using climatic water deficit). They developed a shiny app that combined this information on an easily accessible and user-friendly platform. These deliverables will help public and private stakeholders identify species and regions of highest risk so that they can develop the most effective conservation and management strategies.



## Project Objective :seedling:
The objective of this project is to generate species-level sensitivity maps for most sampled (ITRDB) and threatened tree species that capture exposure and sensitivity to illustrate spatial variation in response to climate change. This project utilized processed versions of these data sets, provided by the client Dr. Joan Dudney. The processed data is not yet available publicly, as it is being used in ongoing research. For more information on the processing of the initial data, please contact Dr. Joan Dudney.
 

Project Goals:
* Design a new workflow from a global to species level analysist to analyze sensitivity of trees to decreased water availability 🗺️  
* Create accurate risk maps for vulnerable species of trees :earth_americas:
* Develop an interactive dashboard using R-Shiny app that summarizes our findings on an easily accessible and user-friendly platform :computer:


## Organization Structure

**climatree-mapping-repo**

contains project scripts to process and calculate sensitivity. For more information, visit our [repo's README.md.](https://github.com/ClimaTree/climatree-mapping-repo) 

**Climatree-shiny-dev**

contains dashboard scripts needed to run our outputs: mapping sensitivity. For more information, visit our [repo's README.md.](https://github.com/ClimaTree/climatree-shiny-dev)

```
your-organization/
├── climatree-mapping-repo
│   ├── main.R
│   ├── 1_climate_niche.R
│   ├── 2_plot_level_regressions.R
│   ├── 3_run_regressions.R
│   ├── 4_sens_predictions.R
│   ├── 5_mapping.R
│   └── create_top_species.R
└── climatree-shiny-dev
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
