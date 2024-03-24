## [Predictor model project - Report](https://github.com/lolavc/predictor_model/blob/main/Multivariate4gh_191223.pdf)
This report outlines the process of building a predictor model to evaluate coronary heart disease (CHD) while considering potential risk factors. 
The dataset utilized originates from a retrospective sample of males residing in Western Cape, South Africa, an area known for its high risk of heart disease. 
Data collection occurred throughout the year 2019.
### Tasks Completed:
1. Data Cleaning and Descriptive Statistics:  
The dataset underwent cleaning procedures to ensure data quality, followed by the generation of descriptive statistics to gain insights into the variables.
   
2. Data Splitting:  
The cleaned dataset was divided into training and test datasets to facilitate model development and evaluation.
   
3. Model Development:  
A logistic regression model was constructed using the training dataset, employing backward selection techniques to identify significant predictors of CHD.
   
4. ROC Plot Analysis:  
A Receiver Operating Characteristic (ROC) plot was utilized to determine the optimal balance point between sensitivity and specificity of the model.
   
5. Evaluation Metrics:   
Sensitivity, specificity, and correct classification rate were computed and evaluated using both the training and test datasets to assess the performance of the model.
   
6. Principal Component Analysis (PCA):  
PCA was conducted on the dataset's numerical variables after scaling, utilizing the correlation matrix to identify patterns and reduce dimensionality.

7. Determination of Components:  
The cumulative proportion of variance explained by sequential components, along with the Kaiser Criterion and Scree plot, were analyzed to determine the number of components to retain.

8. Biplot Analysis:  
A biplot was generated to visualize and analyze the first two principal components, providing insights into the relationships between variables and observations.  

These tasks collectively aimed to develop an accurate and interpretable predictor model for CHD, providing valuable insights into the potential risk factors associated with the disease.
![](/img/LinearCorrelation.jpg)
![](/img/Biplot.jpg)
