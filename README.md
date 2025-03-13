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

## 📷 Screenshots of sample datasets 
![image](https://github.com/user-attachments/assets/73678df9-0169-48a3-9d4a-040b8ea98890)
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
 
**1. Severity (Low, Mid, High)**

* **Description:** Categorical classification of the seriousness of the reported adverse event following vaccination.
* **Data Type:** Categorical (String)
* **Possible Values:**
    * **Low:** Minor adverse events that typically resolve quickly without significant intervention. Examples may include mild pain, redness, or swelling at the injection site.
    * **Mid:** Moderate adverse events that may require medical attention or cause some discomfort or temporary disruption to daily activities. Examples may include fever, rash, or more pronounced local reactions.
    * **High:** Severe adverse events that may require hospitalization, lead to long-term complications, or be life-threatening. Examples may include anaphylaxis, seizures, or severe neurological reactions.
      
**2. Outcome Categories**

* **Description:** Describes the current status or resolution of the reported adverse event.
* **Data Type:** Categorical (String)
* **Possible Values:** (Based on the image, only "Resolved" is visible, but this list can be expanded)
    * **Resolved:** The adverse event has subsided and the individual has recovered.
    * **(Other possible values, not visible in the image):**
        * **Ongoing:** The adverse event is still present and being monitored.
        * **Recovering:** The adverse event is improving but not fully resolved.
        * **Fatal:** The adverse event resulted in death.
        * **Unknown:** The outcome of the adverse event is not yet known.

**3. Adverse Event Types**

* **Description:** Specific descriptions of the reported adverse reactions following vaccination.
* **Data Type:** Categorical (String)
* **Possible Values:** 
    * Pain at injection
    * High fever (>40°C)
    * Severe local reaction
    * Anaphylaxis
    * Other neurological... (further detail needed for complete understanding)
    * Severe allergic reaction
    * Seizures
    * Acute paralysis

**4. Vaccine Types**

* **Description:** The name of the vaccine administered.
* **Data Type:** Categorical (String)
* **Possible Values:** (Based on the image)
    * DTP (Diphtheria, Tetanus, Pertussis)
    * Hepatitis A
    * Influenza
    * Japanese Encephalitis
    * Covid-19
    * MMR (Measles, Mumps, Rubella)
    * Polio
    * Pneumococcal
    * Meningococcal
    * Rotavirus
    * Typhoid
    * Varicella (Chickenpox)
    * Yellow fever
    * Rabies

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
🔹 **Author**:[Kavishka Chathuranga Herath]  
🔹 **Email**:[kavishkacherath@gmail.com]  
🔹 **LinkedIn**:(https://www.linkedin.com/in/kavishka-herath-2ab2b3245/)  
🔹 **GitHub**:(https://github.com/Kavi511)  



