# Drug_Recall_Analysis 💊  
Exploratory data analysis of FDA drug recall data to uncover patterns, trends, and key insights using Python.

---

### What Are Drug Recalls?

Recalls are actions taken by a company to remove a product from the market due to various reasons, such as:
- Wrong labels or dosage information  
- Contamination  
- Packaging issues  
- Unexpected side effects  
The U.S. FDA (Food and Drug Administration) monitors and publishes these recalls to protect public health.



## Dataset

- **Source**: [FDA Drug Recalls Dataset] 📁
- The dataset was downloaded from the official FDA website and cleaned before use.  
- The final dataset contains **16,815 rows** and **12 columns**.  
- **Key fields**: `classification`, `recall_initiation_date`, `reason_for_recall`, `recalling_firm`, `voluntary_mandated`



## Objectives of This Analysis

- Understand the **frequency and classification** of recalls  
- Analyze **reasons** and **firms** associated with frequent recalls  
- Study **delays** between recall initiation and public reporting  
- Identify **yearly trends** in recalls  



## Tools Used

- Python 🐍  
- Pandas, NumPy  
- Seaborn, Matplotlib  
- Jupyter Notebook  

---

## Key Findings

- **Class II recalls** dominate, indicating non-life-threatening but serious risks.  
- **Labeling issues** and **contamination** are the top reasons for recalls.  
- **Voluntary recalls** far outnumber mandated ones.  
- Delays exist between recall initiation and FDA public reporting.  
- A **few large pharmaceutical firms** account for a significant number of recalls, possibly due to their high production volume.


