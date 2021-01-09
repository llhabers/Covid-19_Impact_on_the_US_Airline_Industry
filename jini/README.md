# Team Analytics Alliance

## Jini's Project Results and Observations

### How has the coronavirus affected the volume of passengers between 2019 and 2020?

#### Website where the data was pulled from: - https://www.tsa.gov/coronavirus/passenger-throughput 

##### Task:
Due to the initial containment measures taken by the government, people were instructed to shelter in place and refrain from traveling. The question I posed is: how has the coronavirus affected the volume of passengers between 2019 and 2020?

##### Action:
In order to answer this question, I researched different datasets that would accurately reflect the number of passengers airlines were seeing on their flights. During the exploration process, I found data that pertained to inidividual airlines or a certain airport, which gave me only a sample of the whole picture. I was able to find a holistic dataset from the TSA website that included a csv showing the total passenger throughput in 2019 compared to 2020 from March to present day, by date. 

##### Results:
After cleaning the data, I grouped the dates by month to see how the total volume changed from March to December and also calculated the percent change between 2019 and 2020. On a micro level, I also wanted to look at some of the busiest travel days/holidays - in this case, I used December 23rd before Christmas and July 3rd before Independence Day - to analyze the differences there. 

We can see here the total volume of passengers between 2019 and 2020 from March to December using a bar chart:

![Total Volume Bar Graph](https://github.com/llhabers/data-analysis-project-1/blob/main/output_data/TSA%20Passenger%20Volume%20Across%20All%20Months.png)


This line graph shows the percent change of the volume over the same time period:

![Percent Change Line Graph](https://github.com/llhabers/data-analysis-project-1/blob/main/output_data/TSA%20Passenger%20Percent%20Change.png)



##### Observation:
- The largest deficit in passengers is seen in the months of April and May - safely assuming due to the immediate lockdown. The summertime is also one of the busiest times to travel especially for families with kids and professionals looking to take vacations, so with travel restrictions across the states (with exceptions for frontline/essential workers and quarantine rules) these numbers were severely deflated.
- We can see a steady increase in passengers mid-summer as covid numbers became more steady/decline. However this negative relationship proves the same for when covid numbers spiked in November/December, since passenger volume decreased again. This is shown in the bar graph for the total volume across the months. 
- When looking at the holidays, July 4th (Independence Day) volume was more heavily skewed than the volume for December 23rd (before Christmas). We can infer it may have to do with the restrictions surrounding capacity in homes and outdoor places. Christmas also tends to be a busier travel day as people go home to family or have vacation time in the winter. 
- The percent change line chart shows the steepest drop in April and increases vasty in May, and evens out from July to December. We can infer that it might show a slight decrease due to the spike in covid numbers in December, but with the vaccination rollout will even out again during 2021. 

##### Challenges:
The challenges I experienced were finding a holistic data set at first which showed total numbers of passenger volume verses passenger volumme for a sample of the total. I also wanted to shrink my dataset by month and add the totals for each day/date because it would be easier to analyze by month versus hundreds of dates. The dataset however only starts their passenger count from March - it would have been helpful if it started at January 1st so we could see the trend previous to when covid was detected in the US. 

