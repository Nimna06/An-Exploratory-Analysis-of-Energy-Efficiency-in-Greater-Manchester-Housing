# Energy Performance Analysis of Manchester Local Authorities

## Overview
This project analyzes **Energy Performance Certificate (EPC)** data for residential properties across **Greater Manchester** using **SQL Server** and visualizes insights through an interactive **Power BI dashboard**.  

The analysis focuses on **energy efficiency trends, CO₂ emissions, energy costs, and improvement potential** to support sustainability initiatives and data-driven policy decision-making.

---

## Dataset
The project uses two EPC datasets: **Certificates** and **Recommendations**, which provide property-level energy performance data and suggested efficiency improvements.

**Source:** UK Domestic EPC Open Data Portal  
**Format:** CSV  
**Coverage Period:** 2014–2024  

---

## Project Components

### 1. SQL Analysis
**SQL Server (T-SQL)** was used for data cleaning, transformation, and integration.

Key tasks include:

- Cleaning and standardizing EPC data  
- Removing duplicates and handling missing values  
- Integrating certificates and recommendations using **LMK_KEY**  
- Preparing analytical tables for Power BI  

---

### 2. Power BI Dashboard
The **Power BI (.pbix)** dashboard presents interactive visualizations including:

- Current vs Potential Energy Efficiency  
- CO₂ Emissions by Property Type and Over Time  
- Heating and Lighting Cost Analysis  
- Recommendation Frequency and Improvement Potential  
- Geospatial Distribution of EPC Certificates  


### 3. Report
A detailed **PDF report** covering:

- Data preparation and SQL methodology  
- Power BI modeling and DAX measures  
- Results analysis, key findings, and recommendations  

---

## Key Findings

- **85% of properties** show potential for energy efficiency improvement  
- **Average potential efficiency** exceeds current efficiency by approximately **12 points**  
- **Heating costs** are the primary contributor to energy expenses and CO₂ emissions  
- **Houses** represent the largest opportunity for **mass retrofitting**  
- **Park Homes** are identified as the **least energy-efficient property type**

---

## Limitations

- EPC data does not cover all properties in Manchester  
- Analysis is based on **lodged EPC records**, not real-time energy usage  
- **Socio-economic factors** were not included in the dataset  
- Findings may not fully represent **post-2024 conditions**

---

## Recommendations

- Prioritize **heating system improvements and insulation upgrades**  
- Implement **targeted retrofit programs** for low-efficiency properties  
- Support **local authority energy-efficiency policies**  
- Use **interactive dashboards** for continuous monitoring and planning  

---

## Challenges

- Handling **large datasets with inconsistent formats**  
- Cleaning **corrupted and duplicate values**  
- Designing **clear and meaningful Power BI visualizations**  
- Interpreting **efficiency gaps across property types**

---

## Conclusion

This project demonstrates how **SQL Server and Power BI** can transform large-scale public **EPC datasets** into actionable insights.  

The findings highlight significant opportunities to **improve residential energy efficiency** and support **sustainable urban planning in Greater Manchester**.

---

## Author
Nimna Jayawardhana
BSc in Applied Data Science Communication (Undergraduate)

---

## License

This project is for **educational purposes only**.
