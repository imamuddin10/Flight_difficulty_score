# Flight Difficulty Score SQL Project

### 📘 Overview
This project analyzes flight management complexity using SQL.  
Five datasets (flight_level_data, bag_level_data, , pnr_remark_data, etc.) were merged and processed to calculate a **Difficulty Score** indicating how hard each flight is to manage.

### 📊 Files
- `data/` → contains all CSV datasets and final output.
- `queries/difficulty_score.sql` → contains SQL logic.
- `output_difficulty_score.csv` → final ranked flights.

### 🧠 Key Insights
- Flights with more special service requests or transfers had higher difficulty scores.
- SQL window functions and joins were used for aggregation.

### ⚙️ Tools Used
- MySQL 

### 🧩 How to Run
1. Import all CSVs into your SQL environment.
2. Run queries from `queries/difficulty_score.sql`.
3. Export the result to `output_difficulty_score.csv`.

### 🧾 Author
**Imamuddin**

B.Tech (Production and Industrial Engineering), Delhi Technological University
