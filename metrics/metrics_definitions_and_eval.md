# 🧠 Prompts and Answers: Custom Metrics & Evaluation – Phase 2

This document outlines the custom metrics designed for Phase 2 of Research Task 5 and evaluates how well the LLM understood and used these metrics in its responses.

---

## ❓ Q1: What is Draw Control Efficiency and how did the LLM interpret it?

**Metric**:  
`Draw Control Efficiency (DCE) = Total Draw Controls / Games Played`

**LLM Response**: Ella Simkins led with 88 draw controls in 21 games, resulting in a DCE of over 4 per game. The LLM correctly emphasized the importance of draw controls in possession and recommended further training for Simkins.

**Evaluation**: ✅ The LLM accurately applied the metric and linked it to game strategy.

---

## ❓ Q2: How did the LLM handle volatility analysis using the Game Volatility Index?

**Metric**:  
`Game Volatility Index (GVI) = |Syracuse Score – Opponent Score|`

**LLM Response**: The LLM correctly identified high-volatility games such as the 6–17 loss to UNC and the 18–6 win over Loyola. It noted that these extremes reflect inconsistent performance.

**Evaluation**: ✅ Strong. The LLM understood the metric and provided relevant game context.

---

## ❓ Q3: How did the LLM interpret Free-Position Goal impact via Foul Cost Rate?

**Metric**:  
`Foul Cost Rate (FCR) = Free-Position Goals Allowed / Total Goals Allowed`

**LLM Response**: Syracuse allowed 57 free-position goals out of 209 total (FCR ≈ 27.3%). The LLM flagged this as a key defensive weakness and recommended reducing fouls in scoring zones.

**Evaluation**: ✅ Excellent reasoning with clear application of the metric.

---

## ❓ Q4: Did the LLM apply the Defensive Influence Index correctly?

**Metric**:  
`Defensive Influence Index (DII) = (Caused Turnovers + Ground Balls) / Games Played`

**LLM Response**: Sarah Cooper led with 33 CTs and 48 GBs over 21 games. The LLM recognized her high DII and labeled her as the team’s defensive anchor.

**Evaluation**: ✅ Accurate. The LLM interpreted and applied the composite metric as expected.

---

## ❓ Q5: Was the Balanced Impact Score understood?

**Metric**:  
`Balanced Impact Score (BIS) = (Goals + Assists + Ground Balls + Caused Turnovers) / Games Played`

**LLM Response**: Emma Tyrrell scored 42 goals, 16 assists, 43 GBs, and 23 CTs in 21 games. The LLM identified her as a versatile, high-impact player on both ends.

**Evaluation**: ✅ Fully correct and well supported by stats.

---

## ❓ Q6: How did the LLM deal with the Clutch Performance Index?

**Metric**:  
`Clutch Performance Index (CPI) = Total Points in Games with Margin ≤ 2`

**LLM Response**: The LLM could not calculate CPI directly but suggested Meaghan Tyrrell and Emma Ward based on known tight matches and their season stats. It struggled to apply filtering logic on its own.

**Evaluation**: ⚠ Partial. Good guesses but lacked metric-level filtering.

---