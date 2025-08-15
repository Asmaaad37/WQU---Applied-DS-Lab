# Applied Data Science Lab at WorldQuant University
# Data Science Lab Projects - WorldQuant University
Welcome to my repository showcasing the culmination of my hands-on Data Science training at WorldQuant University! This collection highlights my expertise gained through eight end-to-end Data Science projects, covering cutting-edge techniques and real-world applications. Below is an overview of the skills and concepts I mastered through these projects, designed to demonstrate my proficiency in data science and machine learning to potential collaborators, employers, or curious minds.

# Project Overview
* The Data Science Lab at WQU equipped me with practical, industry-relevant skills through a rigorous curriculum. My projects focused on:
1. **ETL Pipelines**: Designed and implemented robust Extract, Transform, Load (ETL) pipelines to process and clean complex datasets, ensuring data integrity and usability for downstream analysis.
2. **Supervised & Unsupervised Machine Learning**: Built and evaluated advanced ML models, including regression, classification, and clustering algorithms, to solve diverse predictive and exploratory tasks.
3. **Web Application Development**: Engineered end-to-end web apps, from designing intuitive user interfaces to deploying scalable solutions, integrating data science models for real-time insights.
4. **End-to-End Workflow**: Executed full-cycle data science projects, from data acquisition and preprocessing to model deployment and visualization, delivering actionable results.

# Key Skills Demonstrated
1. **Programming**: Proficient in Python, leveraging libraries like pandas, scikit-learn, TensorFlow, and Flask for data manipulation, modeling, and app development.
2. **Data Engineering**: Streamlined data workflows using ETL processes, ensuring high-quality datasets for analysis.
3. **Machine Learning**: Applied supervised (e.g., Random Forests, Gradient Boosting) and unsupervised (e.g., K-Means, PCA) algorithms to uncover patterns and predict outcomes.
4. **Web Development**: Created and deployed interactive web applications using frameworks like Flask or Streamlit, integrating ML models for user-friendly insights.
5. **Problem-Solving**: Tackled real-world challenges, from data preprocessing to model optimization, delivering impactful solutions.


<img width="792" height="488" alt="image" src="https://github.com/user-attachments/assets/e394d100-e4ca-4dbe-987c-6d3ccfec3d1a" />


# 1 & 2. Housing in Mexico and Buenos Aires:

* Imported multiple CSV files from a private repository into a pandas DataFrame using for loops
* Created preliminary and exploratory histograms, scatter plots, whisker plots and bar charts
* Examined the relationship between variables by assessing Pearson correlation coefficients
* Cleaned and munged raw data by creating a custom wrangle function
* Built ML pipelines by means of Ridge, OneHotEncoder, SimpleImputer, LinearRegression and make_pipeline built-in sklearn functions
* Applied L2 Regularization in order to prevent overfitting or underfitting in Linear Regression models
* Created an interactive dashboard utilizing ipywidgets library to module predictions based on different input features


# 3. Air quality forecast in Nairobi:

* Connected to a MongoDB server using pymongo library to localize and fetch the required data.
* Applied rolling average, autocorrelation and lag operations to Times Series data variables
* Utilized Train Test Split procedures to create proper train and test datasets for a Linear Regression model
* Built, explored and interpreted Partial/Auto Correlation Functions plots
* Using statsmodels modules, constructed Auto Regressive and ARMA models and validated them via Walk Forward optimization.
* Tuned the number of lagged observations and moving avg. window size via GridSearchCV
* Detected an optimal balance between Model Performance and Computational Costs


# 4. Earthquake damage prediction in Nepal:

* Connected to a SQL database and wrangled data using magic commands and sqlite3 library
* Executed randomized Train Test Split to create proper training, testing and validation datasets
* Elaborated ML pipelines utilizing OrdinalEncoder, DecisionTreeClassifier, LogisticRegression and make_pipeline built-in sklearn functions
* Besides computing and evaluating training and validation accuracy scores:
- For Decission Tree algorithms, tuned the Tree’s depth and assessed its predictions by assessing the Gini importance of its features
- For Logistic Regression algorithms, evaluated Odds ratios to explain its predictions
* Reviewed the Ethics of Environmental and Social impact that Machine Learning models may lead to because of data biases
