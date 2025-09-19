# 🚖 NCR Uber Ride Bookings Analysis

This project analyzes Uber ride booking data for NCR (Delhi region).  
The goal is to explore ride trends, cancellations, customer behavior, and payment methods using **Python (Pandas, Matplotlib, Seaborn)** and build an interactive **Tableau dashboard**.

---

## 📂 Project Structure


---

## ⚙️ Steps Performed

1. **Data Cleaning (Python / Pandas)**  
   - Handled missing values logically (e.g., filling 0 for incomplete rides, `"Not Applicable"` for payment methods).  
   - Standardized date-time columns.  
   - Removed unnecessary duplicates.  
   - Saved the cleaned dataset for EDA.  

2. **Exploratory Data Analysis (EDA)**  
   - Ride booking trends (daily, monthly).  
   - Cancellations (by customer vs. driver).  
   - Payment method distribution.  
   - Ride distance vs. booking value relationships.  

3. **Dashboard (Tableau)**  
   - Created an **interactive dashboard** with:  
     - Total rides & completion rate  
     - Cancellation reasons  
     - Ride distance and value trends  
     - Payment method breakdown  

---

## 📊 Tableau Dashboard

- Open the packaged workbook here:  
  👉 [dashboard/uber_dashboard.twbx]([dashboard/uber_dashboard.twbx](https://public.tableau.com/views/UberRidesinNCRTrendsCancellationsCustomerInsights/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link))  


---

## 🛠️ Tech Stack

- **Python**: pandas, numpy, matplotlib, seaborn  
- **Jupyter Notebook**  
- **Tableau** (dashboard & visualization)  
- **GitHub** (project hosting)  

---

## 🚀 How to Use

1. Clone the repository:  
   ```bash
   git clone https://github.com/lily23445/ncr-uber-ride-bookings-analysis.git
   cd ncr-uber-ride-bookings-analysis
