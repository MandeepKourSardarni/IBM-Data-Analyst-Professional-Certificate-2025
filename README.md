# IBM Data Analyst Professional Certificate — 2025

A working repo for my Coursera/IBM **Data Analyst Professional Certificate (2025 cohort)**.  
It contains notes, labs, assignments, datasets, and Jupyter notebooks I created while learning **Excel, SQL, Python, data wrangling, visualization, dashboards, and storytelling**.

---

## 🔍 What’s inside
- `notebooks/` & standalone `*.ipynb` — analysis, mini-projects, practice labs  
- `datasets/` & `*.csv / *.xlsx` — input data used by notebooks  
- `reports/` & `*.pdf` — assignment write-ups and exported results  
- Misc course artifacts (cheat sheets, slides, screenshots)

> Tip: Large PDFs/data are kept minimal. For files >100MB I use Git LFS or store externally.

---

## 🧠 Skills & tools practiced
- **Excel**: formulas, lookups, pivot tables, charts, dashboards  
- **SQL**: SELECT/JOIN/AGGREGATE, subqueries, window functions, SQLite  
- **Python**: `pandas`, `numpy`, `matplotlib/plotly`, `scikit-learn` (basics)  
- **Data wrangling**: cleaning, reshaping, missing values, outliers  
- **Web scraping**: `requests`, `BeautifulSoup` (light use)  
- **Visualization**: storytelling with charts; dashboards (Excel / Cognos)  
- **Analytics workflow**: framing problems → EDA → insights → presentation

---

## ▶️ How to run locally
**Prereqs:** Python 3.10+ (or use Anaconda) and `git`.

```bash
# clone
git clone https://github.com/MandeepKourSardarni/IBM-Data-Analyst-Professional-Certificate-2025.git
cd IBM-Data-Analyst-Professional-Certificate-2025

# (optional) create and activate a virtual env
python -m venv .venv
# Windows
. .venv/Scripts/activate
# macOS/Linux
# source .venv/bin/activate

# install common packages used across notebooks
pip install -U pandas numpy matplotlib plotly seaborn scikit-learn jupyterlab \
            requests beautifulsoup4 lxml openpyxl sqlalchemy ipywidgets
jupyter lab  # or: jupyter notebook
