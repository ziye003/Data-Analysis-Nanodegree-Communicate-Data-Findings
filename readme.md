# Data-Analysis-Nanodegree-Communicate-Data-Findings
### Project details
This project is divided into two major parts. In the first part, I will conduct an exploratory data analysis on a dataset. I will use Python data science and data visualization libraries to explore the dataset’s variables and understand the data’s structure, oddities, patterns and relationships. The analysis in this part should be structured, going from simple univariate relationships up through multivariate relationships, but it does not need to be clean or perfect. There is no one single answer that needs to come out of a given dataset. This part of the project is your opportunity to ask questions of the data and make your own discoveries. It’s important to keep in mind that sometimes exploration can lead to dead ends, and that it can take multiple steps to dig down to what you’re truly looking for. Be patient with your steps, document your work carefully, and be thorough in the perspective that you choose to take with your dataset.

In the second part, I will take your main findings from your exploration and convey them to others through an explanatory analysis. To this end, you will create a slide deck that leverages polished, explanatory visualizations to communicate your results. This part of the project should make heavy use of the first part of the project. Select one or two major paths in your exploration, choose relevant visualizations along that path, and then polish them to construct a story for your readers to understand what you found. (Modified from the project details from Udacity project requirement)

#### Step 1.1: Choose your Dataset
The FordGoBike System Dataset is chosen for this data. This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco
Bay area

#### Step 1.3: Explore Your Data
It’s time to get to the interesting bits. Explore your data and document your findings in a report. The report should briefly introduce the dataset, then systematically walk through the points of exploration that you conducted. You should have headers and text that organize your thoughts and findings. Visualizations in this part of the project need not be completely polished: this is just your own exploration at this point. However, you should still make sure that you adhere to principles of using appropriate plot types and encodings so that accurate conclusions can be drawn, and that you have enough comments and labeling so that when you return to your work, you can quickly grasp your analysis steps.

#### Step 2.1: Document your Story
At the end of your exploration, you probably have a bunch of things that you’ve discovered. Now it’s time to organize your findings and select a story that you will convey to others. In your readme document, you should summarize your main findings and reflect on the steps you took in your data exploration. You should also lay out the key insights that you want to convey in your explanatory report as well as any changes to visualizations, or note new visualizations that will be created to bridge between your insights.

#### Step 2.2: Create your Slide Deck
Follow the plans you laid out in the previous step and create a slide deck with explanatory data visualizations to tell a story about the data you explored. You can start with code that you used in your exploration, but you should make sure that the code is revised so that your plots are polished. Make sure that you also pay attention to aspects of design integrity in your revisions.

### Main findings
The average time for a trip is 11.2 minutes while the longest trip took 1402 minutes. However, majority of trips took less than 10 minutes. As for starting time of the trip, 8:00 and 17:00 are the time with the most trips.

Thursday is the day with the highest number pf trips, followed by Tuesday. Weekends have the least number of trips. The multivariate exploration strengthened some findings about duration and daily usage in univariate and bivariant explorations, for example, the two time spans with high usage of bikes, which are 7:00-9:00 and 16:00 - 18:00. However, multivariant analysis also revealed that this is only valid from Monday to Friday. For week ends, the usage reduce significantly at those two time spans. 

Also, there is moderate but consistend bike usage from 10:00 to 15:00 everyday throughout the week, which was not found in previous analysis. There are many trips that is at the duration below 30 mins occured at the two peak hour of day, 7:00-9:00 and 16:00 - 18:00. Not many trips for any durations from 0:00 - 5:00. 


### Key insights
The distribution of duration in minutes is a skewed distribution that has a longer tail in the right section.

The bike usage pattern for weekdays and weekends are very different and should be analyzed seperately. The difference in pattern could result from different purpose of usage, but this hypothesis would require more data and furthere analysis (such as if the bike usage occured at CBD or countryside) to back up.

Bike usage in the peak hours are mostly short trips, while longer trips, such as 2hr-5hr trips, occurs constantly throughtout the day regardless of time.


```python

```
