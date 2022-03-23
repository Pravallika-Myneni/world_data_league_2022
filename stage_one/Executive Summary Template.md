# World Data League 2022

3. ✏️ Write your executive summary - make sure you write to a non-technical crowd. You can refer to images that are in the Submission Notebook.

## 🎯 Challenge
**Predict Waste Production for its Reduction**

## 👥 Authors
Include all the authors that have worked on this submission. It is not obligatory to include all the team members if not everyone has worked on it. This will not impact the evaluation in any way.
* Nicholas Sistovaris
* Sai Pravallika Myneni
* Wiem Borchani
* Neha Shaah

## ✨ Introduction (250 words max)
In today’s time, we have pressures to minimize the carbon footprint and other environmental effects caused by their businesses – Waste management and disposal is one of the most important issues for them. In today’s world, waste management and disposal is a big challenge not only for the industries, but also for the communities in general. It is not an issue restricted to any particular region or country, but is a global challenge across countries and continents. The challenge is real as increase in global population and commercial activity is only likely to increase in waste. Globally, various governments and businesses are working to find innovative ways to minimize the waste generation as well as to find and implement effective and efficient ways of waste disposal; recycling is one of the effective and widely adopted methods.

Estimation of the waste production is for the successful planning of efficient waste management system, their further sustainable development and optimization.

## 🔢 Data (250 words max)
We started with the Austin garbage collection data that was provided with the challenge. Through over literature survey we found that it would be wise to include weather and air pollution data in our analysis. The pollution data that we have is pm25 numbers while weather data includes information about temperatures, wind and precipation. We also used open street map data for our analysis. It would be great to see the geographic co-ordinates mapped and also include block wise census data to further support our analysis. We have grouped the data for each week as we got to know from locals that major waste management operations happen weekly. Also we focused on the years 2014-2019 (the pre-covid years) for our analysis. We also wanted to understand the impact of holidays on waste generation, we used Holidays python library. 

## 🧮 Methods and Techniques (250 words max)
We started by performing data analysis to understand the given data. 
Data Analysis Steps:
 * 1
 * 2
 * 
For forcasting the weekly waste generated (load weight) we have used the time series analysis and forecasting algorithm ARIMA. We have also tried a few regression techniques, relatively ARIMA performed better based on the evaluation metric Mean Absolute Error. 

## 💡 Main Insights (300 words max)
Explain what you discovered from addressing this problem, such as interesting facts or statistics.
1. 1
2. 

## 🛠️ Product
### Definition
A dashboard that assists in forecasting the load weights for various types of garbage across the city of Austin

### Users
Waste managers or garbage collectors use the dashboard when planning a trip to collect garbage from various sites. The truck type can be selected based on the estimated load weight and type of waste. 

### Activities
* Predicts the load weight for a given day at a given site
* Suggests a truck type for garbage collection for a given site

### Output
Describe what the product outputs to the users and how it does that. You can add mockups and/or visualisations.
Example: Location of the accident on a map and suggest the fastest route from the dispatch centre.

## 🌍 Social Impact Measurement
### Outcome
If the outputs are your immediate results, describe your long-term results. What do you want your product to achieve? What ''good'' are you creating?
Example: To decrease response time from dispatchers so that people in urgent need receive help faster.

### Impact Metrics
From the outcome, define **2 to 4 metrics** that measure if you are achieving that outcome or not.
Example:
* Average Dispatch Time
* Average Distance from Accident Location and Dispatch Center

### Impact Measurement
Since you cannot wait to see the impact of your product, estimate it. You can do that by either using the estimations/predictions of your model, market research, products from proxy industries and/or similar locations, etc.

Example:
* *Based on model predictions*: Our model estimates a decrease of 6 minutes of the average dispatch time and a decrease of the average distance of 200 meters
* *Based on proxy products*: Similar studies in other cities show that the dispatch time can be decreased by as much as 13 minutes, depending on the traffic intensity of that city.
