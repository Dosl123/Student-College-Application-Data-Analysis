# Student College Application Data Analysis
Analysis of student college application data exploring the impact of academic performance, mathematics proficiency, and socio-economic factors on application decisions. Built using Excel for cleaning and visualization and SQL for structured data analysis.

### Overview
Applying to college is a major milestone for students worldwide, influenced by academic performance and other socio-economic factors. This project analyzes student data to understand how grades, subject performance, and background factors impact college application decisions.

The dataset was sourced from Kaggle and contains information on 106 students, including academic performance, demographics, and application behavior.

---

### Dataset Description
The dataset includes the following fields:
- Student ID  
- Class  
- Gender  
- Race  
- CGPA  
- Subjects Taken  
- Home Location  
- Performance in Mathematics  
- Means of Application  
- Home Wealth  
- Application Rate  

---

### Tools Used
- **Excel**: Data cleaning, preprocessing, and visualization  
- **SQL (PostgreSQL)**: Data structuring, querying, and analysis  

---

### Data Preparation
- Removed duplicates and ensured data consistency using Excel  
- Renamed columns and tables for clarity  
- Verified grading scale (scores and CGPA out of 100, with 50 as pass mark)  
- Transferred cleaned data into SQL for structured analysis  
- Exported results back to Excel for visualization using pivot tables and charts  

---

### Key Analysis Areas
- Student performance across subjects  
- Failure rates in key courses  
- Relationship between math performance and application behavior  
- Impact of home wealth on application decisions  

---

### Key Insights

#### Academic Performance
- All students had CGPA above 50%, with strong performance in statistics and measurement  
- Some students still failed individual subjects despite overall good CGPA  

#### Subject Difficulty
- Calculus 1 had a higher failure rate compared to Calculus 2  
- Functional analysis, probability, and algebra recorded minimal failures  
- Mathematics had a relatively higher failure rate, making it a critical subject  

#### Math Performance and Applications
- Students with strong math skills had higher chances of applying and gaining admission  
- Students with weak math performance were less likely to apply, even with good CGPA  

#### Impact of Home Wealth
- Wealthier students showed stronger application rates and better academic performance  
- Students from less privileged backgrounds were less likely to apply, even when academically qualified  
- Financial constraints likely influenced application decisions  

---

### Observations
- A significant percentage of students with weak math skills did not apply to college  
- Some academically strong students from low-income backgrounds did not apply, likely due to financial limitations  
- Students with both strong academic performance and financial support had the highest chances of admission  

---

### Conclusion
College application outcomes are influenced by a combination of academic performance and socio-economic factors. Mathematics plays a critical role in application success, while financial background significantly affects whether students apply at all.

---

### Recommendations
- Students should focus on improving performance in key subjects, especially mathematics  
- Early financial planning (e.g., scholarships, loans) can improve application rates  
- Teachers and counselors should provide targeted guidance, especially for students from less privileged backgrounds  

---

### Notes
- Dataset sourced from Kaggle  
- Analysis performed using SQL and Excel  
- Visualizations created using Excel pivot charts  
