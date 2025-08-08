# 🧠 Prompts and Answers: LLM Failure Summary – Phase 2

This document outlines instances where the LLM did not fully meet expectations in reasoning, metric interpretation, or data filtering. Each section includes the question asked, the LLM’s response, and an evaluation of the shortcomings.

---

## ❓ Q1: Who was the most improved player compared to last year?

**LLM Response**: The dataset only includes single-season stats, so improvement could not be measured. However, breakout players like Emma Ward and Ella Simkins were highlighted.

**Evaluation**: ⚠ Partial. While the LLM correctly acknowledged the lack of historical data, it failed to suggest an alternative proxy (e.g., impact score per game).

---

## ❓ Q2: In games with score margin ≤ 2, who contributed the most?

**LLM Response**: Meaghan Tyrrell and Emma Ward were cited based on overall stats, without filtering for close games.

**Evaluation**: ❌ Missed. The LLM did not apply conditional logic or isolate stats within specific games. Manual analysis was required.

---

## ❓ Q3: Did high attendance influence game outcomes?

**LLM Response**: The LLM noted examples of both wins and losses with high attendance and said a correlation was possible but not conclusive.

**Evaluation**: ⚠ Partial. While the reasoning was fair, the LLM did not calculate or test the relationship quantitatively.

---

## ❓ Q4: Who performed best in high-volatility games?

**LLM Response**: The LLM listed strong overall performers like Meaghan Tyrrell but did not cross-reference their stats with volatility metrics.

**Evaluation**: ❌ Missed. The LLM lacked the ability to combine two metrics (score margin and player stats) across filtered game sets.

---

## ❓ Q5: How did the LLM handle derived metrics like Clutch Performance Index?

**LLM Response**: It guessed top performers in high-pressure games based on intuition but could not compute CPI.

**Evaluation**: ⚠ Partial. The LLM lacked the capability to simulate filtering logic needed to calculate this metric.

---

## ❓ Q6: Did the LLM ever misinterpret basic stats?

**LLM Response**: In most factual queries, the LLM was accurate. However, in rare cases, it conflated ground balls with caused turnovers.

**Evaluation**: ⚠ Minor. While mostly accurate, the LLM occasionally misattributed defensive actions to the wrong player category.

---

## ✅ Summary

| Question / Task                              | Evaluation | Issue Type             |
|----------------------------------------------|------------|-------------------------|
| Most improved player                         | ⚠ Partial  | Data limitation         |
| Performance in close games                   | ❌ Missed  | Filtering failure       |
| Attendance correlation                       | ⚠ Partial  | Lack of computation     |
| Volatility-specific performance              | ❌ Missed  | Metric crossover logic  |
| Clutch Performance Index (CPI)               | ⚠ Partial  | Custom metric handling  |
| Stat attribution accuracy                    | ⚠ Minor    | Occasional confusion    |

---