# 🧠 Prompts and Answers: Research Task 5 - Descriptive Statistics & LLM Evaluation

This document contains the prompts submitted to the LLM and its corresponding responses, as well as an evaluation of the model's performance.

---

## ❓ Q1: How many games did Syracuse play in the 2021 season?

**LLM Response**: Syracuse played a total of 21 games during the 2021 season.

**Evaluation**: ✅ Correct. This is a simple factual retrieval task, and the LLM was able to identify the number of games by summing wins and losses from the dataset summary.

---

## ❓ Q2: Who was the highest scorer on the team?

**LLM Response**: Meaghan Tyrrell led the team with 68 goals.

**Evaluation**: ✅ Accurate. The LLM correctly identified the player and also provided her total contributions when prompted (112 points = 68 goals + 44 assists).

---

## ❓ Q3: Who had the most draw controls, and why does that matter?

**LLM Response**: Ella Simkins had the most draw controls with 88. Draw controls are critical because they determine possession after each goal, which can set the tone for the game.

**Evaluation**: ✅ Correct. The LLM both extracted the correct number and provided meaningful insight into the role of draw controls.

---

## ❓ Q4: As a coach, if I wanted to win two more games next season, should I focus on offense or defense?

**LLM Response**:
- Syracuse had an excellent offense (15.14 goals/game).
- However, they allowed 57 free-position goals, and goalie save percentage was only 43.5%.
- Focusing on reducing fouls and increasing saves could lead to more wins.

**Recommendation**: Focus on **defense**, particularly goalkeeper training and reducing free-position fouls.

**Evaluation**: ✅ Strong recommendation, well-supported by data reasoning and appropriate interpretation of team weaknesses.

---

## ❓ Q5: Who was the most improved player this season?

**LLM Response**: The dataset only includes single-season data, so improvement cannot be objectively measured. However, based on performance impact, breakout players like Emma Ward (43 goals, 30 assists) and Ella Simkins (88 draw controls) stood out.

**Evaluation**: ⚠ Partial. The LLM correctly noted dataset limitations and offered reasonable alternatives by identifying high-impact performers.

---

## ❓ Q6: What kind of visualizations would help us better understand this team's performance?

**LLM Suggestions**:
- Bar chart of top scorers
- Team vs opponent goals by game half
- Goalkeeper save percentages
- Free-position goal comparisons

**Evaluation**: ✅ Insightful. While the LLM could not generate visualizations directly, it clearly described helpful charts that were implemented in Python.