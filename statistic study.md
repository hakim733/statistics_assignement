
**Course:** MA660E  
**Instructor:** Dr. Yuanji Cheng  
**Lab Assignment:** Quantitative Data Analysis  
**Deadline:** 2024-10-27

---

## Part One: Analysis Based on Job Survey Data

In this part, we will use job survey data from the book: _Quantitative Data Analysis with SPSS_. The data is provided in the SPSS file `jss13_ht22.sav` or as an Excel file `Data_source.xlsx`. Below is a brief explanation of the variables available in the dataset:

### Variables:
- `ethnicgp`: Ethnic group (1 = White, 2 = Asian, 3 = West Indian, 4 = African, 5 = Other)
- `gender`: Gender (1 = Male, 2 = Female)
- `income`: Gross annual income before tax (in £1000)
- `age`: Age in years
- `years`: Number of years working at the firm
- `commit`: Organizational commitment (Scale: 1 to 5)
- `satis`: Job satisfaction (Scale: 1 to 5)
- `autonom`: Job autonomy (Scale: 1 to 5)
- `routine`: Job routine (Scale: 1 to 5)
- `attend`: Attendance at meetings (1 = Yes, 2 = No)
- `skill`: Rated skill (1 = Unskilled, 2 = Semi-skilled, 3 = Fairly skilled, 4 = Highly skilled)
- `prody`: Rated productivity (1 = Very poor, 2 = Poor, 3 = Average, 4 = Good, 5 = Very good)
- `qual`: Rated quality (1 = Very poor, 2 = Poor, 3 = Average, 4 = Good, 5 = Very good)
- `absence`: Days of being absent in the last 12 months

---

### Exercise 1.1
a) **Bar Chart (Gender)** and **Pie Diagram (Ethnic Group)**:
- Create a bar chart for `gender`.
- Create a pie diagram for `ethnicgp`.

b) **Five-Number Summary and Box Plot of Age**:
- Summarize `age` (min, max, median, Q1, Q3) and plot a box plot.

c) **Mean, Standard Deviation, and Histogram of Income**:
- Calculate the mean and standard deviation of `income`, and generate a histogram.

---

### Exercise 1.2: Relationship between Income and Absence
a) **Scatter Plot**:
- Visualize the relationship between `income` and `absence` using a scatter plot.

b) **Simple Linear Regression**:
- Perform a linear regression where `income` is the dependent variable and `absence` is the independent variable. Report the determination coefficient (R²).

---

### Exercise 1.3: Multiple Regression Model for Job Satisfaction
a) **Impact of Variables**:
- Study the impact of the independent variables (`commit`, `autonom`, `income`, `skill`, `qual`, `age`, `years`) on the dependent variable `satis`.

b) **Simplified Model**:
- Remove non-significant variables and report the simplified multiple regression model.

---

### Exercise 1.4: Confidence Intervals
- Calculate the confidence interval for job satisfaction.
- Calculate the confidence interval for the difference in job satisfaction between men and women.

---

### Exercise 1.5: Mann-Whitney-Wilcoxon Test
- Perform the Mann-Whitney-Wilcoxon test to check for significance in skill levels between men and women. Compare this with the confidence interval for the difference.

---

### Exercise 1.6: Kruskal-Wallis Test vs. ANOVA
- Perform a Kruskal-Wallis test to check for significant differences in `absence` among different ethnic groups.
- Compare the result with a One-Way ANOVA analysis.

---

### Exercise 1.7: Re-code Income into Classes
- Re-code `income` into `income_class` based on limits:  
  - Low income: [Min, Q1]  
  - Middle income: (Q1, Q3]  
  - High income: (Q3, Max]  

---

## Part Two: Your Own Data Analysis

In this part, you will work with your own dataset and have the freedom to choose the topic.

---

### Exercise 2.1: Descriptive Statistics
- Perform descriptive statistics analysis for at least two qualitative and two quantitative variables.

---

### Exercise 2.2: Confidence Interval Analysis
- Calculate the confidence interval for one quantitative variable.
- Calculate the confidence interval for the difference between two groups.

---

### Exercise 2.3: T-test or ANOVA
- Perform a T-test to check if there is a significant difference in characteristics between two groups, or conduct an ANOVA to check if all groups have the same mean value for a characteristic.

---

### Exercise 2.4: Non-parametric Test
- Conduct a non-parametric test for the same variable as in Exercise 2.3 and compare the result with the ANOVA conclusion.

---

### Exercise 2.5: Correlation Analysis
- Perform a correlation analysis. Identify the strongest correlation and any statistically non-significant relationships.

---

### Exercise 2.6: Multiple Regression
- Conduct a multiple regression analysis.

If you're interested in COVID-19 data, you may find it from the following sources:
- [WHO COVID-19 Dashboard](https://covid19.who.int/)
- [Johns Hopkins University Coronavirus Resource Center](https://coronavirus.jhu.edu/)

---

## Lab Report Guidelines

You may work individually or in a team of up to two students.

**General Rules for the Lab Report**:
- Please follow the template provided.
- For each exercise, include both tables/figures and the associated interpretations. Submitting only a table or figure without interpretation will be considered incomplete.

**Deadline for Submission**:  
Submit your lab report via Canvas by **Sunday, 2024-10-27**.
