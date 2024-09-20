# 🍽️ Restaurant_Tips_Analysis

![Alt text](https://raw.githubusercontent.com/NgaLam1703/Restaurant_Tips_Analysis/refs/heads/main/download.jpg)

This project aims to use the restaurant tips dataset to practice creating composition plots and visualizations. We will examine the relationship between different variables and the tips given.

The dataset consists of information from 244 restaurant bills, collected in the US in 1987.

It includes details about the tips given to restaurant staff, such as the total bill, tip amount, gender of the person paying, smoking status, day of the week, time of day, and party size.

## 👣 The First Steps

### 📥 Data import
First, let's import the needed libraries: Pandas & Matplotlib.

```
import pandas as pd
import matplotlib.pyplot as plt
```
Then load data from the following link: https://raw.githubusercontent.com/RusAbk/sca_datasets/main/tips.csv

```
df = pd.read_csv('https://raw.githubusercontent.com/RusAbk/sca_datasets/main/tips.csv')
```

### 🔍 Data exploration
**Test sample**
Let's take a look at the first 5 rows to be sure, that data is loaded properly:
```
df.head(5)
```

**Column types checking**
**Ooops... 🤔**
**Basic descriptive statistics**
## 💸 Tip value influencers
### 🚬 Do people who smoke give more tips?
**Separate smokers and non-smokers**
**Compare their measures of central tendency**
### 🌏 Whole dataset
### 🚬 Smokers
### 🚭 Non-smokers
### 📝 Conclusion
**Insights based on measures of central tendency comparison:**
## Look at histograms
### 🌏 Whole dataset tips histogram
### 🚬 Smokers tips histogram
### 🚭 Non-smokers tips histogram
### ⭐ Extra-task with a higher difficulty
### 📝 Conclusion
**Insights based on distribution comparison:**
## 👨👩 Do males give more tips?
### Male tips compare
### Female tips compare
### 📝 Conclusion
**Insights based on measures of central tendency comparison:**
## Look at histograms
### 🌏 Whole dataset tips histogram
### Male tips histogram
### Female tips histogram
### ⭐ Extra-task with a higher difficulty
### 📝 Conclusion
**Insights based on distribution comparison:**
## 📆 Do weekends bring more tips?
### Separate weekdays and weekends
### Average tips for weekdays and weekends
**Insights based on measures of central tendency comparison:**
## Look at histograms
### 🌏 Whole dataset tips histogram
### Weekend tips histogram
### Weekday tips histogram
### ⭐ Extra-task with a higher difficulty
### 📝 Conclusion
**Insights based on distribution comparison:**
## 🕑 Do dinners bring more tips?
### Compare their measures of central tendency
### Dinner
### Lunch
### 📝 Conclusion
**Insights based on distribution comparison:**
## Look at histograms
### 🌏 Whole dataset tips histogram
### Dinner tips histogram
### Lunch tips histogram
### ⭐ Extra-task with a higher difficulty
### 📝 Conclusion
## Insights










