# Environmental Justice in LA: Lasting impacts of redlining

A workflow investigating the impact of historical redlining in the city of Los Angeles on environmental (in)justice and the location and frequency of reported bird biodiversity observations. 

- Use EJScreen data to map current environmental and demographic indicators in LA
- Compare current conditions across census block groups in LA that were historically redlined
- Compare percent of reported bird observations across areas in LA that were historically redlined

## What's in this repo?
```
.
|
├── Outputs/                           # visualizations and tables that the workflow should output if working correctly
|  └── la_wastewater_discharge.png     # map of LA wastewater discharge by census block group, centroids indicating groups over 85th percentile
|  └── la_holc_census_block_grps.png   # map of LA census block groups within areas that were historically redlined with HOLC grades
|  └── la_current_conditions_tbl.png   # table comparing current environmental and demographic indicators across HOLC grades
|  └── bird_obs_by_holc_grade.png      # plot visualizing the percent of reported bird observations by HOLC grade
|
├── R/                                   # folder for code used in workflow
|  └── redlining-biodiveristy-obs.rmd    # a R markdown containing background and workflow
|  └── redlning-biodiveristy-obs.html    # R markdown knitted to html
|
├── README.md
├── .gitignore
└── redlining-biodiveristy-obs.Rproj
```
## Data access

EJScreen and bird observation data were downloaded, stored locally, and included in the .gitignore. The links and references for downloading access are included in the `redlining-biodiversity-obs.rmd`. 

Redlining data is imported via URL listed in the `redlining-biodiversity-obs.rmd`.
