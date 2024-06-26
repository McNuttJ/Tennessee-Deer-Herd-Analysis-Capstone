# Tennessee Deer Harvest Analysis
## Table of Contents
* [Motivation](#motivation)
* [Technologies](#technologies)
* [Problems & Hurdles](#problems--hurdles)
  * [Getting the Data](#getting-the-data)
  * [Hurdles](#hurdles)
* [Link to Dashboard](#link-to-dashboard)

## Motivation
#### My motivation for this project comes from my love of deer hunting, animal conservation, and the great outdoors. I was not introduced to hunting until my mid twenties, and until that time I knew little about wildlife and conservation efforts. One-hundred percent of hunting and fishing license fees go to support wildlife conservation in Tennessee. This includes things such as habitat restoration, population monitoring and research to maintain healthy wildlife populations. 

#### My project therefore is intended to analyze the past 10 years of data on deer harvest numbers for Tennessee and to provide an exploratory dashboard on the information collected and reviewed.

## Technologies
#### For this project, I chose to use Python 3 within a Jupyter Notebook. The harvest data was obtained from the Tennessee Wildlife Resources Agency with their "Hunter's Toolbox" data page found at https://hunterstoolbox.gooutdoorstennessee.com/?reportId=180 and had specifically deer harvest information available. I also obtained licensing data from a data page created by the U.S. Fish & Wildlife Service that partnered with the Wildlife & Sport Fish Restoration Program: https://partnerwithapayer.org/funding-sources/

#### To visualize the cleaned data, Tableau was used to create a dashboard tool that also functions as presentation slides.

## Problems & Hurdles
### Getting the Data
#### The first problem I ran into was collecting the data for deer harvest information. It is readily available but only by selecting date ranges. This would seem simple, but if selecting dates from 2013 to 2023, it summarized the data and did not have a year category. In order to ensure accurate numbers for each year, separate csv files needed be exported based on a date range of July 1 to June 30th of the following year, for each year between 2013 and 2023.

#### Once pulled into Python I was able to add a 'Season' column for each year on each file and then merge the data together. 

### Hurdles
#### The second problem I encountered was handling incomplete data and . Some counties had total harvest numbers but had incomplete inputs for the types. Luckily it was just one type missing and a simple calculation was used to determine the needed number. Then it was a matter of manually inputting the information to complete the equation. 

#### The last problem I encountered was insufficient data from a data source that I thought could provide impactful insight. In the last 10 years, Chronic Wasting Disease (CWD) has been detected in Tennessee deer herds. I hypothesize that CWD may have an affect on the deer herd and harvest numbers; however, the data available on CWD prevalance is insufficient to draw conclusions from or determine meaningful relationships. Information was on this subject has only been substantially collected for 2023. I believe as more data is collected that this could be an important metric to measure against harvest numbers.

## Link to Dashboard
#### https://public.tableau.com/shared/5RYMFTT79?:display_count=n&:origin=viz_share_link
