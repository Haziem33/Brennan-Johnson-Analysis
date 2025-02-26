# Brennan Johnson Analysis ⚽📊

![Dashboard Preview](dashboard_screenshot.png)  
*Example of the Power BI dashboard summarizing Brennan Johnson’s key stats*  

## 📌 Project Overview  
This project analyzes **Brennan Johnson’s** performance using **Python, Jupyter Notebooks, and Power BI**. The dataset includes key metrics such as goals, assists, expected goals (xG), shot accuracy, and performance trends.  

The aim is to gain deeper insights into his contributions and efficiency as an attacker.  

## 📊 Key Objectives  
- **Evaluate Goal Contributions:** Analyzing goals and assists per 90 minutes.  
- **xG vs. Actual Performance:** Comparing expected goals with actual goals.  
- **Shot & Passing Analysis:** Assessing shot accuracy, key passes, and final third effectiveness.  
- **Trends & Improvements:** Tracking performance patterns across different matches.  

## 🛠️ Tech Stack  
- **Python:** Data cleaning & analysis (`pandas`, `numpy`, `matplotlib`, `seaborn`).  
- **Jupyter Notebooks:** Exploratory Data Analysis (EDA).  
- **Power BI:** Visualizing player performance in an interactive dashboard.  
- **GitHub:** Version control & collaboration.  

## 📂 Project Structure  
```
├── data/  
│   ├── brennan_johnson_cleaned.csv         # Cleaned dataset  
│   ├── brennan_johnson_grouped.csv         # Aggregated statistics  
│   └── raw_data/                           # Original raw data files  
│  
├── notebooks/  
│   ├── BJ_data_EDA.ipynb                   # Exploratory Data Analysis  
│   ├── BJ_editing_data.ipynb               # Data processing & cleaning  
│   └── Brennan_johnson_data_cleaning.ipynb # Final preprocessing steps  
│  
├── dashboard/  
│   ├── Finally_john.pbix                    # Power BI dashboard file  
│   └── dashboard_screenshot.png             # Dashboard preview image  
│  
├── README.md  
└── requirements.txt                         # Python dependencies  
```  

## 🚀 How to Run  
1. **Clone the repository**  
   ```
   git clone https://github.com/Haziem33/Brennan-Johnson-Analysis.git  
   cd Brennan-Johnson-Analysis
   ```  
2. **Set up the environment**  
   ```
   pip install -r requirements.txt
   ```  
3. **Run Jupyter Notebook for EDA**  
   ```
   jupyter notebook
   ```  
4. **Open Power BI file**  
   - Load `Finally_john.pbix` to explore the dashboard.  

## 📈 Dashboard  
The **Power BI dashboard** provides an **interactive view** of Brennan Johnson’s performance. It includes:  
- Goals & Assists Overview  
- xG Analysis  
- Shot Map & Accuracy  
- Passing & Creativity Metrics  
- Match-wise Performance Trends  

👉 *Check out the dashboard in Power BI (`Finally_john.pbix`).*  


