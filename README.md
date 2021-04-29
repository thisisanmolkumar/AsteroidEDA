# Exploratory Data Analysis on Asteroid Data
Exploratory Data Analysis, or EDA, is one of the first steps of the data science process. It involves learning as much as possible about the data, without spending too much time.
1. Basic data set Exploration
  - Displaying a few rows
  - Getting the shape of the data
  - Checking DataTypes of every column  
  **Conclusion: Understood the column names and reference, got the categorical and numerical variables and that there are a lot of NaN values.**  
2. Checked for null values
  - Deleted columns with more than 80% null values
  - Dropped rows that have any null values since we have a lot of data  
  **Conclusion: Got a data without null values**  
3. Checked for correlation between the attributes
  - Plotted a heatmap
  - Checked through background gradient
  - Removed any attribute with a correlation more than 80%  
  **Conclusion: No strong positive relation between any attributes.**  
4. Categorical variables
  - Removed the non useful categorical data
  - Converted the useful one into binary classified data
  - Used one hot encoding on the class attribute  
  **Conclusion: Got a completely numerical data.**  
5. Scaling
 - Scaled the data
 - Removed the NaN values that came after scaling  
  **Conclusion: Data is properly distributed now.**  
