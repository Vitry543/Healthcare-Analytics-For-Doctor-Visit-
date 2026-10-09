# Healthcare-Analytics-For-Doctor-Visit-
This EDA project investigates socio-economic, demographic, and health determinants of patient doctor visits using 5,190 records. By analyzing chronic conditions, insurance status, and illness counts, it uncovers healthcare demand patterns to optimize medical resource allocation.


---

## 📖 Project Overview
Healthcare systems often struggle with understanding the factors influencing medical consultations. This project analyzes patient records to uncover patterns in healthcare utilization. By evaluating variables such as chronic conditions, insurance coverage, income levels, and illness counts, this repository provides actionable insights to help optimize healthcare resource allocation.

---

## 📊 Dataset Description
The analysis utilizes a dataset of **5,190 patient records** containing the following features:
* **Target Variable:** `visits` (Number of doctor visits during the observation period)
* **Demographics:** `age`, `gender`, and scaled `income`
* **Health & Clinical Metrics:** `illness` (number of illnesses), `reduced` (restricted activity days), `health` (general health status score), `nchronic` & `lchronic` (chronic conditions)
* **Insurance & Welfare Status:** `private` (private health insurance), `freepoor` (low-income government insurance), and `freerepat` (veterans/repatriation insurance)

---

## 🛠️ Tech Stack & Libraries
* **Language:** Python
* **Data Processing:** Pandas, NumPy
* **Data Visualization:** Seaborn, Matplotlib
* **Environment:** Jupyter Notebook

---

## 🚀 Key Project Workflow
1. **Data Inspection & Cleaning:** Loaded dataset, verified structure, checked for missing values, and cleaned index artifacts.
2. **Univariate Analysis:** Explored distributions of individual features like income histograms, visit count distributions, and gender ratios.
3. **Bivariate & Multivariate Analysis:** Examined relationships between health status (illness counts, reduced activity days) and consultation frequencies, as well as insurance disparities across income brackets.

---

## 📈 Key Insights
* **Utilization Skew:** The vast majority of patients had zero doctor visits (mean ~0.30 visits), while high utilizers went up to 9 times.
* **Health Correlation:** A direct link exists between the number of reported illnesses, reduced activity days, and increased doctor consultation frequency.
* **Insurance Impact:** A significant portion of patients hold private health insurance, highlighting distinct socio-economic divides in medical access.

---

## ⚙️ How to Run the Code
1. Clone this repository:
   ```bash
   git clone [https://github.com/your-username/healthcare-analytics-doctor-visits.git](https://github.com/your-username/healthcare-analytics-doctor-visits.git)
