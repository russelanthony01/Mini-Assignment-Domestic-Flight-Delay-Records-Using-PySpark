# ✈️ Domestic Flight Delay Records Using PySpark

### 📌 Overview
This project performs an in-depth analysis of a **Domestic Flight Delay Dataset**, focusing on flight punctuality, departure and arrival delay trends, airtime behavior, and long-distance flight patterns.

The notebook demonstrates **data engineering + analytics** using:

- **Python** for programming  
- **PySpark** for scalable data processing  

> ⚠️ *Dataset is used only for academic and educational purposes.*

---

### 🎯 Analytical Tasks Completed

#### Data Exploration & Filtering
- Count flights arriving earlier than expected  
- Determine typical departure time for long-distance flights (> 2000 miles)  
- Calculate proportion of flights arriving > 60 minutes late  
- Compute average airtime for flights departing before 9:00 AM  
- Identify maximum arrival delay for flights with no departure delay  

---

### 📊 Dataset Details
The dataset contains **1,000,000 observations** and **7 features**, each representing a unique domestic flight.

| Feature | Description |
|---|---|
FL_DATE | Flight Date  
DEP_DELAY | Departure delay in minutes *(negative = early, zero = on-time, positive = delayed)*  
ARR_DELAY | Arrival delay in minutes *(negative = early, zero = on-time, positive = delayed)*  
AIR_TIME | Total time spent in air (minutes)  
DISTANCE | Flight distance (miles)  
DEP_TIME | Departure time (HHMM format)  
ARR_TIME | Arrival time (HHMM format)  

> Negative values = Early departure/arrival  
> Zero = On-time performance  

---

📎 License  
Distributed under the **MIT License.**

---

👤 Author  
**Russel Anthony Reynold Chandanshiv**
