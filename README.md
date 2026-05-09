# Birth Defects in Minnesota: Data Analysis Project

This repository contains the data and code for STAT/COMP 212's final project. This analysis explores how maternal characteristics, socioeconomic status, and food policy shape the birth defect outcomes in Minnesota. 


Using data from the [Minnesota Department of Health](https://mndata.web.health.state.mn.us/birth_defects/messaging_pre.html), we examine birth defect prevalence across race/ethnicity, education, and poverty levels. We also evaluate the impact of the FDA's 1998 folic acid grain fortification policy and its effect on Neural Tube Defect (NTD) rates over time.


## Repository Structure
- `index.qmd` contains the clean, complete code for our final report
- `data` subdirectory contains the raw data, accessed from the MDH on 4-21-2026
- `appx/proposal` is our initial plan and proposal for this project
- `appx/case-study` is our analysis of a Pudding article
- `eda` subdirectory contains our individual explorations and analyses of the data


### How to Use
1.  Install R and RStudio.
2. Clone this repository to your machine, find it in your file navigation systems, and open it by selecting the **project** file.
3. In the packages tab, navigate to 'Restore' to **restore** the packages from the virtual environment.
4. Open and run the code in **index.qmd.**


### Expected Output
Running `index.qmd` will generate an HTML report with the following visualizations:
- **Bar chart** of overall birth defect prevalence by types
- **Dot plot** of folic acid supplementation rates by education and poverty levels
- **Stacked bar chart** of birth defect prevalence by race/ethnicity and defect types
- **Line chart** of NTD prevalence pre- and post- 1998 fortification over time by race


### Software Requirements
- R 4.2.2
- RStudio 2026.01.0+392.

***
**Contributors**: [@samjkenney](https://github.com/samjkenney), [@sssuweda](https://github.com/sssuweda), [@yeshedj](https://github.com/yeshedj)
