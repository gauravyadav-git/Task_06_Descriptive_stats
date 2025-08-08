# Research Task 06 – Descriptive Statistics with Grouping (Premier League Dataset)

## 📌 Overview
This project is **Research Task 06**, which builds upon the work completed in **Research Task 05**.  
In Task 05, I:
- Used the Premier League 2022–23 dataset (first 10 rows only) to create descriptive statistics without grouping.
- Generated 10 natural language questions for an LLM (ChatGPT) to answer.
- Compared LLM responses with my Python-generated descriptive statistics.
- Wrote Python queries for questions that could not be directly answered from the summary.

**Task 06** continues the analysis, this time **grouping the dataset by stadium** to generate more granular insights.

---

## 🏟 Task 06 Objective
- Perform descriptive statistics **grouped by stadium**.
- Create a **pivot-style summary table** that is more concise and easier to read than the raw grouped output.
- Limit visualizations to specific columns to focus the analysis:
  - `Goals Home`
  - `Away Goals`
  - `home_possessions`
  - `away_possessions`
  - `home_chances`
  - `away_chances`
- Draft 10 new natural language prompts for the LLM, focused on stadium-level insights.
- Write Python scripts to answer questions whose answers cannot be directly read from the grouped summary.

---

## 📂 Repository Contents

| File Name                                         | Description                                                                 |
| **Premier_League**                                | Excel dataset of the 2022–23 Premier League season.                         |
| **Premier_League_bar_Away_Goals.png**             | Bar chart of away goals by stadium.                                         |
| **Premier_League_bar_away_possessions.png**       | Bar chart of away possessions by stadium.                                   |
| **Premier_League_bar_Goals_Home.png**             | Bar chart of home goals by stadium.                                         |
| **Premier_League_bar_home_possessions.png**       | Bar chart of home possessions by stadium.                                   |
| **Premier_League_bar_home_chances.png**           | Bar chart of home chances by stadium.                                       |
| **Premier_League_bar_away_chances.png**           | Bar chart of away chances by stadium.                                       |
| **Prompt_log.txt**                                | Record of LLM prompts used in Task 06.                                      |
| **qa_results.xlsx**                               | Python-generated results for questions that require extra computation.      |
| **questions.txt**                                 | The 10 Questions for Task 06.                                               |
| **summary_grouped_by_stadium_Premier_League.xls** | Stadium-level descriptive statistics (pivot-style summary).                 |
| **Task_06_descriptive_stats.ipynb**               | Jupyter Notebook containing all Python code for Task 06.                    |

---

## ⚙️ How It Works
1. **Data Loading & Cleaning**
   - The dataset is read in full (unlike Task 05 where only the first 10 rows were used).
   - Missing values are handled.
   
2. **Grouping & Summary**
   - Data is grouped by `stadium`.
   - Summary statistics (mean, min, max, standard deviation, etc.) are computed for relevant numeric columns.
   - Output is saved as an easy-to-read pivot-style summary.

3. **Visualization**
   - Bar charts generated only for the six selected numeric columns.
   - Plots saved to PNG files.

4. **LLM Questioning**
   - 10 prompts created for ChatGPT to answer.
   - Python scripts created for non-summary questions.

---

## 📊 Key Learning Outcomes
This task helped me:
- Work with grouped descriptive statistics.
- Produce more readable aggregated summaries.
- Create targeted visualizations instead of plotting every numeric column.
- Compare AI-generated insights with Python-calculated results.

---

## 🔗 Continuation from Task 05
Task 06 expands upon Task 05 by introducing grouping logic and more targeted visualizations, providing deeper, stadium-specific insights.

---
