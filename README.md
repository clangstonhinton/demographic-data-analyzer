# demographic-data-analyzer

This challenge is 1 of 5 project requirements of freeCodeCamp's Data Analysis with Python certification. Below are the project instructions. Full details can be found on freeCodeCamp [here](https://www.freecodecamp.org/learn/data-analysis-with-python/data-analysis-with-python-projects/demographic-data-analyzer).
<img width="1225" alt="Screen Shot 2023-09-15 at 5 45 10 AM" src="https://github.com/clangstonhinton/demographic-data-analyzer/assets/44728723/05a94dcf-0550-4181-b31a-cf97c6fe5397">

### project purpose & data description
In this challenge you must analyze demographic data using Pandas. You are given a dataset of demographic data that was extracted from the 1994 Census database. Here is a sample of what the data looks like:

|    |   age | workclass        |   fnlwgt | education   |   education-num | marital-status     | occupation        | relationship   | race   | sex    |   capital-gain |   capital-loss |   hours-per-week | native-country   | salary   |
|---:|------:|:-----------------|---------:|:------------|----------------:|:-------------------|:------------------|:---------------|:-------|:-------|---------------:|---------------:|-----------------:|:-----------------|:---------|
|  0 |    39 | State-gov        |    77516 | Bachelors   |              13 | Never-married      | Adm-clerical      | Not-in-family  | White  | Male   |           2174 |              0 |               40 | United-States    | <=50K    |
|  1 |    50 | Self-emp-not-inc |    83311 | Bachelors   |              13 | Married-civ-spouse | Exec-managerial   | Husband        | White  | Male   |              0 |              0 |               13 | United-States    | <=50K    |
|  2 |    38 | Private          |   215646 | HS-grad     |               9 | Divorced           | Handlers-cleaners | Not-in-family  | White  | Male   |              0 |              0 |               40 | United-States    | <=50K    |
|  3 |    53 | Private          |   234721 | 11th        |               7 | Married-civ-spouse | Handlers-cleaners | Husband        | Black  | Male   |              0 |              0 |               40 | United-States    | <=50K    |
|  4 |    28 | Private          |   338409 | Bachelors   |              13 | Married-civ-spouse | Prof-specialty    | Wife           | Black  | Female |              0 |              0 |               40 | Cuba             | <=50K    |

### data analysis & questions to answer
You must use Pandas to answer the following questions:
  - How many people of each race are represented in this dataset? This should be a Pandas series with race names as the index labels. (race column)
  - What is the average age of men?
  - What is the percentage of people who have a Bachelor's degree?
  - What percentage of people with advanced education (Bachelors, Masters, or Doctorate) make more than 50K?
  - What percentage of people without advanced education make more than 50K?
  - What is the minimum number of hours a person works per week?
  - What percentage of the people who work the minimum number of hours per week have a salary of more than 50K?
  - What country has the highest percentage of people that earn >50K and what is that percentage?
  - Identify the most popular occupation for those who earn >50K in India.
  - Use the starter code in the file demographic_data_analyzer. Update the code so all variables set to "None" are set to the appropriate calculation or code. Round all decimals to the nearest tenth.

### data source
Dua, D. and Graff, C. (2019). UCI Machine Learning Repository. Irvine, CA: University of California, School of Information and Computer Science.

