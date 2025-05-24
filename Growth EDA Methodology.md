# 🌱 GROWTH — Exploratory Data Analysis (EDA) Methodology  
*By Tlaloc Alvarez*

> **What is GROWTH?**
> 
> **GROWTH** is a practical methodology created by Tlaloc Alvarez for conducting Exploratory Data Analysis (EDA) from start to finish. Each letter stands for a key step: **Goal**, **Review**, **Optimize**, **Work**, **Tell**, and **Highlight**. During the **Optimize** phase, you can apply the **CLEAN** framework by Christine Jiang to make sure your dataset is accurate and ready for analysis, but feel free to use any tools that suit your needs. Think of this process like tending a garden—your raw data are seeds that, with proper care and structure, grow into valuable insights. This methodology works with any dataset and fosters clarity, consistency, and reproducibility.

## G — Goal of the Analysis  
> Define what you're solving and why it matters.

- Clarify the main question or problem  
- Understand context and scope  
- Identify datasets and sources  
- List stakeholders and collaborators  
- Document clear objectives  

## R — Review the Data  
> Explore your dataset before making changes.

- Check shape (rows, columns) and data types  
- Understand what each variable means  
- Preview sample values and patterns  
- Note early observations  

## O — Optimize the Data (CLEAN Framework)  
> Clean and prepare using the **CLEAN** method:

- **C — Conceptualize**: Understand the structure and meaning of the data  
- **L — Locate**: Find missing, duplicate, or irrelevant entries  
- **E — Evaluate**: Investigate outliers and quality issues  
- **A — Augment**: Add new features or transform variables  
- **N — Note**: Document all changes made

<details>
<summary><b>CLEAN Framework with Activities and Techniques</b></summary>

### C — Conceptualize the Data  
Understand the data and what questions you want to answer.  
- Explore dataset structure and columns  
- Define analysis goals  
- Identify relevant variables for the problem  
- Note initial assumptions about data quality and expected issues  

### L — Locate Solvable Issues  
Find problems in the data you can fix.  

**Fixing Data:**  
- Remove irrelevant columns or rows  
- Identify and remove duplicates  
- Detect and handle outliers (unusual or extreme values)  
- Handle missing values (fill with median, mean, or delete rows)  

**Data Wrangling:**  
- Check and correct inconsistent data formats (e.g., date formats, text case)  
- Ensure all data types are correct (text, numbers, dates)  
- Filter, group, or aggregate data to simplify the dataset  

### E — Evaluate Unsolvable Issues  
Identify problems you can’t fully fix but need to acknowledge.  
- Note missing values that cannot be fixed or imputed reliably  
- Document data inconsistencies or possible biases  
- Recognize limitations due to data collection methods or incomplete information  
- Decide which outliers should be retained because they represent real phenomena  

### A — Augment the Data  
Add new features or enrich the dataset for better analysis.  

**Feature Engineering:**  
- Create new columns from existing data (e.g., extract year/month from dates)  
- Normalize or scale numerical data when necessary  
- Encode categorical variables (one-hot encoding, label encoding)  
- Create binary indicators (e.g., Active = 1, Inactive = 0)  
- Combine or split columns to extract useful information (e.g., full name → first and last name)  

### N — Note and Document  
Keep records of all cleaning decisions and changes made.  
- Write down all data cleaning steps, reasons, and assumptions  
- Track how missing values were handled  
- Log feature engineering transformations  
- Save versions of cleaned datasets  
- Document limitations and unresolved issues clearly for future reference  

</details>

## W — Work the Data  
> Analyze the data to discover patterns and relationships.

- **Univariate**: Distributions, summaries  
- **Bivariate**: Correlations, comparisons  
- **Multivariate**: Clusters, PCA, heatmaps  
- Use basic stats tests where relevant  

## T — Tell with Visuals  
> Communicate insights clearly with visuals.

- Use the right charts (bar, line, scatter, pie, map)  
- Build simple, interactive dashboards  
- Highlight key points with labels and color  
- Keep visuals clean and focused  

## H — Highlight Results  
> Share conclusions and actionable outcomes.

- Summarize key insights and their impact  
- Document hypotheses and findings  
- Acknowledge limitations and risks  
- Recommend next steps or actions  
- Organize files for future reuse  
