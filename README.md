# 🏠 The Effect of Price Salience on Willingness to Rent in the Boston Housing Market

## 📜 Overview

This project explores how price salience affects consumers' willingness to rent and their perception of fairness in rental prices in Boston. Using a controlled experiment with survey data, we investigate behavioral economics principles to uncover actionable insights for real estate stakeholders.

---

## 📚 Table of Contents

1. [Introduction](#-introduction)
2. [Methodology](#-methodology)
3. [Data Analysis](#-data-analysis)
4. [Key Findings](#-key-findings)
5. [Limitations and Assumptions](#-limitations-and-assumptions)
6. [Conclusion](#-conclusion)

---

## 🔍 Introduction

Price salience plays a crucial role in consumer decision-making, especially in complex markets like housing. This study analyzes the effects of price presentation (transparent pricing vs. holistic pricing) on:
- **Willingness to rent**
- **Perceived price fairness**

Our hypothesis: Less salient prices would positively influence willingness to rent and fairness perception.

---

## ⚙️ Methodology

### Survey Design:
- Distributed via **Qualtrics** to a random sample of U.S. residents.
- Participants reviewed real Boston apartment listings with price and amenity details.
- Two groups:
  1. **Treatment Group**: Saw rent prices broken down with additional fees.
  2. **Control Group**: Saw an all-inclusive price.

### Key Metrics:
1. **Willingness to Rent** (Likert scale: 1-5)
2. **Price Perception** (Fairly priced, underpriced, or overpriced)
3. **Suggested Price** (Optional for respondents perceiving the price as unfair)

---

## 📊 Data Analysis

### Tools and Techniques:
- **Data Processing**: Python (Pandas, NumPy)
- **Statistical Methods**: OLS regression, Fixed effects modeling, ATE and CATE calculations
- **Visualizations**: Matplotlib, Seaborn

### Statistical Power:
- Sample size: 79 respondents
- Statistical power for key metrics: 31%-46% (below ideal thresholds)
- Recommended sample size for 80% power: ~1100 participants

---

## ✨ Key Findings

1. **Willingness to Rent (ATE: -0.12)**  
   - Treatment group participants were less likely to rent than the control group.  
   - Gender difference: Men (-0.31) were less likely to rent under the treatment, while women (+0.08) were slightly more likely.

2. **Price Perception (ATE: +0.05)**  
   - Treatment group participants perceived prices as slightly more unfair.  

3. **Suggested Prices (ATE: -$54)**  
   - Treatment group participants suggested prices $54 lower than those in the control group.

4. **Location-Based Insights (CATE)**  
   - Boston residents: -0.24 willingness to rent in the treatment group.  
   - Non-Boston residents: +0.08 willingness to rent in the treatment group.

---

## ⚠️ Limitations and Assumptions

1. **Sample Size**:  
   - Small sample (n=79) limits statistical power.
   - High variance from spam responses.

2. **Design Constraints**:  
   - Treatment presented as percentages; including dollar amounts could enhance insights.

3. **Biases**:
   - Hypothetical bias: Survey responses may not reflect real-world behavior.
   - Information bias: Lack of location details may have influenced perceived value.

4. **Generalizability**:  
   - Findings are specific to Boston and may not apply to other markets.

---

## ✅ Conclusion

While the results did not support the hypothesis, they highlight:
- **Gender and location differences** in price sensitivity.
- The importance of **transparent and salient pricing** in influencing renter behavior.

Future research should focus on:
1. Larger, more diverse samples.
2. Refined experimental designs to isolate key variables.

---
