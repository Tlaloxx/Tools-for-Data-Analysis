# ✨ CLEAN Framework – Clean and Prepare Datasets

## 📌 About This Framework

**CLEAN** is a practical and adaptable framework to clean and prepare datasets before analysis. This enhanced version was created by **Tlaloc Alvarez**, inspired by the original CLEAN framework by **Christine Jiang**.

🎥 **Watch the Original Presentation**  
_Christine Jiang – The ONLY Data Cleaning Framework You Need_  
[![Watch on YouTube](https://img.youtube.com/vi/y9wFFD2bXQM/0.jpg)](https://www.youtube.com/watch?v=y9wFFD2bXQM)

Use CLEAN as a step-by-step guide to ensure your data is clean, structured, and ready for analysis — no matter what tool you use (Excel, Python, SQL, Power BI, etc.).

---

## 🔠 The CLEAN Framework

<details>
  <summary>🧠 <strong>C – Conceptualize the Data</strong></summary>

> _Start with a clear mental model of your dataset._

### 🎯 Goal: Understand the purpose, structure, and meaning of your data.

### ✅ Key Actions:
- Identify key columns: ID fields, dates, measures, categories.
- Detect data types: numerical, categorical, boolean, datetime.
- Map relationships and hierarchies (e.g., customer → orders).
- Understand the business context: what does each value mean?

### 🔧 Useful Techniques:
- Build a **data dictionary** with column definitions.
- Use **summary statistics** and **value counts**.
- Visually scan tables or use profiling tools.

**🛠 Tools:** Excel, pandas, Power BI, OpenRefine
</details>

---

<details>
  <summary>🔍 <strong>L – Locate Solvable Issues</strong></summary>

> _Detect and fix common, correctable data problems._

### 🎯 Goal: Clean up noise that can be easily resolved.

### ✅ Key Actions:
- Handle missing values logically (fill, delete, flag).
- Remove exact duplicates.
- Standardize inconsistent formatting (e.g., date or text cases).
- Fix incorrect entries (e.g., invalid ages or negative values).

### 🔧 Useful Techniques:
- Use filters and conditional formatting to detect issues.
- Apply text functions (`TRIM`, `UPPER`, etc.).
- Use `fillna()`, `.dropna()`, `.duplicated()` in pandas.
- Normalize date/time formats.

**🛠 Tools:** Excel, Power Query, pandas, Data Wrangler
</details>

---

<details>
  <summary>⚠️ <strong>E – Evaluate Unsolvable Issues</strong></summary>

> _Identify deeper problems that can't be easily fixed._

### 🎯 Goal: Assess what’s missing, ambiguous, or unfixable.

### ✅ Key Actions:
- Flag extreme outliers that lack explanation.
- Identify missing values in critical fields.
- Detect ambiguous or unreliable entries.
- Decide what to drop, impute, or exclude — and justify it.

### 🔧 Useful Techniques:
- Use **boxplots**, **histograms**, or **z-scores**.
- Flag and isolate suspicious records.
- Keep logs of questionable entries before removal.

**🛠 Tools:** seaborn, matplotlib, Power BI, pandas
</details>

---

<details>
  <summary>🧩 <strong>A – Augment the Data</strong></summary>

> _Enhance your dataset to support better analysis._

### 🎯 Goal: Add value through transformation and enrichment.

### ✅ Key Actions:
- Reshape data: pivot, unpivot, transpose if needed.
- Combine datasets (merge or append).
- Create new features (e.g., year from a date).
- Encode categories and scale numeric values if modeling.

### 🔧 Useful Techniques:
- Feature engineering: extract parts of strings or dates.
- Aggregation for KPIs or group analysis.
- Use `merge()`, `melt()`, and `groupby()` in pandas.
- Apply one-hot encoding or normalization.

**🛠 Tools:** pandas, Excel, Power Query, scikit-learn
</details>

---

<details>
  <summary>📝 <strong>N – Note and Document</strong></summary>

> _Document every step to ensure transparency and reproducibility._

### 🎯 Goal: Make your work traceable and explainable.

### ✅ Key Actions:
- Keep a cleaning log (Excel, markdown, Notion).
- Comment code or transformations clearly.
- Save versions before and after cleaning.
- Write down assumptions, dropped fields, and logic used.

### 🔧 Useful Techniques:
- Use Git or backup files to track changes.
- Insert inline comments or markdown cells in Jupyter.
- Create README-style summaries for team sharing.

**🛠 Tools:** Notion, Git, Excel, markdown, Jupyter
</details>

---

## ✅ Suggested Workflow

1. **Conceptualize** the structure and business logic of your data.  
2. **Locate** and correct all solvable issues.  
3. **Evaluate** problems that can’t be fixed directly.  
4. **Augment** your data for better insights or modeling.  
5. **Note** your steps to ensure your process is transparent and replicable.

---

## 💡 Pro Tips

- 🔒 Always work on a copy of the original data.  
- 🔁 Data cleaning is iterative — go back and refine as needed.  
- 👁 Use visual tools to spot patterns or issues faster.  
- 📚 Document everything — it saves time later.

---

Made with care 💙 by **Tlaloc Alvarez**

