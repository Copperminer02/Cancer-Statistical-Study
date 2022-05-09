# FinalProject_050322

## Topic and Reason
- Global Cancer Death Rates between 2000-2018 based on Socioeconomic Factors
#### Reason?
- Cancer is the second leading cause of death worldwide, with over 100 different types. The data collected from cancer death rates can be used to track the progression of cancer while also analyzing the sustainability of countries around the world. Our purpose in this project is to better understand these socioeconomical trends of 149 countries and their relation with cancer mortality. 

## Description of Data Source
[Link to Cancer Death Rates](https://www.kaggle.com/datasets/bahadirumutiscimen/cancer-death-rates-in-the-world-19902019)

- This dataset from Kaggle shows the total cancer deaths by type of cancer between 1990 and 2019. We will be extracting data from a specific amount of cancer types as well as only from the years 2000-2018 to match our second dataset. 

[Link to Global Sustainability](https://www.kaggle.com/datasets/truecue/worldsustainabilitydataset?select=WorldSustainabilityDataset.csv)

- This dataset, also pulled from Kaggle, tracks sustainability metrics in 173 countries from the year 2000 to 2018. We will be using specific factors from this dataset such as life expectancy, income, emission production, etc.


## Question to answer
- Do socioeconomic factors influence the rates of death by cancer?
- How have these factors changed throughout time?
- Are certain types of cancer more prevalent in specific regions?


## Communication Protocols
-   Indiviual weekly tasks assigned each Tuesday during regular class hours.
-   Datasets maintained, cleaned, and stored as a group in the main branch.
     -    Dastaset updates performed in class hours.
     -    Group decides final workable dataset for the week.
     -    Dataset editing can only occur inside indiviual scripts and related to the requirements of that assignment.
          -    Changes to the main dataset **must be communicated and agreed to by all members** before change can be implemented.  
-   Each member maintains individual git branch related to their assignment.
     -   Individual Branches contain scripting, schema, etc related to their assignments.
-   Main communication about strategy and workability between tasks to be performed during Class Hours
-   Saturday Zoom meetings 11 AM to review challenges and coordinate approval of assignments to main branch.
-   All inter meeting communication to be held via Slack channel  **_0fp-kavita-josh-khadijah-rhian**
-   All members approve main branch changes and README prior to Sunday submissions.

## SQL Mockup Data Flow
- Database will be created and housed in PostgreSQL via pgAdmin.
- Within the database the following tables will be included:
     - Cancer death rates organized by types and country
     - Sustainability statistics organized by Country
     - Sustainability statistics joined with Cancer death rates (joined on country and year)—this will be the “working” table used primarily in the
          analyses
     - There may be additional tables generated based on further data analyses

- Machine learning models will be connected to SQL database in Jupyter notebook importing the following libraries: sqlalchemy & psycopg2.

- The final cleaned & analyzed data will be exported as CSV files to be then utilized in Tableau for visualizations as deemed appropriate by group.


## ML Mockup and Data Flow
1.	Explore Clean Data:
     a. Descriptive Statistics: Count, Mean, Std, min, 25%, median, 75%, max
2.	Plot Data:
      a.Histograms to check normality and distribution
3.	Create a Training and Test Set of Data
      a. 70:30 split, 80:20 split, 90:10 split
      b. Determine which split works best for the data. Models evaluated based on accuracy, recall, F1 score and precision. 
      c. The F1 score will be used to measure the model’s accuracy and it’s a mean of precision and recall. F1 scores closer to 1 indicate lower false    positives and lower false negatives The recall score measures the extent to which the model can correctly identify true positives. The accuracy score is the relationship between the number of correct predictions and total number of predictions. The precision score represents the relationship between the true positives and all positives. 
      d. Determine optimal number of features to be included.
4. 	Model Classification:
    a. Build classification models to evaluate performance on the training data
    b. Supervised ML Models: random forest, decision trees, logistic regression, random forest, support vector mechanisms.
    c. Unsupervised ML Models: clustering, PCA
    c. These machine learning algorithms were chosen because of they are robust to outliers and non-linear data, run efficiently on large data sets, robust  against overfitting and consistent with the ML algorithms used in biomedical research.

## Tableau

Final result Dahsboard and visualization anticipated to be performed with Tableau.  Tableau will either link directly to the postgresSQL database or csv outputs from jupyter notebook ML project.
