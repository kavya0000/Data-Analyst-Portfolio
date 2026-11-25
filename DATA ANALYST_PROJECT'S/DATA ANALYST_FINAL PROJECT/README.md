**#### Healthcare Data Analysis \& Transformation**



**\*\*Data Analytics Capstone | Final Project\*\* | \*\*Analyst:\*\* Poleboina Kavya **



**#### Project overview**



**This project takes a raw 55,000+ record healthcare patient dataset and transforms it into a clean, analysis-ready file (healthcare\_data\_transformed.csv). The notebook audits data quality issues, standardizes mixed-case patient names and date formats, engineers admission-year and billing metrics, and explores patient demographics, medical conditions, and hospital billing patterns across 11 visualizations. **



**#### Dataset**



**\* \*\*File:\*\* healthcare\_dataset.csv.zip (54,966 clean patient records, 15 columns)**

**\* \*\*Key Fields:\*\* Name, Age, Gender, Blood Type, Medical Condition, Date of Admission, Doctor, Hospital, Insurance Provider, Billing Amount, Room Number, Admission Type, Discharge Date, Medication, Test Results**



**#### Tech stack**



**Python, pandas, NumPy, Matplotlib, Seaborn, Google Colab / Jupyter Notebook **



**#### What the notebook does**



**StepWhat was done**

**\*\*1. Importing data\*\***

**Loaded healthcare\_dataset.csv and inspected schema, data types, and sample records**

**\*\*2. Cleaning the data\*\***

**Removed duplicate entries, standardized inconsistent text casing (e.g., patient names), and checked missing values**

**\*\*3. Data transformation\*\***

**Parsed admission/discharge dates, extracted Admission\_Year (2019–2024), computed summary metrics, and exported healthcare\_data\_transformed.csv**

**\*\*4. Statistical analysis\*\***

**Calculated mean, median, and standard deviation for Age (mean 51.54 yrs) and Billing Amount (mean $25,544.31)**

**\*\*5. Exploratory data analysis\*\***

**Grouped records by Gender, Medical Condition, Admission\_Year, and Insurance Provider**

**\*\*6. Data visualization\*\***

**Generated 11 distribution, trend, and comparative plots across demographics and hospital billing**



**#### Results: key metrics \& distributions**



**MeasureValue**

**\*\*Clean patient records\*\***

**54,966**

**\*\*Gender split\*\***

**Male: 27,496 (50.02%) · Female: 27,470 (49.98%)**

**\*\*Mean / Median Age\*\***

**51.54 years / 52.00 years (SD: 19.61)**

**\*\*Mean / Median Billing Amount\*\***

**$25,544.31 / $25,542.75 (SD: $14,208.41)**

**\*\*Average Billing by Gender\*\***

**Male: $25,614.45 · Female: $25,474.10**

**\*\*Top Medical Conditions\*\***

**Arthritis (9,218), Diabetes (9,216), Hypertension (9,151), Obesity (9,146), Cancer (9,140)**

**\*\*Peak Admission Year\*\***

**2020 (9,507 admissions), followed by 2022 (9,327) and 2023 (9,318)**



**#### Key decisions and why**



**\* \*\*Text \& date standardization first:\*\* Raw patient names contained irregular capitalization (e.g., Bobby JacksOn) and string dates; normalizing them early prevented grouping fragmentation.**

**\* \*\*Mean vs. median verification:\*\* Checking both mean ($25,544.31) and median ($25,542.75) billing confirmed a symmetric distribution across genders despite a few negative billing adjustments.**

**\* \*\*Saving transformed output:\*\* Exporting healthcare\_data\_transformed.csv separates data preparation from downstream visualization and reporting.**



**#### Screenshots**



**\*\*Visualization 1 — Patient Demographics \& Age Distribution:\*\***

** **



**\*\*Visualization 2 — Medical Condition Breakdown:\*\***

** **



**\*\*Visualization 3 — Billing Amount Distribution:\*\***

** **



**\*\*Visualization 4 — Annual Admission Trends (2019–2024):\*\***

** **



**\*\*Visualization 5 — Billing by Medical Condition:\*\***

** **



**\*\*Visualization 6 — Gender vs. Medical Condition Comparison:\*\***

** **



**\*\*Visualization 7 — Admission Type \& Insurance Analysis:\*\***

** **



**\*\*Visualization 8 — Medication \& Test Results Overview:\*\***

** **



**\*\*Visualization 9 — Multi-Variable Correlation \& Trends:\*\***

** **



**\*\*Visualization 10 — Hospital \& Billing Patterns:\*\***

** **



**\*\*Visualization 11 — Summary Analytical Dashboard:\*\***

** **



**#### Files in this folder**



**\* Final\_Project.ipynb: complete notebook with code, statistical summaries, and outputs**

**\* Final Project - Colab.pdf: exported PDF report of the executed notebook**

**\* healthcare\_dataset.csv.zip: compressed raw healthcare dataset**

**\* screenshots/: extracted chart images (chart\_1.png – chart\_11.png)**



**#### How to run**



**1. Install the libraries: pip install pandas numpy matplotlib seaborn jupyter**

**2. Extract healthcare\_dataset.csv.zip in the same folder as Final\_Project.ipynb.**

**3. Open Final\_Project.ipynb in Jupyter Notebook or Google Colab and choose \*\*Run All\*\*.**

