# 📊 Exploratory Data Analysis on Healthcare Appointments

This project performs an end-to-end **Exploratory Data Analysis (EDA)** on a real-world **medical appointment dataset** to uncover factors affecting **patient no-shows**. Using tools like Python, Pandas, NumPy, and Seaborn, the project visualizes, analyzes, and interprets patterns related to patient behavior, appointment scheduling, and medical conditions.

---

## 🔍 Objective

The goal is to understand why patients **miss their appointments** and identify which features — such as **age**, **SMS reminders**, **medical conditions**, or **appointment timing** — significantly influence their attendance behavior.

---

## 🗂️ Dataset Description

The dataset contains over **110,000 medical appointment records** from Brazil, with the following key fields:

- `PatientId`, `AppointmentID`
- `ScheduledDay`, `AppointmentDay`
- `Age`, `Gender`
- `Neighbourhood`
- `Scholarship`, `Hypertension`, `Diabetes`, `Alcoholism`
- `SMS_received`, `No-show` (Target Variable)

---

## ⚙️ Tools and Libraries Used

- **Python**  
- **Pandas**, **NumPy** for data handling  
- **Seaborn**, **Matplotlib** for data visualization  
- **Jupyter Notebook** for interactive analysis

---

## 🔧 Key Steps Performed

1. **Data Cleaning**  
   - Removed invalid ages (e.g., age < 0)  
   - Standardized column names and date formats  
   - Handled missing and duplicate values

2. **Feature Engineering**  
   - Extracted **day of week** from `ScheduledDay` and `AppointmentDay`  
   - Created new variables for time difference between scheduling and appointment

3. **Univariate and Bivariate Analysis**  
   - Plotted distributions of age, gender, and SMS reception  
   - Compared attendance across different medical conditions (e.g., diabetes, hypertension)

4. **Insights and Observations**  
   - SMS reminders did **not consistently reduce no-shows**  
   - Patients with **hypertension and diabetes** had slightly higher show-up rates  
   - **Weekday trends** showed more no-shows on certain days (e.g., Fridays, Saturdays)  
   - Longer time gaps between scheduling and appointment date correlated with higher no-shows

---

## 📌 Sample Visualizations

> _Insert screenshots of your visualizations below (save in `screenshots/` folder and update paths)_
