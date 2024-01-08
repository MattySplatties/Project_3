#  Project 3: Most Winningest Cities in Sports

# Background
The aim of our project is to see if the success of local sports teams impacts the economy of that metropolitan area. We’ll examine the relationship between the percent gain/loss winnings year over year in the top five cities and bottom five cities and the economy in that area, from 2001-2018. We also compared the percentage gain/loss winnings to the labor productivity, as well as, per capita.

# Software/Tools:
* Python
* Bokeh
* Pandas
* Excel
* SQL Alchemy
* GitHub
* Numpy

# Instructions
This assignment is broken down into the following tasks:

# Prepare the Data
1. Gather the data. Data Sources:
   * https://www.kaggle.com/datasets/thedevastator/winningest-cities-in-sports/
   * https://salarysport.com/
   * https://stats.oecd.org/Index.aspx?datasetcode=FUA_CITY
   * https://www.statista.com/topics/963/national-football-league/#topicOverview
   * https://stathead.com/all/
   * https://www.openintro.org/data/index.php?data=mlb_teams 

2. Clean the Data both in Excel, Python, and SQL Alchemy.
In (project_3.ipynb):
![FinalGDPhead](https://github.com/MattySplatties/Project_3/assets/136475202/237cb0b5-8989-4f58-8d68-b8428ec3ad04)

![FinalLabor](https://github.com/MattySplatties/Project_3/assets/136475202/53b429a0-c996-448f-b1e3-7db60ff82547)

![FinalLaborProductdf](https://github.com/MattySplatties/Project_3/assets/136475202/963c2404-e621-45cc-9841-b242bb587484)

3. Determine the top five cities and bottom five cities we would focus on based on the average win percentage for each city:
   
![TopBottom](https://github.com/MattySplatties/Project_3/assets/136475202/1480ab35-15e8-4d88-8afc-78871d688873)

# Data Visulizations
   * Top left represents the Win Rate
   * Top Right represents the Employment
   * Bottom left represents the Labor Productivity
   * Bottom right represents the GDP Change
     
1. Here are the four visualizations for Charlotte, which was one of our top five winning percentages.

![Web capture_7-1-2024_204223_](https://github.com/MattySplatties/Project_3/assets/136475202/4a6a2d20-79fb-4041-9208-ad9cef02a274)

Findings: We chose to focus on Charlotte due to the constant change in win and loss percentages YoY. This allowed us to see if there was any relationship with the other three graphs (Employment, Labor Productivity, and GDP Change). There does seem to be some sort of correlation as the win percentage goes down th Labor Productivity and GDP Change looks to mirror this, as well as, when the win percentage raises.
 
2. Here are the four visualizations for San Antonio, which was one of our bottom five winning percentages. 

![Web capture_7-1-2024_204924_](https://github.com/MattySplatties/Project_3/assets/101214487/510c36d2-bfaf-4a2d-99a9-86c6908df8e5)

Findings: 

3. Here are the four visualizations for Sacramento, which was one of our bottom five winning percentages.

![Web capture_7-1-2024_205223_](https://github.com/MattySplatties/Project_3/assets/101214487/3bdfaf56-6fa1-4bbc-b92b-00ffbdfd27d1)

Findings: 


# References
* color https://docs.bokeh.org/en/latest/docs/examples/basic/data/linear_cmap_colorbar.html
* multiplots https://docs.bokeh.org/en/2.4.1/docs/gallery/anscombe.html https://docs.bokeh.org/en/latest/docs/user_guide/interaction/linking.html#ug-interaction-linked <= Good refences for linking multiplots
* Bars https://docs.bokeh.org/en/latest/docs/examples/basic/bars/nested_colormapped.html https://docs.bokeh.org/en/latest/docs/user_guide/basic/bars.html
* Arrows https://docs.bokeh.org/en/latest/docs/examples/basic/annotations/arrow.html#index-0 https://docs.bokeh.org/en/latest/docs/user_guide/basic/annotations.html <= everything about annotations (arrow and label refrence)
* Marker Shapes https://docs.bokeh.org/en/latest/docs/examples/basic/data/transform_markers.html
* Legends https://docs.bokeh.org/en/latest/docs/examples/models/legends.html
