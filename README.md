# Task-1
Data Cleaning and Preprocessing
# Medical Appointment No-Show Dataset 🏥

This project involves cleaning and preprocessing the [KaggleV2-May-2016.csv](https://www.kaggle.com/datasets/joniarroba/noshowappointments) dataset containing information on 110,000+ medical appointments in Brazil, with the aim of identifying patterns behind patient no-shows.

## 🧹 Cleaning Summary

The following changes were made to prepare the dataset for analysis:

- ✅ **Renamed Columns**:
  - `Handcap` ➝ `Handicap`
  - `No-show` ➝ `No_Show`
- 📅 **Converted to DateTime**:
  - `ScheduledDay` and `AppointmentDay`
- 🔁 **Mapped `No_Show` to Boolean**:
  - `Yes` ➝ `True` (No-show)
  - `No` ➝ `False` (Showed up)
- 🧼 **Removed Invalid Rows**:
  - 1 entry with a negative age removed
- 🔢 **Formatted ID Columns**:
  - `PatientId` converted to string to prevent scientific notation
- 🧯 **Duplicate Check**:
  - No duplicate rows found

## 📁 Files

- `KaggleV2-May-2016.csv` – Original dataset
- `cleaned_appointments.csv` – Cleaned dataset ready for analysis
- `clean_data.py` – Python script used for cleaning

## 📊 Next Steps

- Perform EDA (Exploratory Data Analysis)
- Build predictive models for patient no-shows
- Visualize trends and demographic patterns

## 📌 Credits

Dataset from Kaggle: [No-show appointments](https://www.kaggle.com/datasets/joniarroba/noshowappointments)

---

🧠 Maintained by: *Your Name Here*
