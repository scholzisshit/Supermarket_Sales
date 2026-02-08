#Check out this repo for the Supermarket Sales Analysis

#The Vibe Check
This is an in-depth EDA on a supermarket dataset with 1,000 transactions. I used Python to figure out who’s spending, what’s actually trending, and which branch is carrying the company.

#The Tea
*Branch A is the Final Boss: It’s leading in total transaction volume. Yangon is literally the moment.

*Food and Beverages Paid the Bills: This product line is bringing in the most revenue, no contest.

*E-wallets are Meta: Cash is for boomers. Most customers are using E-wallets because the digital flex is real.

*Peak Hours: 19:00 is when the store is absolutely unmatched. Everyone is shopping after work, fr.

#The Build
Feature Engineering I had to do some heavy lifting on the Time column. I converted the raw strings into datetime objects and extracted the Hour variable so we could actually see when the store peaks.

Data Quality Checked the integrity with `df.isna().sum()` and it came back with zero misses. We love to see clean data. I also made sure the dtypes were right so the math actually mathed—floats for the money and objects for the categories.

#Tech Stack
*Python: The only language that matters.

*Pandas: For the data manipulation grind.

*Seaborn & Matplotlib: To make the charts look clean.

*Jupyter Notebook: Where the vision came to life.

#How to Run:

*Clone the repo.

*Run pip install pandas seaborn matplotlib so your environment doesn't crash.

*Open the notebook and run all cells to see the data glow up.
