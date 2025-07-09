# Trader Behavior vs Market Sentiment - Data Science Assignment

This project explores how traders behave under different market sentiments like Fear or Greed. It uses real-world trading and sentiment data to analyze patterns in profit, risk and trade volume.

---

## Project Contents

- `notebook_1.ipynb` - Google Colab notebook with full code and analysis  
- `ds_report.pdf` - Final report summarizing insights and charts  
- `csv_files/` - Contains the original datasets  
- `outputs/` - Contains saved charts (as PNG images)

---

## Note on Datasets

Due to GitHub file size limits, the datasets are uploaded as `.zip` files:

- `fear_greed_index.zip`  
- `historical_data.zip`  

Please **download and unzip** these files before running the notebook.

---

## Summary of Work

- Merged sentiment and trading datasets by date  
- Calculated average profit, standard deviation (risk), and total volume per sentiment category  
- Visualized the results using bar charts  
- Saved graphs in PNG format  
- Compiled final insights into a structured PDF report

---

## Tools & Technologies

- Google Colab  
- Python  
  - pandas  
  - seaborn  
  - matplotlib

---

## Reflections & Next Steps

### Challenges Faced
- Aligning the two datasets by date was slightly tricky due to different formats and granularities.
- Selecting the most meaningful trader behavior metrics required careful consideration.
- Saving plots cleanly for PDF export involved adjusting layout and figure size.

### What I'd Do Differently
- Normalize profit/volume per trader or symbol for deeper insights.
- Filter outliers to reduce skew in averages.
- Make the visualizations interactive using Plotly or Altair.

### Future Improvements
- Add more context by including Bitcoin price/volatility data.
- Use machine learning to classify or predict sentiment based on trades.
- Automate full report generation with a Python-based template.

---

## View the Colab Notebook

[Open notebook on Google Colab](https://colab.research.google.com/drive/1TqSDSkoF_WFwBO7G9AUrEpzs8e9qW2hi?usp=sharing)
