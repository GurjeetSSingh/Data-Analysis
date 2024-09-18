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
![image](https://github.com/user-attachments/assets/2537b0c3-91d6-435f-9d5e-5a17a1f89d48)

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
![1](https://github.com/user-attachments/assets/b9ce982d-f5e6-4094-9ee6-1c435202fc16)
![2](https://github.com/user-attachments/assets/6a7d1afd-bb36-4505-99b1-ea5539b8b437)
![3](https://github.com/user-attachments/assets/386ad6ab-3b4d-4181-9c2e-a7de891762ef)
![4](https://github.com/user-attachments/assets/f5b813df-f4d6-421c-847d-87b065ce5119)

  Screenshot showing the **S3 bucket** and uploaded dataset. This demonstrates that the data has been properly ingested into AWS.

#### **Data Cleaning and Structuring**
- Data was cleaned using **AWS Glue DataBrew** to address missing values and structure the dataset for analysis.
![image9](https://github.com/user-attachments/assets/c3f049f3-bcf5-4a28-bc5f-0355558f180f)
![image10](https://github.com/user-attachments/assets/1173ef2e-b904-4908-8021-0a7f1dd29586)
![image11](https://github.com/user-attachments/assets/95bf2904-b9a9-4832-8fb5-4fc868eb8ec3)

  Screenshot from **AWS Glue DataBrew** showing the data cleaning process, such as handling missing values or structuring the dataset.

#### **Data Storage and Pipeline**
- Data was stored in an **AWS S3 bucket** for easy access and processing.

- A data pipeline was designed using **draw.io and AWS Glue** to automate the steps.
![image7](https://github.com/user-attachments/assets/f5d256dc-41b3-4b2d-827d-9fb193c9efd2)
![image8](https://github.com/user-attachments/assets/c5bfea3c-7243-4595-bc14-0e57b4596326)
![image12](https://github.com/user-attachments/assets/fa3c99ea-ed96-40ef-b845-e96b6509c807)

  If available, include a screenshot of the **AWS Glue jobs** running or the pipeline creation process. This would highlight the data transformation workflow.

#### **Data Analysis**
- Descriptive statistics (mean, median, mode) were calculated using **AWS Athena**.
- Queries focused on summarizing the **Project Value** across different time periods.

![image13](https://github.com/user-attachments/assets/97ca6120-a075-4c94-bd0d-2fc619e6f27f)

  Screenshot of **AWS Athena** showing query results, including any statistics you've generated like **mean or median** of project values.

#### **Data Visualization**
- Visualizations were created to highlight trends in project values and permit issuance.

![image14](https://github.com/user-attachments/assets/089a03f6-d289-4d21-9575-f65a69dbff56)
![image15](https://github.com/user-attachments/assets/a4baca17-0d65-494f-88f8-7bda1f1684bb)


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

## Background:
The City of Vancouver has initiated a migration to AWS to implement a robust data analytic platform (DAP). This diagnostic phase focuses on ensuring that the platform is secure, well-governed, and consistently monitored. This involves applying encryption and security policies, governance frameworks, and real-time performance monitoring.
## DAP Diagram:
Below is the **Data Analytic Platform (DAP)** diagram, which outlines the architecture for Vancouver's AWS-based data platform. This phase focuses on data protection, governance, and monitoring.

![image2](https://github.com/user-attachments/assets/b2b06222-37eb-4f34-95f6-4169c9c35ae6)
---

## Dataset:
The dataset consists of operational data related to the **building permits issued by the City of Vancouver**. The data is stored securely using AWS S3 with encryption, governance rules, and replication rules applied. Key features include:
- **Permit Number**: Unique identifier for each permit issued.
- **Project Type**: The type of building project (e.g., residential, commercial).
- **Permit Issue Date**: The date on which the permit was issued.
- **Project Value**: The financial value of the project.
- **Location**: Geographic details of the project site.
- **Contractor Information**: Data about the contractor responsible for the project.

---

## Methodology:
This project focuses on ensuring **Data Protection**, **Data Governance**, and **Data Monitoring** using AWS services. Here’s how each of these steps was implemented:

### **Step 15: Data Protection**
- **Approach**: 
    - Implemented encryption using **AWS KMS** (Key Management Service) to create encryption and decryption keys.
    - Configured the keys for S3 bucket encryption to ensure that all stored data is encrypted at rest.
    - Applied **bucket replication rules** to replicate data across regions for disaster recovery and failover support.
    - Set up S3 bucket policies and IAM roles to control access and ensure that only authorized personnel can read or write data.

- **Screenshot**: Screenshot of KMS keys, bucket policies, and replication rules applied to the bucket for protection.
   ![image1](https://github.com/user-attachments/assets/45f470e8-41ed-4fb0-91cd-ec9af48a4610)
   ![image2](https://github.com/user-attachments/assets/11219440-2a4c-4767-908d-112a1f403b5b)
   ![image3](https://github.com/user-attachments/assets/d6ba91f4-e166-4b5d-9821-a65ddca97793)
  
### **Step 16: Data Governance**
- **Approach**:
    - Used **AWS Config** to track all changes in bucket configurations and applied compliance rules to ensure that security and governance policies are being followed.
    - Set up **AWS CloudTrail** to log all actions taken on the platform, ensuring full audit trails for data access and usage.
    - Established governance policies and monitoring systems that allow administrators to oversee data access and activity effectively.

- **Screenshot**: Screenshot of AWS Config rules and CloudTrail logs showing governance in action.
  ![image4](https://github.com/user-attachments/assets/4f5b918d-0d7b-4ada-8c3e-93a0eeea1d8f)
  ![image5](https://github.com/user-attachments/assets/dfdb8140-ea9f-406b-8e96-11e0c1a48da1)
  ![image6](https://github.com/user-attachments/assets/e9d5d762-3fed-4e03-a50b-6097af6eb933)
  ![image7](https://github.com/user-attachments/assets/fa3d26cc-d892-4298-9c86-b1a86babe883)
  ![image8](https://github.com/user-attachments/assets/22cd9ee0-d162-4b26-a188-e0a3e9b23990)
  ![image9](https://github.com/user-attachments/assets/37b20b25-d9f5-43ff-ae2d-fd6733b49cca)


### **Step 17: Data Monitoring**
- **Approach**:
    - Configured **AWS CloudWatch** to continuously monitor system performance and track metrics such as CPU usage, memory utilization, and data processing times.
    - Set up **AWS SNS (Simple Notification Service)** for real-time alerts. If any thresholds (e.g., high resource usage or security breaches) are crossed, notifications are sent automatically.
    - Used CloudWatch dashboards to visualize the platform’s performance in real time and generate automated reports.

- **Screenshot**: Screenshot of CloudWatch dashboard and SNS alert system showing real-time monitoring.
  ![image10](https://github.com/user-attachments/assets/31af6061-b132-4e1b-84a1-f88674ac0e85)
  ![image11](https://github.com/user-attachments/assets/0b733710-a6a5-439c-a695-d32dc1d27143)
  ![image12](https://github.com/user-attachments/assets/729c05a7-6d67-4e5e-a990-2761c3a39974)
  ![image13](https://github.com/user-attachments/assets/434f54e3-135a-4175-b3fe-1d81c3b55d7c)
  ![image14](https://github.com/user-attachments/assets/189b64df-d302-41ca-b44d-be91143745b4)

---

## Timeline:
- **Week 1-2**: Initial setup of S3 buckets with encryption, IAM roles, and bucket policies.
- **Week 3-4**: Implementation of replication rules, KMS keys, and data governance using AWS Config and CloudTrail.
- **Week 5-6**: Setup of CloudWatch monitoring and SNS alert systems for real-time performance tracking.
- **Week 7**: Final review and integration of the entire protection, governance, and monitoring systems into the DAP.

---

## DAP Architecture Analysis:
### Based on AWS Well-Architected Framework:
The architecture for the Vancouver DAP was evaluated on six key pillars of AWS Well-Architected Framework:

- **Operational Excellence**: The DAP automates critical processes, including encryption and data replication, ensuring that it operates smoothly without manual intervention.
  
- **Security**: AWS KMS and IAM roles were used to enforce strong encryption and access control policies, ensuring that all sensitive data is protected against unauthorized access.
  
- **Reliability**: Bucket replication rules ensure data redundancy, and the use of CloudWatch ensures that the platform remains highly reliable, with real-time performance alerts.
  
- **Performance Efficiency**: The platform uses efficient data storage and retrieval mechanisms, including optimized bucket policies and monitoring services that help minimize resource usage during peak times.
  
- **Cost Optimization**: AWS Pricing Calculator was used to ensure that the costs of storage, replication, and monitoring remain within budget, while CloudWatch optimizes resource usage based on real-time demand.
  
- **Sustainability**: AWS services allow for highly sustainable data processing and storage, reducing the environmental impact of the platform’s operation by utilizing cloud-based, energy-efficient services.

---

## Tools and Technologies:
- **AWS S3**: For scalable and secure data storage.
- **AWS Glue**: For ETL (Extract, Transform, Load) operations and building the data catalog.
- **AWS Athena**: For running SQL queries to explore and analyze datasets directly from S3.
- **AWS CloudWatch**: For usage visualization and alerting via SNS.
- **AWS SNS**: For alerting when services exceed usage limits or performance thresholds.
- **AWS IAM**: For user management and data access control.
- **AWS KMS**: For creating encryption and decryption keys to secure sensitive data.
- **AWS Config**: For tracking configuration changes and ensuring compliance with governance policies.
- **AWS CloudTrail**: For logging and auditing all actions taken on the platform.

---

## Insights and Findings:
This diagnostic analysis revealed several critical insights into the security, governance, and monitoring aspects of the City of Vancouver's data platform:

- **Enhanced Data Security**: The implementation of KMS encryption and IAM roles ensures that only authorized users can access sensitive data, reducing the risk of unauthorized access.
  
- **Comprehensive Governance**: With AWS Config and CloudTrail, all actions are logged, and governance policies are continuously enforced, ensuring compliance with security standards and regulations.

- **Proactive Monitoring and Alerting**: AWS CloudWatch and SNS enable real-time monitoring of system performance, ensuring that any anomalies are detected and resolved swiftly. This reduces downtime and improves the platform's reliability.

These insights support the overall goal of providing a secure, well-governed, and continuously monitored data platform for the City of Vancouver.

---

## Deliverables:
The following deliverables have been produced as part of this project:

- **Data Protection Report**: A detailed document outlining how AWS KMS and IAM were implemented to secure sensitive data.
- **Data Governance and Compliance Report**: A comprehensive report generated via AWS Config and CloudTrail, showing all actions taken on the platform for governance and auditing.
- **Monitoring and Alerting Dashboard**: A CloudWatch-based monitoring dashboard integrated with SNS for real-time alerts and system performance tracking.
- **Cost Analysis Report**: A breakdown of the costs involved in running AWS security, governance, and monitoring services, ensuring the platform remains cost-effective while maintaining high standards.

---

