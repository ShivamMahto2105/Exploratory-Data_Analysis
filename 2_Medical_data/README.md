# 🏥 Medical Appointment No-Show Analysis – EDA Project

This project explores a real-world dataset of medical appointments in Brazil, with a specific focus on analyzing factors that influence whether a patient **shows up for their scheduled medical appointment** or not.

---

## 📁 Project Folder Structure


---

## 🧠 Objective

To investigate and identify:

- 📊 What factors influence patient no-shows?
- 📅 How do scheduling and appointment day gaps affect attendance?
- 🩺 Are age, gender, or medical conditions like diabetes and hypertension correlated with missing appointments?
- 💬 Does receiving an SMS reminder improve attendance?

---

## 📊 Dataset Overview

The dataset contains over **110,000+ records** with the following key features:

| Column Name      | Description                                         |
|------------------|-----------------------------------------------------|
| `PatientId`      | Unique patient identifier                           |
| `AppointmentID`  | Unique appointment identifier                        |
| `Gender`         | Patient gender (M/F)                                |
| `ScheduledDay`   | Timestamp of when the appointment was scheduled     |
| `AppointmentDay` | Date of the appointment                             |
| `Age`            | Patient’s age                                       |
| `Neighbourhood`  | Area in which the patient lives                     |
| `Scholarship`    | 1 if patient is enrolled in Bolsa Família (welfare) |
| `Hipertension`   | 1 if patient has hypertension                       |
| `Diabetes`       | 1 if patient has diabetes                           |
| `Alcoholism`     | 1 if patient suffers from alcoholism                |
| `Handcap`        | 1 or more indicating disability                     |
| `SMS_received`   | 1 if an SMS reminder was sent                       |
| `No-show`        | 'Yes' if the patient missed the appointment         |

📄 [**Click here to view the dataset**](https://github.com/Shivam-DataAnalytics/Exploratory-Data_Analysis/blob/main/2_Medical_data/Medical_data.csv)

📘 [**Click here to view the EDA Notebook**](https://github.com/Shivam-DataAnalytics/Exploratory-Data_Analysis/blob/main/2_Medical_data/Medical_data_appointment.ipynb)

---

## 🧪 Key Findings

- ✅ **SMS reminders** slightly increase attendance, but are not strongly predictive
- ✅ **Patients with hypertension or diabetes** are more likely to show up
- ❗ **Younger patients (below 30)** tend to miss appointments more often
- 📅 A **large gap** between scheduling and appointment dates often results in no-shows
- 🌍 Neighborhood and socio-economic background (Scholarship) may influence attendance

---

## 📈 Tools & Techniques Used

- **Python (Jupyter Notebook)**
- **Pandas** – Data manipulation and date-time handling
- **Matplotlib & Seaborn** – Data visualization
- **Datetime Analysis** – Day gaps, time trends
- **GroupBy Analysis** – Targeted breakdown by gender, age, and conditions
- **Correlation Heatmaps**, **Pie Charts**, **Countplots**, and **Bar Charts**

---

## 🖼️ Sample Visuals

📍 [Scholarship](https://github.com/Shivam-DataAnalytics/Exploratory-Data_Analysis/blob/main/2_Medical_data/Scholarship.png)

📍 [Alcoholism and Handicaped](https://github.com/Shivam-DataAnalytics/Exploratory-Data_Analysis/blob/main/2_Medical_data/Alcoholism%20and%20Handicap.png)

📍 [Hypertension and Diabetes](https://github.com/Shivam-DataAnalytics/Exploratory-Data_Analysis/blob/main/2_Medical_data/Hypertension%20and%20Diabetes.png)

---

## 📌 Conclusion

This EDA offers valuable insights for healthcare providers and policy makers to improve **patient engagement**, **reduce appointment gaps**, and **enhance reminder systems**. Addressing the issues uncovered here can contribute to:

- Better resource allocation  
- Improved patient care delivery  
- Cost savings for healthcare institutions

---

## 📬 Contact

- 🔗 [LinkedIn – Shivam Kumar Mahto](https://www.linkedin.com/in/shivam-kumar-mahto-b7a84a311)
