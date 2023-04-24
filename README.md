# CapstoneProject
## Submitted By: Swati Mishra

# <ins>Insights in Cancer Data: The Power of Analysis </ins>

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
 
