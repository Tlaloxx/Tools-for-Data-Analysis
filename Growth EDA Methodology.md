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
> - Explore dataset structure and columns  
> - Define analysis goals  
> - Identify relevant variables  
> - Note assumptions about data quality  

### L — Locate Solvable Issues  
> **Fixing Data:**  
> - Remove irrelevant or duplicate data  
> - Handle outliers (unusual/extreme values)  
> - Fix missing values (median, mean, or delete)  
>
> **Data Wrangling:**  
> - Correct data formats and types  
> - Filter, group, or aggregate data  

### E — Evaluate Unsolvable Issues  
> - Note missing data that can’t be fixed  
> - Document inconsistencies and biases  
> - Recognize limitations from data collection  
> - Decide which outliers to keep  

### A — Augment the Data  
> **Feature Engineering:**  
> - Create new columns (e.g., extract year)  
> - Normalize or scale data  
> - Encode categorical variables  
> - Create binary indicators  
> - Split/combine columns (e.g., names)  

### N — Note and Document  
> - Log cleaning steps and reasons  
> - Track missing value handling  
> - Record feature engineering changes  
> - Save versions of cleaned data  
> - Document limitations and unresolved issues  

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
