# AVIS Survey Analysis

A comprehensive statistical analysis of Asynchronous Video Interviews (AVI) survey data focusing on user perceptions and behavioral intentions.

## 📊 Overview

This is a project where I did the statistical analysis for a client's thesis in management and business administration. The survey was created by the client and was sent to people who are currently looking for a job. The data was translated into English by me. Part of the content is what the client requested. The survey was conducted using Google Forms, so my job was to provide additional information, rather than just have the standard insights that Google provides by default.

The base of this case study is to see if there is any correlation between the following categories:
- "Have you previously given an asynchronous video interview to an organization?"
- "Perceived_Ease_of_Use"
- "Perceived_Usefulness" 
- "General_Attractiveness"
- "Behavioural_Intentions"
- "Prestige"

**Of course correlation does not mean causation!**

## 🔍 Analysis Methodology

The analysis follows a systematic approach to extract meaningful insights from survey data:

### Data Processing
- Data cleaning and preparation
- Variable transformation and encoding
- Generalization of dataset for analysis

### Statistical Reliability
- Cronbach's alpha reliability coefficient for each scale
- Internal consistency validation of measurement instruments

### Correlation Analysis
- Pearson correlation calculations
- P-value determination for statistical significance
- Identification of significant correlations
- Confidence intervals for correlations

### Descriptive Statistics
- Central tendency measures (mean, median, mode)
- Dispersion measures (standard deviation, variance)
- Coefficient of variation
- Confidence intervals for means
- Distribution analysis (skewness, kurtosis, IQR)

### Data Visualization
- Correlation heatmaps
- Histograms with density plots
- Box plots for outlier detection
- Violin plots for distribution comparison

## 🚀 Installation

```bash
# Clone the repository
git clone https://github.com/TsakalParis/AVIS_survey_analysis.git
cd AVIS_survey_analysis

# Install the required dependencies
pip install -r requirements.txt
```

## 📋 Requirements

The analysis requires the following Python libraries:
```
pandas
numpy
statsmodels
matplotlib
seaborn
scipy
pingouin
```

## 🖥️ Usage

To run the analysis:

```bash
python survey_analysis.py
```

## 📊 Analysis Steps

This analysis contains the following steps:

- Process dataframe
- Generalize dataframe
- Cronbach's alpha reliability coefficient
- Finding Correlations
- Function to calculate p-value from pearson correlation table
- Function that filters values in dataframe based on condition
- Checking correlations statistical importance using p-value
- Displaying the important correlations
- Confidence Interval for Correlation
  - Step 1: Create functions
  - Step 2: Pass desired values
- Creating Heatmap
- Describing Data
- Coefficient of Variation
- Confidence Interval for Mean
- Median and Mode
- Skewness
- IQR
- Kurtosis
- Data Visualization
  - Histogram
  - Box Plot
  - Violin Plot

## 🔬 Technical Details

### Variable Constructs

The analysis focuses on these key constructs:

- **Perceived Ease of Use**: User-friendliness of asynchronous video interviews
- **Perceived Usefulness**: Practical benefits of the interview format
- **General Attractiveness**: Overall appeal of organizations using this format
- **Behavioral Intentions**: Future actions regarding organizations using AVIs
- **Prestige**: Perceived status of organizations using this interview format

### Statistical Methods

- **Cronbach's Alpha**: Measures internal consistency of survey items
- **Pearson Correlation**: Quantifies relationships between variables
- **Fisher's Z Transformation**: Creates confidence intervals for correlations
- **Descriptive Statistics**: Summarizes central tendency and dispersion
- **Distribution Analysis**: Examines normality and shape of data distributions

## ⚠️ Disclaimer

This analysis provides correlational evidence only. As noted in the project description, correlation does not imply causation. The findings should be interpreted with appropriate caution when making business decisions.

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

---

*Note: This analysis was conducted for academic research purposes. The survey was created by the client, and the data was translated into English for analysis.*
