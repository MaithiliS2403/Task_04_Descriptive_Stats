# Task 04 — Descriptive Statistics System

This repository contains three implementations of a descriptive statistics engine using:
- Pure Python (no libraries)
- Pandas
- Polars

The system was developed to analyze public datasets related to social media and political candidates during the 2024 U.S. presidential election.

---

## 📂 Files Included

| File Name            | Description                              |
|---------------------|------------------------------------------|
| `pure_python_stats.py` | Descriptive stats using only base Python |
| `pandas_stats.py`      | Descriptive and grouped stats using Pandas |
| `polars_stats.py`      | High-performance analysis using Polars    |

---

## 🔍 Dataset Used

**Dataset**: `2024_fb_ads_president_scored_anon.csv`  
**Source**: Provided via OPT research task  
**Location**: _Not uploaded_ (as per guidelines)

---

## 💡 Summary of Insights

- All scripts compute overall summary stats (count, mean, min, max, etc.)
- Scripts group by `page_id`, and `page_id + ad_id`
- Polars significantly improves speed on large datasets
- Data shows campaign-level patterns in ad content and reach

---

## 🚀 How to Run

1. Place CSV file in `data/` (do not push it to GitHub)
2. Run any script:

```bash
python3 pure_python_stats.py
python3 pandas_stats.py
python3 polars_stats.py
