# 🎓 Faith & STEM: A College Ranking for First-Gen Latina Women

## 📌 Project Overview
This project ranks the best colleges for first-generation, Christian, Latina women pursuing STEM degrees. The ranking is based on factors such as Christian affiliation, first-generation student success rates, STEM program strength, post-graduation earnings, affordability, and Hispanic women’s graduation rates.

As a first-generation Latina in STEM myself, I created this ranking to provide personalized insights for students like me and their families who value both faith and high-quality STEM education.

📄 **View the Full Analysis Report:**  
[Newest-College-Ranking.Rmd](Newest-College-Ranking.Rmd)  


## 🗂️ Dataset

- Source: IPEDS College Data
- [Google Drive Link to data](https://drive.google.com/drive/folders/1NRs2mt-IipExgAHCDlewW5vc6_2J8A2p?usp=drive_link)
- Data Size: 2012 rows × 1000 columns (45.5 MB)
- Preprocessing: Standardized all variables to compare data fairly across different metrics.
  
## 🏗️ Ranking Factors & Methodology
The ranking algorithm assigns weights to each factor based on its importance to the target audience:

- Christian Affiliation (20%) – Ensuring the school aligns with faith-based values.
- First-Generation Completion Rate (15%) – Likelihood of first-gen students graduating in 4 years.
- Retention Rate (15%) – Stability of students staying enrolled.
- STEM Program Strength (20%) – Percentage of degrees awarded in key STEM fields.
- Earnings After College (10%) – Median salary five years post-graduation.
- Affordability (10%) – Average net price for middle-income families.
- Financial Aid Availability (10%) – Pell Grant and federal loan eligibility.
- Hispanic Women Graduation Rate (10%) – Representation and success of Latina students.

## 🔍 Key Findings
- Top-ranked colleges have strong Christian affiliations, with institutions like Duke University and Notre Dame ranking highly.
- Schools with higher first-gen graduation rates tend to have better financial aid and retention rates.
- The best STEM-focused Christian colleges offer competitive post-graduation salaries, making them great options for Latina women in STEM.

- ## 🚀 How to Run the Project  

1. **Clone the repository**:  
   ```sh
   git clone https://github.com/axelle-le-rate/Faith-STEM-College-Rankings.git
   
2. **Install dependencies**:

 ```sh
install.packages(c("dplyr", "tidyr", "ggplot2", "readr"))
 ```

4. **Run the R script in RStudio or Jupyter Notebook with an R kernel.**

## ⚙️ Technologies Used
R · dplyr · tidyr · ggplot2 · readr

## 📌 Future Improvements
- Incorporate student satisfaction data to refine rankings.
- Compare rankings across different income levels for financial accessibility insights.
- Expand the analysis to non-Christian universities for broader options.
