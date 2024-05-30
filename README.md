# 📊 Analyses of Customer Service Data using Microsoft Excel

## Table of Contents

- [Project Overview](#project-overview)
- [Data Description](#data-description)
- [Software/Tools](#softwaretools)
- [Business Objective](#business-objective)
- [Project Goals](#project-goals)
  - [Customer Sentiment Analysis](#customer-sentiment-analysis)
  - [Root Cause Analysis](#root-cause-analysis)
  - [Service Response Time Analysis](#service-response-time-analysis)
  - [Customer Segmentation](#customer-segmentation)
  - [Trends and Patterns Identification](#trends-and-patterns-identification)
- [CRISP-DM Methodology](#crisp-dm-methodology)
  - [1. Business Understanding](#1-business-understanding)
  - [2. Data Understanding](#2-data-understanding)
  - [3. Data Preparation](#3-data-preparation)
  - [4. Data Analysis](#4-data-analysis)
  - [5. Results and Insights](#5-results-and-insights)
  - [6. Deployment](#6-deployment)
- [Expected Deliverables](#expected-deliverables)
- [Artifacts](#artifacts)
- [License](#license)
- [Contact](#contact)
- [How to Use](#how-to-use)
- [License](#license)
- [Contact](#contact)

## 📝 Project Overview
iVision is a well-known analytics firm that recently collaborated with Nile, an E-commerce company, to improve their customer service. Nile wants insights on their customer service request data to make better business decisions and enhance their services. iVision is responsible for creating an analytics report based on this data.

## Data Description
- **Id**: Unique Customer id
- **customer_name**: Name of the customer
- **sentiment**: Sentiment of the customer (Neutral, Positive, Very Positive, Negative, Very Negative)
- **csat_score**: Customer Satisfaction Score (Scale of 1 to 10, 1 being lowest and 10 being Highest)
- **call_timestamp**: Date on which the call was made by the customer
- **call_day**: Day of the Call (1 represents call was made on 1st of the month, similarly for other numbers)
- **reason**: Reason why the customer called (Billing Question, Service Outage & Payments)
- **city**: City to which the customer belongs
- **state**: State to which the customer belongs
- **channel**: Mode of communication that customer used (Call-center, Chatbot, Email, Web)
- **response_time**: How fast the customer request was serviced (SLA level: Above SLA, Below SLA, Within SLA)
- **call_duration_in_minutes**: Duration of the call
- **call_center**: Location of the call center where service request was handled

## Software/Tools
- Microsoft Excel
- Microsoft Powerpoint

## Business Objective
The analysis aims to leverage data-driven approaches to optimize customer service processes, enhance customer experience, and drive overall business growth. By examining historical customer service data, the project seeks to identify patterns, trends, and opportunities for improvement, ultimately leading to enhanced customer loyalty and increased operational efficiency.

## 🔄 CRISP-DM Methodology:
- The choice of analytics framework for a task or project depends on the specific objectives, complexity, and nature of the project. Here we’ll be using CRISP-DM for this Project.
- CRISP-DM stands for Cross-Industry Standard Process for Data Mining. It's a widely used methodology in the field of data mining and analytics. The approach is a structured and comprehensive way to guide professionals through the 
  stages of a data mining project, from understanding the business problem to deploying the results.
- CRISP-DM is iterative, meaning it’s common for the process to cycle back to previous stages as new insights are gained or as requirements change. The flexibility of this methodology allows data scientists and analysts to adapt and 
  refine their approach based on the ongoing analysis and evolving business needs.
- The CRISP-DM process consists of six main phases.

![image](https://github.com/shishir1991/MS_Excel_Project/assets/157515610/4d777d42-9582-4230-b22a-65a39b160749)


1. Business Understanding: a. Goals and objectives b. Project plan c. Business success criteria

2. Data Understanding: a. Data collection sources b. Data exploration c. Initial data description

3. Data Preparation: a. Data cleaning b. Data transformation c. Data pre-processing
 
4. Modeling: a. Selection of modeling techniques b. Building models c. Assessing model quality

5. Evaluation: a. Model assessment b. Business success criteria evaluation c. Review of process

6. Deployment: a. Deployment plan b. Final report c. Project review

## 🔍 Features:

### Business Understanding 
    This initial phase involves understanding the project objectives, requirements, and determining how data mining can provide solutions to the business problem.
 
    - Business Objective:
   
      The analysis aims to leverage data-driven approaches to optimize customer service processes, enhance customer experience, and drive overall business growth. By examining historical customer service data, the project seeks to 
      identify patterns, trends, and opportunities for improvement, ultimately leading to enhanced customer loyalty and increased operational efficiency. 

    - Project Goals:
   
     A Customer Sentiment Analysis: Perform sentiment analysis on customer interactions. Identify positive, negative, and neutral sentiments expressed by customers to understand overall satisfaction levels. 
  
     B Root Cause Analysis: Investigate common customer complaints. Pinpoint recurring problems to address them proactively and prevent future escalations. 
  
     C Service Response Time Analysis: Analyse response times for customer queries and support requests to assess the efficiency of the customer service team.
  
     D Customer Segmentation: Segment customers based on their demographics, behaviour, and preferences. Understand different customer segments' needs and pain points to tailor services and communications accordingly. 
  
     E Trends and Patterns Identification: Identify patterns and trends in customer service data to uncover opportunities for process improvements and innovative service offerings.

### Data Understanding
    In this phase, data collection, exploration, and initial data quality assessment take place. It involves understanding the available data sources, their quality, and their potential to meet the project objectives.
    Here we have the original data file which will show what is the task which we have to perform and how we have to proceed with it.

   [Download CSV File](https://github.com/shishir1991/MS_Excel_Project/blob/main/MS%20Excel%20Graded%20Project/Call_Center_data_Raw.csv)

### Data Preparation
    This phase involves cleaning, transforming, and pre-processing the data to make it suitable for analysis. Tasks include dealing with correction of file type, missing values, handling outliers, removing duplicates and transforming 
    data into a usable format.

   [Download Cleaned File](https://github.com/shishir1991/MS_Excel_Project/blob/main/MS%20Excel%20Graded%20Project/Call_Center_data_Cleaned.xlsx)

### Modeling
    In this phase, various modeling techniques are selected and applied to the prepared dataset. Different algorithms and methodologies are used to build and assess models based on the business problem.

    For this project we have use different Pivot tables, charts and slicers according to the requirement and analysis.
    
    We have in total of five goals that we have to achieve based on the given data :

    📊 Results:

    A. Customer Sentiment Analysis :

       Here we have performed sentiment analysis on customer interactions through Pie chart and Identified positive, negative, and neutral sentiments expressed by customers to understand overall satisfaction levels.

   ![image](https://github.com/shishir1991/Nile-MS_Excel_Project/assets/157515610/1ce7410a-1979-4bbc-89db-eaa589b60278)

    B. Root Cause Analysis: We have investigated common customer complaints. Pinpoint recurring problems to address them proactively and prevent future escalations.

   ![image](https://github.com/shishir1991/Nile-MS_Excel_Project/assets/157515610/821de83d-ebd7-4d74-b367-2c6aa1dd7f99)

    C. Service Response Time Analysis: Analyse response times for customer queries and support requests to assess the efficiency of the customer service team.

   ![image](https://github.com/shishir1991/Nile-MS_Excel_Project/assets/157515610/cf39da37-5356-48f2-ab43-654a9148156d)

    D. Customer Segmentation: Segment customers based on their demographics, behaviour, and preferences. Understand different customer segments' needs and pain points to tailor services and communications accordingly.

   ![image](https://github.com/shishir1991/Nile-MS_Excel_Project/assets/157515610/6140cae1-870b-40d3-800b-ec6b7aeb7662)

    E. Trends and Patterns Identification: Identify patterns and trends in customer service data to uncover opportunities for process improvements and innovative service offerings.

   ![image](https://github.com/shishir1991/Nile-MS_Excel_Project/assets/157515610/cfea79b8-6ccc-41b5-a24d-4f9965971718)

    a. By analysing the bar chart it is clear that most of the communication is related to billing question through all the four channel modes. So the process of Billing should be reviewed and checked for any improvement or 
       rectification.
   
    b. Whereas on payment only one channel has been considered i.e. call centre which makes it limited and busy for communicating. By improving mail and web channel for queries and rapid solution, the traffic on call-centre can be 
       diverted over these other channels which can result a decrease in call-centre traffic.
   
    c. By the analysation from Bar chart we learn that the Service outage queries are resolved over three Channels but not on call-centre. As the queries over this reason are minimum we can assume that it is getting resolved over the 
       respective channels.

### Evaluation
    Once models are created, they need to be evaluated to determine their effectiveness in addressing the business objectives. This phase involves assessing model performance, considering different metrics, and selecting
    the best model.

### Deployment
    The deployment phase involves making the insights and tools accessible to the stakeholders at Nile. This includes:

    - Dashboard Implementation: Setting up a real-time monitoring dashboard in Microsoft Excel, providing easy access to key metrics and insights.
    - Training: Conducting training sessions for Nile’s staff to effectively use the dashboard and understand the insights.
    - Documentation: Providing comprehensive documentation on the analysis process, dashboard usage, and interpretation of the results.
    - Feedback Loop: Establishing a feedback mechanism to continuously improve the analysis based on user inputs and evolving business needs.

## Expected Deliverables
- Data-driven insights and actionable recommendations based on sentiment analysis and root cause identification.
- Real-time monitoring dashboard for tracking all the Project Goals.

## Artifacts to be Generated
- MS Excel File (.xlsx)
- Presentation (Slides) summarizing the project

## How to Use
 - Clone the repository to your local machine.
   
git clone https://github.com/shishir1991/Nile-MS_Excel_Project.git
- Open the MS Excel file in the artifacts folder to view the detailed analysis.
- Review the presentation in the artifacts folder for a summary of the project findings and recommendations.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

## Contact
For any further questions or contributions, please contact us:

- Project Lead: Shishir KHerod
- Email: shishirdma@gmail.com

Thank you for visiting our project repository!











   








