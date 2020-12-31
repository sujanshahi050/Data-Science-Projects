# PROJECT : Write a Data Science Blog Post on Location Based Analysis of Boston AirBnb data


# Business Understanding

With the prevalence of AirBnb around the world, I wanted to see how AirBnb properties near Boston Logan International Airport are doing. To do so, I
came up with three questions:

    1) How have people rated on locations to those properties closer from the airport?
    2) How does average price of AirBnb properties vary as we move farther away from the airport?
    3) What does overall ratings of properties look like as we move farther away from airport?

           
# Data Understanding

For this project, I used Boston AirBnb data which can be found here https://www.kaggle.com/airbnb/boston.
The datasets(in the link provided) contains three files ('listings.csv','reviews.csv' and 'calendar.csv').
In order to answer questions mentioned above, only 'listings.csv' is used.


# Data Preparation

In order to answer all three questions , only certain columns were selected (which can be found in 'Location Based Analysis of properties in Boston.ipynb'). The missing values in each numerical column were filled with mean value of that column.


# Data Modeling

No models were created to answer questions mentioned. It is a purely anlytical project.


# Evaluation

 1) How have people rated on locations to those properties closer from the airport?
 
 Finding : 
 It looks like people tend to rate higher on locations for AirBnbs near the airport compared to AirBnbs farther from the airport.
 ![alt text](https://github.com/sujanshahi050/Data-Science-Projects/Data Science Blog/result_images/locationRatings-vs-distance.png?raw=true)
 
 
 2) How does average price of AirBnb properties vary as we move farther away from the airport?
 
 Finding:
 The average price of AirBnb gets higher as we go closer to the airport.
 ![alt text](https://github.com/sujanshahi050/Data-Science-Projects/Data Science Blog/result_images/avg-price-vs-distance.jpg?raw=true)
 
 3) What does overall ratings of properties look like as we move farther away from airport?
 
 Finding:
 The overall ratings seems to be higher for those properties near the airport
  ![alt text](https://github.com/sujanshahi050/Data-Science-Projects/Data Science Blog/result_images/overallRating-vs-distance.png?raw=true)




# INSTALLATION

- Anaconda navigator was used to host a jupyter notebook.

Libraries:
  - numpy, pandas, matplotlib, sklearn, re, math



# Link to my blog
Link to Medium BlogPost: 
https://sujanshahi050.medium.com/this-data-will-make-you-think-twice-before-renting-a-hotel-near-boston-logan-international-airport-8aca5b83169

# Find me on Linkedin:
www.linkedin.com/in/sujan-shahi
