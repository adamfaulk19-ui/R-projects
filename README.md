# R Data Analytics Portfolio

This repository contains data analytics projects completed using R, with a focus on data cleaning, exploratory data analysis, statistical modeling, visualization, and sports analytics.

## Projects

### ⚾ MLB Trade Deadline Analysis — 2023 Baltimore Orioles

**Question:** How could the Baltimore Orioles use data to identify roster weaknesses and potential trade targets at the 2023 MLB trade deadline?

Using MLB data accessed through the `baseballr` package, I analyzed the Orioles' offensive performance leading up to the 2023 trade deadline. I compared player and team performance against league averages, examined offensive production by batting handedness, and developed a process for identifying potential trade targets.

**Skills demonstrated**

* Data acquisition with `baseballr`
* Data cleaning and filtering
* `dplyr` / `tidyverse`
* Exploratory data analysis
* Statistical calculations
* Data visualization with `ggplot2`
* Translating statistical findings into organizational decisions

**Key analysis**

* Compared Orioles hitters against the 2023 MLB league-average OPS
* Evaluated offensive production by batting handedness
* Identified right-handed hitting as an area for potential improvement
* Filtered potential trade targets based on offensive performance and playing time
* Evaluated potential acquisitions based on team and contract circumstances

[View the full analysis](./MLB_final_project.Rmd)

---

### 🏥 Emergency Room Performance by State

**Question:** Are states with longer average emergency-room wait times also less effective in delivering time-sensitive care?

Using the 2025 TidyTuesday "Timely and Effective Care by US State" dataset, I cleaned and analyzed state-level emergency-room performance data. I examined geographic variation in wait times, compared different types of emergency-room care, and tested the relationship between average ER wait times and the percentage of stroke patients receiving results within 45 minutes.

**Skills demonstrated**

* Data cleaning and tidying
* Exploratory data analysis
* Geographic visualization
* `dplyr` / `tidyverse`
* `ggplot2`
* Correlation analysis
* Linear regression
* Communicating statistical findings

**Key analysis**

* Compared average ER wait times across U.S. states
* Created geographic visualizations of state-level performance
* Examined mental-health and stroke-related ER performance
* Tested the relationship between average ER wait times and timely stroke results
* Used correlation and linear regression to quantify the relationship between the two measures

[View the full analysis](./finalproject.qmd)

