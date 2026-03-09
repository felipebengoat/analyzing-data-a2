# Assignment 2: Simple Linear Regression Analysis

## Course
Analyzing Data - University of Groningen

## Description
This project analyzes whether story features (Agency, Event Sequencing, World Building, Curiosity, Surprise, Suspense) are good predictors for story score using Simple Linear Regression.

## Dataset
- **Source:** ChangeMyView comments and posts
- **File:** `data_full_story.csv`
- **Observations:** 620 rows
- **Variables:**
  - `story_score` (dependent): Story strength (scale 0-1)
  - 6 independent variables (scale 1-5): agency_score, event_score, world_score, suspense_score, surprise_score, curiosity_score

## Project Structure
```
A2/
├── data/
│   └── data_full_story.csv
├── notebooks/
│   └── A2_Linear_Regression.ipynb
├── requirements.txt
├── README.md
└── .gitignore
```


## Setup

### 1. Create conda environment
```bash
conda create -n nlp-analysis python=3.11
conda activate nlp-analysis
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Run Jupyter
```bash
jupyter notebook
```
