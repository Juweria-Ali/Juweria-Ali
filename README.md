# Data Science Portfolio 
## [Project 1: Building-a-dashboard-for-STEM-subject-entrants-in-Higher-Education-and-Further-Education](https://github.com/Juweria-Ali/Building-a-dashboard-for-STEM-subject-entrants-in-Higher-Education-and-Further-Education)
This is a project I did as Data Intern for the University of Highlands and Islands as partof my Data Science Master's program.
Aim:
The purpose of this project phase is to design, implement, and evaluate a prototype self-service
dashboard to help STEM providers in the Highlands and Islands STEM Partnership plan activities,
understand enrolments in STEM subject entrants at college and forecast future trends.

Objectives
1. Investigate the availability & viability of data sources for inclusion in the visualisations.
2. Review state of the art in data visualisation dashboards including available software tools.
3. Create an efficient and usable data visualization.
4. Evaluate the effectiveness in terms of usability & accuracy.

Data Sources:
1. Skills Development Scotland (SDS) RSA Data Matrix
2. Higher Education Statistics Agency (HESA)
3. Scottish Funding Council (SFC) Data
4. Scottish Index of Multiple Deprivation (SIMD) Data

Overview of the project with figures is published as poster in pdf format.
A powerpoint presentation is also prepared to present the findings.
The complete write up is available as a project report in pdf format.

## [Project 2: Classification of Medical X-ray images of different body parts using Python](https://github.com/Juweria-Ali/Machine-Learning-using-Python)

Data Compilation:

The images were downloaded from three different URL and the dataset consists of 4331 x-ray images.
1. Chest images were downloaded from https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia. 2366 images were randomly taken from the two directories.
2. Knee images were downloaded from https://data.mendeley.com/datasets/t9ndx37v5h/1. 1124 images were randomly taken from the two directories.
3. Shoulder images were downloaded from https://www.kaggle.com/dryari5/shoulder-xray-classification.The dataset is organized into 3 folders (train, test, val) and contains subfolders for each image category (Type A1, C1, D1 and Others). There are 841 Shoulder X-Ray images (PNG) and 4 categories (Type A1, C1, D1 and Others).

## [Project 3: Data cleaning, preparation,EDA and initial analysis on Events and Weather datasets using Excel and R](https://github.com/Juweria-Ali/Data-Cleaning-Data-Merging-EDA-and-initial-analysis-using-R-on-Events-and-Weather-datasets)

Prepare and explore the datasets, perform data cleaning, data transformation and data exploration prior to performing learning tasks.
This project was done a part of a module assessment and the datasets were given by the school.

## [Project 4: Statistical Analysis and Visualisations on Transactions data](https://github.com/Juweria-Ali/Statistical-Analysis-and-Visualisations-related-to-Transactions-dataset)

transactions.csv contains synthetic data relating to a hypothetical research analysis on a set of online banking transactions. The dataset has 600 instances (rows) and 8 attributes (columns).

Attribute Description id: id is a unique transaction identifier and will play no role in the statistical analysis.

status: status is a categorical variable, indicating whether the transaction is the first one made by the account holder to a given recipient. It has 2 possible values: New or Existing

device: device is a categorical variable, indicating the type of computing device used by the account holder to make the online transaction. It has 3 possible values: PC, mobile or tablet.

recipient: recipient is a categorical variable, indicating the type of transaction in terms of who the online payment was made to. It has 4 possible values: bill, purchase, self or transfer.

value: value is a numerical variable representing the amount of pounds that way paid during the online transaction.

time: time is a numerical variable representing the total log-in time in seconds taken to complete the online transaction.

model1: model1 is a numerical variable on the scale 0-100 representing the accuracy with which a benchmark machine learning algorithm can identify the online transaction as being genuine or fraudulent.

model2: model2 is a numerical variable on the scale 0-100 representing the accuracy with which a new machine learning algorithm can identify the online transaction as being genuine or fraudulent.

The purpose of the study for which the data has been gathered is to evaluate the effectiveness of the new algorithm, whose accuracies are given by variable model2, relative to the performance of the benchmark algorithm, whose accuracies are given by variable model1.

## [Project 5(Part1): Data cleaning,merging, EDA and initial analysis on fish farms data using R](https://github.com/Juweria-Ali/Part-1-Data-Cleaning-Data-Merging-EDA-and-initial-analysis-using-R)

Aquaculture (fish farms) are an important part of the Scottish economy. Fish are grown in large cages, either in the sea or in lakes. The industry involves the use of animals and has an impact on the environment, so there is an increased focus in monitoring the fish farms, and keeping records of any incidents there may be.

The two datasets used were: • escapes.csv: contains records of fish escapes, i.e. incidents where some of the fish in the cages have escaped into the wild. This is undesirable and is reported. • analysis.csv: the results of water analysis using a number of components. This file has been selected to contain records which somehow align with some of the escapes data.

The following tasks were carried out in R:

1. Prepare each individual dataset for learning. Perform some exploratory data analysis in order to justify data preparation. This includes: 
  a. Cleaning the data.
  b. Transforming data / attributes. 
  c. Removing data. 
  d. Imputing data. 
  e. Discarding features/attributes. 
  f. Deleting instances.
2. Integrate the 2 datasets together into a merged dataset called escapesPlus and was saved to a file called escapesPlus.csv.
3. Additional exploratory data analysis of the dataset, highlighting any interesting information. Note that data exploration may involve the application of statistical functions and/or the use of visualisations. Preparing this new dataset for learning.
4. ONE other learning task that is different from tasks 1-3 and, ideally, it complements the work undertaken in previous tasks.

## [Project 5(Part2): Model fitting, evaluation and deployment using R](https://github.com/Juweria-Ali/Part-2-Model-fitting-Model-Evaluation-Model-Deployment)

Dataset has similar theme and context to that from Part 1 • but is cleaned and complete • has some renamed columns • has some additional columns

Five tasks were carried out

1. Fit a logistic regression model to predict Cause
2. Fit another classification model of your choice to predict Cause
3. Fit a linear regression model to predict Number
4. Fit another regression model of your choice to predict Number
5. Deploy one model as part of a basic Shiny app to predict Cause
