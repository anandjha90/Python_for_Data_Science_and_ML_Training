# Python for Data Science & Machine Learning — 40-Hour Corporate Training

![Duration](https://img.shields.io/badge/duration-40%20hours-blue)
![Format](https://img.shields.io/badge/format-10%20days%20%C3%97%204%20hrs-blue)
![Level](https://img.shields.io/badge/level-beginner%20to%20intermediate-green)
![Python](https://img.shields.io/badge/python-3.10%20%7C%203.11-blue)
![Environment](https://img.shields.io/badge/runs%20on-VS%20Code%20%7C%20Google%20Colab-orange)

A complete, instructor-led corporate training programme taking working professionals from Python fundamentals to a deployed machine learning model — built around hands-on labs, graded home assignments and an enterprise-style capstone project.

Delivered by **[ANALYTICSWITHANAND](https://www.youtube.com/@analyticswithanand)**.

---

## Table of Contents

- [Who This Is For](#who-this-is-for)
- [Programme at a Glance](#programme-at-a-glance)
- [Learning Outcomes](#learning-outcomes)
- [Curriculum](#curriculum)
- [Day-by-Day Roadmap](#day-by-day-roadmap)
- [Repository Structure](#repository-structure)
- [Getting Started](#getting-started)
- [Environment Setup](#environment-setup)
- [Datasets](#datasets)
- [Home Assignments](#home-assignments)
- [Capstone Project](#capstone-project)
- [Assessment & Certification](#assessment--certification)
- [Documents in This Repository](#documents-in-this-repository)
- [FAQ](#faq)
- [Licence & Contact](#licence--contact)

---

## Who This Is For

This programme is designed for technologists who write code but have not yet worked with data science or machine learning:

- Software Developers
- SDETs and QA Engineers
- Technology Leads and Architects
- Application Support Engineers
- DevOps and Platform Engineers moving into data roles

**Assumed background:** programming logic in any language, and basic mathematics. No prior Python, statistics or machine learning experience is assumed. Participants with existing Python knowledge will find Days 1–2 fast-paced rather than remedial.

---

## Programme at a Glance

| | |
|---|---|
| **Total duration** | 40 hours (2,400 minutes) |
| **Schedule** | 10 days × 4 hours |
| **Daily pattern** | 90 min concept & live coding → break → 90 min guided lab → 45 min review & doubt clearing |
| **Modules** | 10 |
| **Topics** | 78 |
| **Home assignments** | 4 (17–21 hours independent effort) |
| **Capstone** | Customer Churn Prediction (enterprise simulation) |
| **Theory : hands-on** | ~40% concept, ~60% hands-on |
| **Delivery** | Instructor-led, online or classroom |
| **Recommended batch size** | 15–20 (max 25) |

---

## Learning Outcomes

By the end of the programme, participants will be able to:

1. Write clean, tested, packaged Python — from core syntax through OOP, generators and decorators
2. Perform vectorised numerical computing with NumPy and reason about its performance
3. Ingest, clean, join, reshape and aggregate real multi-source data with Pandas
4. Turn messy raw data into a documented, leakage-free modelling dataset
5. Produce presentation-grade visualisations and run a disciplined, hypothesis-driven EDA
6. Explain ML concepts, learning paradigms, evaluation metrics and the bias–variance trade-off
7. Build, tune and evaluate regression, classification, ensemble and clustering models
8. Package preprocessing and modelling into a single leakage-safe scikit-learn pipeline
9. Serve a trained model through a REST endpoint and explain its predictions with SHAP
10. Deliver and present a complete, enterprise-style end-to-end ML project

---

## Curriculum

| # | Module | Hours | Topics | Key Content |
|:--:|---|:--:|:--:|---|
| 1 | **Python Foundations** | 4.5 | 11 | Environment setup, data types, operators, I/O & strings, control flow, loops, collections, functions & type hints, lambda, comprehensions |
| 2 | **Advanced Python & Engineering Practices** | 3.5 | 7 | Exceptions & logging, file handling, OOP (4 pillars), modules & packaging, iterators/generators/decorators, PEP 8, debugging, pytest |
| 3 | **NumPy for Numerical Computing** | 2.5 | 5 | ndarray internals, indexing & boolean masking, reshaping & stacking, broadcasting & vectorisation, linear algebra |
| 4 | **Pandas for Data Analysis** | 4.5 | 8 | Series & DataFrame, I/O (CSV/Excel/JSON/SQL), `loc`/`iloc`/`query`, transformations, GroupBy, merge & join, pivot & reshape, time series |
| 5 | **Cleaning, Wrangling & Feature Engineering** | 3.5 | 7 | Data profiling & quality scorecards, missing values, duplicates & outliers, encoding, scaling & transforms, feature engineering & selection, **data leakage** |
| 6 | **Visualisation & EDA** | 3.5 | 7 | Matplotlib fundamentals, distributions, relationships, categorical plots, correlation heatmaps, Seaborn theming, structured EDA & storytelling |
| 7 | **Statistics & ML Theory** | 4.0 | 8 | Statistics for ML, AI vs ML vs DL, learning paradigms, ML lifecycle & problem framing, train/test & cross-validation, bias–variance, regression & classification metrics |
| 8 | **ML Practical Implementation** | 5.5 | 9 | scikit-learn API & baselines, linear & regularised regression, logistic regression, decision trees, random forest, gradient boosting & XGBoost, KNN/Naive Bayes/SVM, model comparison |
| 9 | **Unsupervised, Tuning, Pipelines & Deployment** | 4.0 | 7 | K-Means, hierarchical & DBSCAN, PCA, hyperparameter tuning, Pipelines & ColumnTransformer, model persistence & FastAPI serving, responsible AI & SHAP |
| 10 | **End-to-End Capstone** | 4.5 | 9 | Problem framing → ingestion → cleaning → EDA → feature engineering → modelling → tuning → business insights → presentation |
| | **Total** | **40.0** | **78** | |

---

## Day-by-Day Roadmap

| Day | Modules | Focus | Day-End Outcome |
|:--:|---|---|---|
| 1 | M1 | Python core foundations | Write clean Python using functions, collections and comprehensions |
| 2 | M2 | Advanced Python & engineering practices | Structure Python as tested, packaged, production-quality code |
| 3 | M3 + M4 | NumPy & Pandas foundations | Perform vectorised computing and ingest any enterprise data format |
| 4 | M4 | Pandas data analysis | Analyse, aggregate, join and reshape multi-source data |
| 5 | M5 | Cleaning & feature engineering | Turn a messy raw dataset into a clean, leakage-free modelling dataset |
| 6 | M6 | Visualisation & EDA | Run a full EDA and present quantified insights to a business audience |
| 7 | M7 | Statistics & ML theory | Frame an ML problem and choose the right validation strategy and metric |
| 8 | M8 | ML implementation | Build, evaluate and compare a full portfolio of supervised models |
| 9 | M9 | Unsupervised, tuning & deployment | Tune, package and serve a model, and explain its behaviour |
| 10 | M10 | Capstone | Deliver and present a complete enterprise-style ML project |

---

## Repository Structure

```
.
├── README.md
├── requirements.txt
├── docs/
│   ├── Python_for_Data_Science_and_ML_40Hrs_ToC.xlsx   # Full ToC, labs, roadmap, capstone
│   ├── PreAssessment_Questions.docx                   # 25-question baseline test
│   └── PreAssessment_Answer_Key.docx                  # Trainer copy — explanations
├── notebooks/
│   ├── day01_python_foundations/
│   ├── day02_advanced_python/
│   ├── day03_numpy_pandas/
│   ├── day04_pandas_analysis/
│   ├── day05_cleaning_feature_engineering/
│   ├── day06_visualisation_eda/
│   ├── day07_statistics_ml_theory/
│   ├── day08_ml_implementation/
│   ├── day09_tuning_pipelines_deployment/
│   └── day10_capstone/
├── data/
│   ├── raw/            # Immutable source data — never edited
│   ├── processed/      # Cleaned, analysis-ready outputs
│   └── README.md       # Dataset sources and licences
├── src/
│   ├── cleaning_utils/ # Reusable package built in Module 2
│   └── api/            # FastAPI scoring service (Module 9)
├── assignments/
│   ├── HA1_utility_package/
│   ├── HA2_numpy_pandas_analysis/
│   ├── HA3_eda_feature_engineering/
│   └── HA4_model_build_deployment/
└── capstone/
    ├── charter.md
    ├── notebooks/
    └── deck/
```

---

## Getting Started

Participants may use **either** of the two supported environments. Both are used in class, and every notebook in this repository runs in both.

### Option A — Google Colab (zero install, recommended for Days 1–8)

No setup required. Open any notebook directly in the browser:

1. Go to [colab.research.google.com](https://colab.research.google.com)
2. Choose **File → Open notebook → GitHub**
3. Paste this repository URL and select the notebook

To use the repository's data and modules inside Colab, run this in the first cell:

```python
!git clone https://github.com/<your-org>/python-ds-ml-40hrs.git
%cd python-ds-ml-40hrs
!pip install -q -r requirements.txt
```

Most libraries used in this course (NumPy, Pandas, Matplotlib, Seaborn, scikit-learn, SciPy, statsmodels, XGBoost) are **pre-installed** in Colab. The `pip install` above covers the few that are not.

> **Note on Module 9.6 (model serving):** the FastAPI lab is designed for VS Code, where the endpoint runs on `localhost`. A Colab fallback using `uvicorn` in a background thread is provided in `notebooks/day09_tuning_pipelines_deployment/09_6_serving_colab.ipynb`.

### Option B — VS Code (recommended for Days 9–10 and all assignments)

```bash
# 1. Clone the repository
git clone https://github.com/<your-org>/python-ds-ml-40hrs.git
cd python-ds-ml-40hrs

# 2. Create and activate an isolated environment
python -m venv .venv
source .venv/bin/activate        # Windows: .venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Register the environment as a Jupyter kernel
python -m ipykernel install --user --name python-ds-ml --display-name "Python DS & ML"
```

Then install the **Python** and **Jupyter** extensions in VS Code, open any `.ipynb` file, and select the `Python DS & ML` kernel.

---

## Environment Setup

### `requirements.txt`

```txt
# Core
numpy>=1.26
pandas>=2.1
scipy>=1.11
statsmodels>=0.14

# Visualisation
matplotlib>=3.8
seaborn>=0.13

# Machine learning
scikit-learn>=1.4
xgboost>=2.0
imbalanced-learn>=0.12

# Interpretability
shap>=0.44

# Tuning
optuna>=3.5

# Data I/O
openpyxl>=3.1
pyarrow>=14.0

# Serving (Module 9)
fastapi>=0.109
uvicorn>=0.27
joblib>=1.3

# Quality & testing (Module 2)
pytest>=8.0
black>=24.0
flake8>=7.0

# Optional helpers
ydata-profiling>=4.6
category_encoders>=2.6

# Notebooks
jupyterlab>=4.0
ipykernel>=6.29
```

### Verify your setup

```python
import sys, numpy, pandas, sklearn, matplotlib, seaborn
print("Python  :", sys.version.split()[0])
print("NumPy   :", numpy.__version__)
print("Pandas  :", pandas.__version__)
print("sklearn :", sklearn.__version__)
```

### Hardware

| | Minimum | Recommended |
|---|---|---|
| RAM | 8 GB | 16 GB |
| Disk | 20 GB free | 40 GB free |
| CPU | Dual core | Quad core |

No GPU is required. If local installation is blocked by corporate policy, **use Google Colab** — it needs only a browser.

---

## Datasets

All datasets are public and are mirrored in `data/raw/` so labs never depend on live internet access or account creation.

| Dataset | Used In | Size | Why This Dataset |
|---|---|---|---|
| **Telco Customer Churn** | M4, M5, M6, M8, M10 | 7,043 × 21 | The reference dataset for the programme — mixed types, real missing values, mild class imbalance |
| IBM HR Employee Attrition | M5, M8, M10 (alt) | 1,470 × 35 | Rich categoricals with a clear business narrative |
| Ames / House Prices | M3, M8.2, M8.3 | 1,460 × 81 | The reference regression dataset — skewed target, heavy missingness |
| Loan / Credit Risk | M8.4, M10 (alt) | ~600–10,000 | Classification with genuine cost asymmetry |
| Online Retail (UCI) | M4.5–4.8, M9.1 | ~540,000 | Volume, joins, time series and RFM feature engineering |
| Application log sample | M1.4, M2.1, M2.2 | ~50,000 lines | Domain-relevant text parsing for QA/SDET participants |
| Test execution results | M1.3, M1.6, M2.2 | ~5,000 rows | Automation metrics mirroring participants' own work |
| `sklearn.datasets` built-ins | M7, M8.8, M9.3 | 150–1,797 | Instant, dependency-free demonstration data |

See `data/README.md` for source URLs and licence terms.

---

## Home Assignments

Four graded assignments, each building on the last, all feeding the capstone. **Total effort: 17–21 hours.**

| # | Title | After | Due | Effort | Deliverable |
|:--:|---|:--:|:--:|:--:|---|
| **HA-1** | Reusable Python Utility Package | Day 2 | Day 4 | 3–4 h | Installable package + passing pytest suite |
| **HA-2** | NumPy & Pandas Multi-Source Analysis | Day 4 | Day 5 | 4–5 h | Analysis notebook + 8 quantified insights |
| **HA-3** | EDA, Data Quality & Feature Engineering | Day 6 | Day 8 | 5–6 h | EDA report + feature specification + transformation log |
| **HA-4** | Model Build, Tuning, Explainability & Serving | Day 9 | Day 10 | 5–6 h | Model leaderboard + pipeline artefact + running endpoint |

> ⚠️ Assignments are **cumulative**. HA-3 produces the modelling dataset that HA-4 consumes, and HA-4 produces the model the capstone presents. A participant who skips one will not complete the capstone within the scheduled time.

Full specifications — Focus, Task, Requirements and Expected Outcomes — are in the **Home Assignments** sheet of the ToC workbook.

---

## Capstone Project

### Customer Churn Prediction & Retention Intelligence

**Business problem.** A subscription telecom provider loses ~26% of its customer base annually. Retention campaigns are sprayed across the entire base at high cost and low conversion. Identify in advance which customers are likely to churn in the next billing cycle, and explain why, so retention spend can be targeted.

**ML framing.** Binary classification predicting `P(churn = Yes)` at the end of a monthly observation window.

**Primary metric.** Recall on the churn class at a fixed precision floor, with ROC-AUC for ranking.

> A model predicting "no churn" for everyone scores **74% accuracy** and delivers **zero business value**. Accuracy is explicitly rejected as the decision metric.

**Success criteria.** Capture ≥70% of actual churners within the top 3 deciles of predicted risk, with a documented estimated revenue saving.

### Execution phases

| Phase | Activity | Min | Deliverable |
|:--:|---|:--:|---|
| P1 | Business problem framing | 25 | Project charter |
| P2 | Data collection & ingestion | 25 | Raw layer + data dictionary |
| P3 | Cleaning & quality remediation | 30 | Cleaned dataset + transformation log |
| P4 | Exploratory data analysis | 35 | EDA notebook + 10 insights |
| P5 | Feature engineering & selection | 30 | Feature specification |
| P6 | Model building | 40 | Candidate models + experiment log |
| P7 | Evaluation, tuning & selection | 35 | Final model + evaluation report |
| P8 | Prediction & business insights | 30 | Scored output + impact analysis |
| P9 | Presentation & walkthrough | 20 | Deck + final repository |

**Alternates:** Employee Attrition Prediction · House Price Prediction (regression variant) · Loan Approval Prediction.

**Evaluation rubric** (100 points): problem framing 10 · data cleaning 15 · EDA & insight quality 15 · feature engineering 15 · modelling & evaluation 20 · code quality & reproducibility 10 · business communication 15.

---

## Assessment & Certification

| Stage | What | Weight |
|---|---|:--:|
| Continuous | Lab deliverables against stated acceptance criteria | — |
| Mid-programme | Module 1–6 quiz + EDA report evaluation | — |
| Home assignments | Four graded submissions | — |
| Final | Capstone submission, code walkthrough and presentation | — |

**Certification criteria:** minimum 80% attendance · all lab deliverables submitted · all four home assignments completed · capstone presented.

A **25-question pre-training assessment** (easy to moderate, 30 minutes) is issued before Day 1 to baseline the cohort and calibrate pace. It is **not** pass/fail — see `docs/`.

---

## Documents in This Repository

| File | Audience | Purpose |
|---|---|---|
| `docs/Python_for_Data_Science_and_ML_40Hrs_ToC.xlsx` | Trainer, L&D | Full ToC (78 topics × 12 columns), duration summary, training roadmap, software & setup, datasets & resources, home assignments, capstone details |
| `docs/PreAssessment_Questions.docx` | Participants | 25-question baseline assessment + answer sheet |
| `docs/PreAssessment_Answer_Key.docx` | **Trainer only** | Answer key with explanations, distractor analysis, coverage map and question-level diagnostics |

---

## FAQ

<details>
<summary><b>I have no Python experience at all. Is this programme suitable?</b></summary>

Yes. Days 1–2 assume no Python knowledge, only programming logic in some language. Around 40% of a typical cohort is new to Python. The pre-assessment exists precisely so the trainer can calibrate.
</details>

<details>
<summary><b>My company laptop blocks software installation. What do I do?</b></summary>

Use **Google Colab**. It requires only a browser and a Google account, and every notebook in this repository runs there. Flag this before Day 1 so the trainer can pair you appropriately for the Module 9 serving lab.
</details>

<details>
<summary><b>Do I need a GPU?</b></summary>

No. Every model in this programme trains on CPU in seconds to minutes. Deep learning is deliberately out of scope.
</details>

<details>
<summary><b>Can I use my own company data for the assignments?</b></summary>

No. Use public datasets or the sample data supplied in class. Do not commit employer source code, customer data or any confidential material to a personal repository.
</details>

<details>
<summary><b>What if I miss a day?</b></summary>

Recordings and notebooks cover the content, but the home assignments are cumulative. Missing Day 5 or Day 6 is the most damaging — those produce the modelling dataset the rest of the programme depends on. Speak to the trainer to catch up before the next assignment is due.
</details>

<details>
<summary><b>Is 40 hours enough to become a data scientist?</b></summary>

No, and the programme does not claim to. It makes you **productive and independent** — able to analyse data, build and evaluate models, and continue advanced learning without guidance. Objective 10 is explicitly "confident enough to continue advanced learning independently."
</details>

---

## Licence & Contact

Course materials © ANALYTICSWITHANAND. Datasets remain under their original licences — see `data/README.md`.

**Training enquiries:** [ANALYTICSWITHANAND on YouTube](https://www.youtube.com/@analyticswithanand) · [LinkedIn](https://www.linkedin.com/in/anandjha90/) · [GitHub](https://github.com/anandjha90)

---

<div align="center">

*Built for people who write code and now need to make sense of data.*

</div>
