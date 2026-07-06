# data-cleaning-ml-projects
Hands-on pandas + scikit-learn portfolio: cleaning messy real-world data and building baseline ML models, organized across 4 difficulty levels.
# Pandas + AI Engineering Portfolio

Hands-on data cleaning and machine learning projects across 20 real-world datasets, organized across 4 difficulty levels — from pandas fundamentals to production-grade, defended pipelines.

## About This Repository

Each project follows the same disciplined workflow:
1. **Profile** the raw dataset — shape, dtypes, missing values — before touching anything.
2. **Investigate** *why* data is missing or messy, rather than guessing.
3. **Clean** with documented, defensible decisions (not silent fixes).
4. **Verify** after every destructive operation.
5. *(From the ML phase onward)* Engineer features, split data properly, and build baseline models.

## Tools Used
- **Python** / **pandas** — data profiling, cleaning, and feature engineering
- **scikit-learn** — encoding, train/validation/test splitting, baseline modeling
- **Jupyter / Google Colab** — development environment

## Curriculum Structure

| Level | Focus | Datasets |
|-------|-------|----------|
| 1 — Beginner | Inspect · Clean · Ask Basic Questions | 5 |
| 2 — Intermediate | Reshape · Merge · Engineer Features | 5 |
| 3 — Pro | Optimize · Automate · Pipeline | 5 |
| 4 — Master | End-to-End · Production-Grade · Defended | 5 |

## Projects

### Level 1 — Beginner
- ✅ **Titanic Passenger Survival** — missing value profiling, group-based imputation, proxy-variable reasoning, one-hot encoding, and a baseline Logistic Regression model (~81% validation accuracy).
- ⬜ Netflix Movies and TV Shows
- ⬜ Zomato Restaurant Data
- ⬜ COVID-19 World Dataset
- ⬜ World Happiness Report

*(Datasets 2 onward focus purely on pandas cleaning and feature engineering; the full ML pipeline — EDA, splitting, encoding, modeling — will be reintroduced gradually once the pandas-mastery phase is complete.)*

### Level 2 — Intermediate
- ⬜ NYC Airbnb Open Data
- ⬜ Spotify Tracks Dataset
- ⬜ FIFA Player Ratings Dataset
- ⬜ Amazon Product Sales Dataset
- ⬜ US Traffic Accidents Dataset

### Level 3 — Pro
- ⬜ Google Play Store Apps
- ⬜ Stack Overflow Developer Survey
- ⬜ NYC Yellow Taxi Trip Records
- ⬜ Airline Delay and Cancellation Data
- ⬜ Yelp Business Dataset

### Level 4 — Master
- ⬜ Sentiment140 — Twitter Sentiment
- ⬜ Medical Appointment No-Shows
- ⬜ Global Terrorism Database
- ⬜ E-Commerce Customer Churn
- ⬜ World Bank Development Indicators

## Notes
Every cleaning decision in these notebooks is backed by evidence checked against the data itself (not assumptions) and documented in markdown cells alongside the code.
