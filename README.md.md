# (FordGo Bike Trips Data)
## by (Ishola Abdulquadri)


## Dataset

> The dataset used is for the FordGo bike business. It includes records of bike trips by users for the month of February and includes 183,412 records and 16 columns. 

> Some data wrangling steps were done on the raw dataset. The datatype of the start_time and end_time were converted to datetime, afterwards, the age of the user in every record was calculated by substracting the member_birth_year from the most recent year. 
Also, a 'day' column was created to carry the dayname of each record and the duration of every trip was converted from seconds to minutes.
Additionally, a integer variable in the form (0 or 1) was created to represent weekdays or weekends
Afterwards, I dropped unused columns from the dataset to avoid distractions while analysing.

## Summary of Findings

> After the wrangling and exploratory visualization of the dataset, the following were observed:

• The distribution of trip durations is normal on the logarithmic scale with modal duration at around 5-7 minutes.

• The modal age of users is in the range of 28-38.

• There are more subscribers 91% than there are customers. There are also more males 76% than females 24%.

• The number of trips in the weekends falls sharply compared to weekdays.

• However, the hourly rides becomes significant during the rush hours (6am - 10am) and (4pm - 7pm). This shows bike rides increases during hours when people commute to work and retun home.

• Customers tend to take longer duration on a single ride than subscribers.

• There does not appear to be any significant difference in the duration spent by users during the weekend against weekdays. Although, more bike trips are taken during the weekdays than weekends.

• Females are more likely to be customers than subscribers.

• The usage pattern by subscribers reduces during the weekend while the usage pattern by customers stays mostly unchanged.

• Subscribers seem to use bikes more during the rushing hours (6am - 10am) and beyond 5pm. While customers use bikes more from the mid-day until rushing hours in the evening.

• Female customers tend to take longer duration per trip than any other user category.Summarize all of your findings from your exploration here, whether you plan on bringing them into your explanatory presentation or not.


## Key Insights for Presentation

> The main features of interest are related to the user demographic and usage patter. The key insights from the visualizations are:

- Most users are between their late 20s and late 30s. Specifically, between the ages of 28 and 38.
- Customers tend to spend longer duration on trips than Subscribers.
- Although, male users are dominant, female users tend to spend longer on trips.
- There are more bike trips during rushing hours (6am - 10am & 5pm - 10pm) than other times and on weekdays than weekends
