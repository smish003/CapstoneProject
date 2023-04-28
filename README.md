# CapstoneProject
## Submitted By: Swati Mishra

# <ins>Analysis of Cancer Services, Financial Burden, and the effects of the Covid-19 disruptions in Healthcare </ins>

# Summary

Cancer is a broad category of diseases that can begin in practically any organ or tissue of the body when aberrant cells develop uncontrollably, cross their normal boundaries to infect other body parts, and/or spread to other organs. It was reported by [WHO](https://www.who.int/news-room/fact-sheets/detail/cancer) in February 2022 that One in six deaths, or around 10 million deaths in 2020 is due to cancer, making it the top cause of death globally. The most widespread cancers include breast, prostate, lung, colon, and rectum cancers. Lots of research are going around cancer treatments and drug effectiveness.

In order to acquire some insights from the data, I will be working on some of the cancer datasets in general which are made public by the National Cancer Institute and other platforms in my research study. 	In addition, I'll conduct some research on breast cancer, a subject that's highly popular among women these days. 

The American Cancer Society estimates that in the United States in 2022 ***“About 287,850 new cases of invasive breast cancer will be diagnosed in women. About 51,400 new cases of ductal carcinoma in situ (DCIS) will be diagnosed. About 43,250 women will die from breast cancer”***

This project will be divided into several phases, and the specified analysis such as Descriptive, Predictive, Statistical, and Data Analysis on certain parameters, will be performed. Each of the phases will be discussed in detail in the Project Overview.

# Motivation

One of the rapidly spreading diseases that affects many individuals worldwide is cancer. The main reason I'm interested in working on this project is because of a real-life occurrence in my family when my grandmother was diagnosed with cancer that had advanced and was no longer treatable. However, I discovered several further incidents close to my community since then. Today, several organizations are diagnosing various treatments and determining the best course of action.

A huge amount people come to treat their cancer in United States. Millions of people seeking medical care in the United States have selected from among a vast number of hospitals. Each hospital has a particular reputation that influences patients to pick it over another.

In my research study I would be analyzing some of the hospitals present in California which treats cancer patients and will try to identify possible lacking the resources and their issues being observed within their system and then they can use the report results to construct ways to address any potential problems in their system.

# System Architecture
The system architecture that needs to be followed to is listed below:

![image](https://user-images.githubusercontent.com/89666159/235035720-c443a96f-fe53-4acb-82cf-e0ec31d753b6.png)



# Overview of the Project Phases and Dataset

* **Phase-1(Number of Cancer Surgeries (Volume) Performed in California Hospitals):**

     *This dataset includes the information about the volume of annual cancer surgeries conducted in California hospitals for 11 different cancer kinds, including bladder, breast, brain, colon, esophagus, liver, lung, pancreatic, prostate, rectum, and stomach.*
 
 * **Phase-2(Hospital Characteristics List for California Providers in State Fiscal Year 2019-20):**
 
     *The dataset includes a list of 15 characteristics for hospitals serving the State of California in Fiscal Year 2019–20, such as OSHPD ID, HCAI Provider Name, Designated Neonatal Intensive Care Unit status as defined by DHCS, Designated Public Hospital status, Non-designated Public Hospital, HCAI Rural Hospital status, DHCS Designated Remote Rural status, Cost-to-Charge Ratio, Wage Index Value, Wage Index Value-Adjusted for California Neutrality, Unadjusted Statewide Base Rate, Wage-Adjusted Statewide Base Rate, Rehab Rate*
   
 * **Phase-3(Patients Leaving California Hospitals Against Medical Advice (AMA)):**
 
     *This dataset includes discharge numbers, and a breakdown of discharge counts by patients who left against medical recommendation. The information is separated into groups according to the year of discharge, admission type, patient age, anticipated payer, primary diagnosis, race/ethnicity group, and sex.*
 
  * **Phase-4(Comprehensive list of approved cancer medications created by the Anticancer Fund):**
 
     *The Anticancer Fund's CancerDrugs DB is a carefully managed database of approved cancer medications. The NCI, FDA, EMA, and other data sources provide the source data. The goal is to offer a database of approved medications used to treat cancer that can be easily filtered for researchers, doctors, and regulators. Drugs used for diagnostic purposes are not included, nor are those used to treat cancer symptoms or for other forms of supportive care. Additionally excluded are investigational medicines and substances utilized in clinical trials.*
     
 * **Phase-5(Financial Burden of Cancer Care):**
 
     *The national cancer-attributed medical care costs in the United States.*
     
 * **Phase-6(Effects of COVID-19 on Hospital Utilization Trends):**
 
     *In-hospital deaths in three hospital settings are counted in this dataset (inpatient discharges, emergency department, and ambulatory surgery). Asthma, cancer, cardiac arrest, chronic obstructive pulmonary disease (COPD), COVID-19, diabetes, homelessness, hypertension, obesity, pneumonia, respiratory arrest/failure, sepsis, and stroke are among the common medical conditions/categories for which monthly totals are provided for the entire state and are also included in the monthly totals for each of these conditions/categories.*
   
 * **Phase-7(Advanced Stage Breast Cancer Among Women 40 Years and Older, by Medical Service Study Area (MSSA), California Counties, 2010-2014):**
 
     *Geographical locations with a disproportionately high number of breast tumors detected at a late or otherwise advanced stage were identified by analysis of data from the population-based, statewide California Cancer Registry (CCR). The CCR provided information on women with a breast cancer diagnosis between January 1, 2010, and December 31, 2014, aged 40 and older. By comparing the percentage of upper-socioeconomic, non-Hispanic white women in counties and Medical Service Study Areas (MSSAs) with the percentage of late-stage breast cancer cases nationwide, proportional incidence ratios (PIRs) were computed.*
     
 * **Phase-8(Premise General Population COVID-19 Health Services Disruption Survey 2020):**
 
     *The COVID-19 Health Services Disruption Survey 2020 is a collection of surveys designed to measure the degree of disruption to various health services brought on by the COVID-19 pandemic and subsequent governmental directives and behavioral modifications to slow the disease's spread.76 nations participated in this survey, which was carried out utilizing the smartphone-based Premise data gathering technology. Individual people from the general population served as respondents. 52,492 respondents provided information that was gathered. The poll concentrated on the degree of interference with the delivery of general healthcare services, including access to healthcare professionals and prescription drugs. The survey was created primarily to evaluate the shift in service delivery levels before and right away after the start of the COVID-19 worldwide pandemic. It is not intended to use the survey's data to determine the overall quality of health service delivery.*
     
 * **Phase-9(Global Burden of Disease):**
 
     *This dataset consists of information about 30 years of data with the goal of providing timely, valid, and relevant assessments of critical health outcomes. It will be interesting to analyze the data with respect to 5 -10 years for all the health outcomes versus cancer disease. The dataset is obtained from Global Health Data Exchange (commonly known as GHDx). The Institute for Health Metrics and Evaluation's GHDx database compiles statistics on population health around the world (IHME). IHME is a non-profit research organization dedicated to finding the most effective ways to create a healthy society.*
     
 * **Phase-10(An Analysis of Cancer Data in the United States):**
 
     *The dataset was collected from the American Cancer Society portal and contains information on cancer incidence and mortality rates in the United States for the year 2023. It provides estimates for the number of new cancer cases and deaths by cancer type and gender. The dataset also includes cancer incidence rates from 2015-2019 and death rates from 2016-2020 based on cancer type, ethnicity, and age group. Furthermore, it includes historical data on cancer death rates by gender from 1930-2020. In addition, the dataset contains data on the probability of developing cancer from 2017-2019, as well as cancer mortality rates from the same time period. Finally, it includes information on cancer survival rates for different cancer types based on stages from 2012-2018.*
     
**Note -** *American Cancer Society portal which states that "In 2023 in the U.S., there will be an estimated 1,958,310 new cancer cases and 609,820 cancer deaths.* [American Cancer Society](https://cancerstatisticscenter.cancer.org)
     
  # Data Cleaning
  
  Data cleaning is a crucial step in the data preparation process that aims to identify and rectify any errors, inconsistencies, redundancies, and irrelevant data present in a raw dataset.It is crucial to make sure that the data used for analysis, visualization, modeling, or any other purpose is accurate and reliable.

The data cleaning process involves several steps, including data profiling, identifying inconsistencies, missing data, and duplicates, correcting errors and filling missing values, and finally, validating the cleansed data to ensure accuracy and consistency. The process may also include standardizing formats, removing outliers, and transforming data to meet specific requirements.

It  is necessary to address issues such as incomplete data, inconsistent formatting, software glitches, data entry errors, or incomplete/missing values, which can lead to inaccurate analysis, flawed business decisions, and misleading insights.
It enhances data quality and provides accurate and reliable information for making informed decisions. By eliminating irrelevant data and correcting errors, it minimizes the risk of data bias, improves data accuracy, and increases the efficacy of data-driven decisions.

**Note :** *I had performed data cleaning using **Open Refine** for all phases of the project, and I have provided a breakdown of the steps taken for each phase.*

### Phase-1 (Number of Cancer Surgeries (Volume) Performed in California Hospitals)
In this phase below steps are been carried out:
* Firstly, have renamed all the columns as per the provided data dictionary as shown below:
    * Surgery as Type of Cancer Surgery
    * #of cases (ICD-9)  as Number of Cases (ICD-9)
    * #of cases (ICD-10) as Number of Cases (ICD-10)
    * LONGITUDE as Longitude
    * LATITUDE as Latitude
<img width="635" alt="image" src="https://user-images.githubusercontent.com/89666159/226541504-adda9ffe-c543-4c4a-9e90-f3180b7c379d.png">

#### Before:
<img width="960" alt="1" src="https://user-images.githubusercontent.com/89666159/226542456-8bf74199-063e-490e-bf10-4711d50f8455.png">        

#### After:
<img width="958" alt="2" src="https://user-images.githubusercontent.com/89666159/226542475-2324a74f-74f1-4ed3-8b3f-595117385826.png">

* To clean the dataset, I initiated by clustering the data with Cluster and Edit technique to identify discrepancies in the data for the Hospital column. Following that, I cross-checked the hospital names on the internet to ensure their validity. The Clustering of data was been done using different methods and Keying Function.

<img width="751" alt="4" src="https://user-images.githubusercontent.com/89666159/226543223-092fc28a-f582-4020-a230-33f5438e9594.png">

<img width="744" alt="5" src="https://user-images.githubusercontent.com/89666159/226543285-221a373b-6ba2-42e2-b083-63bfa732be42.png">
    
<img width="743" alt="6" src="https://user-images.githubusercontent.com/89666159/226543272-e0a6852b-4967-4f4b-a2de-013b73f60dca.png">

* After successfully completing the above operation, I used the Text Facet approach to remove the Statewide Hospital data from the dataset,as it was not relevant for the analysis.
* Finally, I verified all the hospital names individually using the Text Facet feature.


### Phase-2 (Hospital Characteristics List for California Providers in State Fiscal Year 2019-20)

In this phase below steps are been carried out:

* Transformed Provider name as Title case.

<img width="959" alt="1" src="https://user-images.githubusercontent.com/89666159/226545077-196b1ace-4344-4ac5-a048-8c3ecf4f3ca8.png">
<img width="959" alt="2" src="https://user-images.githubusercontent.com/89666159/226545078-09e8c7b7-a5b2-475b-8030-58b9d6789830.png">

* Renamed all the columns as per the attached provided data dictionary:
    * DPH as Designated Public Hospital
    * NDPH as Non-Designated Public Hospital

[Data-Dictionary for Phase-2](https://github.com/smish003/CapstoneProject/files/11025972/data-dictionary.csv)

<img width="959" alt="3" src="https://user-images.githubusercontent.com/89666159/226546103-a19bb9d6-8e5d-46b6-b5b3-3dc10a7e9f0c.png">

* To clean the dataset, I initiated by clustering the data with Cluster and Edit technique to identify discrepancies in the data for the Provider Name column. Following that, I cross-checked the Provider Name on the internet to ensure their validity. The Clustering of data was been done using different methods and Keying Function.

<img width="749" alt="4" src="https://user-images.githubusercontent.com/89666159/226546295-e3514115-0608-4d2b-80b4-470666927b35.png">

### Phase-3 (Patients Leaving California Hospitals Against Medical Advice (AMA))

In this phase, No data cleaning was required as the data collected was already in an appropriate format and contained no inconsistencies, redundancies, or irrelevant data. Therefore, the data was suitable for the research study, and there was no need for any additional data cleaning.Moreover, it ensures that the research study is founded on dependable and precise data, resulting in more resilient and reliable research outcomes.

### Phase-4 (Comprehensive list of approved cancer medications created by the Anticancer Fund)

In this phase, No data cleaning was required as the data collected was already in an appropriate format and contained no inconsistencies, redundancies, or irrelevant data. Therefore, the data was suitable for the research study, and there was no need for any additional data cleaning.Moreover, it ensures that the research study is founded on dependable and precise data, resulting in more resilient and reliable research outcomes.

### Phase-5 (Financial Burden of Cancer Care)

In this phase, the data regarding healthcare expenses in the United States has been classified in two ways.
 * National Expenditure
    * Medical Services
    * Prescription Drugs
    * Total Cost
 * Per-Patient Cost
    * Medical Services
    * Oral Prescription Drugs
 The given dataset does not require any essential cleansing since it is already in an appropriate format and can be directly utilized for the research study.
 
 ### Phase-6 (Effects of COVID-19 on Hospital Utilization Trends)
 
 In this phase, the given data has been classified into various categories:
 * Hospital Utilization Trends
 * In Hospital Mortality Trends By Secondary Diagnosis
 * In Hospital Moratlity Trends By Diagnosis Type
 * In Hospital Moratlity Trends By Health Category
 * Utilization Trends By Health Category

Each of these categories were cleaned seperately as shown below:

#### Hospital Utilization Trends
In this phase below steps are been carried out:
* Firstly, Splitting the Date Column in Month and Year Seperately as Date Column contains both value.
<img width="959" alt="1" src="https://user-images.githubusercontent.com/89666159/226555046-7d70048c-9a4f-48cb-bd31-374b55595ea1.png">

* After splitting the data into Date 1 and Date 2, the column was renamed as Month and Year, respectively.
<img width="911" alt="4" src="https://user-images.githubusercontent.com/89666159/226556091-b44f06ae-8622-4c18-a688-136605028127.png">

 * Finally the Month and Year Columns values was been replaced Using GREL expression as shown below:

 <img width="959" alt="2" src="https://user-images.githubusercontent.com/89666159/226555081-8f565388-6ac9-4239-8fcc-12b4420b722d.png">
 
 <img width="960" alt="3" src="https://user-images.githubusercontent.com/89666159/226555692-9ff53536-36a6-4f88-b5d3-fc6d5b1ddded.png">

  #### In Hospital Mortality Trends By Secondary Diagnosis
  In this phase below steps are been carried out:
  
  * The unnecessary column named Date , which contains the month and year in it, was removed as we already have separate fields for each.
 
  <img width="960" alt="1" src="https://user-images.githubusercontent.com/89666159/226556636-fdb710d5-a901-4a8a-aa0d-a05cb6a3453a.png">
  
 * Replacing Month Number with Month Name as shown below using GREL expression:
 <img width="739" alt="3" src="https://user-images.githubusercontent.com/89666159/226557094-eaaa1253-c0b8-4e48-8dd0-98a0e4a6fb54.png">

#### In Hospital Mortality Trends By Diagnosis Type
 In this phase below steps are been carried out:
* The unnecessary column named Date , which contains the month and year in it, was removed as we already have separate fields for each.

<img width="960" alt="1" src="https://user-images.githubusercontent.com/89666159/226557542-7239a696-18ab-4f88-b609-44d1fde9a9ca.png">

* The values in the Month column were changed from month numbers to month names using the Text Facet Option.

<img width="951" alt="2" src="https://user-images.githubusercontent.com/89666159/226557893-d8365e11-ca26-45bc-84fa-905228e68868.png">

#### In Hospital Mortality Trends By Health Category
 In this phase below steps are been carried out:
 * Firstly, Splitting the Date Column in Month and Year Seperately as Date Column contains both value.
 
<img width="955" alt="1" src="https://user-images.githubusercontent.com/89666159/226558252-48d91fc3-b420-4e19-b703-9d0eb369b90d.png">


* After splitting the data into Date 1 and Date 2, the column was renamed as Month and Year, respectively.

<img width="947" alt="2" src="https://user-images.githubusercontent.com/89666159/226558296-e0875693-a63f-4148-8aab-9716bfd9e7f7.png">

* The values in the Month column were changed from month numbers to month names using the Text Facet Option.

<img width="959" alt="3" src="https://user-images.githubusercontent.com/89666159/226558598-2af1b4a1-fe17-428a-be20-2633979f1dd2.png">

#### Utilization Trends By Health Category
 In this phase below steps are been carried out:
  * Firstly, Splitting the Date Column in Month and Year Seperately as Date Column contains both value.
  
  <img width="960" alt="1" src="https://user-images.githubusercontent.com/89666159/226559187-5ed0bfb6-f26d-45d2-8cbd-aefb7edcd8c3.png">
  
* After splitting the data into Date 1 and Date 2, the column was renamed as Month and Year, respectively.

<img width="959" alt="2" src="https://user-images.githubusercontent.com/89666159/226559300-af7985e8-9dd5-4a90-aea5-3b178e52d678.png">

* Renaming Month Column values as Shown below:
    * 18 - 2018
    * 19 - 2019
    * 20 - 2020
    * 21 - 2021
    
<img width="957" alt="3" src="https://user-images.githubusercontent.com/89666159/226559687-b8b92dee-7a21-4648-98b1-24f0bdbde9aa.png">

  * Removed the unwanted rows *(i.e., 2 rows)* which doesn’t contains Month and Year information in it:
  
<img width="960" alt="4" src="https://user-images.githubusercontent.com/89666159/226559899-ee4afd25-7df7-4a5d-b18f-d25504e1469e.png">

* The values in the Month column were changed from Month Name Suffix to Full Month Name using the Text Facet Option.
<img width="960" alt="5" src="https://user-images.githubusercontent.com/89666159/226560487-1a2ceb4b-6eac-419c-a5b6-f7bc38e892b6.png">

<img width="959" alt="6" src="https://user-images.githubusercontent.com/89666159/226560454-59e4bb05-c736-46a1-965f-fd42c76af050.png">


 ### Phase-7 (Advanced Stage Breast Cancer Among Women 40 Years and Older, by Medical Service Study Area (MSSA), California Counties, 2010-2014)

For this phase, the dataset was downloaded from:  https://cdphdata.maps.arcgis.com/apps/webappviewer/index.html?id=8612fd4394784bdea7b0bdca5e34fc2e

In this phase, No data cleaning was required as the data collected was already in an appropriate format and contained no inconsistencies, redundancies, or irrelevant data. Therefore, the data was suitable for the research study, and there was no need for any additional data cleaning.Moreover, it ensures that the research study is founded on dependable and precise data, resulting in more resilient and reliable research outcomes.

 ### Phase-8 (Premise General Population COVID-19 Health Services Disruption Survey 2020)
 
 In this phase below steps are been carried out:
 * Renaming the Columns name as per data dictionary
    * observation_id - Observation ID
    * submitted_time - Date and time survey was submitted
    * gender - What is your gender?
    * Age - What is your age?
    * Geography - Where do you live?
    * financial_situation - What is your current financial situation?
    * Education -What is the highest level of schooling you have completed?
    * employment_status	- What is your current employment status?
    * Ethnicity -	What is your ethnicity?
    * religion	- What is your religion?
    * gp_hh -On average, in the last six months, how many members usually live in your household, counting yourself?
    * gp_pre_provider_need	- During December-February, did you have a need to see a health provider?
    * gp_pre_provider_condition -	What health condition(s) required you to see a health provider during December-February?
    * gp_pre_provider_condition_other	- Specify the other condition that required you to see a health provider during December -February.
    * gp_pre_provider_visit - Were you able to see a health provider during December-February?
    * gp_pre_provider_where - Where did you see a health provider between February - December?
    * gp_pre_provider_where_other	- Where else did you see a health provider between December - February?
    * gp_pre_provider_num_visit -	How many times did you see a healthcare provider during December - February?
    * gp_pre_provider_why- What was the reason you were not able to see a health provider during December-February?
    * gp_pre_provider_why_other - Specify the other reason you were not able to see a health provider.
    * gp_post_provider_need	- Since March, did you have a need to see a health provider?
    * gp_post_provider_condition - What health condition(s) required you to see a health provider since March?
    * gp_post_provider_condition_other - Specify the other condition that required you to see a health provider since March.
    * gp_post_provider_visit - Were you able to see a health provider since March?
    * gp_post_provider_where - Where did you see the health provider since March?
    * gp_post_provider_where_other  - Where else did you see the healthcare provider since March? 
    * gp_post_provider_num_visit  - How many times did you see a healthcare provider since March?
    * gp_post_provider_why  - What was the reason you were not able to see a health provider since March?
    * gp_post_provider_why_other  - For what other reason were you not able to see a health provider since March?
    * gp_medication  - In the last 6 months, did you have a health condition that required you to take medication?
    * gp_medication_condition  - What health condition(s) did you require medication for in the past six months?
    * gp_pre_miss_dose  - During December-February, did you miss any doses of medication?
    * gp_pre_num_miss_dose  - On average during a week, how many doses did you miss December - February?
    * gp_pre_miss_dose_why  -   What was the reason you missed a dose of your medication December - February?
    * gp_pre_miss_dose_why_other  - What was the other reason you missed a dose of your medication during December - February?
    * gp_post_miss_dose  - Since March, did you miss any doses of medication?
    * gp_post_num_miss_dose  - On average during a week, how many doses did you miss since March?
    * gp_post_miss_dose_why  - What was the reason you missed a dose of your medication since March?
    * gp_post_miss_dose_why_other  -  What was the other reason you missed a dose of your medication since March?
    * gp_post_labor_force  - Last week, did you do any work for pay, do any kind of business, farming or other activity to generate income, even if only for one hour?
    * gp_pre_labor_force  - Were you working during December-February?
    * gp_unemployment_why  - What was the main reason you stopped working?
    * gp_unemployment_why_other  - What was the other reason you stopped working?
    * gp_pre_income  -  During December-February, what was your personal average income in a month?
    * gp_post_income  - Since March, what was your personal average income in a month?weight  - Survey weight
    * country - Country
    * user_id - User ID


**Note:** *Date and time survey was submitted column was splited into Date, Time, and Time Zone column respectively.*

<img width="959" alt="1" src="https://user-images.githubusercontent.com/89666159/233909404-d3362b3b-9008-4e2f-8502-3f44b32698dc.png">

* As the time zone column only consist of value as UTC which is Universal Time Coordinated (UTC). So, removing that column as its not needed for the analysis.
* Renamed Age column values using text facet as below:

<img width="212" alt="2" src="https://user-images.githubusercontent.com/89666159/233909604-b18923fe-8f24-4d87-ad96-3cbd1d05fcf7.png">

   * 16 to 25 years old - 16-25
   * 26 to 35 years old - 26-35
   * 36 to 45 years old - 36-45
   * Over 45 years old - 45+

Removing the blank fields from the gender column.

<img width="960" alt="3" src="https://user-images.githubusercontent.com/89666159/233910059-4ae11d0a-c2aa-4fb6-a310-af396cfd69d2.png">

Since we have an ethnicity column, we can eliminate the religion column as it is not relevant to our study.

<img width="957" alt="4" src="https://user-images.githubusercontent.com/89666159/233910274-a2b37b64-866d-4537-96d7-1cc18335247f.png">

The column 'Specify the other condition that required you to see a health provider during December-February' only has two values - 'XXXX' and blank - which are not necessary for the study. Therefore, they will be removed.

<img width="959" alt="5" src="https://user-images.githubusercontent.com/89666159/233910385-8342b982-4c50-405c-b41f-d8371e082a63.png">

Removing unwanted column:

1.	What is your current financial situation?
2.	Where else did you see a health provider between December - February?
3.	Specify the other reason you were not able to see a health provider?
4.	Specify the other condition that required you to see a health provider since March
5.	Where else did you see the healthcare provider since March?
6.	For what other reason were you not able to see a health provider since March?
7.	What was the other reason you missed a dose of your medication during December - February?
8.	What was the other reason you missed a dose of your medication since March?
9.	What was the other reason you stopped working?
10.	Time

### Phase-10(An Analysis of Cancer Data in the United States)

In this phase, the dataset was cleaned using Microsoft Excel, as the only necessary modifications were reorganizing and restructuring the data for the purpose of the study.

 # Data Analysis

Data analysis is the methodical process of looking at and evaluating data with the intention of finding pertinent facts and insights that can guide decision-making.For firms trying to make data-driven decisions that can help them function more effectively and efficiently in today's business environment, data analysis is essential. Businesses can learn more about consumer behavior, market trends, operational inefficiencies, and other elements that affect their performance and bottom line by studying data. Utilizing this data can help businesses run more profitably, increase customer satisfaction, enhance product and service quality, and optimize operations. Organizations can make better judgments based on evidence rather than intuition with the aid of data analysis.

To begin with data analysis,all the above mentioned dataset was first cleaned using Open Refine.  Once the data was cleaned, it was uploaded to Tableau using the ***Connect to Data*** option and selecting ***Microsoft Excel*** as the file type. Several worksheets was been made to examine each dataset once it had been successfully uploaded, and it was then merged into a dashboard which consists of several worksheets.
**Tableau**  *uses a workbook and sheet file structure, much like Microsoft Excel. A workbook contains sheets. A sheet can be a worksheet, a dashboard, or a story.*
* **Worksheet -**  *It contains a single view along with shelves, cards, legends, and the Data and Analytics panes in its side bar.*
* **Dashboard -**  *It is a collection of views from multiple worksheets. The Dashboard and Layout panes are available in its side bar.*
* **Story -** *A story contains a sequence of worksheets or dashboards that work together to convey information.* 


### An Analysis of California Hospitals: Cancer Surgery Volume, Hospital Characteristics, and Patients Leaving Against Medical Advice (AMA) in Fiscal Year 2019-20

**Note -** *Above analysis was carried out using a combination of Phase-1, Phase-2, and Phase-3.*

To begin analyzing the above data, the dataset was first cleaned using Open Refine and then uploaded to Tableau using Connect to Data Option and choosing  ***Microsoft Excel*** as a File Type. Several worksheets had been made to examine the dataset once it had been successfully uploaded, and it was then merged into a dashboard which consists of several worksheets.

The tableau dashboards are presented in the images below:

![image](https://user-images.githubusercontent.com/89666159/235051146-b0c2a237-47a9-488d-8220-1ebe26615f7f.png)

*The dashboard above shows the number of various cancer cases in California counties that are classified using the ICD-9 according to various cancer types. The visualization is accessible in real time, and values for various counties and cancer operation types can be verified using the legend located on the right side.
While validating the map it was been observed that not all cancer types surgeries were performed in all the counties during 2019-2020.Furthermore, it was been observed that,compared to other counties in California, Los Angeles was the hub where the majority of surgeries for all cancer types were performed.*

**Note:** *ICD-9 is refered as an International Classification of Diseases, 9th revision which is a coding system used to classify and code diagnoses, symptoms, and procedures related to medical conditions. ICD-9 codes were used extensively in the United States until October 1, 2015, when they were replaced by ICD-10 codes.
ICD-9 cases refer to cases or diagnoses that are classified using the ICD-9 coding system. In medical research and clinical practice, ICD-9 codes are used to identify and track specific medical conditions, procedures, and treatments.*

![image](https://user-images.githubusercontent.com/89666159/235048372-e3d0d9dc-cde1-47c0-816d-e0cf9241f4a5.png)

*The dashboard above shows the number of various cancer cases in California counties that are classified using the ICD-10 according to various cancer types. The visualization is accessible in real time, and values for various counties and cancer operation types can be verified using the legend located on the right side.
While validating the map it was been observed that not all cancer types surgeries were performed in all the counties during 2019-2020.Furthermore, it has been observed that, compared to other counties in California, Los Angeles was the hub where the majority of surgeries for all cancer types were performed.*

**Note:** *ICD-10 is refered as an International Classification of Diseases, 10th revision which is a coding system used to classify and code diagnoses, symptoms, and procedures related to medical conditions. ICD-10 codes replaced ICD-9 codes in the United States on October 1, 2015.ICD-10 cases refer to cases or diagnoses that are classified using the ICD-10 coding system. In medical research and clinical practice, ICD-10 codes are used to identify and track specific medical conditions, procedures, and treatments. The ICD-10 system provides more detail and specificity compared to the ICD-9 system, allowing for more accurate tracking and analysis of medical conditions.*


![image](https://user-images.githubusercontent.com/89666159/235051052-ca43a915-f19e-4524-9088-3ac39d53b043.png)


*The stacked bar chart presented above illustrates the evaluation of cancer surgery facilities based on cancer type in different California Counties.The visualization is accessible in real time, and values for various counties and cancer operation types can be verified using the legend located on the right side.*

![image](https://user-images.githubusercontent.com/89666159/235051880-34d0ac8a-4c1f-4995-a80e-559d33f92d11.png)


*The above dashboard exhibits the historical trend of cancer surgeries that have been performed between 2013 and 2021, including both actual data and estimated forecasts.*

![image](https://user-images.githubusercontent.com/89666159/235046843-cce7b9f2-157a-4856-bc0f-a66811ca49d5.png)

*The graph presented above displays an exploration of discharge counts across various segments, including* ***Admission Type, Age, Expected Payer, Primary Diagnosis, Race/Ethinicity Group, Sex*** *Each segment is further broken down into sub-categories for more detailed analysis.*

![image](https://user-images.githubusercontent.com/89666159/235046892-532f55d6-4d24-4e28-adf3-80b47c4f87dc.png)

*The table above illustrates the Differences Between All Discharges, AMA Discharges, and Repeated AMA Discharges about the Patients Leaving California Hospitals Against Medical Advice (AMA).The table can be accessed dynamically.*

![image](https://user-images.githubusercontent.com/89666159/235046936-0a8c4320-f418-4de2-9f0f-d43c749c8c90.png)

*The above dashboard is designed to check different types of designated hospital in California for Fiscal-Year 2019-2020.*

Below is a list of designated/non-designated hospitals in California along with their respective frequency counts.
* Designated NICU by Department of Health Care Services
* Designated Public Hospital by Department of Health Care Services
* Non-Designated Public Hospital by Department of Health Care Services
* Designated Remoted Rural Hospital by Department of Health Care Services
* Designated Rural Hospital by Department of Health Care Services

*Upon analyzing the values in the above chart, it was discovered that the majority of the designated hospitals were categorized as rural hospitals by the Department of Health Care Services with respect to other categories.*

![image](https://user-images.githubusercontent.com/89666159/235046958-26402fe7-44a7-477a-87c4-d97d15fa8c18.png)

*The bubble chart featured in the above dashboard provides information regarding OSHPD provider names and their counts in California. It is evident from the chart ***Kaiser Foundation Hospital*** *has the highest number of hospitals.*

**Note:** *OSHPD (Office of Statewide Health Planning and Development) is a state agency in California responsible for collecting, analyzing, and disseminating health care data. In California, OSHPD providers refer to healthcare facilities that are licensed or certified by OSHPD, including hospitals, nursing homes, hospices, and clinics. OSHPD collects data from these facilities and uses it to develop healthcare policies and programs, as well as to monitor healthcare trends and outcomes across the state.*

![image](https://user-images.githubusercontent.com/89666159/235047004-0b0437c5-6f63-4b4a-829d-c172eb390e63.png)

*The table present above shows different factors contributing to the characteristics of California hospital based on different OSHPD provider.The dashboard allows for dynamic changes to the OSHPD provider value, facilitating the examination of values across different factors.*

In conclusion, the numerous dashboards discussed above offer insightful information about cancer cases, procedures, and healthcare facilities in California. The cancer case maps for ICD-9 and ICD-10 show that Los Angeles has the greatest percentage of surgery for all cancer kinds and that not all cancer procedures are carried out in all counties. The stacked bar graph makes it possible to compare the types of cancer surgical centers in various California counties. Additionally, from 2013 to 2021, the historical trend dashboard displays the development of cancer surgeries along with projected estimates. Lastly, the bubble chart lists OSHPD providers and their numbers in California, showing that Kaiser Foundation Hospital has the most hospitals. Overall, the information provided by these visualizations is helpful for healthcare practitioners and the general public.

The entire dashboard for the above visualization can be accessed [here](https://public.tableau.com/views/AnAnalysisofCaliforniaHospitalsCancerSurgeryVolumeHospitalCharacteristicsandPatientsLeavingAgainstMedicalAdviceAMAinFiscalYear2019-20/QuantifyingCancerSurgeryVolumesAnAnalysisofCaliforniaHospitalDatabasedonICD-09?:language=en-US&:display_count=n&:origin=viz_share_link)


### Life-Saving Cancer Treatments: A Comprehensive Guide to Approved Medications

To begin analyzing the above data, the dataset was first cleaned using Open Refine and then uploaded to Tableau using Connect to Data Option and choosing  ***Microsoft Excel*** as a File Type. Several worksheets had been made to examine the dataset once it had been successfully uploaded, and it was then merged into a dashboard which consists of several worksheets.

The tableau dashboards are presented in the images below:

*The dashboard presented below displays the distribution of various cancer medicines that have been approved by different providers,including* ***FDA, EN, EMA, and Generic.***
* FDA: Food and Drug Administration
* EN:  European National Approval
* EMA: European Medicines Agency

*This information provides an overview of the different medications available for treating cancer and the regulatory bodies responsible for approving them.Users can interact with the dashboard in real-time to explore the distribution of medicines across different providers.*

![image](https://user-images.githubusercontent.com/89666159/235058662-d1122894-7dc5-426c-8e35-dbec1f9adfe7.png)

*The World Health Organization (WHO), a worldwide public health body, has designated a number of cancer pharmaceuticals, and the dashboard below displays these allocations together with a list of medications approved by various providers for various forms of cancer treatment. It offers a graphic depiction of the number of authorized drugs, organized according to the agency in charge of issuing the authorisation, such as FDA, EMA, EN, Generic, and WHO based on year (from 1939-2023). The distribution of cancer medications approved by multiple providers can be examined using this data, and the approval procedures of various providers can be contrasted. Additionally, it offers a thorough list of approved medications, together with information on the cancer types to which each one is matched and the provider who approved them, making it easy for users to find the specific details they need.*

![image](https://user-images.githubusercontent.com/89666159/235058702-384c8543-438a-40a8-b1a6-d857a54abb54.png)

In summary, the dashboard presented above provides valuable insights into the distribution of cancer medications approved by different providers, including the World Health Organization (WHO), FDA, EN, EMA, and Generic. The data is organized by year and cancer type, allowing users to explore the approval procedures of different regulatory bodies and compare the number of authorized drugs.The data in this dashboard can assist healthcare professionals and researchers in gaining a better understanding of the cancer treatment landscape and the various medications available for treating different types of cancer.













