# Netflix Data Analysis — Problem 1

## Business Question
**How many Movies vs. TV Shows are on Netflix?**  

This question helps us understand the **content distribution** on Netflix and whether the platform focuses more on movies or TV shows.  

---

## Steps Taken
1. **Loaded dataset** (`netflix_titles.csv`) using pandas.  
2. **Data Cleaning**  
   - Removed duplicates.  
   - Filled missing country, cast, and director values with `"Unknown"`.  
   - Converted `date_added` column to datetime format.  
   - Removed rows with no valid `date_added`.  
3. **Analysis**  
   - Counted the number of *Movies* and *TV Shows* using `value_counts()`.  
4. **Visualization**  
   - Created a bar chart and pie chart with matplotlib to show distribution.   

---

## Results
- **Movies**: 6,000+ titles  
- **TV Shows**: 2,500+ titles  

---

## Insight
Netflix has significantly more **Movies than TV Shows**, but the rise in TV Show releases in recent years suggests 
a **shift towards serialized content** to engage users longer.  

---

## 📂 Files in this Folder
- `netflix_analysis.ipynb` → Jupyter Notebook with full code  
- `README.md` → Explanation of the problem, steps, and results  

---
