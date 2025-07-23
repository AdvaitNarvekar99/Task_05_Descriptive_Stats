# 🧪 Task_05_Descriptive_Stats

**Researcher**: Advait Narvekar  
**Institution**: Syracuse University  
**Reporting Period**: July 2025 – Research Phase 1  
**Dataset**: 2021 Syracuse University Women’s Lacrosse Season Stats  
**LLM Evaluated**: ChatGPT (GPT-4)  
**Submission Email**: jrstrome@syr.edu  

---

## 📘 Overview

This repository contains the descriptive statistics analysis and natural language reasoning task using a real-world dataset. The research evaluates the capabilities of a **Large Language Model (LLM)**—specifically ChatGPT—to interpret sports performance data and derive actionable insights, simulating a coach-level decision-making scenario.

The dataset is **NOT INCLUDED** in this repository as per instructions.

---

## 🎯 Objective

The primary goal of this task is to answer the research question:

> **“Can a Large Language Model (LLM) reliably interpret structured sports data and provide meaningful, explainable recommendations to improve team performance?”**

To answer this, I used the official 2021 Syracuse Women’s Lacrosse dataset and tested ChatGPT’s ability to:
- 🔍 Retrieve accurate statistics
- 📊 Summarize and explain descriptive metrics
- 🧠 Provide strategic reasoning (e.g., whether to improve offense or defense)
- 💬 Handle complex natural language queries
- ⚠ Recognize and report its own limitations

---

## 🔍 Methodology

1. **Dataset Selection**  
   I selected the 2021 SU Women’s Lacrosse dataset because:
   - It’s compact but rich in statistics  
   - It includes both team and player-level data  
   - It reflects real-world sports scenarios where decisions impact game outcomes  

2. **Prompt Design**  
   I designed both factual and strategic prompts, such as:
   - “Who was the top scorer?”
   - “What’s the draw control rate?”
   - “Should the coach focus on offense or defense to win 2 more games?”

   **Justification**: This mixed difficulty tests both **data retrieval** and **inference skills** of the LLM.

3. **Evaluation Criteria**  
   Each response was reviewed based on:
   - ✅ **Accuracy**  
   - ✅ **Reasoning**  
   - ✅ **Contextual understanding**  
   - ✅ **Explanatory power**  

4. **Visualization Support**  
   Python scripts were written to generate key visualizations such as:
   - Top scorers' bar chart
   - Team vs opponent goal trends by half

   These helped **verify claims made by the LLM** and **support research reporting**.

---

## 🔎 Research Constraints

- **No season-over-season data**: The dataset is from one year only. This made it difficult to determine trends like “most improved player” without additional context. The LLM acknowledged this constraint and pivoted to identifying breakout players instead.
  
- **No qualitative variables**: Player morale, injuries, or opponent strategy were not part of the dataset. Hence, **LLM recommendations rely solely on quantitative indicators**.

- **LLM reasoning is prompt-dependent**: For high-quality results, I had to **refine prompts iteratively**, a key aspect of **prompt engineering**. Poorly worded prompts often returned vague or incorrect answers.

- **Visualizations not natively produced by LLM**: Although ChatGPT explained what to visualize, **I had to write the Python code manually** to produce supporting graphs.

---

## 📈 Key Results & Findings

| Question Type                | Accuracy | LLM Behavior |
|-----------------------------|----------|--------------|
| Simple Stats (e.g. top scorer) | ✅ 100%  | Immediate correct response |
| Descriptive Summaries       | ✅ 100%  | Aggregated and ranked values properly |
| Strategy Recommendation     | ✅ High  | Justified focus on defense using goal/foul/save metrics |
| Improvement Analysis        | ⚠ Partial | Correctly acknowledged lack of data |
| Visual Insight Explanation  | ✅       | Recommended useful plots, but could not generate directly |

---

## 🧠 Final Recommendation by LLM

> **Focus on defense to improve season outcome.**  
> Syracuse already had a top-tier offense. However, data shows they allowed 57 free-position goals and had a modest save percentage (43.5%). Improving defense—especially reducing fouls and increasing goalie efficiency—could directly convert losses to wins.

**Suggested Player to Coach**:  
- 🧤 **Asa Goldstock** (Goalie) – Improve save percentage  
- 🛡️ **Sarah Cooper** (Defense) – Reinforce ability to cause turnovers  
- 🔁 **Ella Simkins** – Critical for draw control dominance

---

## 💡 Reflection

This project demonstrated that LLMs like ChatGPT:
- Can **reliably interpret structured statistics**  
- Can reason when asked strategic, coach-like questions  
- Struggle with **comparative metrics** when data is limited  
- Require **well-formed prompts** and visual aids for nuanced interpretation  

With proper constraints, LLMs can be powerful assistants in performance analysis—not just for sports, but for any structured, metric-heavy domain.

---

## 📨 Submission Instructions

- 📤 Do **NOT upload the dataset** to GitHub  
- 📧 Email this repository link to: `jrstrome@syr.edu`  
- 🕒 Submit by July 31st for Period 1 Reporting  
- 🧾 Complete the **OPT Progress Survey** here:  
  👉 https://syracuseuniversity.qualtrics.com/jfe/form/SV_cDgnzM695AMx8d8

---