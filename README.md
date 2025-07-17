# 📊 Overview of Automatic EDA Libraries

This document provides a summary of popular Python libraries used for **automated Exploratory Data Analysis (EDA)**.

---

## 1. `ydata_profiling` (formerly `pandas-profiling`)
**Description:**  
Automatically generates a **detailed HTML report** about your entire dataset — with stats, correlations, missing values, data types, and more.

**Highlights:**
- Fully automatic
- Interactive visualizations
- Great for both small and large datasets
- Easy to save as `.html`

**Best for:**  
👉 One-click, full dataset analysis.

---

## 2. `dtale`
**Description:**  
Launches an **interactive web app** (like Excel in your browser) to **explore and edit** your Pandas DataFrame.

**Highlights:**
- Clean UI for sorting, filtering, visualizing
- Supports editing cells and running Python code
- Works locally via `localhost`

**Best for:**  
👉 Visual data exploration and quick cleaning.

---

## 3. `pygwalker`
**Description:**  
Turns your DataFrame into a **drag-and-drop BI tool** (like Tableau or Power BI), right inside Jupyter or Colab.

**Highlights:**
- Auto-generates charts
- Drag and drop chart builder
- Based on [Graphic Walker](https://github.com/Kanaries/pygwalker)

**Best for:**  
👉 Visual storytelling and chart exploration without coding.

---

## 4. `sweetviz`
**Description:**  
Creates a **beautiful HTML dashboard** comparing datasets (e.g., train vs test) with visual summaries.

**Highlights:**
- Very visual, colorful, and intuitive
- Focus on **target variable** relationships
- Can compare two datasets side-by-side

**Best for:**  
👉 Comparing training and testing datasets.

---

## 5. `skimpy`
**Description:**  
Lightweight tool that gives a **quick summary table** of your data — like `skimr` in R.

**Highlights:**
- Minimal and fast
- Summary of types, missing %, mean, std, etc.
- Good for terminal or quick checks

**Best for:**  
👉 Quick glance at data without heavy HTML reports.

---

## 6. `lida` (Language Interface for Data Analysis)
**Description:**  
Natural Language-based EDA powered by AI — lets you type questions like:  
> "What’s the average age by gender?"

**Highlights:**
- AI understands your questions
- Suggests charts and analysis
- Great for non-coders and fast insight

**Best for:**  
👉 Conversational analysis and chart generation.

---

## 7. `dataprep`
**Description:**  
An EDA tool designed for **cleaning and summarizing data efficiently**, especially in Jupyter.

**Highlights:**
- Beautiful inline visuals
- `dataprep.eda` for profiling
- Can handle larger datasets
- Fast and memory-efficient

**Best for:**  
👉 Modern EDA workflows in Jupyter notebooks.

---

## 🧾 Summary Table

| Library         | Type                 | Key Feature                           | Best Use                             |
|------------------|----------------------|----------------------------------------|--------------------------------------|
| `ydata_profiling` | Full Report          | Detailed HTML profile report           | All-in-one EDA                       |
| `dtale`           | Interactive UI       | Edit & explore in browser              | Spreadsheet-like view                |
| `pygwalker`       | Visual Builder       | Tableau-like chart explorer            | Drag-and-drop visual analytics       |
| `sweetviz`        | Comparison + Visuals | Auto comparisons & target analysis     | Train-test comparisons               |
| `skimpy`          | Summary Table        | Fast, simple stats summary             | Quick look in terminal               |
| `lida`            | AI-powered           | Ask questions in natural language      | No-code insights                     |
| `dataprep`        | Modern EDA           | Fast, pretty reports in notebooks      | Jupyter-friendly, fast EDA           |
