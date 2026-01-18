# AI Website Copy Generator for Local Businesses
**Created by:** [M.Aniruddha](https://www.linkedin.com/in/aniruddha-mattam/)
**Submission for:** Future Interns Program (Prompt Engineering Task 1)

## 📌 Project Overview
This project demonstrates a structured "Prompt System" designed to generate high-conversion website copy for local businesses. Instead of generic one-shot prompts, I engineered a **Modular System** that separates logic (Marketing Strategy) from data (Client Profile).

## 🏢 The Client: Qahwa Commons
For this task, I selected a realistic local business scenario:
* **Business Name:** Qahwa Commons
* **Type:** 20/7 Premium Study Cafe
* **Location:** Opposite IIT Delhi, Hauz Khas
* **Target Audience:** IIT Students, Research Scholars, and Professors.
* **Key Problem:** Students need a safe, focused space open late at night (past 2 AM) with nutritious food.

## ⚙️ The Prompt Logic (How it Works)
I designed a **Universal System Prompt** that operates in three phases:
1.  **Context Injection:** The user inputs the business details (Name, USP, Audience) into a variable block.
2.  **Strategic Analysis:** The AI is forced to analyze the "User Pain Points" before writing a single word.
3.  **Constraint Enforcement:** Negative constraints prevent generic AI phrases (e.g., "unlock potential") and ensure specific tone matching.

## 🛠️ Tools Used
* **Engine:** ChatGPT (GPT-5o / 5.2 Model) and Google Gemini 3 Pro
* **Framework:** Markdown for structure
* **Methodology:** Chain-of-Thought Reasoning & Modular Prompting

## 📂 File Structure
* `prompts.md`: Contains the reusable System Prompt and Modules.
* `website_copy.md`: The final generated content for Qahwa Commons.
