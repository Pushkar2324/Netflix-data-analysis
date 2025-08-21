# Netflix Data Analysis

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/downloads/)
[![Pandas](https://img.shields.io/badge/Pandas-1.3%2B-green.svg)](https://pandas.pydata.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-3.0%2B-orange.svg)](https://matplotlib.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)

## 📋 Project Overview

This project provides a comprehensive analysis of Netflix's content catalog, exploring various aspects of movies and TV shows available on the platform. The analysis aims to uncover insights about content trends, geographic distribution, genre preferences, and viewing patterns.

## 🎯 Objectives

- **Content Distribution Analysis**: Examine the distribution of movies vs. TV shows
- **Geographic Insights**: Analyze content production by country and region
- **Genre Trends**: Identify popular genres and their evolution over time
- **Release Patterns**: Study content release trends across years
- **Rating Analysis**: Explore content ratings and their distribution
- **Duration Insights**: Analyze movie durations and TV show seasons

## 📊 Dataset Information

The dataset contains information about Netflix content including:
- **Title**: Name of the movie/show
- **Type**: Movie or TV Show
- **Director**: Director(s) of the content
- **Cast**: Main cast members
- **Country**: Country of production
- **Date Added**: When content was added to Netflix
- **Release Year**: Year of original release
- **Rating**: Content rating (PG, R, etc.)
- **Duration**: Runtime for movies / Number of seasons for TV shows
- **Listed In**: Genres/Categories
- **Description**: Brief description of the content

## 🛠️ Technologies Used

- **Python 3.8+**
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computing
- **Matplotlib**: Data visualization
- **Seaborn**: Statistical data visualization
- **Plotly**: Interactive visualizations
- **Jupyter Notebook**: Development environment

## 📁 Project Structure

```
netflix-data-analysis/
│
├── netflix_data_analysis.ipynb    # Main analysis notebook
├── data/
│   └── netflix_titles.csv         # Netflix dataset
├── images/                        # Generated visualizations
├── README.md                      # Project documentation
└── requirements.txt               # Python dependencies
```

## 🚀 Getting Started

### Prerequisites

Ensure you have Python 3.8 or higher installed on your system.

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/netflix-data-analysis.git
   cd netflix-data-analysis
   ```

2. **Install required packages:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Launch Jupyter Notebook:**
   ```bash
   jupyter notebook netflix_data_analysis.ipynb
   ```

### Required Libraries

```python
pandas>=1.3.0
numpy>=1.21.0
matplotlib>=3.4.0
seaborn>=0.11.0
plotly>=5.0.0
jupyter>=1.0.0
```

## 📈 Key Findings

### Content Distribution
- Analysis of the movie-to-TV show ratio on Netflix
- Trends in content addition over the years

### Geographic Analysis
- Top content-producing countries
- Regional content preferences and availability

### Genre Insights
- Most popular genres on the platform
- Genre evolution and trends over time

### Temporal Patterns
- Peak years for content production
- Seasonal patterns in content addition to Netflix

### Content Characteristics
- Average movie duration analysis
- TV show season distribution
- Rating distribution across content types

## 📊 Visualizations

The notebook includes various visualizations:
- **Bar Charts**: Content distribution by type, country, and genre
- **Line Graphs**: Trends over time
- **Heatmaps**: Correlation analysis
- **Pie Charts**: Proportional distributions
- **Box Plots**: Statistical distributions
- **Interactive Plots**: Enhanced user experience with Plotly

## 🔍 Analysis Methodology

1. **Data Cleaning**: Handling missing values, data type conversions
2. **Exploratory Data Analysis (EDA)**: Understanding data structure and patterns
3. **Statistical Analysis**: Computing descriptive statistics
4. **Visualization**: Creating informative charts and graphs
5. **Insights Extraction**: Drawing meaningful conclusions from data

## 📋 Usage

1. Open the Jupyter notebook
2. Run cells sequentially to reproduce the analysis
3. Modify parameters or add new analyses as needed
4. Export visualizations for presentations or reports
