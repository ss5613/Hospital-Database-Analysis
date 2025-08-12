# 📊 Hospital Database Analysis with Power BI
This project presents a comprehensive analysis of a hospital's operations using a custom-generated database and an interactive Power BI dashboard. It demonstrates key data analysis skills, including data wrangling, data modelling, and effective data visualization, to provide actionable insights for hospital management.

## 💡 Problem Statement
Hospitals generate large volumes of data, but often struggle to derive meaningful insights for decision-making. This project addresses the challenge of transforming raw operational data into a clear, visual format to help stakeholders monitor key performance indicators (KPIs) and improve efficiency. The analysis focuses on understanding patient demographics, doctor performance, appointment trends, and billing metrics.

## 💻 Data Source and ETL
The dataset was created from scratch to simulate a realistic hospital environment. Using Python and Jupyter Notebooks, I generated six interconnected tables:

 	• **Patient Details:** Contains demographic information on patients, including age groups and insurance providers.

 	• **Doctor Details:** Lists doctors' specializations, working hours, and salaries.

 	• **Appointment Details:** Tracks appointment statuses (e.g., Scheduled, Completed, No-Show) and links patients to doctors.

 	• **Billing:** Provides financial data, including amounts due and payment statuses.

 	• **Inventory:** Details the hospital's medical supplies, their prices, and quantities.

 	• **Room Details:** Manages room assignments, types, and daily prices.
 
## ⚙️ Data Modelling
I created a relational model to link these tables within Power BI, ensuring that the data is organized for efficient querying and analysis. Key relationships established were between:
	• Patient Details and Appointment Details (using patient_id)
	• Doctor Details and Appointment Details (using doctor_id)
	• Appointment Details and Billing (using appointment_id)
	• Patient Details and Room Details (using patient_id)

 Below shows the ER diagram fo the data :
 
<img width="1431" height="806" alt="image" src="https://github.com/user-attachments/assets/b4ecf0e9-2d80-4157-bf45-ce17f85e3d14" />

## 📊 Key Insights & Visualizations
The Power BI dashboard provides an interactive and intuitive interface for exploring the data. It answers critical business questions through a series of key visualizations and metrics:


• **Patient Demographics:** A breakdown of patients by age group and gender to help understand the patient base.


<img width="1373" height="761" alt="image" src="https://github.com/user-attachments/assets/b62c7552-6614-4e96-8739-1c26f8bada3e" />


• **Doctor Performance:** A dashboard segment showcasing each doctor's number of patients and total working days.


<img width="1377" height="761" alt="image" src="https://github.com/user-attachments/assets/8c7bb787-0976-4730-a070-e8a1c90c8dba" />


• **Appointment Analysis:** A view of appointment statuses, highlighting the ratio of Completed, Cancelled, and No-Show appointments to identify operational bottlenecks. This section also tracks appointments by doctor and specialization to assess workload.


<img width="1115" height="623" alt="image" src="https://github.com/user-attachments/assets/72f202f1-2fa1-4a0d-ad51-fa1b67bec62e" />



• **Payments Overview:** An at-a-glance summary of financial health, displaying Total Amount, Paid Amount, and Amount Due. A visual of payment_status helps in prioritizing collections efforts.


<img width="1117" height="622" alt="image" src="https://github.com/user-attachments/assets/78cc63c2-9aaf-41c0-b717-5a608fd0dd33" />


• **Inventory Management:** An overview of inventory levels to aid in resource planning and stock management.


<img width="1118" height="626" alt="image" src="https://github.com/user-attachments/assets/af7f466b-541e-4b1f-97ba-3c9afa956c8b" />


• **Room Management:** An overview of room utilization to aid in resource planning and stock management.


<img width="1117" height="624" alt="image" src="https://github.com/user-attachments/assets/04197101-fb87-4bce-9497-acbc99a594db" />


## 🛠️ Skills Demonstrated

This project demonstrates a range of data analysis and business intelligence skills:
	
**• Data Sourcing and Preparation:** Using Python to create a custom, clean dataset from scratch utilizing API's.

**• Data Modelling:** Structuring and linking multiple tables in a relational model within Power BI.

**• DAX (Data Analysis Expressions):** Creating calculated columns and measures to derive complex metrics.

**• Interactive Dashboard Design:** Building a user-friendly and visually appealing dashboard for business users.

**• Business Acumen:** Translating a business problem (hospital management) into a data-driven solution.





