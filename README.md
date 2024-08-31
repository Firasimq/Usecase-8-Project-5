# Introduction 
- When planning a party in Riyadh, selecting the best restaurant that offers the perfect ambiance, high-quality food is crucial. With a wide variety of cuisines available in the city, choosing the right restaurant can be overwhelming. To make an informed decision, analyzing data from restaurant websites becomes essential.

# Dataset Synopsis and Origin
- The dataset contains information about 1,369 restaurants, with the following columns:
1-Name: The name of the restaurant.
2-Cuisines: The types of cuisines offered by the restaurant.
3-City: The city where the restaurant is located.
4-Rating: The rating of the restaurant.
5-NumberOfReviews: The number of reviews the restaurant has received.
  
-This dataset provides a structured view of restaurant data, including their names, the variety of cuisines they offer, their location by city, ratings, and the volume of customer feedback through reviews. It's well-suited for analyzing trends in restaurant popularity, cuisine preferences by city, and the relationship between ratings and the number of reviews. 
## Dataset Origin
[Welcome Saudi](https://welcomesaudi.com/restaurant) is a website that provides detailed information about various restaurants across Saudi Arabia. It includes listings for a wide range of restaurants, categorized by location, cuisine type, and user ratings. Each restaurant profile typically contains key details such as the restaurant's name, type of cuisine, city, average rating, and the number of customer reviews.

# Model Selection
- We trained two unsupervised models, K-means and DBSCAN, to cluster restaurants based on various features. After evaluating their performance, we chose the model that best captured the natural groupings in the data.

# Feature Engineering
- We used all the columns in our analysis, focusing on relevant features. After encoding the city names to convert them into numerical values, we dropped the restaurant names from the dataset, ensuring that the model focused on more meaningful attributes.

# Hyperparameter Optimization 
- We used the K-means elbow method to determine the optimal number of clusters. The analysis indicated that the best value for k was 3, as it provided a clear distinction in cluster performance and minimized within-cluster variance.

# Performance Metric Visuals 
- Faisal 



# Best Model Determination 
- Selected the best clustering model based on silhouette scores and visual inspection of cluster separations.


# Feature and Prediction Insights 
- Faisal 






# Team Members 
- Firas Almoqhim
- Mohammed alamri
- Faisal Alzhrani
- Alaa Alahmadi
