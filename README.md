# Human Resources Dashboard — Tableau Project

## 🧾 Project Description

The **Human Resources Dashboard** project provides an end-to-end analysis of workforce data to uncover insights into employee demographics, performance, and salary distribution. The dataset was generated programmatically using a Python script (`generate_data_set.py`) and stored as `HumanResources_Dataset.csv` for analysis in **Tableau**.

The dashboard is divided into three key analytical sections:

* **Overview** – Highlights total hires, active, and terminated employees over the years, with breakdowns by department, job title, and location (HQ vs. branches).
* **Demographics** – Displays gender ratio, education level, age distribution, and correlations between education and performance ratings.
* **Income Analysis** – Compares salaries by gender, education level, and department, and analyzes how age correlates with compensation.

A second view, **Employee Records**, lists all employee details, including department, job title, salary, status, and tenure, allowing filtering and dynamic exploration of the workforce.

---

## ⚙️ Tools & Technologies Used

* **Python (Pandas, NumPy, Faker)** – For data generation and preprocessing
* **Tableau** – For data visualization and dashboard creation
* **CSV Dataset** – `HumanResources_Dataset.csv` (synthetic dataset with 8,950 employee records)

---

## 🔍 Main Features

* Programmatically generated a realistic HR dataset with Python functions simulating real employee data.
* Built an **Overview Dashboard** showing key HR metrics: hires, terminations, departments, and locations.
* Developed **Demographic Analysis** visuals for gender ratio, education distribution, and performance comparison.
* Designed **Income Insights** to explore relationships between education, gender, age, and salary.
* Created a **Dynamic Employee Records View** to filter employees by multiple criteria (status, gender, department, education, etc.).
* Provided clear, interactive visualization of hiring trends and workforce composition for management reporting.

---

## 📊 Output / Results

* A centralized Tableau dashboard summarizing all HR metrics in one view.
* Identified **gender balance** at 54% male and 46% female.
* Showed that **Operations and Sales departments** have the highest employee counts.
* Found salary growth correlated with both **education level** and **age group**.
* Highlighted performance variations linked to **education background**.
* Provided HR managers with a **filterable employee record list** for detailed analysis.

---

## 📸 Dashboard Visuals

### Overview Dashboard

<p align="center">
  <!-- <img src="https://files.oaiusercontent.com/file_00000000c71c720693723285c8155794" alt="Overview Dashboard" width="800" /> -->
  <img width="1403" height="802" alt="Screenshot 2025-11-12 184016" src="https://github.com/user-attachments/assets/60fab772-ee67-47e3-bf49-ab835e06607b" />

</p>

*Displays overall workforce insights including hires, terminations, departments, locations, and salary analysis.*

### Employee Records Dashboard

<p align="center">
  <!-- <img src="https://files.oaiusercontent.com/file_000000002628720697a2f9eb1f8d62bd" alt="Employee Records Dashboard" width="800" /> -->
  <img width="1403" height="808" alt="Screenshot 2025-11-15 011206" src="https://github.com/user-attachments/assets/a2eef6e3-3a7e-4df2-96c0-94fd5bb3ae27" />


</p>

*Shows detailed employee information with filters by gender, department, education, and employment status.*

---

## 📂 Project Files

* `generate_data_set.py` – Python script used to create the dataset
* `HumanResources_Dataset.csv` – Synthetic dataset (8,950 records)
* `HR_Dashboard.twbx` – Tableau packaged workbook
* `icons/` – Folder containing all custom icons used in the Tableau dashboard design (navigation, charts, and filters)

---

## 👤 Author

**GLAVIN SHRINEMENEZES** — Data Analyst
📧 [glavinm13@gmail.com](mailto:glavinm13@gmail.com)
💼 [LinkedIn](https://www.linkedin.com/in/glavin-shrinemenezes-6120a7307/)

---

*Note: This project is created for learning and analytical demonstration purposes.*
