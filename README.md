# 📊 **Music & Mental Health Analysis**

🔗 **Interactive Tableau Dashboard:** [View Here](https://public.tableau.com/shared/XHWXR6YX4?:display_count=n&:origin=viz_share_link)

---

### 🎯 ***Project Overview***
This project explores the impact of listening to music while working or studying on mental health. Using the **MxMH Survey Results** dataset from [Kaggle](https://www.kaggle.com/datasets/catherinerasgaitis/mxmh-survey-results), we analyze whether music contributes positively or negatively to mental well-being.

---

### 📌 ***Key Objectives***
- ✅ Determine if listening to music while working/studying is associated with **better** mental health.
- ✅ Use **statistical analysis** to check if the observed differences are **statistically significant**.
- ✅ Provide insights into how music affects **anxiety, depression, insomnia, and OCD**.

---

### 🛠 ***Technologies & Tools Used***
- 🐍 **Python** (`pandas`, `numpy`, `scipy`, `seaborn`, `matplotlib`)
- 📒 **Jupyter Notebook** for exploratory data analysis
- 📊 **Tableau Public** for data visualization
- 📈 **Statistical Test:** Independent **t-test** (Welch’s t-test)

---

### 📊 ***Statistical Analysis***
To determine if there is a significant difference in mental health scores between people who **listen to music while working/studying** and those who **do not**, we performed an **independent t-test**:

- **t-test value:** `1.99`
- **p-value:** `0.048`

#### 📌 ***Interpretation:***
- Since **p < 0.05**, the difference is **statistically significant**.
- Contrary to initial expectations, people who listen to music while working/studying tend to report **better mental health** (*lower anxiety, depression, insomnia, and OCD scores*) than those who do not.
- This suggests that **music could have a positive effect on mental well-being** by reducing stress and improving focus.
- **Note:** This was an **observational study**, *not a controlled A/B test*, as participants were *not randomly assigned* to groups.

---

### 📈 ***Key Insights***
✔️ **Music is linked to better mental health** – those who listen to music while working/studying report **lower levels of anxiety, depression, insomnia, and OCD** compared to those who do not.  
✔️ **Younger individuals are more likely to listen to music** while working or studying, and they tend to have **better mental well-being scores** when they do.  
✔️ **Statistical analysis confirms a significant difference**, supporting the idea that listening to music could be beneficial in managing stress and improving focus.  
