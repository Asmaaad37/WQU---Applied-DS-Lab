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
* Created preliminary and **exploratory histograms, scatter plots, whisker plots and bar charts**
* Examined the relationship between variables by assessing _Pearson correlation coefficients_
* Cleaned and munged raw data by creating a custom wrangle function
* Built ML pipelines by means of _Ridge, OneHotEncoder, SimpleImputer, LinearRegression and make_pipeline_ built-in sklearn functions
* **Applied L2 Regularization** in order to prevent overfitting or underfitting in Linear Regression models
* Created an **interactive dashboard utilizing ipywidgets** library to module predictions based on different input features


# 3. Air quality forecast in Nairobi:

* **Connected to a MongoDB server using pymongo** library to localize and fetch the required data.
* **Applied rolling average, autocorrelation and lag operations** to Times Series data variables
* Utilized **Train Test Split** procedures to create proper train and test datasets for a Linear Regression model
* Built, explored and interpreted **Partial/Auto Correlation** Functions plots
* Using statsmodels modules, constructed **Auto Regressive and ARMA models** and validated them via Walk Forward optimization.
* Tuned the number of **lagged observations and moving avg. window size** via _GridSearchCV_
* Detected an optimal balance between **Model Performance** and **Computational Costs**


# 4. Earthquake damage prediction in Nepal:

* Connected to a **SQL database** and wrangled data using magic commands and sqlite3 library
* Executed randomized Train Test Split to create p**roper training, testing and validation datasets**
* Elaborated **ML pipelines** utilizing _OrdinalEncoder, DecisionTreeClassifier, LogisticRegression and make_pipeline_ built-in sklearn functions
* Besides **computing and evaluating training and validation** accuracy scores:
    1.  **For Decission Tree algorithms**, tuned the Tree’s depth and assessed its predictions by assessing the Gini importance of its features
    2.  **For Logistic Regression algorithms**, evaluated Odds ratios to explain its predictions
* Reviewed the **Ethics of Environmental and Social impact** that Machine Learning models may lead to because of **data biases**


# 5. Bankruptcy in Poland:

* Applied **Undersampling** and **Oversampling** to adjust the **class distribution of datasets**
* Computed **confusion matrices** to summarize how **Decission Tree algorithms** performed and find areas of improvement
* Constructed **ML pipelines** by means of _SimpleImputer, RandomForestClassifier, GradientBoostingClassifier and make_pipeline_ built-in sklearn functions
* Performed **k-fold Cross-Validation** to evaluate **model performance**
* Utilized _GridSearchCV_ to compute different **hyperparameters** and found their **optimal ranges** for the selected ones
* Built** interactive confusion matrices** to asses how the model's probability threshold affects accuracy, precision and recall scores


# 6. Customer segmentation in the US:

* Performed preliminary **EDA** on a dataset from Survey of Consumer Finances (SCF) compound by **28k observations and 350 features** after subsetting it
* Build and **fit k-means models** to create multi-feature clustering after computing and standardizing their feature matrix
* Assessed the **optimal clustering selection** by _evaluating variance, inertia and silhouette scores_
* Reduced the dimension of feature matrices by means of **PCA transformation**
* Developed and deployed a **Dash web app architected in 3 layers** (Business, Service and Presentation) where interactive scatter plots and barcharts were modified via sliders


# 7. A/B Testing at WorldQuant University:

* Fetched synthetic data from a **Mongo DB** and performed data wrangling using pymongo queries
* Designed, built and developed **OOP class definitions** containing the database attributes and **ETL methods** based on the experimental hypothesis
* Performed **cross-tabulation** to the wrangled dataset in order to create a contingency table and obtain odds ratios
* Designed and conducted chi square tests using statsmodels module and analyzed its results
* Built and launched an interactive and **3-tier decoupled web application** to deploy and display barcharts and choropleth maps. The layer distribution and their OOP classes and functions were the compound by the following objects:
    1. **Database:** customized MongoRepository class
    2. **Business:** GraphBuilder and StatsBuilder classes from statsmodels module
    3. **Design/Layout:** Demographic, Experiments and Result sections with dropdowns and sliders
 

# 8. Volatility forecasting in India:

* Applied **Defensive programming** when designing functions to **access APIs** through an **URL and request objects**
* By means of **Test Driven Development** practices, built the following OOP objects:
    1. _AlphaVantageAPI_ class, to programmatically fetch data from an API
    2. _SQLRepository_ class, to load and extract data into and from a SQLite database
* Constructed wrangling functions to create training Series for **GARCH** models
* Built and fit **GARCH models** and evaluated their detailed summary and performace
Created:
    1. A **GarchModel** class compound by methods for **data wrangling, model training, prediction generation and model load/saving**
    2. A w**eb API and launched the server** by means of _FastAPI and uvicorn, respectively_
    3. **Data classes** in order to **forestall client-server communication errors**
    4. **API paths** for **model fitting and predictions serving**


 # Credential of Completion - https://www.credly.com/badges/0b975a0c-14d7-4f15-b51e-c572ef2b52b0/public_url


_Note:_ Due to WorldQuant University's Copyright Licenses and Policies, I am unable to share the original course notebooks or code. However, this repository provides detailed summaries and insights into the methodologies, tools, and outcomes of my work. Feel free to reach out to discuss my projects or explore potential collaborations!
