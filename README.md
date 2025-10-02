# ds_Dhanujaa-P

✅ Deliverables


📓 Google Colab Notebook → https://colab.research.google.com/drive/1iFR9PMCQ-Y85yJt1NNw9xKCJDwio0deN?usp=sharing


💻 GitHub Repository → https://github.com/DhanujaaSudhi/ds_Dhanujaa-P/tree/main


📑 Final Report (PDF) → ds_report.pdf

🚀 How to Run
Open notebook_1.ipynb in Google Colab
Upload the two raw datasets:
fear_greed_index.csv
historical_data.csv
Run all cells step by step.

The notebook will automatically generate:


📂 Cleaned CSV files in csv_files/


🖼️ Visualizations in outputs/


📑 A merged dataset → merged_data.csv



📝 To generate the final PDF report:
Run the last section of the notebook → ds_report.pdf
The report includes summary insights + sample charts.

📊 Steps Taken


🔹 Data Cleaning
Converted date fields into consistent datetime format
Removed missing values & standardized column names

🔹 Feature Engineering
Aggregated daily metrics from trader data:
Closed PnL
Trade Volume
Average Execution Price
Merged with daily sentiment (Fear & Greed index)

🔹 Exploratory Data Analysis (EDA)


📈 Daily PnL time trends


📊 PnL vs Market Sentiment (boxplots)


📊 Trade Volume vs Sentiment


🔥 Correlation Heatmap between sentiment & trading metrics

🔹 Insights & Report


✅ Traders tend to perform better during Greed cycles


⚠️ Higher losses observed during Fear cycles


📊 Volume spikes in both Extreme Greed and Extreme Fear phases


🛡️ Sentiment index can serve as a risk-management signal

