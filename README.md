![pexels-goumbik-669610](https://github.com/user-attachments/assets/88b4a2a9-d88a-4a84-8724-3cbf06f893bf)

# Analysing customer behaviour using exploratory data analysis and machine learning algorithm

# PROBLEM STATEMENT
Develop a robust user profiling and segmentation system that leverages machine learning and data analysis techniques to categorize users into distinct segments. By analyzing user interaction data, demographic information, and engagement metrics, identify meaningful patterns and clusters within the user base. The ultimate goal is to enable businesses to tailor their advertising campaigns to the identified segments, thereby increasing ad relevance, user engagement, and conversion rates while optimizing ad spend.

# ABOUT THE DATASET
The dataset comprises a diverse set of user metrics collected from an online platform, consisting of 1,000 user profiles with 16 distinct features. These features include demographics (age, gender, income level, and education), online behavior (likes and reactions, followed accounts, device usage), engagement with content (time spent online during weekdays and weekends, click-through rates, conversion rates), interaction with ads (ad interaction time), and user interests.
Dataset can found https://statso.io/wp-content/uploads/2024/02/user_profiles_for_ads.csv

**KEY INSIGHTS AND RECOMMENDATIONS FOR THE BUSINESS**
* Cluster 0 – “Weekend Warriors”: High weekend online activity, moderate likes and reactions, predominantly male, age group 25-34, income level 80k-100k.
* Cluster 1 – “Engaged Professionals”: Balanced online activity, high likes and reactions, predominantly male, age group 25-34, high income (100k+).
* Cluster 2 – “Low-Key Users”: Moderate to high weekend online activity, moderate likes and reactions, predominantly male, age group 25-34, income level 60k-80k, lower CTR.
* Cluster 3 – “Active Explorers”: High overall online activity, lower likes and reactions, predominantly female, age group 25-34, income level 60k-80k.
* Cluster 4 – “Budget Browsers”: Moderate online activity, lowest likes and reactions, predominantly female, age group 25-34, lowest income level (0-20k), lower CTR.

*	Target High-Engagement Clusters with Premium Products
*	Focus Weekend Campaigns on Cluster 1
*	Use Retargeting for Low CTR Clusters
*	A/B Test Different Campaigns
*	Diversify Ad Content Based on Demographics

# EXPLORATORY DATA ANALYSIS
The dataset has been cleaned and does not contain missing values thus it is ready for exploration.

**Analysing the distribution of Age, Gender, Education Level, Income Level we can conclude that:**
*	25-34 is the most common age group, with 65+ be the least frequent
*	Male and Female gender are equally distributed
*	Education Level is fairly evenly distributed
*	Income Level is also fairly evenly distributed with 0-20k being the least frequent income level

![image](https://github.com/user-attachments/assets/fdf4c38d-a13d-4c34-bdeb-16814be759b6)

**Distribution Analysis for Numerical Features**
![image](https://github.com/user-attachments/assets/66c5001a-ec4a-4fc4-bffc-665fce3c6602)

**What are the top 10 Interests from users**
![image](https://github.com/user-attachments/assets/d15bab2d-cf35-4ff9-9438-cf1d59e405bf)

Using Kmeans Unsupervised Machine Learning Algorithm the dataset can be segemented into 5 different clusters and we can observe the mean and mode for the numerical and categorical features below
![image](https://github.com/user-attachments/assets/d9717426-ade6-44ac-93ab-6257b3d6ef62)

We can visualise the clusters with a Radar Chart. Below we can see that Engaged Professionals spend more time online during the weekend and have a high click though rate which could be as a result of their income level being 80k-100k 
![newplot (1)](https://github.com/user-attachments/assets/6ac86d02-219e-45f4-890e-48a4fb117ecd)











