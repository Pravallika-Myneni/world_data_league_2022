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
Provide a contextualization of the problem, together with an estimation of its size using real numbers and references.


## 🔢 Data (250 words max)
Explain what data you used (both provided by WDL and external) and improvements you suggest to those datasets. Explain how those improvements would lead to a better solution.
We started with the Austin garbage collection data that was provided with the challenge. Through over literature survey we found that it would be wise to include weather and air pollution data in our analysis. The pollution data that we have is pm25 numbers while weather data includes information about temperatures, wind and precipation. We also used open street map data for our analysis. It would be great to see the geographic co-ordinates mapped and also include block wise census data to further support our analysis

## 🧮 Methods and Techniques (250 words max)
We have used various EDA techniques to look for insights through the data. For forcasting the load weight we have used the ARIMA algorithm. This algorithm uses the available time series data and prediscts Load Weight. 

## 💡 Main Insights (300 words max)
Explain what you discovered from addressing this problem, such as interesting facts or statistics.
*Write here*

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
