# 📊 Global Layoffs Analysis & Pandas vs Polars Benchmark

## 🧠 Project Overview
This project explores a real-world dataset of global tech layoffs to uncover key trends and patterns across companies, countries, industries, and time.

In addition, it includes a performance comparison between **Pandas** and **Polars** to evaluate their efficiency in real-world data analysis tasks.

---

##  Objectives
- Clean and preprocess the layoffs dataset  
- Analyze layoffs across:
  - 🌍 Countries  
  - 🏢 Companies  
  - 🏭 Industries  
  - 📈 Time trends  
- Identify extreme cases (e.g., 100% layoffs)  
- Explore the relationship between funding and layoffs  
- Benchmark **Pandas vs Polars** performance  

---

## Key Insights

-  The United States dominates global layoffs by a significant margin  
-  Layoffs did not occur gradually, but in **waves**, with a major spike around 2022–2023  
-  A small number of companies account for a large portion of total layoffs  
-  Some companies experienced **100% layoffs**, indicating complete shutdowns  
-  Layoffs extended beyond tech into industries like consumer and retail  
-  High funding does **not guarantee stability**, as even well-funded companies faced layoffs  

---

##  Pandas vs Polars – Performance Comparison

The project compares both libraries across:

- Data loading  
- GroupBy operations  
- Filtering  
- Column calculations  

###  Result
- **Pandas performed faster** in this case  
- Reason: the dataset is relatively small (~1.7K rows)  

###  Key Takeaway
> Tool performance depends on data size:
- Pandas is efficient for small to medium datasets  
- Polars shows its advantage with large-scale data  

---

##  Tech Stack
- Python   
- Pandas  
- Polars  
- Matplotlib / Plotly  

---

## 📂 Dataset

The dataset used in this project is publicly available:

 [Tech Layoffs Dataset]([PUT_YOUR_LINK_HERE](https://www.kaggle.com/datasets/ulrikeherold/tech-layoffs-2020-2024?resource=download))

It includes:
- Company information  
- Location and country  
- Industry  
- Number and percentage of layoffs  
- Funding raised  
- Layoff dates  
---


##  Conclusion
This project demonstrates that:
- Data analysis can reveal meaningful patterns in real-world events  
- Tool selection (Pandas vs Polars) should be based on context and data size  
- Combining analysis with performance benchmarking provides deeper insights  

