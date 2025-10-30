# 📊 Lead Quality Analysis

## 🧠 Project Overview
This project analyzes a dataset of approximately **8.8K leads** from a single publisher with multiple traffic sources delivered to one advertiser.  
Each row represents one lead and its final disposition.  
The goal is to understand **lead quality trends, key influencing factors, and cost–performance trade-offs** to improve advertiser ROI.

---

## 🎯 Objectives

1. **Trend Analysis:** Determine if lead quality is improving, declining, or stable over time, and test for statistical significance.  
2. **Drivers of Lead Quality:** Identify major factors affecting lead outcomes — including ad placement, data quality, geography, and creative format.  
3. **CPL Trade-off Analysis:** Evaluate whether a **+20% CPL increase (from $30 → $33)** can be justified by a **+20% uplift in lead quality (from 8.0% → 9.6%)**.  
4. **Optimization Goal:** Recommend actionable strategies to maximize lead quality and minimize wasted spend.

---

## 🧮 Key Methods

- **Data Cleaning & Preprocessing:**  
  - Handled missing values for `CallStatus`, `AddressScore`, and `PhoneScore`.  
  - Removed non-essential columns like `IP Address`.  

- **Feature Categorization:**  
  Leads grouped into **Closed**, **Good**, **Bad**, and **Unknown** for consistent evaluation.

- **Exploratory Data Analysis (EDA):**  
  - Trend analysis of lead quality over time.  
  - Comparison of call disposition across campaigns and widgets.  
  - Distribution of address and phone quality scores.

- **Statistical Testing:**  
  - Conducted hypothesis tests to identify statistically significant differences in lead quality.

---

## 📊 Visualizations

Below are the main visual insights derived from the analysis:

---

### **1. Lead Outcome Distribution**

![Lead Outcome Distribution](Lead%20Outcome%20Distribution.png)  
*Distribution of leads categorized as Good, Bad, or Closed.*

---

### **2. Lead Quality Trends Over Time**

![Lead Quality Trends Over Time](Lead%20Quality%20Trends%20Over%20Time.png)  
*Trend showing how lead quality evolved over time.*

---

### **3. Top Widgets by Good Rate**

![Top Widgets by Good Rate](Top%20Widgets%20by%20Good%20Rate.png)  
*Top-performing widgets ranked by percentage of Good leads.*

---

### **4. CPL vs Quality Trade-Off (Simulation)**

![CPL vs Quality Trade Off (Simulation)](CPL%20vs%20Quality%20Trade%20Off%20(Simulation).png)  
*Simulation showing trade-off between CPL and overall lead quality improvement.*

## 📊 Visualizations

### **1. Lead Outcome Distribution**
![Lead Outcome Distribution](./Lead%20Outcome%20Distribution.png)  
*Distribution of leads categorized as Good, Bad, or Closed.*

---

### **2. Lead Quality Trends Over Time**
![Lead Quality Trends Over Time](./Lead%20Quality%20Trends%20Over%20Time.png)  
*Trend showing how lead quality evolved over time.*

---

### **3. Top Widgets by Good Rate**
![Top Widgets by Good Rate](./Top%20Widgets%20by%20Good%20Rate.png)  
*Top-performing widgets ranked by percentage of Good leads.*

---

### **4. CPL vs Quality Trade-Off (Simulation)**
![CPL vs Quality Trade Off (Simulation)](./CPL%20vs%20Quality%20Trade%20Off%20(Simulation).png)  
*Simulation showing trade-off between CPL and overall lead quality improvement.*

---


---

## 💡 Key Insights & Final Recommendations

### **Key Insights**

1. **Quality Trend:** Overall lead quality has remained **flat**, with no statistically significant improvement or decline over time.  
2. **Top Drivers of Quality:** Key influencing factors include **widgets**, **publisher campaigns**, **data hygiene** (address and phone scores), and **geography**.  
3. **Performance Segmentation:** Certain **widgets and campaigns consistently outperform others**, delivering higher proportions of Good and Closed leads.  
4. **Data Quality Correlation:** Leads with **strong address and phone scores** show a clear positive correlation with conversion rates.  
5. **CPL–Quality Trade-off:** A **+20% increase in CPL (from $30 → $33)** is justifiable when targeting segments achieving **≥10% Good Rate** or higher.  

---

### **Actionable Recommendations**

- **🎯 Attribution:** Minimize “Unknown” lead sources by improving tracking and tightening attribution channels.  
- **📈 Campaign Optimization:** Pause or restructure underperforming campaigns and **scale the top 5 high-quality widgets/publishers**.  
- **✅ Data Validation:** Implement address and phone validation at lead capture to eliminate low-quality entries early.  
- **🗺️ Geographic Targeting:** Redirect budget toward **top-performing regions/states** and reduce spend in weak zones.  
- **💰 Pricing Strategy:** Negotiate **higher CPL rates** for pre-qualified, validated leads that historically convert better.  
- **📊 Continuous Monitoring:** Develop **monthly dashboards** to track Good/Closed rates and detect performance drifts in real time.  

---

### **Overall Conclusion**

The analysis indicates that **lead quality optimization is achievable without major cost escalation**, provided focus remains on  
**data hygiene, campaign refinement, and performance-based pricing.**  
Strategic realignment of budget and validation filters can yield a sustainable **uplift in ROI and lead quality.**
 
---

## 🛠️ Technologies Used

- **Python**
- **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn**
- **Jupyter Notebook**

---

## ⚙️ Setup & Installation

**1. Clone this repository:**
   ```bash
   git clone https://github.com/indu-explores-data/lead-quality-analysis.git
   ```
**2. Navigate to the project folder**
   ```
   cd lead-quality-analysis
   ```
**3. Install required dependencies:**
   ```
   pip install -r requirements.txt
   ```
**4. Open the notebook:** 
   ```
   jupyter notebook "Lead Quality Analysis.ipynb"
   ```
---

## ▶️ Usage

- Run the notebook cells sequentially to:
- Clean and preprocess data
- Perform exploratory analysis
- Visualize patterns and trends
- Interpret insights and business recommendations

You can also adapt the notebook for your own lead datasets by updating the input file path and rerunning the workflow.

---

## 🔗 Connect with Me

Let’s connect on LinkedIn for project discussions or data-driven collaborations:

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?logo=linkedin)](https://www.linkedin.com/in/indu-r-3a3767170/)

---

## 🙌 Feedback & Support

If you found this project helpful, please ⭐ star the repository and share your thoughts. Suggestions and contributions are always welcome!

