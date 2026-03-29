# Gender Wage Gap under COVID-19

## Overview
This project examines how the COVID-19 pandemic affected the gender wage gap in the United States. Using a difference-in-differences (DID) framework, the analysis compares wage outcomes before (2018–2019) and after (2021–2022) the pandemic.

The study focuses on prime-age, full-time workers to isolate wage differences among those who remained employed.

---

## Key Findings

- Women earn significantly lower wages than men, even after controlling for observable characteristics  
- Average wages increased after COVID-19 for both men and women  
- The gender wage gap did **not significantly change** after the pandemic  
- This suggests that structural inequalities persisted despite large economic shocks  

---

## Methodology

- Data Source: American Community Survey (ACS) via IPUMS  
- Sample: Ages 25–39, full-time workers, positive wage income  
- Model: Difference-in-Differences (DID)

Regression specification:

ln(wage) = β₀ + β₁ Female + β₂ Post + β₃ (Female × Post) + Controls + ε

- Controls include: age, education, race, occupation, industry, and state fixed effects  

---
## Visualization

![Wage Trend](wage_trend.png)

This figure shows trends in average hourly wages for men and women from 2018 to 2022. While wages increased for both groups over time, the gender wage gap remained relatively stable. Regression results confirm that this change is not statistically significant.

---
## Interpretation

While the pandemic significantly disrupted labor markets, it did not alter the relative wage gap between men and women among employed workers.

The increase in average wages may reflect:
- labor market recovery
- inflationary pressure
- compositional effects (exit of lower-wage workers)

---

## Limitations

- Focuses only on employed individuals (selection bias)
- Does not capture labor force exit
- Short-term analysis (long-term effects unknown)

---

## Tools Used

- Python (data cleaning & analysis)
- Stata (regression analysis)
- Tableau (visualization, optional if used)

---

## Author

Risa Kuriyama  
UC San Diego | Economics  
Interested in social epidemiology and data analysis

---

# COVID-19による男女賃金格差の変化

## 概要
本プロジェクトでは、COVID-19が米国における男女賃金格差に与えた影響を分析した。差の差分法（DID）を用い、パンデミック前（2018–2019）と後（2021–2022）の賃金を比較した。

---

## 主な結果

- 女性は男性より有意に低い賃金を得ている  
- パンデミック後、男女ともに平均賃金は上昇  
- 男女賃金格差は統計的に有意な変化なし  
- 構造的な不平等は短期的ショックでは変わりにくい  

---

## 手法

- データ：ACS（IPUMS）  
- 対象：25〜39歳、フルタイム労働者  
- モデル：差の差分法（DID）

---

## 解釈

パンデミックは労働市場に大きな影響を与えたが、雇用を維持した人々の間では男女の賃金格差は変化しなかった。

---

## ツール

- Python  
- Stata  
- Tableau
