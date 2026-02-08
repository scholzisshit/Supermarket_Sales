Check out this repo for the Supermarket Sales Analysis

The Vibe Check
This is an in-depth EDA on a supermarket dataset with 1,000 transactions. I used Python to figure out who’s spending, what’s actually trending, and which branch is carrying the company.

The Tea
Branch A is the Final Boss: It’s leading in total transaction volume. Yangon is literally the moment.

Food and Beverages Paid the Bills: This product line is bringing in the most revenue, no contest.

E-wallets are Meta: Cash is for boomers. Most customers are using E-wallets because the digital flex is real.

Peak Hours: 19:00 is when the store is absolutely unmatched. Everyone is shopping after work, fr.

The Build
Feature Engineering: I had to do some heavy lifting on the Time column. I converted the raw strings into datetime objects and extracted the Hour variable so we could actually see when the store peaks.

Data Quality Checked the integrity with `df.isna().sum()` and it came back with zero misses. We love to see clean data. I also made sure the dtypes were right so the math actually mathed—floats for the money and objects for the categories.

Tech Stack
Python: The only language that matters.

Pandas: For the data manipulation grind.

Seaborn & Matplotlib: To make the charts look clean.

Jupyter Notebook: Where the vision came to life.

How to Run:

Clone the repo.

Run pip install pandas seaborn matplotlib so your environment doesn't crash.

Open the notebook and run all cells to see the data glow up.


<img width="615" height="553" alt="Screenshot 2026-02-08 at 9 17 12 am" src="https://github.com/user-attachments/assets/e1589e1f-6b1d-41e0-b24a-ce2269504c54" />
<img width="720" height="520" alt="Screenshot 2026-02-08 at 9 16 57 am" src="https://github.com/user-attachments/assets/1e691268-7834-47ad-a6f6-dcbce10f99af" />
<img width="944" height="406" alt="Screenshot 2026-02-08 at 1 04 43 pm" src="https://github.com/user-attachments/assets/9ab50733-c7a1-4dbc-b2b1-8b6f25e46af3" />
<img width="691" height="462" alt="Screenshot 2026-02-08 at 9 16 43 am" src="https://github.com/user-attachments/assets/811b0dd5-4d03-448d-87ac-33afa8b8555f" />
<img width="1215" height="774" alt="Screenshot 2026-02-08 at 1 07 06 pm" src="https://github.com/user-attachments/assets/5a15cb75-ed24-475e-b6eb-20932cd6548b" />
<img width="1268" height="661" alt="Screenshot 2026-02-08 at 1 07 00 pm" src="https://github.com/user-attachments/assets/b4986cc1-5057-4810-a9e4-555642673bad" />
<img width="894" height="457" alt="Screenshot 2026-02-08 at 1 00 54 pm" src="https://github.com/user-attachments/assets/c547fc59-41f1-4256-a0ea-d4caeaa87bad" />
<img width="738" height="362" alt="Screenshot 2026-02-08 at 1 00 46 pm" src="https://github.com/user-attachments/assets/e0b71fd6-e9e9-4cb4-b1eb-0e30527aa1af" />

