# 🕵️‍♂️ Crime, Arrests, and Traffic Collisions in Los Angeles (2021)

This project explores and visualizes trends in **Crime**, **Arrests**, and **Traffic Collisions** in Los Angeles during the year 2021, using datasets sourced from [Data.gov](https://catalog.data.gov/). It involves a full data pipeline from extraction and transformation, to analysis and visual storytelling — aimed at supporting public safety, urban planning, and policymaking.

👥 **Contributors:**
- Preena Darshini (Crime Analysis)
- Priscila Cristina da Silva de Oliveira (Arrest Analysis)
- Reyna Vargas Antonio (Traffic Collision Analysis)

---

## 🚦 Focus Area: Traffic Collision Analysis (by Reyna Vargas Antonio)

This part of the project analyzes **18,992 traffic collision incidents** reported in Los Angeles during 2021.

### 🔍 Key Insights

- **Monthly Trends:** January saw the most reported traffic collisions (1,767). Other months averaged ~1,000.
- **High-Risk Areas:**  
  - 77th Street area had the **highest number** of incidents: 1,251 total (741 men, 452 women).
  - West LA, Northeast, and Pacific had fewer reported incidents.
- **Locations of Collisions:**
  - Most common: **Street** (12,932 cases)
  - Other locations: Parking Lots, Sidewalks, and even unique spots like churches and restaurants.
- **Victim Demographics:**
  - **Ethnicity:**  
    - 45.7% Hispanic/Latino  
    - 20.4% White  
    - 17.6% Black
  - **Gender Differences:**  
    - Men were 2–3x more likely than women to be involved in traffic incidents.
  - **Age:**  
    - Most victims were aged **28–50 years**.  
    - Median age: 38 (men), 36 (women)
- **Time of Day:**  
  - Peak incidents: **17:00–17:49**  
  - Lowest: Around 04:00
- **Probability by Age Group:**  
  - Highest risk of incident involvement was in people in their **30s**.
  - Unknown gender group had unusually high probability in the **20s** age range.

### 🛠 Tools & Techniques Used
- **Python:** `pandas`, `matplotlib`, `seaborn`, `datetime`, `pymongo`
- **MongoDB:** For initial semi-structured data storage (JSON)
- **PostgreSQL:** Final storage and querying
- **Data Preprocessing:** Handling missing values, encoding formats, restructuring nested JSON


![Traffic Trends Chart]([https://example.com/images/trends.png](https://github.com/Rey-irl/Traffic-Collisions-in-Los-Angeles-A-Deep-Dive-into-2021-Trends/blob/main/Number%20of%20Traffic%20Collision%20by%20Area%20and%20Gender.png))

---

## 🧠 Project Overview

### 📂 Datasets Used:
- **Crime (XML)** – 208K records
- **Arrest (JSON)** – 66K records
- **Traffic Collision (JSON)** – 18K records

### 📌 Methodology:
- **ETL Process:** Extract → Transform → Load
- **Databases:** MongoDB for staging, PostgreSQL for final analysis
- **Visualization:** Data analyzed using `Seaborn`, `Matplotlib`, and `Plotly`

---

## 🔮 Future Work
- Apply **Machine Learning** for predictive modeling of future crime or collision hotspots.
- Perform **geospatial clustering** to detect accident-prone zones.

---

## 📚 References
[1] [Crime Data](https://catalog.data.gov/dataset/crime-data-from-2020-to-present)  
[2] [Arrest Data](https://catalog.data.gov/dataset/arrest-data-from-2020-to-present)  
[3] [Traffic Collision Data](https://catalog.data.gov/dataset/traffic-collision-data-from-2010-to-present)

---

## 👩‍💻 Author (Traffic Collision Section)

**Reyna Vargas Antonio**  
School of Computing, National College of Ireland  
---
