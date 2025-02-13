## Introduction
University rankings provide valuable insights into the global higher education landscape. This usecase analyzes university ranking data across **three globally recognized ranking systems**:

1. **Academic Ranking of World Universities (ARWU)** – also known as the **Shanghai Ranking**.
2. **Times Higher Education World University Rankings (THE)**.
3. **Center for World University Rankings (CWUR)**.  

### Team Members: 

1- Tahani Alotaibi 

2- Munirah Alzuman

3- Suliman Alghanmi

4- Kawthar Aljubran

---

## Problem Statement 

This study aims to address the following key questions:  

1. **Which universities are ranked in the top 10 globally?**  
2. **Which universities are ranked in the top 10 based on employment outcomes?**  
3. **What is the position of Saudi universities in global rankings?**  
4. **Among factors such as employment rankings, research rankings, and academic reputation, which has the most significant impact on a university’s overall ranking?**  
5. **Is there a correlation between national and global rankings, and can we identify a country with a high concentration of top-ranked universities based on this correlation?** 

**Bonus**: Identify additional research questions that can be explored using the available dataset.

---

## Objectives 

This project aims to **analyze global university rankings** by leveraging available data to extract meaningful insights into the factors influencing university performance. The study seeks to achieve the following:  

1. **Identify top-ranked universities** across multiple ranking systems (**ARWU, THE, and CWUR**).  
2. **Assess the position of Saudi universities** within global rankings and benchmark them against leading institutions.  
3. **Analyze the influence of key factors** such as **scientific research, employment outcomes, academic awards, and citations** on ranking performance.  
4. **Evaluate the correlation between national and global rankings** to determine the consistency and reliability of various ranking methodologies.  
5. **Identify countries with the highest concentration of top-ranked universities** based on global ranking patterns.  
6. **Develop strategic recommendations** to help universities enhance their ranking performance.  
7. **Expand the analysis** by incorporating additional insights.  

---

## Dataset Overview and Source
We have 3 datasets for ranking universities with different methodologies, we get them from Kaggle.

1 - [Shanghai Ranking](https://www.kaggle.com/datasets/computingvictor/2024-academic-ranking-of-world-universities)

2 - [Times Ranking](https://www.kaggle.com/datasets/ddosad/timesworlduniversityrankings2024)

3 - [CWUR Ranking](https://www.kaggle.com/datasets/armanghazi/top-1000-univercity-ranking-2014-2024-cwur)

We decided to change the given datasets and collect the most current data (for the year 2024) and use it for our analysis instead, for these two reasons:

1- The problem statment questions does not specified certian time period or if they need it over the years.

2- The available datasets are not in the same period one dataset in 2022 and two datasets in 2023 and they have large number of null values that we can not handale it and will miss the inporatnat information if we delete them.


--- 

## Exploratory Data Analysis (EDA) Steps:
### 1- Data Profiling:
Here we take two steps: 

 Step1: Doing describtive analysis and get a quick sense of the datasets. 

 Step2: We checks for the 7 data quality dimension issues.
 
#### 1- Reliability

The data source is trustworthy; it comes from the Kaggle.

#### 2- Timeliness

The data provided is current and accurately represents the situation.

#### 3- Consistency

As we have different ranking methodology for each data sets so, the logical meaning of the column accept different values for the same data items.

#### 4- Relevance

- Sample Appropriateness: The data sample aligns with analysis objectives.

- Variable Selection:
  - **In Shanghai Ranking:** All the columns are important and related to our question. Just we need to add further column for universities countries.
  - **In Times Ranking:**
  - **In World University Rankings:** All the columns are related to our questions but the year column we are no longer need it after filtered the data.

#### 5- Uniqueness

Here we checked for the duplicated values. 

#### 6- Completeness

Here we checked for the Null values. 

#### 7- Accuracy

Here we checked for the data foramat and the outlier values. 

### 2- Data Cleaning:

We handle the issues that appear in the 4 dimensions (Variable Relevance, Uniqueness, Completeness, Accuracy). 

### 3- Univariate, Bivariate, Multivaiate Analysis:

Using visualization and statistics for one, two and more columns to understand their distribution and look at the relationships between variables. 

----

## Final Insights: 

1- In Shanghai ranking, USA universities takes most of top 10 ranks.

<img width="1268" alt="Screenshot 1446-08-14 at 2 10 34 AM" src="https://github.com/user-attachments/assets/fc854310-c474-402b-a9ec-e5c29d5161a1" />

2- In Shanghai ranking, USA universities occupy 37% of the ranks out of top 100 universities.

<img width="1297" alt="Screenshot 1446-08-14 at 2 12 09 AM" src="https://github.com/user-attachments/assets/54905700-4c7e-4da5-a35f-c3c40a0d4e02" />

3- In Shanghai ranking, Saudi Arabia is the Arab country whose universities are ranked the most in shanghia ranking compared to other Arab countries.

<img width="1279" alt="Screenshot 1446-08-14 at 2 13 10 AM" src="https://github.com/user-attachments/assets/e7985b11-1b16-482d-9fbb-1d6955f7911e" />

4- In Shanghai ranking, Arab universities are late in researching as few universities that appear in top 300 ranks.

<img width="1302" alt="Screenshot 1446-08-14 at 2 14 41 AM" src="https://github.com/user-attachments/assets/dbd34e43-71e9-4166-a936-e7dd0437ccf5" />

5- In Shanghai ranking, saudi arabia universities takes a rank in almost all ranks intervals. 

<img width="1297" alt="Screenshot 1446-08-14 at 2 15 59 AM" src="https://github.com/user-attachments/assets/06164d96-f5fd-4ebe-a3cb-4b83eda70d90" />

6- In caterer for world University Ranking, the almost top 10 University in the world located in the USA that points to the strength of the outputs of American University.

<img width="1255" alt="Screenshot 1446-08-14 at 2 25 26 AM" src="https://github.com/user-attachments/assets/5c679ec4-59e1-4651-89a2-575ad862cf69" />

7- France accounts for 40% and the USA for 30% of the countries represented in the top 10 universities by employability rank, according to the Center for World University Rankings 2024. 

<img width="1322" alt="Screenshot 1446-08-14 at 2 26 16 AM" src="https://github.com/user-attachments/assets/367ed79f-ce2f-4833-bf4d-3361fac9091c" />

8- According to the Center for World University Rankings 2024, this chart highlights that Arab countries have relatively weak research rankings, which significantly affect their overall positions in the list of the world's top universities.

<img width="1334" alt="Screenshot 1446-08-14 at 2 26 47 AM" src="https://github.com/user-attachments/assets/29dc02dc-dd28-489a-9b2f-74931a5df96b" />

9- Globally, the research factor plays a pivotal role in significantly influencing a university's overall rank, according to the Center for World University Rankings 2024.

<img width="1292" alt="Screenshot 1446-08-14 at 2 27 13 AM" src="https://github.com/user-attachments/assets/43522492-a36d-41e3-9d54-19a7f3d34064" />

10 -  In Times ranking, USA universities also takes most of top 10 ranks.

<img width="1277" alt="Screenshot 1446-08-14 at 8 58 28 AM" src="https://github.com/user-attachments/assets/a6167b68-cbc4-4355-934b-62566a60532f" />
