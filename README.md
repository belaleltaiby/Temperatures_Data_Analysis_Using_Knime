# KNIME Temperature Analysis

## 📌 Overview
This project is a data analysis task using KNIME to process temperature data over the past 270 years. The goal is to compute average temperatures, classify temperature levels, compare against global trends, and visualize the data.

## 📁 Dataset
- Two CSV files containing temperature data by country and year.

## ✅ Requirements
- KNIME Analytics Platform
- Dataset (included in the `data/` folder)

## 🚀 Steps & Workflow
### **1️⃣ Calculate Average Temperature per Country**
- Used the **GroupBy** node to calculate the average temperature for each country.

### **2️⃣ Classify Countries by Temperature Level**
- Used the **Numeric Binner** node to classify temperatures into:
  - **Low:** 0 - 30
  - **Mid:** 30 - 60
  - **High:** 60 - 90

### **3️⃣ Compute Temperature Difference**
- Calculated the difference between country average temperature and the global temperature in the last 24 years.

### **4️⃣ Identify Top 5 Countries with Largest Temperature Difference**
- Sorted the temperature difference and extracted the top 5 countries.

### **5️⃣ Draw a Histogram of Yearly Global Temperatures**
- Used **Histogram** node to visualize yearly global temperatures.

### **6️⃣ Compare a City’s Temperature with Global Average**
- Selected a city and created a **Line Chart** comparing its yearly temperature with the global average.

## 📊 Outputs
Screenshots of the workflow are available in the `screenshots/` folder.

## 💾 Exported Workflow
The workflow is saved in `workflow/Belal-Test.knwf` and can be imported into KNIME.

## 🛠️ How to Use
1. Download and install KNIME.
2. Open KNIME and import the `.knwf` file.
3. Run the workflow and verify the outputs.

---

