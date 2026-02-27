Fear & Greed Trading Performance Analysis
⚠ Important: Large Dataset Not Included

Due to GitHub's 25MB upload limitation, historical_data.csv is hosted externally.

📥 Download Full Dataset Here:
https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view?usp=sharing

After downloading, place the file in the same directory as the notebook before running the analysis.

📌 Objective

To analyze how market sentiment (Fear & Greed Index) impacts trading performance using historical trade data and statistical validation.

📂 Files Included

ProjectUI.ipynb — Complete analysis notebook

fear_greed_index.csv — Sentiment dataset

summary_table.csv — Final aggregated performance metrics

README.md — Project documentation

⚙️ Methodology

Cleaned and standardized both datasets

Converted timestamps into proper date format

Merged trading data with Fear & Greed sentiment classification

Calculated key performance metrics:

Average Closed PnL

Win Rate

Volatility (Standard Deviation of Daily PnL)

Performed statistical validation using independent T-tests

Segmented traders based on:

Trading frequency (Frequent vs Infrequent)

Consistency (Low vs High volatility)

Profitability level (High vs Low profit traders)

📊 Key Insights

Highest average PnL observed during Extreme Greed

Win rate highest during Extreme Greed

Volatility highest during Fear phases

Frequent traders performed better during strong positive sentiment

High-profit traders showed greater stability across sentiment regimes

Statistical testing confirmed significant performance differences between sentiment phases

📈 Strategy Recommendations

Increase exposure during Greed / Extreme Greed phases

Reduce risk during Fear / Extreme Fear conditions

Apply volatility-based position sizing

Use sentiment classification as a macro-level trade filter

Avoid overexposure during highly volatile sentiment periods

🛠 Tools & Libraries Used

Python

Pandas

NumPy

Matplotlib

Seaborn

SciPy

▶ How to Run the Project
1️⃣ Install Dependencies
pip install pandas numpy matplotlib seaborn scipy
2️⃣ Place Dataset

Download historical_data.csv from the Google Drive link above and place it in the project root directory.

3️⃣ Run Notebook
jupyter notebook ProjectUI.ipynb

Run all cells to reproduce the analysis and charts.

📌 Output

The notebook generates:

Sentiment-wise Average PnL

Win Rate comparison charts

Volatility analysis

Trader segmentation performance comparison

Statistical T-test validation

Final summary table (summary_table.csv)


