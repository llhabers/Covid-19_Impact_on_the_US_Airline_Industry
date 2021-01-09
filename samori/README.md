# Team Analytics Alliance

## Samori's Project Results and Observations

### What was the impact on airlilne fare?

#### Website where Samori pulled Airfare data from: https://www.transtats.bts.gov/AverageFare/ 

##### Task:
The goal was to compare the average airfares for flights in 2019 to fligths in 2020. By posing the question I hoped to gain further insight on how the coronavirus has affected flights in 2020. 

##### Action:
To answer the question at hand, I took to the internet to find a database that has data regarding airfare. I found the bureau of transportation statistics database and their subsequent data regarding airfare. They store the data quarterly and annually dating back to 1993. My original intention was to take the annual data for 2019 and 2020. However, they do not currently have all the data for 2020, only the first two quarters. Since that was the case, the I only took the second quarter of the both 2019 and 2020, since COVID-19 only really took effect at the end of the first quarter of 2020. I only utilized the relevant data in the .csv files such as, average airline fare and airport code. 

##### Results:
After cleaning and manipulating the data, I created two bar graphs.

![Q2 Average Airfare of Top 20 US Airports](https://github.com/llhabers/data-analysis-project-1/blob/main/output_data/Q2%20average%20airfare.png)

The first graph displays the average airfare of the top 20 U.S airports in both 2019 and 2020. The blue bars represent 2019 and the orange bars represent 2020 

![Q2 Percent Change in Airfare of Top 20 US Airports](https://github.com/llhabers/data-analysis-project-1/blob/main/output_data/Q2%20Percent%20Change.png)

The second graph displays the percent change of the top 20 U.S. airports from 2019 to 2020.

##### Observations:
- Every average airline price had decereased by 15% or more.
- PHL (Philidelphia International Airport) had the greatest loss from 2019 to 2020. (-31.89%)
- FLL (Fort Lauderdale-Hollywood International Airport) had the smalles loss from 2019 to 2020. (-17.25%)
- EWR (Newark International Airport) had the highest average airfare in 2019 but fell to second in 2020. 

##### Challenges:
The challenges I faced were limiting the data to a single quarter instead of using the annual data. 