# Bikeshare capstone case study

## Project Summary
#### For my capstone project, I am analyzing a bikeshare dataset to understand how casual riders use the service compared to the annual members. The goal is to explore how their riding habits differ so the company can make better decisions about marketing, user experience, and ways to encourage more casual riders to become members. Since I’m still developing my skills, this project also gives me a chance to practice working with real data and applying what I’ve learned.

## Dataset Source
#### The dataset comes from a bikeshare company’s public trip data, which includes details about individual rides. Each record contains information such as trip start and end times, ride duration, starting and ending stations, and rider type (casual or member). It’s commonly used for learning because it’s realistic, large, and gives a good look at how people use shared transportation.

## Tools Used for Analysis
#### For this project, I decided to use R as my main tool. Since the dataset was very large, R made it easier for me to import all the files, clean the data, and run my summaries without everything freezing or crashing. I’m still a beginner, but I’ve been learning R through my coursework, and this project helped me practice a lot of those skills. I used R for tasks like combining the monthly trip files, fixing missing or incorrect values, creating summary tables, and making my visualizations. Using one tool also helped me stay organized and really understand each step instead of switching back and forth between different programs

## Steps I’m Taking
#### Here are the main steps I’m following in my analysis:
### Define the Business Question
#### The company wants to know: How do casual riders use bikes differently than members?

### Explore the Data
#### I review the structure of the dataset, check column types, and look at basic stats like total rides, average ride length, and the ratio of casual vs. member trips.

### Clean the Data
#### I check for missing values, incorrect timestamps, or rides with zero or negative duration. I also remove or fix any entries that don’t make sense. I also take note of the time range included in the files I imported so I understand which months and years are part of my analysis. This step was important because the large dataset had a lot of small issues that needed to be fixed before I could trust the results.

### Prepare the Data for Analysis
#### I organize the data so I can compare the two rider groups. This includes creating new columns (like day of the week or hour of the day), calculating ride lengths, and grouping the data by category. I also verified that the cleaned dataset was saved correctly so I can reuse it later without redoing all the steps.




### Analyze Usage Patterns
#### I look for differences between casual riders and members, such as:
#### When they ride (weekday vs. weekend)
#### How long their rides last
#### What times of day they use the bikes
#### I also plan to explore seasonal patterns or trends across different months as a possible next step.

### Build Visualizations
#### I create charts and tables, to help show the differences clearly. These visualizations help make the patterns easier to explain and share.

### Summarize Insights
#### I explain the main patterns I found and suggest how the company can use those insights to attract more members or improve the service. I may add more insights later as I create additional charts or test new comparisons.

