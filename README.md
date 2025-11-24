# Electric Vehicles Dashboard Analysis (Tableau)

This project is an interactive **Electric Vehicles Dashboard** built in **Tableau** to analyze the adoption of electric vehicles (EVs) across the United States.  
It helps users explore how EV adoption varies by **model year, state, make, model, eligibility status, and EV type**.

---

## ✨ Objective

- To provide a **single view** of key metrics related to electric vehicles.
- To help stakeholders understand:
  - Growth of EVs over time  
  - Distribution of EVs across states  
  - EV performance in terms of average electric range  
  - Breakdown by **BEV vs PHEV**  
  - CAFV (Clean Alternative Fuel Vehicle) eligibility status  
  - Top contributing makes and models

---

## 🖼️ Dashboard Preview

Below is a snapshot of the interactive Tableau dashboard created for Electric Vehicle Dashboard Analysis 👇  

![Electric Vehicles Dashboard Preview](## 🖼️ Dashboard Preview

Below is a snapshot of the interactive Power BI dashboard created for Hospital Emergency Dashbaord 👇  

![Hospital Emergency Dashboard Preview](https://github.com/ths887/Electric-Vehicles-Dashboard-Analysis/blob/main/Electric%20Vehicle%20Dashboard%20Image.png)

## 📊 Key Metrics

The KPI cards at the top of the dashboard summarize:

- **Total Vehicles** – overall number of registered electric vehicles  
- **Average Electric Range (Miles)** – average range across all EVs  
- **Total BEV Vehicles** – count and share of **Battery Electric Vehicles**  
- **Total PHEV Vehicles** – count and share of **Plug-in Hybrid Electric Vehicles**

---

## 📈 Dashboard Views

The dashboard includes the following visualizations:

1. **Total Vehicles by Model Year**
   - Line/area chart showing how EV registrations have grown over time.
   - Highlights trends in adoption and any peak years.

2. **Total Vehicles by State (Map)**
   - Filled map of the United States showing the number of EVs in each state.
   - Helps identify **high-adoption** and **low-adoption** regions.

3. **Top 10 Total Vehicles by Make**
   - Bar chart summarizing the **top manufacturers** (e.g., Tesla, Nissan, Chevrolet).
   - Shows each make’s contribution to the total vehicle count and share (% of total).

4. **Total Vehicles by CAFV Eligibility**
   - Donut chart showing:
     - CAFV Eligible  
     - CAFV Not Eligible  
     - CAFV Unknown  
   - Useful for understanding how many vehicles qualify for clean fuel incentives.

5. **Total Vehicles by Model**
   - Table listing EV models with:
     - Make  
     - EV Type (BEV or PHEV)  
     - Total vehicles  
     - Percentage of total  
   - Helps identify **top-performing EV models** in the market.

---

## 🔍 Filters & Interactivity

The dashboard is fully interactive and includes the following filters:

- **CAFV Eligibility** – (All, Eligible, Not Eligible, Unknown)  
- **EV Type** – (All, BEV, PHEV)  
- **Model** – filter by specific vehicle model  
- **State** – filter by one or more U.S. states  

Users can combine filters to answer questions like:

- *“How many BEVs are CAFV eligible in California?”*  
- *“Which make has the highest vehicle count in recent model years?”*  
- *“What is the distribution of PHEVs by state?”*

---

## 🧹 Data & Preparation

> (Update this section based on your actual data source.)

- **Data Source:** Electric vehicle registration dataset (e.g., state EV registration/open data portal).
- **Data Cleaning & Preparation:**
  - Removed duplicates and invalid records
  - Standardized state names and codes
  - Created calculated fields for:
    - EV type categories (BEV / PHEV)
    - CAFV eligibility groups
    - Percentage of total vehicles
  - Handled missing or unknown eligibility values

---

## 🛠 Tools & Skills Demonstrated

- **Tools**
  - Tableau Desktop
- **Skills**
  - Data cleaning & transformation  
  - Creating calculated fields & KPIs  
  - Building interactive dashboards & filters  
  - Using maps and advanced charts in Tableau  
  - Designing user-friendly, insight-driven layouts  

---


├── Electric_Vehicles_Dashboard.twbx      # Tableau workbook (if shared)
└── README.md
