# Data-Analysis-on-NASA-Asteroid-classification-XGBooster-Claasifier

Project Title: NASA Asteroid Classification using XGBoost for Data Analysis Portfolio

I am thrilled to present my latest project, focusing on data analysis and classification of NASA asteroids using the XGBoost algorithm. This project, part of my Data Analysis Portfolio, involved employing various tools and techniques to analyze the dataset and build an accurate classification model.

Project Description:
In this project, I conducted a comprehensive analysis of a NASA asteroid dataset with the objective of classifying asteroids based on the presence of hazards. Leveraging the power of XGBoost, a robust machine learning algorithm, I aimed to develop a model that accurately predicts the hazardous nature of asteroids based on the available features.

Key Project Highlights:

*Data Preprocessing: I began by importing the necessary libraries and reading the dataset in CSV format. Next, I performed data preprocessing by dropping columns that were not required for the classification task. Additionally, I employed one-hot encoding on the "Hazardous" column to convert categorical data into a numerical format.

*Feature Selection: During the analysis, I observed the unique values in the "Orbiting Body" and "Equinox" columns. Since both columns contained only a single value, they were dropped from the dataset as they provided no meaningful information. Additionally, I explored the correlation among the remaining features using a heatmap. Identical columns with different units, which exhibited a correlation of 1, were removed to eliminate redundancy.

*Model Building: With the dataset prepared, I proceeded to build the classification model using the XGBoost Classifier. XGBoost is a highly effective algorithm known for its ability to handle complex relationships and deliver accurate predictions. I trained the model on the selected features and evaluated its performance.

*Accuracy Evaluation: Following the model training, I calculated the final accuracy score to assess its performance in accurately classifying the asteroids. The accuracy score provided an indication of how well the model could predict the presence of hazards.

Tools and Techniques Used:

*Python: I utilized the Python programming language throughout the project.
*Pandas: The Pandas library was employed for data manipulation and preprocessing.
*XGBoost: The XGBoost algorithm was used for building the classification model.
*Heatmap Visualization: Heatmaps were employed to observe the correlation among features.

This project not only showcased my expertise in data analysis but also highlighted my ability to preprocess data, select relevant features, and build a robust classification model. By leveraging XGBoost, I achieved accurate results and demonstrated the potential of machine learning in accurately classifying NASA asteroids.

For a more detailed overview of this project, including code implementation and visualizations, please visit my GitHub profile. I am open to discussions, collaboration opportunities, and further inquiries related to this project.


**Droping Columns which are not Required for Classification
**One hot encoding on Hazardous column
**Observing Unique Values in Orbiting Body and Equinox
**Both Columns can be dropped, as both have single one value present
**Correlation vis Heatmap
**Need to drop Some Columns as they are having correlation 1 because they are identical columns with a different unit.
**Now again but Final Heatmap Correlation
**Now as True Column is needed for our Classifications , therefore False column can be drop from dataset
**Finally We will Build Model
**XGBoost Classifier
**Final Accuracy Score
We can do more Classifications with Different Different Columns.

![unnamed](https://github.com/HOSHANGI/Data-Analysis-on-NASA-Asteroid-classification-XGBooster-Claasifier-/assets/118753140/d2a2fcbd-bfa9-4a95-a8b5-3a0ba7612bb4)
![OIP](https://github.com/HOSHANGI/Data-Analysis-on-NASA-Asteroid-classification-XGBooster-Claasifier-/assets/118753140/93957d86-05e1-40f9-8182-7c560f6f52eb)
![__results___31_0](https://github.com/HOSHANGI/Data-Analysis-on-NASA-Asteroid-classification-XGBooster-Claasifier-/assets/118753140/7d27d75e-3d96-470a-b5d0-962464945005)
![__results___23_1 (1)](https://github.com/HOSHANGI/Data-Analysis-on-NASA-Asteroid-classification-XGBooster-Claasifier-/assets/118753140/bc967f5c-f334-4d8b-8369-2df0aec78eea)
