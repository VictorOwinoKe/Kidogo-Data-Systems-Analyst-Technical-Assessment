# Kidogo Data Systems Analyst Technical Assessment

## Introduction
Welcome to the Kidogo Data Systems Analyst Technical Assessment! In this assessment, you are provided with an Excel file named 'assignment dataset' that contains valuable data on daycares that have enrolled in Kidogo's Quality Improvement Program (QIP) and their transition to become Kidogo members. Your task is to analyze the data, calculate essential metrics, and present your findings to the business stakeholders.

## Dataset Overview
The Excel file consists of four tabs, each containing specific data as follows:

1. **qip_data**: This tab contains information about daycares enrolled in the Quality Improvement Program (QIP). Each row represents a daycare with its respective details.

2. **joining_session_data**: This tab includes data on the daycares that have completed the QIP program and signed a contract to become Kidogo members. Each row represents a community along with its daycares that have signed the contract. The daycares that have signed the contract are listed in the 'kidogo_code_signed_contract' column.

3. **qip_metadata**: A data dictionary that provides a description of the columns in the 'qip_data' tab.

4. **joining_session_metadata**: A data dictionary that provides a description of the columns in the 'joining_session_data' tab.

## Task Description
Your main objectives in this assessment are:

1. **Preprocessing**: Utilize Python, preferably Google Colab, to preprocess the 'joining_session_data' and 'qip_data'. During this step, please take note of any data quality issues encountered during the cleaning process. These issues should be documented in your summary report.

2. **Reporting**: Provide a summary report that includes the following key metrics:
   - Conversion rate: Calculate the percentage of QIP daycares that transitioned into Kidogo members per community.
   - Collection rate: Determine the average collection rate of the QIP fee per community.

3. **Presentation**: Create a PowerPoint or Google Slides presentation that you will deliver to the business stakeholders during a one-on-one interview. Identify and communicate any key insights and recommendations derived from your analysis.

## Instructions
1. Use Python, particularly Google Colab, for data preprocessing and analysis.
2. Summarize the findings in a well-structured report, including visualizations where appropriate.
3. Prepare a PowerPoint or Google Slides presentation for the one-on-one interview with business stakeholders.
4. Present your key insights and recommendations in a clear and concise manner.

## Submission
You have 2 hours (from 2.00pm to 4.00pm) to complete this assignment and submit the zip file to hr
anything shared after 4.00pm will NOT be considered for grading.

## My Solution
## A. Data Processing

1. **Loaded the Assessment Dataset:**:  I used Pandas rad excel in Google Colab to load the Excel file containing the assessment dataset. The dataset consists of multiple sheets, each containing specific data related to the QIP and joining sessions.

2. **Loaded Sheets into a Dictionary:** To efficiently handle multiple sheets, I organized the data into a dictionary, where the keys represent the sheet names, and the values are DataFrames containing the respective data for each sheet. This approach allows for easy access to specific data when needed for analysis.

3. **Accessed Data for Each Sheet:**  With the sheets loaded into a dictionary, I can now access the data for each sheet using the sheet names as keys. This enabled me to work with individual DataFrames independently, making it convenient for analysis and manipulation.

<img width="661" alt="image" src="https://github.com/VictorOwinoKe/Kidogo-Data-Systems-Analyst-Technical-Assessment/assets/56676033/6ecafb11-56d8-49de-96e8-5d1c542c380f">

4. **Data Cleaning and Feature Engineering:**   Data cleaning and feature engineering are crucial steps in preparing the dataset for analysis. During this step, I addressed missing or incorrect data, handled duplicates, and created new features or analytical measures (KPIs) relevant to the assessment's objectives.

5. **Writing Cleaned Datasets to Excel:**   Using the Pandas Excel Writer, I successfully wrote the cleaned datasets 'cleaned_qip_data' and 'cleaned_joining_session_data' into an Excel file. This file now contains two tabs, making it easy to access the cleaned data for future use or sharing.

   <img width="682" alt="image" src="https://github.com/VictorOwinoKe/Kidogo-Data-Systems-Analyst-Technical-Assessment/assets/56676033/5ecd5106-72d2-48ce-99ac-b7c4192cffdd">

## B. Data Visualization and Presentation with Power BI 

I loaded the cleansed dataset into Power BI, so I can create compelling data visualizations and interactive dashboards. This step enables me to showcase the analysis results and KPIs in a visually appealing and user-friendly manner.

1. **Calculated Conversion Rate and Collection Rate:** Utilized the cleaned datasets to calculate the conversion rate and collection rate for each community based on the KPIs  derived.

 <img width="861" alt="image" src="https://github.com/VictorOwinoKe/Kidogo-Data-Systems-Analyst-Technical-Assessment/assets/56676033/f813a3c8-e8c5-405b-a046-000b8fa648b5">

<img width="868" alt="image" src="https://github.com/VictorOwinoKe/Kidogo-Data-Systems-Analyst-Technical-Assessment/assets/56676033/3efa9291-8ac6-470a-8624-ad603652298c">

3. **Creating Visualizations in Power BI:**  Developed data visualizations, such as bar charts, pie charts, and tables, to present the KPIs and insights effectively. customized the visuals to highlight key findings and make the presentation engaging.Organize the content logically and ensure it aligns with the business stakeholders' expectations.
## C. Data Story Telling with Power BI 

 Page 1: **About Myself**
 
<img width="842" alt="image" src="https://github.com/VictorOwinoKe/Kidogo-Data-Systems-Analyst-Technical-Assessment/assets/56676033/3841adff-e120-4edd-8e69-4648089afc9b">

 Page 2: **Conversion rate**

<img width="577" alt="image" src="https://github.com/VictorOwinoKe/Kidogo-Data-Systems-Analyst-Technical-Assessment/assets/56676033/95dd9d63-39af-4077-a3a2-3d20542a5004">

Page 3: **Collection rate**

<img width="577" alt="image" src="https://github.com/VictorOwinoKe/Kidogo-Data-Systems-Analyst-Technical-Assessment/assets/56676033/b44bbdf0-19ba-48ad-833e-16dba9b66fe6">

Page 4:**Insights & Recommendations**

<img width="576" alt="image" src="https://github.com/VictorOwinoKe/Kidogo-Data-Systems-Analyst-Technical-Assessment/assets/56676033/181311cc-d6d2-4654-98bb-06adedbc967f">

I am confident that the insights presented in the report and the Power BI presentation will aid the business stakeholders in making informed decisions to drive Kidogo's growth and success.

Thank you for the opportunity to participate in this assessment. I welcome any feedback and look forward to discussing the findings in further detail during the review meeting.

## Author

Connect with me on social media:

[![Facebook](https://img.shields.io/badge/Facebook-Profile-blue?style=flat-square&logo=facebook&logoColor=white)](https://www.facebook.com/VictorOwinoKe)


[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/victorowinoke/)

[Victor Owino](https://github.com/VictorOwinoKe) - [GitHub Profile](https://github.com/VictorOwinoKe)

---
## License
This project is licensed under the [MIT](LICENSE) License.
