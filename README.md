# 🎬 Movie-Data-Analysis-Project
This project investigates what factors contribute to a movie’s box office success using a dataset of film attributes. I performed data cleaning, exploratory data analysis (EDA), and correlation analysis to uncover trends between budgets, gross earnings, and production companies.

## 🧠 Objective  
This project explores relationships between various features of movies — such as budget, gross earnings, and production companies to uncover insights about what drives box office success.

## 🗂️ Dataset  
The analysis uses a dataset named `movies.csv`, which contains detailed information about films, including:
- Movie titles  
- Budget and gross earnings  
- Release dates  
- Production companies  
- Additional metadata (e.g., ratings, countries, genres)

## ⚙️ Tools & Libraries  
- **Python** for data manipulation and analysis  
- **Pandas** and **NumPy** for data cleaning and preprocessing  
- **Matplotlib** and **Seaborn** for data visualization and correlation analysis  

## 🔍 Process Overview  
1. **Data Cleaning & Preparation**  
   - Loaded and examined the dataset for missing values and dropped incomplete rows.  
   - Standardized data types (e.g., converted `budget` and `gross` columns to integers).  
   - Extracted release year information and corrected inconsistencies.  
   - Removed duplicate company entries for clarity.

2. **Exploratory Data Analysis (EDA)**  
   - Visualized **Budget vs. Gross Earnings** using scatter plots and regression plots.  
   - Identified a **strong positive correlation** between a movie’s budget and its gross revenue.  
   - Created a **correlation heatmap** to explore relationships among all numeric features.  
   - Encoded categorical variables to assess how production companies and other factors correlated with earnings.

3. **Correlation Analysis**  
   - Calculated **Pearson correlation coefficients** between variables.  
   - Found that higher budgets generally lead to higher gross earnings.  
   - Used sorted correlation pairs to highlight the most influential features.

## 📈 Key Insights  
- There is a **strong positive correlation** between movie **budget** and **gross earnings**.  
- Some production companies show consistent high returns, hinting at brand influence.  
- Encoding categorical data enables deeper numerical correlation analysis across non-numeric features.

## 💡 Conclusion  
This project demonstrates practical **data wrangling**, **EDA**, and **visualization** techniques for discovering meaningful insights in real-world datasets. It provides a foundation for predictive modeling of movie performance or financial forecasting in the entertainment industry.

## 🧰 Future Improvements  
- Add predictive modeling using regression or machine learning algorithms.  
- Include genre-based profitability analysis.  
- Build an interactive dashboard for visualization.
