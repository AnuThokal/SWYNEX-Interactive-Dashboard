# Project Overview :
<img width="1276" height="726" alt="Screenshot (86)" src="https://github.com/user-attachments/assets/b076e61f-b098-4ff1-b63c-a6034bdb5664" />
This dashboard gives a quick view of hospital revenue and patient numbers in one place. It helps answer simple questions like which month earned the most, which department brings the most revenue, and who the top doctors are.
# Business Questions:
-How much total revenue did the hospital earn, and how many patients did it treat?
-Which months had the highest and lowest revenue?
-Which departments bring in the most revenue?
-Which doctors generate the most revenue?
-How are patients split by department, gender and age group?
 # Dataset:
 -Source: Messy_clinic_appointment dataset 
 -Records: 465 patients
 -Main columns: (patient_id, appointment_id, age, age group, gender, appointment_date, booking_date, doctor, department, amount, follow_up_required)
 # Tools Used:
 Power BI Desktop : Building the dashboard and visuals
 Excel : Source data / data checking
# Dashboard Features:
### KPI Cards:
**Sum of Amount**
<img width="110" height="41" alt="80" src="https://github.com/user-attachments/assets/334def83-3835-4629-a77f-4b938e13b566" />
Shows the total revenue earned, which is ₹6.01629M. It gives a quick view of the overall income at a glance.
**Total Patients**
<img width="90" height="40" alt="90" src="https://github.com/user-attachments/assets/a3d51f34-4c29-4fd3-b875-c78626196068" />
Shows the total number of patients treated, which is 465. It helps compare revenue against patient volume.
### Filter
<img width="282" height="22" alt="91" src="https://github.com/user-attachments/assets/de05b2ab-b2b2-4e08-9f75-f531d9bd0867" />
**Quarter Buttons (Qtr 1 to Qtr 4)**
Click any quarter to see the numbers for that part of the year only. All the charts update together.
### Charts
**Amount by Month (Column Chart)**
<img width="320" height="147" alt="92" src="https://github.com/user-attachments/assets/6f2f5671-bc4d-456b-85c9-2e6f2eb274ea" />
Shows revenue for each month from January to December. February is the highest at 789K and September is the lowest at 301K.
**Department wise Patients (Treemap)**
<img width="156" height="146" alt="93" src="https://github.com/user-attachments/assets/2a29234a-ee98-49b2-a75c-7b08e0a04827" />
Shows the number of patients in each department, with bigger boxes for more patients. Neurology and Orthopedics have 119 each, General has 118 and Cardiology has 109.
**Patients: Male vs Female (Clustered Column Chart)**
<img width="239" height="153" alt="94" src="https://github.com/user-attachments/assets/d2a16414-e4ec-40f1-a8de-59e769fb6230" />
Compares male and female patients across Adult, Senior and Teenager groups. Adults are the biggest group, with 134 female and 106 male patients.
**Top 5 Doctors by Amount (Bar Chart)**
<img width="272" height="104" alt="doctor chart" src="https://github.com/user-attachments/assets/d3bab836-9795-4e4e-91aa-1885ecdba193" />
Shows the five doctors who brought in the most revenue. Emily Barnes and Richard Walker lead at 48K each, and Nancy Hernandez, Scott Shannon and Kathryn Young follow closely at 47K each.
# What I Learned
-Building a full dashboard in Power BI from raw data
-Choosing the right chart for each question
-Using cards, slicers and buttons to make a report easy to read
-Turning charts into simple business insights
