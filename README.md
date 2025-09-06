# 🏡 House Price Analysis – Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project performs an **Exploratory Data Analysis (EDA)** on a housing prices dataset to uncover key factors that influence property values.  
The goal is to understand pricing trends, detect outliers, and identify significant predictors of housing prices, laying the foundation for **predictive modeling**.  

---

## 🛠️ Tools & Technologies
- **Python** – Programming & data analysis  
- **Pandas, NumPy** – Data cleaning & manipulation  
- **Matplotlib, Seaborn** – Data visualization  
- **Scikit-learn** – Feature preprocessing & regression analysis  
- **Jupyter Notebook** – Interactive analysis  

---

## 🧹 Data Preprocessing
Steps performed before analysis:
- Handled missing values (imputed/removed where necessary)  
- Encoded categorical variables (e.g., house style, condition)  
- Removed duplicate rows  
- Created derived variables such as **price per sqft** and **age of house**  

---

## 📊 Exploratory Data Analysis (EDA)

### Key Analyses
1. **Distribution of House Prices**
   - Majority of houses priced between **$200K – $600K**  
   - Luxury outliers above **$2M**  

2. **Correlation Analysis**
   - **Living area (sqft)** and **overall quality** are the strongest predictors of price  
   - Lot area, garage capacity, and year built also contribute  

3. **Categorical Insights**
   - Newer houses tend to be priced higher  
   - Certain neighborhoods consistently show premium pricing  

---

## 📈 Visualizations
- **Price Distribution** – Histogram & KDE plots  
- **Scatterplot** – Living area vs. Sale Price (clear upward trend)  
- **Boxplots** – Neighborhood vs. Price (outliers & spread)  
- **Heatmap** – Correlation matrix of numerical features  

📷 *Example Visualization*  
![House Price vs Living Area](House%20Price%20vs%20Living%20Area_Visualization.png)



---

## 🔑 Key Insights
- Most homes fall in the **$200K–$600K** range.  
- **Living area (sqft)** and **overall quality** have the strongest impact on price.  
- Outliers above **$2M** represent luxury homes.  
- Certain **neighborhoods** show significantly higher median prices.  

---

## 📂 Repository Structure
├── `House_Price_EDA.ipynb` → Full analysis notebook  
├── `requirements.txt` → Python dependencies  
├── `house_price_plot.png` → Sample visualization (optional)  
└── `README.md` → Project documentation  

---

## 🚀 How to Run
1. Clone this repository  
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
3. Open the notebook:
   ```bash
   jupyter notebook House_Price_EDA.ipynb
4. Run all cells to reproduce the analysis

## 🛠️ Dependencies
### 📦 Requirements
- pandas==2.2.2  
- numpy==1.26.4  
- matplotlib==3.9.2  
- seaborn==0.13.2  
- scikit-learn==1.5.1  
- jupyter==1.0.0  



