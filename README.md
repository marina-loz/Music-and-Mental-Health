# 📊 Music & Mental Health Analysis

## 🎯 **Project Overview**
This project analyzes the impact of listening to music while working or studying on mental health. Using the **MxMH Survey Results** dataset from [Kaggle](https://www.kaggle.com/datasets/catherinerasgaitis/mxmh-survey-results), we explore whether music contributes positively or negatively to mental well-being.

## 📌 **Key Objectives**
- Determine if listening to music while working/studying is associated with worse mental health.
- Use **statistical analysis** to check if the observed differences are **statistically significant**.
- Provide insights into how music affects **anxiety, depression, insomnia, and OCD**.

## 🛠 **Technologies & Tools Used**
- **Python** (`pandas`, `numpy`, `scipy`, `seaborn`, `matplotlib`)
- **Jupyter Notebook** for exploratory data analysis
- **Statistical Test:** Independent **t-test** (Welch’s t-test)

## 📊 **Statistical Analysis**
To determine if there is a significant difference in mental health scores between people who **listen to music while working/studying** and those who **do not**, we performed an **independent t-test**:

- **t-test value:** `1.99`
- **p-value:** `0.048`

📌 **Interpretation:**
- Since **p < 0.05**, the difference is **statistically significant**.
- This suggests that people who listen to music while working/studying tend to report **worse mental health** (*higher anxiety, depression, insomnia, and OCD scores*) than those who do not.
- **Note:** This was an **observational study**, *not a controlled A/B test*, as participants were *not randomly assigned* to groups.
