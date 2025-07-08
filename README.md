# 📊 Analysis of Trader Behavior & Market Sentiment

Google Colab Notebook
All analysis code is provided in the following Google Colab notebook:   https://colab.research.google.com/drive/1k29K820aCyA49tCGtrmOaocYitxc6O87

This repository contains the code, data outputs, and report analyzing how trader behavior from Hyperliquid aligns with the Bitcoin Fear & Greed Index.

> ⚠️ **All work must strictly follow this structure:**  
> `ds_palak/`

---

## 🏗 Project Structure

ds_palak/
├── ds_task.ipynb # Google Colab notebook with analysis
├── csv_files/ # Processed & intermediate data outputs
│ └── *.csv
├── outputs/ # Charts and visualization files
│ └── *.png / *.jpg
├── ds_report.pdf # Final summary report of findings & recommendations
└── README.md

---

## 📂 Data Sources

| Dataset                                      | Path                                    | Description                                     |
|----------------------------------------------|-----------------------------------------|-------------------------------------------------|
| Bitcoin Market Sentiment (Fear & Greed Index)| `/content/csv_files/fear_greed_index.csv` | Daily sentiment classification (Fear / Greed) |
| Historical Trader Data (Hyperliquid)        | `/content/csv_files/historical_data.csv` | Detailed trade-level data (PnL, size, leverage) |

Original datasets provided as Google Drive links:
- [Trader Data](https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view?usp=sharing)
- [Fear & Greed Index](https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view?usp=sharing)

---

## 🎯 Objective

Analyze how trading behavior metrics — profitability, leverage, volume, and risk — align or diverge from market sentiment.  
Identify hidden trends and actionable signals to design smarter trading strategies.

---

## ⚙️ Analysis Workflow

1. **Data Loading & Inspection**  
2. **Data Cleaning & Preparation**  
3. **Merging Sentiment & Trader Data**  
4. **Exploratory Data Analysis (EDA)**  
5. **Sentiment vs Trader Behavior Analysis**  
6. **Key Trend Identification & Strategy Recommendations**  
7. **Saving Outputs:**  
   - CSV files → `csv_files/`  
   - Charts → `outputs/`  
   - Summary report → `ds_report.pdf`

---

## 📈 Key Findings & Recommendations

> *Replace this section with your summarized insights from the analysis.*

---

## 🚀 How to Reproduce

1. Open `ds_task.ipynb` in **Google Colab**
2. Confirm datasets are located at:  
   - `/content/csv_files/fear_greed_index.csv`
   - `/content/csv_files/historical_data.csv`
3. Run all cells sequentially
4. Check:
   - Processed CSVs → `csv_files/`
   - Visual charts → `outputs/`
   - Summary report → `ds_report.pdf`

---

## ✅ Submission Checklist

- [ ] Google Colab notebook shared with “Anyone with link can view”
- [ ] GitHub repo mirrors the directory structure
- [ ] CSVs saved to `csv_files/`
- [ ] Visual outputs saved to `outputs/`
- [ ] Final `ds_report.pdf` generated
- [ ] README.md updated and committed

---

## ✏️ Author

`Palak Mori` | Data Science Assignment for Web3 Trading Team


---
