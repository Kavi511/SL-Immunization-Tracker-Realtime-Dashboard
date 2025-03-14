# 📈 Sri Lankan Immunization Tracker - Power BI Dashboard 

## Power BI Dashboard: [SL Immunization_Tracker.pdf](https://github.com/user-attachments/files/19227676/SL.Immunization_Tracker.pdf)

## 📖 Overview  
SL Immunization Tracker is an interactive Power BI dashboard designed to visualize and monitor adverse events following immunization (AEFI) in Sri Lanka. It provides real-time insights into vaccine-related safety concerns, enabling medical professionals, policymakers, and researchers to make informed decisions.

The dashboard leverages Big Data analytics to identify patterns and trends in reported adverse events, ensuring proactive responses to potential safety issues. It aims to bridge the gap between vaccination data and healthcare professionals, improving vaccine safety surveillance and public trust in the National Vaccination Programme of Sri Lanka.

## 🚀 Features 
✔️ Real-time monitoring of vaccine-related adverse events

✔️ Interactive visualizations for trend analysis and pattern recognition

✔️ Data-driven decision-making for healthcare professionals

✔️ Integration of primary & secondary data sources for comprehensive analysis

✔️ User-friendly interface for quick insights and reporting 

## 📂 Repository Structure  
```
📦 SL-Immunization-Tracker  
 ┣ 📂 pbix/                # Power BI dashboard files    
 ┣ 📂 images/              # Screenshots and previews of the dashboard  
 ┣ 📜 README.md            # Project documentation  
 
```

## 🛠️ Installation & Setup
1️⃣ Prerequisites

🔹Ensure you have the following installed before proceeding:

🔹Power BI Desktop (https://apps.microsoft.com/detail/9nblgggzlxn1?hl=en-US&gl=LK)

🔹Microsoft Excel (https://www.microsoft.com/en-us/microsoft-365/excel)

🔹Data File: (Only a sample dataset is provided for demonstration purposes) 

## Note: # The full dataset is not included in this repository due to the sensitive nature of medical data. Only a sample dataset is provided for demonstration purposes.

## 📷 Screenshots of Sample Datasets  
**Figure 6: Epidemiology Unit and MOH Raw Data (2019 - 2024)**  
![image](https://github.com/user-attachments/assets/eb134850-2418-4126-ac95-23ec5abe8270)

**Figure 7: Primary Research Raw Data (Responses)**  
![image](https://github.com/user-attachments/assets/0b98b5da-71d9-41af-8b5e-9cd4b8232c90)  

2️⃣ Installing Power BI Desktop For Windows:

🔹Download Power BI Desktop from the official Microsoft website:

👉https://powerbi.microsoft.com/en-us/downloads/

🔹Open the downloaded .exe file and follow the installation wizard.

🔹Once installed, launch Power BI Desktop.

3️⃣ Linking an Excel File in Power BI Follow these steps to connect an Excel file (.xlsx) to Power BI:

Step 1: Open Power BI Desktop

🔹Launch Power BI Desktop from the Start Menu.

Step 2: Import Excel Data

🔹Click on Home → Get Data → Excel.

🔹Browse to the data folder in the cloned repository and select the Excel file (data/your-data.xlsx).

🔹Click Open.

Step 3: Load Data into Power BI

🔹A preview of the Excel sheets will appear. Select the relevant worksheet(s).

🔹Click Load to import data directly OR Transform Data to open the Power Query Editor for modifications.

Step 4: Verify the Connection

🔹Go to the Data View (left sidebar) and confirm that the imported data appears correctly.

4️⃣ Refreshing Data in Power BI If the Excel file is updated, refresh the dataset in Power BI:

🔹Open Power BI Desktop.

🔹Click Refresh from the Home tab.

5️⃣ Publishing the Dashboard To share the dashboard online:

🔹lick Publish in Power BI Desktop.

🔹Sign in to Power BI Service (powerbi.com).

🔹Select a workspace and click Publish.

🔹The dashboard will be available online for stakeholders to view.

## 🔗 Data Source Configuration  
- **Local Files**: Ensure `data/` contains necessary `.csv` or `.xlsx` files.  
- **Database Connections**: Update credentials in Power BI **Transform Data** → **Data Source Settings**.  
  
## 📝 Usage Instructions  
1. **Filters & Slicers**: Customize views using slicers on the dashboard.  
2. **Drill-through & Drill-down**: Click on visuals for deeper analysis.  
3. **Exporting Data**: Use **Export Data** option in Power BI to save reports in `.csv` or `.xlsx`.  
4. **Publishing**: Click **Publish** in Power BI to deploy to **Power BI Service**.
   
## 📊 Data Dictionary
Create a data dictionary explaining fields like: 
 
### **1️⃣ Data Collection**  

#### **• Primary Data Collection:**  
- Surveys and questionnaires were distributed to healthcare professionals to identify their requirements for monitoring vaccine safety.  
- Real-time data was collected from hospitals, vaccination centers, and healthcare institutions regarding adverse events following immunizations.  

#### **• Secondary Data Collection:**  
- Utilized existing databases such as local health ministry records and medical research on immunization (primarily from the Epidemiology Unit in Sri Lanka).  
- Reviewed published studies and global case studies to understand existing systems and the types of data they use.  
- Ensured compliance with **HIPAA** (Health Insurance Portability and Accountability Act) regulations during secondary data collection to maintain patient confidentiality.  

#### **• Challenges in Data Collection:**  
- Ensuring data privacy and compliance with regulations such as HIPAA or local equivalents.  
- Handling incomplete, inconsistent, or duplicate data from various sources.  
- Integrating data from multiple formats and platforms for analysis.  

### **2️⃣ Data Processing**  

#### **• Data Integration:**  
- Used **ETL (Extract, Transform, Load)** tools to consolidate data from various sources into a centralized database.  
- Ensured compatibility of data formats through preprocessing.  
- Standardized data formats (e.g., date formats, numerical ranges).  

#### **• Data Transformation:**  
- Converted raw data into structured formats suitable for analysis (e.g., tables, graphs, JSON files for web rendering).  

### **3️⃣ Key Data Fields**  

#### **Severity**  
- **Description:** Categorical classification of the seriousness of the reported adverse event following vaccination.  
- **Data Type:** Categorical (String)  
- **Possible Values:**  
  - **Low**: Minor adverse events that typically resolve quickly without significant intervention (e.g., mild pain, redness, or swelling at the injection site).  
  - **Mid**: Moderate adverse events requiring medical attention or causing temporary disruption (e.g., fever, rash, pronounced local reactions).  
  - **High**: Severe adverse events that may require hospitalization, lead to long-term complications, or be life-threatening (e.g., anaphylaxis, seizures, severe neurological reactions).  

#### **Outcome Categories**  
- **Description:** Describes the current status or resolution of the reported adverse event.  
- **Data Type:** Categorical (String)  
- **Possible Values:**  
  - **Resolved**: The adverse event has subsided, and the individual has recovered.  
  - **Ongoing**: The adverse event is still present and being monitored.  
  - **Recovering**: The adverse event is improving but not fully resolved.  
  - **Fatal**: The adverse event resulted in death.  
  - **Unknown**: The outcome of the adverse event is not yet known.  

#### **Adverse Event Types**  
- **Description:** Specific descriptions of reported adverse reactions following vaccination.  
- **Data Type:** Categorical (String)  
- **Possible Values:**  
  - Pain at injection site  
  - High fever (>40°C)  
  - Severe local reaction  
  - Anaphylaxis  
  - Severe allergic reaction  
  - Seizures  
  - Acute paralysis  
  - Other neurological complications  

#### **Vaccine Types**  
- **Description:** The name of the vaccine administered.  
- **Data Type:** Categorical (String)  
- **Possible Values:**  
  - DTP (Diphtheria, Tetanus, Pertussis)  
  - Hepatitis A  
  - Influenza  
  - Japanese Encephalitis  
  - Covid-19  
  - MMR (Measles, Mumps, Rubella)  
  - Polio  
  - Pneumococcal  
  - Meningococcal  
  - Rotavirus  
  - Typhoid  
  - Varicella (Chickenpox)  
  - Yellow fever  
  - Rabies  

## **🏥 Data Relationship and Transformation Guide**
This section I try **establishes data relationships and applies transformation processes** to integrate **Primary Research Data** with **Epidemiology Data** for vaccine-related analysis.


1. Relationship: Vaccine Types

📊 Understanding the Data

✅ Primary Research Data: Contains multiple entries for each vaccine type due to various reported adverse events.

✅ Epidemiology Data: Also has multiple entries for each vaccine type, tracking different adverse events over time.

🔄 Recommended Relationship Setup

Cardinality: 🟢 Many-to-Many

Cross-Filter Direction: 🔄 Both

⚙️ Action Steps

🛠 Data Preparation

📌 Ensure consistency in vaccine type names (e.g., "MMR" vs. "Measles-Mumps-Rubella").

📌 Format the relevant columns as Text data type.

🔗 Creating the Relationship

1️⃣ In Model View, drag the Types of Vaccines column from the Primary Research table to the Vaccine Type column in the Epidemiology table.

2️⃣ In the Edit Relationship dialog:

Cardinality: 🟢 Many-to-Many

Cross-Filter Direction: 🔄 Both

3️⃣ Click OK to confirm.

🏷️ 2. Relationship: Age Group

📊 Understanding the Data

✅ Primary Research Data: Uses age groups (e.g., "0–5", "6–10").

✅ Epidemiology Data: Contains individual ages (e.g., 4, 7, 12).

🔄 Recommended Relationship Setup

Data Transformation Needed: Convert individual ages into the same age ranges as the Primary Research Data.

⚙️ Action Steps

🛠 Creating Age Groups in Epidemiology Data

1️⃣ Open Power Query Editor.

2️⃣ Select the Epidemiology table.

3️⃣ Add a new custom column named Age Group using the following logic:

```
= if [Age] >= 0 and [Age] <= 5 then "0–5"
  else if [Age] >= 6 and [Age] <= 10 then "6–10"
  else if [Age] >= 11 and [Age] <= 15 then "11–15"
  else "16+"
```

4️⃣ Adjust the age ranges as necessary.

5️⃣ Close and apply the changes.

🔗 Creating the Relationship

1️⃣ In Model View, drag the Age Group column from the Primary Research table to the Age Group column in the Epidemiology table.

2️⃣ In the Edit Relationship dialog:

Cardinality: 🟢 Many-to-Many

Cross-Filter Direction: 🔄 Both

3️⃣ Click OK to confirm.

## 📷 Screenshots & Visuals  
### **Screenshots & Visuals**  

**Figure 1: Main Dashboard View**  
![Screenshot 2025-03-13 181622](https://github.com/user-attachments/assets/a26f7e12-6276-42ab-b055-0009628081c0)  

**Figure 2: Data relationship in Power Bi**  
![Screenshot 2025-01-03 170542](https://github.com/user-attachments/assets/0fb79a65-eeef-444c-ae1c-a8b21c9d5c74)  

**Figure 3: Data relationship in Power Bi**  
![Screenshot 2025-01-03 171449](https://github.com/user-attachments/assets/6c55dd9d-e7cf-4950-b841-8cdd570e00b8)  

**Figure 4: Changing Data types**  
![Screenshot 2025-01-03 170756](https://github.com/user-attachments/assets/3f50dc26-e4bb-4dff-8857-7d37a01a442f)  

**Figure 5: Data Preparation in Power Query**  
![Screenshot 2025-01-03 170859](https://github.com/user-attachments/assets/eb08a610-be97-46d6-b366-bdda554e5a31)  


## 🛠️ Technical Details  
1️⃣ **Power Query (M Language)**: Used for data transformation, cleaning, and reshaping of records before loading into the data model. 

🔹 Severity counts and distributions

🔹 Age averages by demographic groups

🔹 Adverse event percentages

🔹 Outcome analysis.

2️⃣ **Geospatial Integrations**: Implemented location mapping using TomTom and Microsoft map services with OpenStreetMap data.  
3️⃣ **Filtering Logic**:  Cross-filtering implemented between visualizations for interactive analysis by vaccine type, year, severity, and demographic factors.

## 🔥 Future Improvements  
- [ ] Integrate machine learning models to predict adverse event risks
- [ ] Automate data refresh using Power BI Gateway for real-time updates  
- [ ] Enhance UI/UX with interactive drill-through reports and tooltips
- [ ] Enable mobile-friendly dashboards for better accessibility
- [ ] Incorporate external data sources (e.g., WHO) for comparative insights
- [ ] Develop an alert system to notify healthcare professionals of emerging trends
- [ ] Optimize data processing for faster query performance and lower latency
- [ ] Implement role-based access control (RBAC) for better data security
- [ ] Publish the dashboard to Power BI Service for wider accessibility and collaboration

## 📧 Contact  
🔹 **Author**:Kavishka Chathuranga Herath
🔹 **Email**:[kavishkacherath@gmail.com]  
🔹 **LinkedIn**:(https://www.linkedin.com/in/kavishka-herath-2ab2b3245/)  
🔹 **GitHub**:(https://github.com/Kavi511)  
