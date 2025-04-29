# Team 7 MIST Group Project 2
## Team Name - Group 7 47114
## Team Members: 
- Aritra Mullick @amullickk
- Kathy Do @kathydok
- Carter Mixon @Cartermixon99
- Mary Grace Rudd @mgrudd 
- Sanaya Mohani @sanayamohani

## Description of Dataset:
Our database contains details of Shark Incidents occuring in California from (1950-2022) obtained through the [US Data Government Website](https://catalog.data.gov/dataset). Our database includes thirteen dimensions with various datatypes that specifies information regarding a specific shark incident and the details regarding the incident such as location, date, and severity of the injury. 

**Dimensions Include**: Incident Number (which represents the specific incident id), Time, Country, Location, Mode (which represents the activity that was taking place), Injury, Depth, Species, Comment and Confirmed Source——which are all of the datatype String. Additionally other dimensions include Date that the incident occured (Date datatype), and Longtitude and Latitude (number/decimal datatype) which specify the exact coordinates of where the shark incident happened——while they are of numerical value they still behave like a dimension because when combined those values point to a specific location and acts as a category rather than a measure. 




## Question 1:
**Which activities are associated with the highest number of shark incidents over the years? For the activities with the most shark incidents, how have their incident trends changed over time (1950-2022)?**

**Importance:**
This question is important because it helps to understand which activities are most associated with shark incidents, offering insights into the behaviors and conditions that may lead to these dangerous encounters. By identifying the activities with the highest number of shark incidents, authorities, ocean safety organizations, and even recreational enthusiasts can gain valuable information on where more safety measures or awareness campaigns may be needed. The second part of the question, which looks at how incident trends change over time, helps to identify whether certain activities are becoming riskier or safer over the years. For example, increased incidents in certain activities over time could indicate changing patterns of behavior or environmental factors. Understanding these trends can inform public safety policies, resource allocation, and risk management strategies. This question is tied to the dataset because it includes historical shark incident data across various activities, providing the necessary information to track these patterns and analyze trends over time.

**Analysis:**
<img width="1225" alt="Screenshot 2025-04-29 at 6 39 58 PM" src="https://github.com/user-attachments/assets/9ffb6bf1-0f51-4d02-9ffd-1636983d7a49" />
This first graph illustrates the count of shark incident occurrences by activity type from 1950 to 2022. We observe that Surfing/Boarding consistently has the highest number of shark incidents, with 85 incidents, significantly outpacing other activities. Freediving and Kayaking/Canoeing follow with 36 and 30 incidents, respectively. Activities such as Paddleboarding, Scuba Diving, and Swimming show fewer incidents, while Walking in Shallow Water records the lowest number with only 1 incident. This visualization helps to identify the activities most associated with shark incidents over the years.

<img width="1225" alt="Screenshot 2025-04-29 at 6 40 55 PM" src="https://github.com/user-attachments/assets/d8074279-a903-4020-995c-7f19b2c3d6c2" />
In this second visualization, we analyze how the trends in shark incidents for the top 3 activities (Freediving, Kayaking/Canoeing, and Surfing/Boarding) have changed over time, from 1950 to 2022. The Surfing/Boarding activity shows the most significant fluctuation, with a sharp spike in incidents during the early 2000s, followed by periods of higher frequency and some dips in between. Kayaking/Canoeing also shows some fluctuation, but with smaller spikes in the mid-2000s and 2010s, while Freediving maintains a much more consistent but low level of incidents throughout the years. These trends are valuable for understanding how risk levels associated with each activity have changed over time, helping safety organizations and public officials plan for future prevention efforts. For example, spikes in Surfing/Boarding incidents during specific periods highlight potential shifts in either activity patterns or environmental factors that require targeted interventions. Understanding these trends can help officials allocate resources effectively and advise the public on the activities that may have higher risks during certain years or decades.


## Question 2:
**What is the geographical distribution of shark incidents along the California coast, and how do the severity levels (fatal, major, minor) vary in these locations?**

**Importance:**
This question is important because it identifies high-risk areas along the California coast, allowing authorities to implement targeted safety measures such as increased lifeguard presence and public warnings. Understanding how severity levels (fatal, major, minor) vary across locations helps prioritize resources for areas with more serious incidents. This data also enables the public to make informed decisions about which areas may be riskier, improving overall safety awareness and helping reduce fear of shark incidents. Additionally, this information can guide policies and resource allocation for both safety organizations and local businesses. The dataset provides the necessary details on each incident's location and outcome, making it possible to answer the question about how shark incidents vary geographically and by severity.

**Analysis:**
<img width="1225" alt="question2" src="https://github.com/user-attachments/assets/94cc6559-39b6-4ee2-a93a-1c819c267d87" />
This map illustrates the geographical distribution of shark incidents along the California coast, categorized by severity (fatal, major, and minor). We noticed that fatal incidents (red circles) are primarily concentrated in the central coast, with significant occurrences around popular beach areas. Major injuries (yellow squares) are more evenly distributed along the coast, particularly in the northern and southern regions. Minor incidents (green plus signs) appear throughout the coastline, with a slight concentration in the southern areas. This map provides valuable insights for authorities to prioritize safety measures in high-risk regions and helps the public stay informed about where shark incidents are more frequent.

## The manipulations applied to the data set as part of the analysis:
The manipulations applied to the dataset were minimal. We primarily focused on cleaning the data by filtering out null or missing values. This ensured that the dataset was complete and accurate for analysis, without any incomplete records that could affect the results. No other major transformations or adjustments were necessary, as the data was already in a usable format. Additionally, we analyzed only the first sheet of the the original excel file found on [US Data Government Website](https://catalog.data.gov/dataset), which contained multiple sheets with different datasets by converting it to a csv file. 

## Tableau packaged workbook
The packaged workbook containing the visualizations shown above is attached to this repository.
