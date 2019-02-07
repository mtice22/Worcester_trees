# Introduction

My group was tasked with creating a dashboard for the Worcester Tree Inititave (WTI). They had various tree metric data for Worcster Trees:
  - Diameter at Breast Height (DBH)
  - Condition of trees (Dead, Poor, Fair, Good)
  - Tree Species 
  
With this data, our responsibility was to create a dashboard that creates visualizations for the data and tying the data to mental 
health in Worcester. Our audience was local Worcester officials and visitors to the WTI website. 

# Dashboard
## Tree Status
The WTI data included a “Status” measurement used to determine the overall health of the trees. Each tree was assigned one of the following statuses: Dead/Dying, Poor, Fair, Good. We assigned number values 1 to 4, where 1 = Dead/Dying and 4 = Good, to more easily find the mean health for each neighborhood. However, with only two neighborhoods having sufficient data, a side-by-side bar graph had a more actionable impact than simply comparing the mean health. A standard bar graph with the “Percentage of Recorded Trees” on the y-axis was created. The percentage metric is used because with 777 null data points out of 1336 trees in the “Status” metric, the data would be skewed and would not accurately represent tree health otherwise. In other words, using the percentage within each “Status” measurement creates an estimation for the entire neighborhood.

## Carbon Offset/Cost Benefit
The three most impactful tree metrics found when researching how trees affect air quality were diameter at breast height (DBH), the total number of trees in an area, and percentage of tree coverage. Since WTI’s dataset did not include any measures for tree coverage, DBH and total trees were utilized. Similar to the “Tree Status” data, Burncoat/Greendale had more than 99% null values for DBH, leading to its removal in the graph. With three different Y-axis labels of Average DBH (in), Total Trees, and Estimated Carbon Offset (tons), a bar chart would not be the best method to combine those three metrics. Therefore, by utilizing the bubble chart, each figure could stand alone and take up very little space horizontally.  
Considering the audience, however, these metrics are hollow without an explicit value. rees Atlanta is an urban forestry website with a “Carbon Offset Calculator.” This calculator uses the total number of trees to make a rough estimate of carbon offset and the corresponding cost benefit. By highlighting this, this visual will give Worcester officials a monetary value of tree benefits.
## Distribution of Tree Families
   WTI’s dataset included a “Species” metric with over 40 different tree species. This is difficult to show concisely on a dashboard. Also, WTI’s audience is not interested in the distribution of tree species, since the metric does not inspire any action. Instead, WTI provided a possible approach to display the data. Progressive guidelines suggest no more than five-percent of any given species, ten-percent of any genus, and twenty-percent from any tree family.
For each neighborhood, there were eight to ten different tree families, but a few of them were under five-percent of the total, which led to their removal in the final graphic. The five most common families were selected for display: Beech, Mallow, Pea, Rose, and Soapberry. Similar to the “Tree Status” metric, separating the three neighborhoods provided a precise measure, since each area is distinct in their tree population and has a vastly different tree family distribution. As explained by WTI, a “warning line” was placed at twenty-percent on the Y-axis to clearly display which families are exceeding the guidelines.
## Mental Health
The city of Worcester provides various online resources for mental health data. Although, the data corresponds with the entire city, or large areas of it. With three smaller neighborhoods, finding mental health data for these specific areas was a challenge. However, the 500 Cities Project did have a mental health metric for our chosen neighborhoods. The metric is called “Poor Mental Health,” which is “percentage of adults aged 18 or over with mental health not good for 14 days in 2016” (Centers for Disease Control and Prevention, 2016). 


# Programs Used
Microsoft Excel, Tableau 

# Contributors
Michael Tice, William Fitzpatrick, Adry Sanchez, Aswira Pasha, Gurpreet Singh 
