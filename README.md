# CIS-1051-Final-Project
**Title:** Mapping Heart Disease Mortality and Income Disparities in the U.S.

**Author:** Talha Farooq

**Year/Major:** Senior Biology Major at Temple University

**Overview**:

This project explores how median household income relates to heart disease mortality rates across U.S. states.
I combined public datasets from the U.S. Census Bureau and CDC WONDER and created visualizations to highlight patterns and relationships between income levels and health outcomes.
The full project was completed using R, Quarto, tidycensus, dplyr, and ggplot2.

**Process**:

- Requested and activated a Census API key to pull 2022 American Community Survey income data.
- Downloaded heart disease mortality data for 2020 from CDC WONDER.
- Cleaned and merged datasets by matching U.S. state names carefully.
- Created two choropleth maps, two histograms, and one scatterplot.
- Organized all graphs and written analysis into a Quarto project and rendered it to HTML.

**Challenges and Lessons Learned**:

Finding and downloading reliable public health data was more complicated than expected.
The CDC WONDER mortality file needed significant cleaning to separate states, codes, deaths, population counts, and mortality rates correctly.
Requesting access keys for the Census API, loading different data formats, and fixing messy text files were major hurdles.
Merging the two datasets also required careful checking so that state names matched perfectly.

This project helped me improve my data wrangling, problem-solving, and visualization skills.
I also learned how to structure a clean and readable Quarto project, how to think critically about color choices and scales, and how to make graphs that clearly show trends without being confusing.

**Final Product**:

The final deliverables include a Quarto source file, an HTML output file, a README file, and a video walkthrough.  
The video has been submitted directly to Canvas as it was to0 large a file to be uploaded to GitHub.
Also uploaded a pdf file of the rendered Quarto source code as GitHub only shows raw HTML code. This product was shown in video walkthrough, but I am uploading in case anyone wants
to take a closer look.

**Additional Note:** I am planning to continue developing this project beyond the course. As someone interested in cardiology and preparing to apply to medical school, this topic holds personal and professional importance for me. I hope to expand the analysis over time to explore more factors affecting cardiovascular health.

