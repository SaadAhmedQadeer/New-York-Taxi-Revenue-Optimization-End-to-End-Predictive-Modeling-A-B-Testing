# NYC Taxi Data Analysis

A portfolio of data analysis projects using NYC Taxi & Limousine Commission trip data. This repository walks through the entire data science workflow—from asking questions about the data to building machine learning models.

## What's in here?

I've organized this into five notebooks that follow a natural progression:

**01 - Exploratory Analysis**
Just getting to know the data. What does it look like? Are there missing values? How big is it really? This is where I figure out what I'm working with before diving deeper.

**02 - Visualization & EDA**
Making sense of patterns. I create charts and dig into distributions, correlations, and trends over time. This is where the data starts telling a story.

**03 - Statistical Testing**
Actually testing whether the patterns I'm seeing matter. I focus on whether payment type affects how much people spend on fares—and whether the relationship is statistically significant.

**04 - Regression Model**
Building a model to predict taxi fares. I use multiple linear regression to understand what drives fare amounts (distance, time of day, etc.) and validate that the model actually makes sense.

**05 - Classification Model**
Predicting who tips generously. I build a Random Forest and XGBoost classifier to identify rides where the passenger is likely to tip 20% or more, then dig into which features matter most.

## Tech stack

- Python, pandas, numpy for data work
- Matplotlib and seaborn for visualizations
- Scipy and statsmodels for statistical testing
- Scikit-learn and XGBoost for machine learning
- Jupyter notebooks for everything

## Key takeaways

- Payment type genuinely matters—different payment methods correlate with different spending patterns
- Trip distance and duration are the strongest predictors of fare amounts
- XGBoost significantly outperforms Random Forest for identifying high-tip riders (AUC > 0.85)
- Time of day and location characteristics are surprisingly predictive of tipping behavior

## Running the notebooks

If you want to run these yourself:

```bash
# Clone the repo
git clone https://github.com/yourusername/nyc-taxi-analysis.git
cd nyc-taxi-analysis

# Install dependencies
pip install pandas numpy matplotlib seaborn scipy scikit-learn xgboost jupyter

# Start Jupyter
jupyter notebook
```

Start with notebook 01 and work your way through. Each one builds on the previous analysis.

## About the data

This uses publicly available NYC TLC trip records. The dataset includes trip distance, fares, payment type, pickup/dropoff locations, timestamps, and tip amounts. You can find the official data on the NYC TLC website.

## Why this project?

I built this to demonstrate practical data analysis skills: how to ask the right questions, validate assumptions, communicate findings visually, and move from exploratory analysis to predictive modeling. It's not just about making models—it's about understanding what the data actually tells us.

## Get in touch

Questions about the analysis or want to collaborate? Feel free to reach out:

- **LinkedIn:** [Add your profile]
- **Email:** [Add your email]

---

MIT License. Use this code however you'd like for learning and portfolio projects.
