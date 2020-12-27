<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Will "The Decade of Action" be enough to achieve the SDGs?
*Anna Fonte Farré*

*[Data Analytics FT, Barcelona & October 2020]*

## Content
- [Project Description](#project-description)
- [Questions & Hypotheses](#questions-hypotheses)
- [Dataset](#dataset)
- [Workflow](#workflow)
- [Organization](#organization)
- [Links](#links)

## Project Description
The 2030 Agenda is a comprehensive, universal agenda that refers to the three dimensions of sustainable development (economic, social and environmental). This global framework is based on five pillars: people, the planet, prosperity, peace and alliances, and is deployed through a system of 17 SDGs and 115 indicators, through which it is proposed to address the major global challenges, from the fight against poverty or climate change to education, health, gender equality, peace or sustainable cities. There's only 10 years left to achieve this goals, and COVID-19 may have a negative impact on the way to reach the goals. 

## Questions & Hypotheses
The main objective of the project was discovering if the goals will be achieved by 2030. To find out this, the main hypothesis was that the world won't accomplish the Agenda 2030. 

## Dataset
As noted above, the UN identified 17 SDGs. Each SDG has between 3 and 13 targets, and each target, in turn, has a number of indicators associated with it. The SDG data set is publicly available from the SDG website, from the United Nations Statistics Department. At time of writing (2020) the data set spanned an 5 year period (2015-2020). The SDG data set is relatively large, and is comprised of around 100,000 records holding statistical SDG information covering 195 countries.

## Workflow
- Firstly, some research was done in order to find interesting questions about the topic. Once the question was found, then..
- Time to search a database for the project. The one used to conduct the analysis was from the United Nations Statistics Division, with the indicators rating for each country from the years 2016-2020. 
- Then, the data cleaning and wrangling was performed. Firstly, all the indicators were renamed. Then, the performance index was calculated for each country and goal. 
- To continue, some operations were in place in order to deal with missing data. Firstly, the data was scaled using the MinMaxScaler (ScikitLearn) and the missing values were imputed using the KNN method (ScikitLearn as well). 
- Finally, analysis was conducted in order to find interesting insights about the topic, being the most important part the time series forecasting using the FBprophet model. 
- To finish, all the data was visualized in Tableau in order to make a global dashboard. 

## Organization
All the steps of the project were organized with Trello (find the link attached below). 
Regarding the repository, it contains three main folders: the first one with the data used in the project; the second contains the notebooks for data cleaning and analysis; the last folder contains the technical report as well as some images for the paper. 

## Links
[Repository](https://github.com/annafonte/Project-Week-5-Your-Own-Project/)  
[Slides](https://docs.google.com/presentation/d/13v1YLKB-K2BTzX8bjGWNbHzgZOrqpgt-bu2YmQkGxTk/edit?usp=sharing)  
[Trello](https://trello.com/b/d4oTvG2s/project-4)  
