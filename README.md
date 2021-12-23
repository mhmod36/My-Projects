# Wrangle and Analyze Data

## The project steps are:

### 1. Gathering
Data was gathered from 3 different sources:

1. From WeRateDogs Twitter archive given by Udacity in csv format. 
2. Image prediction file downloaded programmatically using Requests library and the URL provided by Udacity in tsv format. 
3. Data retrieved by querying Twitter's APIs and using Tweepy library. 
### 2. Assessing
After gathering the data and storing them in DataFrames, the following step was assessing the data for quality and tidiness.

### 3. Cleaning
It is the process of fixing and resolving issues identified in the Cleaning process. The (define, code, and test) steps were used in the cleaning process. First, copies of the DataFrames were created before cleaning. Then, the steps of cleaning were applied iteratively on all issues.

### 4. Storing
The final DataFrame called 'twitter_archive_clean' with the correct data types. The dataset is then stored in a csv file called 'twitter_archive_master.csv'. At this point, the data was successfully wrangled and therefore ready for analysis and visualization.

### 5. Analysis & Visualization
These steps are not part of data wrangling process. However, it cannot reflect correct and accurate insights without performing data wrangling first. Visualizations and insights are provided in ‘act_report.pdf
