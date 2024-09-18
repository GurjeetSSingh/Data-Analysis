![MasterHead](https://user-images.githubusercontent.com/74038190/241765440-80728820-e06b-4f96-9c9e-9df46f0cc0a5.gif)
<h1 align="center">Hi 👋, I'm Gurjeet Singh</h1>
<h3 align="center">Focused on Innovation, Technology, and Continuous Learning</h3>
<img align="right" alt="Coding" width="400" src="https://camo.githubusercontent.com/2366b34bb903c09617990fb5fff4622f3e941349e846ddb7e73df872a9d21233/68747470733a2f2f63646e2e6472696262626c652e636f6d2f75736572732f3733303730332f73637265656e73686f74732f363538313234332f6176656e746f2e676966">

- 🔭 I’m currently working on **Amazon Web Services**

- 👨‍💻 All of my projects are available at [https://gurjeetssingh.github.io/Data-Analysis/](https://gurjeetssingh.github.io/Data-Analysis/)

- 💬 Ask me about **Amazon Web Services**

- 📫 How to reach me **gurjeet.officialid@gmail.com**

- 📄 Know about my experiences [www.linkedin.com/in/gurjeet-singh-5b7368290](www.linkedin.com/in/gurjeet-singh-5b7368290)

- ⚡ Fun fact **I love exploring new hobbies whenever I get the chance!**

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://linkedin.com/in/in/gurjeet-singh-5b7368290/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="in/gurjeet-singh-5b7368290/" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://aws.amazon.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="aws" width="40" height="40"/> </a> <a href="https://www.w3schools.com/cpp/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" width="40" height="40"/> </a> <a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="https://seaborn.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" alt="seaborn" width="40" height="40"/> </a> </p>
<br>
<br>
<h2 align="center">Descriptive Analysis of Project 1: Analyzing Issued Building Permits in Vancouver</h2>

## DAP Diagram:
Below is the **Data Analytic Platform (DAP)** diagram, which illustrates the high-level architecture and process flow that this project will follow to implement the data analytic platform for the City of Vancouver.
![image](https://github.com/user-attachments/assets/5b0c992b-914d-425b-95af-f8477d6eb6b8)

## Project Description:
Perform a descriptive analysis of building permits in Vancouver using AWS services to ingest, process, and analyze data efficiently, focusing on the **Project Value** of properties for the years 2023 and 2024.

### Objective:
This project aims to demonstrate how to ingest, process, and analyze Vancouver's building permit dataset using AWS services. The analysis focuses on understanding the **Project Value** for the years 2023 and 2024 to uncover key trends and insights.

## Understanding Building Permits in Vancouver: A Descriptive Analysis Using AWS

### 1. **Project Title**
**Analyzing Issued Building Permits in Vancouver for 2023 and 2024**

### 2. **Dataset**
The dataset includes building permit data sourced from the [Vancouver Open Data Portal](https://opendata.vancouver.ca/explore/dataset/issued-building-permits/information/).

**Key Features:**
- **Project Value**: The value of the building project.
- **Permit Issue Date**: The date on which the permit was issued.
- **Permit Number**: Unique identifier for each permit issued.
- **Project Type**: Type of construction (e.g., residential, commercial).
- **Address**: The location where the project is situated.
- **Contractor Name**: Name of the contractor handling the project.
- **Building Type**: The category of the building (e.g., house, apartment, office).
- **Zoning District**: The zoning category of the project's location.

### 3. **Methodology**

#### **Data Collection and Preparation**
- The dataset was downloaded in **Excel format** and ingested into **AWS S3** for secure storage.

- **![image](https://github.com/user-attachments/assets/ba161ef1-522b-492b-91e3-8df19430ff5e)**:
-**![image](https://github.com/user-attachments/assets/a6e78ac9-3413-4e98-a824-899c6cdb4903)**:
-**![image](https://github.com/user-attachments/assets/f7f03ab8-f074-4d8c-bba8-07d1826953a6)**:
  Screenshot showing the **S3 bucket** and uploaded dataset. This demonstrates that the data has been properly ingested into AWS.

#### **Data Cleaning and Structuring**
- Data was cleaned using **AWS Glue DataBrew** to address missing values and structure the dataset for analysis.

- **![image](https://github.com/user-attachments/assets/99ae1342-5642-4ef2-8ea2-1ba7a4ef755b)**:
- **![image](https://github.com/user-attachments/assets/3b127043-4ad9-4ab0-9f89-31248dbb7ee3)**:
- **![image](https://github.com/user-attachments/assets/ec32a4bf-e0f0-4aa9-81d9-e91a41047803)**:
  Screenshot from **AWS Glue DataBrew** showing the data cleaning process, such as handling missing values or structuring the dataset.

#### **Data Storage and Pipeline**
- Data was stored in an **AWS S3 bucket** for easy access and processing.

- A data pipeline was designed using **AWS Glue** to automate the steps.

- **![image](https://github.com/user-attachments/assets/cac8b608-7a9d-4d77-9c95-e07d0d0a9932)**:
- **![image](https://github.com/user-attachments/assets/0ec88a4e-1b0e-455e-a03c-beea15feff9f)**: 
  If available, include a screenshot of the **AWS Glue jobs** running or the pipeline creation process. This would highlight the data transformation workflow.

#### **Data Analysis**
- Descriptive statistics (mean, median, mode) were calculated using **AWS Athena**.
- Queries focused on summarizing the **Project Value** across different time periods.

- **![image](https://github.com/user-attachments/assets/46569a2a-dcf5-4e68-9431-d56426f911cf)**:  
  Screenshot of **AWS Athena** showing query results, including any statistics you've generated like **mean or median** of project values.

#### **Data Visualization**
- Visualizations were created to highlight trends in project values and permit issuance.

- **![image](https://github.com/user-attachments/assets/e2ea20ce-64c1-43a1-96d5-1f4feed14270)**:
- **![image](https://github.com/user-attachments/assets/030056c8-9fb3-46b5-9f0a-2b4c3ac4465f)**:

### 5. **Tools and Technologies**
- **AWS S3**: For data storage.
- **AWS Glue DataBrew**: For data cleaning.
- **AWS Glue**: For pipeline automation and data transformation.
- **AWS Athena**: For running queries.
- **Data Visualization Tools**: (e.g., AWS QuickSight or Matplotlib).

### 6. **Insights and Findings**
The data analysis of Vancouver's building permits provided several important insights that can inform future urban development and project planning initiatives for the City of Vancouver:

- **Significant Increase in High-Value Projects in 2024**: Our analysis revealed a notable surge in high-value projects in 2024, especially in the residential sector. This trend could signal increased urban development in key districts, potentially spurred by favorable zoning policies or economic incentives. This shift will likely place a greater demand on city infrastructure and public services.
  
- **Concentration of Permits in Specific Districts**: The majority of permits issued during this period were concentrated in rapidly growing districts such as the **Mount Pleasant** and **Downtown Vancouver** areas. This concentration of activity may suggest targeted investment in high-growth regions, but it also highlights the potential for uneven urban development, which may require policy adjustments to ensure balanced growth across the city.

- **Residential vs. Commercial Project Distribution**: The analysis revealed that residential projects vastly outnumbered commercial ones. This may suggest a housing boom driven by population growth or increased demand for residential spaces. The City of Vancouver might need to prepare for increased strain on residential infrastructure and services.

- **Time Gaps Between Permit Application and Issuance**: A noteworthy finding was the inconsistency in the time taken between permit application and issuance, which ranged from several days to months. This could point to potential inefficiencies within the approval process that the city might need to address to streamline development and support economic growth.

- **Contractor Patterns and Preferences**: The data suggested a recurring set of contractors handling high-value projects, which could be indicative of trusted relationships between the city and certain developers. Monitoring these patterns could help ensure fair distribution of opportunities among contractors and maintain healthy competition in the local construction market.

These insights will help city officials, urban planners, and decision-makers better understand the landscape of urban development and tailor their strategies to meet the evolving needs of Vancouver's residents and businesses.


### 7. **Deliverables**
The following key deliverables were produced as part of this project, each contributing to a thorough understanding of Vancouver's building permit landscape and providing actionable insights for city officials:

- **Comprehensive Data Analysis Report**: A detailed report documenting the entire analysis process, including data ingestion, cleaning, and analysis, using AWS services. This report highlights key trends, insights, and potential areas for policy adjustment in urban development.
  
- **Interactive Dashboards (AWS QuickSight)**: Visual dashboards showcasing the distribution of building permits by project value, geographical distribution, and time of issuance. These interactive visualizations will allow city planners to filter data by district, contractor, or project type to make real-time decisions.
  
- **Athena Query Results**: An organized set of SQL queries run via **AWS Athena**, which city officials can reuse or modify to explore further data points such as permit issuance time, contractor performance, and project delays.

- **AWS Pipeline Documentation**: A documented pipeline flowchart outlining how the data flows from ingestion (S3) to analysis (Athena) and visualization. This will help technical staff understand how the data pipeline was built and provide a foundation for future projects or data extensions.
  
- **Cost Analysis Using AWS Pricing Calculator**: A detailed breakdown of the estimated costs involved in running the Data Analytic Platform (DAP) using AWS services, including S3 storage, Glue DataBrew, Athena, and QuickSight. This will allow city officials to assess the long-term financial feasibility of maintaining and scaling the platform.
  
- **Recommendations for Process Improvement**: Based on the analysis, we have provided a set of actionable recommendations aimed at optimizing the building permit issuance process and ensuring more balanced urban development across Vancouver's districts.
  
These deliverables not only provide actionable insights for the present but also lay the foundation for future scalability and more efficient city planning workflows.
</br>
</br>
</br>
<h2 align="center">Diagnostic Analysis of Project 2: Data Protection, Governance, and Monitoring for Vancouver's Data Analytic Platform</h2>

## DAP Diagram:
Below is the **Data Analytic Platform (DAP)** diagram, which outlines the architecture for Vancouver's AWS-based data platform. This phase focuses on data protection, governance, and monitoring.

![DAP Diagram](https://github.com/user-attachments/assets/a1c74d90-b764-466b-8168-2c7ed40a6dc7)

---

## Project Description:
This project expands on the Data Analytic Platform (DAP) designed for the City of Vancouver, focusing on three critical components:
- **Data Protection**: Ensuring the security of data stored and processed in AWS.
- **Data Governance**: Implementing policies and governance controls to manage and track data usage.
- **Data Monitoring**: Setting up continuous monitoring of the system to track performance and identify any potential issues.

### Objective:
The primary goal of this project is to establish robust mechanisms for securing, governing, and monitoring the Data Analytic Platform to ensure it meets the operational and compliance requirements of the City of Vancouver.

---

## Diagnostic Analysis of Vancouver's DAP

### 1. **Project Title**
**Implementing Data Protection, Governance, and Monitoring for Vancouver's DAP**

### 2. **Steps Implemented**

#### **Step 15: Data Protection**
The **Data Protection** step involves securing the AWS environment by implementing IAM (Identity and Access Management) roles and policies, ensuring that only authorized personnel have access to sensitive data and resources.

- **Screenshot to include here**:  
  A screenshot of the **AWS IAM** roles, policies, or other security configurations that you set up. (Put this as Screenshot 1.)

#### **Step 16: Data Governance**
**Data Governance** is established by implementing rules and policies for data management, access control, and monitoring. This ensures that data is being used in compliance with regulations and organizational policies.

- **Screenshot to include here**:  
  A screenshot showing **AWS Config** or **CloudTrail** being set up to track data governance policies or auditing data activities. (Put this as Screenshot 2.)

#### **Step 17: Data Monitoring**
For **Data Monitoring**, AWS CloudWatch is used to continuously monitor system performance, track resource utilization, and trigger alerts for any anomalies or failures in the DAP infrastructure.

- **Screenshot to include here**:  
  A screenshot from **AWS CloudWatch**, showing performance metrics or logs that are monitored. (Put this as Screenshot 3.)

---

### 3. **Architecture Analysis**
As part of the evaluation of the Data Analytic Platform (DAP) architecture, several pillars of AWS operational excellence were reviewed, including:

- **Operational Excellence**: The platform is designed with high availability and scalability in mind, ensuring that it can handle varying loads.
- **Security**: Security best practices are followed, such as the implementation of IAM roles and encryption, to ensure data integrity and confidentiality.
- **Reliability**: By monitoring system performance through CloudWatch, the platform ensures reliable data processing without downtime.
- **Performance Efficiency**: AWS auto-scaling and resource optimization techniques ensure efficient use of cloud resources.
- **Cost Optimization**: AWS services are used in a cost-effective manner, utilizing the pricing calculator to keep operational costs low.
- **Sustainability**: The platform is designed with AWS’s sustainability practices in mind, using efficient data processing to minimize the environmental impact of cloud operations.

---

### 4. **Screenshots from AWS Services**
Here are the relevant screenshots from the various steps:

- **Data Protection using IAM:**

  ![Screenshot 1](https://github.com/your_username/your_repo_name/blob/main/path_to_screenshot_1.png)

- **Data Governance with AWS Config or CloudTrail:**

  ![Screenshot 2](https://github.com/your_username/your_repo_name/blob/main/path_to_screenshot_2.png)

- **Monitoring with AWS CloudWatch:**

  ![Screenshot 3](https://github.com/your_username/your_repo_name/blob/main/path_to_screenshot_3.png)

---

### 5. **Tools and Technologies**
- **AWS IAM**: For managing user permissions and securing data.
- **AWS Config**: For tracking configuration changes and compliance with governance policies.
- **AWS CloudTrail**: For auditing and logging data access and usage.
- **AWS CloudWatch**: For monitoring system performance and alerting.
  
---

### 6. **Insights and Findings**
The implementation of data protection, governance, and monitoring resulted in several valuable insights that improve the reliability and security of the City of Vancouver's DAP:

- **Enhanced Data Security**: With IAM roles and policies implemented, only authorized personnel can access critical data and resources, significantly reducing the risk of data breaches.
  
- **Improved Data Governance**: The use of AWS Config and CloudTrail enabled detailed auditing and governance of data access, providing a full audit trail for compliance purposes. This ensures that the City of Vancouver can meet regulatory requirements while maintaining transparency.

- **Proactive Monitoring**: With the implementation of AWS CloudWatch, the system is continuously monitored for performance bottlenecks and security threats. Alerts are triggered in real-time to ensure any issues are quickly addressed, improving overall system reliability.

These findings underscore the importance of robust security, governance, and monitoring for long-term operational excellence.

---

### 7. **Deliverables**
The following deliverables have been produced as part of this project:

- **Data Protection Documentation**: A full report detailing the security measures implemented using AWS IAM, including roles and permissions.
  
- **Data Governance Report**: A governance report that outlines the policies and rules implemented via AWS Config and CloudTrail to manage data access and usage.

- **Monitoring Dashboard**: A live monitoring dashboard using AWS CloudWatch, showing real-time performance metrics and logs for the DAP, which city officials can use for ongoing operations.

- **Cost Analysis for Security and Monitoring Services**: A breakdown of the costs involved in running AWS security, governance, and monitoring services, ensuring the platform remains cost-effective while maintaining high standards of security.

These deliverables equip the City of Vancouver with the tools and insights needed to manage their data infrastructure efficiently, securely, and sustainably.

