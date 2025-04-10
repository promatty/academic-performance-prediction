# Academic Performance Prediction
In this project, we will propose a problem to solve for a made-up client using machine learning techniques.

## Proposed Client (Who)
The Wellness Center at the University of Calgary. 

## Question being investigated (Why)
With growing stress levels in students, the Wellness Center has asked us to create a regression model in order to find out if there is a correlation between a student’s studying habits and academic performance with their self-reported stress levels. In particular, they want to find opportunities for early support, allowing students to maintain healthy balances in their lives and improve academic outcomes. 

## Plan of Attack (How)
First, we will preprocess the data to make sure that we remove any potentially irrelevant features, and then fill in/remove the NaN values. Next, we will split the data into the feature matrix and target vector containing the stress levels, and then choose some models as well as select the hyperparameters for them. We will fit the model to the data and use validation metrics to figure out if our model is overfitting or underfitting and adjust the hyperparameters accordingly. Lastly, after we choose hyperparameters that we like, we can visualize the results of each of the models we trained, and pick the one that generalizes best.

## Dataset, Models, Frameworks, Components (What)
We will be using the “Student Stress Factors: A Comprehensive Analysis” by user rxnach on Kaggle. This dataset has 1100 records and 21 columns. The target will be the stress_level column which is represented on a scale from 0-2. The machine learning models we will use are lasso regression, random forest, and gradient boosting. We will be using Python and Jupyter Notebooks to develop the code and some relevant tools and libraries that we will use include Scikit-Learn, Pandas, and Matplotlib. We plan to fill in the missing data values using the mean of the feature data associated with each target class. To evaluate and validate our models, we will use mean squared error and R^2 values.

https://www.kaggle.com/datasets/rxnach/student-stress-factors-a-comprehensive-analysis/data
