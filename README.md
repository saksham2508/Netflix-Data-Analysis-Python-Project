# Netflix-Data-Analysis-Python-Project 
![banner](https://github.com/saksham2508/Netflix-Data-Analysis-Python-Project/blob/main/Netflix%20Baneer%20image.jpg)

## Overview  
This project analyzes the Netflix Movies & TV Shows Dataset to extract insights about content trends, genres, ratings, and countries of production. The goal is not only to clean and explore the dataset but also to translate numbers into meaningful business insights that highlight Netflix’s content strategy.  

---

## Tools & Technologies  
- **Python**  
  - Pandas (Data Cleaning, EDA)  
  - Matplotlib / Seaborn (Visualization)  
- **Jupyter Notebook** (Interactive Analysis)  

---

## Dataset  
The dataset contains information about Netflix Movies & TV Shows, including:  
- Title  
- Director  
- Cast  
- Country  
- Date Added  
- Release Year  
- Rating  
- Duration  
- Type (Movie/TV Show)  
- Genre (listed in)  

---

## Preprocessing & Data Cleaning  
**Steps performed:**  
1. **Handling Missing Values**  
   - Removed unnecessary duplicates  
   - Filled/replaced missing values in important columns  

2. **Dropping Incorrect Rows**  
   - Some rows in title had invalid values (e.g., `678, 2012, 23:59, Feb-09`) → removed  
   - Some duplicate/invalid cast rows (e.g., `50 Cent, Ryan Phillippe, Bruce Willis...`) → dropped  

3. **Splitting & Formatting Columns**  
   - Converted `date_added` to datetime format  
   - Extracted year, month, and day separately for analysis  
   - Cleaned duration (numeric minutes for Movies, seasons for TV Shows)  

---

## Exploratory Data Analysis (EDA)  
🔹 **Content Distribution**  
- Count of Movies vs TV Shows  
- Content added over the years  

🔹 **Country Insights**  
- Top countries producing content on Netflix  
- US dominates, but India is 2nd with more movies  

🔹 **Ratings Analysis**  
- Most frequent ratings: TV-MA, TV-14, R  
- Shows Netflix’s focus on mature audiences  

🔹 **Genre & Category Insights**  
- Most common genres: Dramas, Comedies, Documentaries  
- TV shows have grown faster since 2015  

🔹 **Cast & Directors**  
- Directors with highest number of movies  

---

## Visualizations  
- Distribution of release year  
- Movies vs TV Shows count  
- Content trend over years  
- Top 10 countries with most content  
- Most common Ratings (bar chart)  
- Country vs Content Type (Top 15 Countries)  

---

## Business Insights  
Some key observations from the analysis:  
- Netflix is adding more TV Shows than Movies since 2015, showing a shift in strategy.  
- The US produces the most content, but India is second, with a strong focus on movies.  
- TV-MA is the most common rating, proving Netflix targets mature/adult audiences.  
- Drama and International content are dominant, showing Netflix’s global expansion.  
- Content growth surged after 2015, aligning with Netflix’s global expansion plans.  

---

## Project Highlights
- Data Importing  
- Complete data cleaning and preprocessing.  
- Advanced EDA & Visualization
- Clear Business Insights.

---

## Conclusion
This project demonstrates the end-to-end data analysis pipeline — from cleaning messy real-world data to generating business-ready insights. It shows not just technical coding ability but also analytical storytelling, which is crucial for Data Analyst roles.

---

✨ If you like this project, give it a ⭐ on GitHub! ✨
