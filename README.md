# Best Date to Find Chicken of the Woods Mushroom!
![Example Image](Chicken_of_the_Woods_Pic.jpeg)

The above photo was taken by me earlier in 2024 in Rockland County New York, United States. This project helps determine the date with the highest expected number of Chicken of the Woods observations among states with prior observation records on iNaturalist. The key findings are summarized in the below graphic.

![Key_Findings](Best_Date_plot_cropped.jpg)

The below gif helps to visualize all observations of Chicken of the Woods mushrooms made between January 1st, 2010 and December 31st, 2023 based on the day of the year they were observed.

![Key_Findings](ChickenOfTheWoods_weekly.gif)

## DATA SETS:
* **L_cincinnatus_observations.csv**: Observations of *Laetiporus cincinnatus* in the United States occuring prior to January 1st, 2024, queried from iNaturalist.
* **L_conifericola_observations.csv**: Observations of *L. conifericola* in the United States occuring prior to January 1st, 2024, queried from iNaturalist.
* **L_gilbertsonii_observations.csv**: Observations of *L. gilbertsonii* in the United States occuring prior to January 1st, 2024, queried from iNaturalist.
* **L_sulphureus_observations.csv**: Observations of *L. sulphureus* in the United States occuring prior to January 1st, 2024, queried from iNaturalist.
  * For a complete description of all the variables included visit [iNaturalist's](https://www.inaturalist.org/home) download options. Otherwise, variables of interest that were used in this analysis are described within the R Markdown file described below.

## ANALYTIC FILES:
**Chicken_of_the_Woods_Analysis.Rmd**: The R Markdown file containing all the code to reproduce the results in the analysis.

## RESULTS:
**ChickenOfTheWoods_weekly.gif**: A gif visualizing the distribution of aggregated Chicken of the Woods observations per week over the course of the year.
