# Problem Definition

### **Objective:** To determine the impact of the acquisition channel on student learning outcomes and identify geographical regions where social media platforms are the primary source of platform discovery. 

**Research Questions:**

1. **Acquisition Channel Impact:** 
   * Does the acquisition channel significantly influence student performance, engagement, and retention rates? 
   * Are there specific acquisition channels that consistently lead to superior student outcomes? 

2. **Geographical Distribution of Social Media Discovery:**
   * In which geographical regions are students most likely to discover the platform through social media platforms like YouTube and Facebook?
   * Are there specific regions where a focused social media marketing strategy would be most effective?

**Data Analysis Tasks:**
 
1. **Data Preprocessing:** Clean and prepare the dataset for analysis. 
2. **Exploratory Data Analysis (EDA):** Conduct a thorough data analysis to identify patterns, trends, and relationships between variables. 
3. **Feature Engineering:** Create relevant features that capture the nuances of student behavior and acquisition channels. 
4. **Clustering:** Employ k-means and hierarchical clustering algorithms to segment customers based on their characteristics and behaviors. 
5. **Result Interpretation:** Analyze the clusters to identify distinct customer segments and derive actionable insights to inform marketing strategies. 

Addressing these research questions will help us optimize our acquisition strategy, improve student outcomes, and allocate marketing resources effectively.

## Exploratory Data Analysis (EDA):
![image](https://github.com/user-attachments/assets/94f0dd30-85d5-445f-82a3-1d1538f53b61)
#### Insights from the Correlation Matrix
The heatmap shows correlations between variables like minutes watched, CLV, region, and channel. Key insights include:

* **minutes_watched and CLV:** Weak positive correlation, suggesting customers who watch more videos have slightly higher lifetime value.
* **CLV and region:** Moderate negative correlation, indicating region might influence CLV.
* **minutes_watched and channel:** Moderate negative correlation, suggesting channel might affect viewing behavior.
  

## Results of clustering:

![image](https://github.com/user-attachments/assets/cdca02be-a8b2-46b1-9365-acde271ff9db)

The chart shows 8 customer segments based on CLV and minutes watched. Each segment has distinct characteristics:

* **Instagram Explorers**: Low CLV, high video consumption.
* **LinkedIn Networkers**: High CLV, moderate video consumption.
* **Anglo-Saxon Multi-Channel**: Diverse CLV and video consumption.
* **Friends' Influence**: Moderate CLV and video consumption.
* **Facebook Followers**: High CLV, moderate video consumption.
* **European Multi-Channel**: Diverse CLV and video consumption.
* **Twitter Devotees**: Low CLV, high video consumption.
* **Google-YouTube Mix**: Moderate CLV and video consumption.

Insights:

* CLV doesn't solely drive customer behavior.
