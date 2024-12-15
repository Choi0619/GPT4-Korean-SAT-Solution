# 🧠 GPT-4 Korean SAT Solution

This repository demonstrates the use of **GPT-4** to solve Korean SAT (K-SAT) language problems, a task that challenges the model's reasoning and language understanding skills in a non-English context. The project uses **prompt engineering** and **OpenAI's GPT-4 API** to achieve high accuracy in answering complex questions.

---

## 📖 Project Overview

- **Dataset**: The K-SAT dataset (`2023_11_KICE.json`) was sourced from the [NomaDamas/KICE_slayer_AI_Korean](https://github.com/NomaDamas/KICE_slayer_AI_Korean) GitHub repository.
- **Task**: Solve multiple-choice Korean SAT questions by analyzing the given passage and selecting the correct answer.
- **Accuracy Achieved**: The model achieved **82.22% accuracy**, correctly answering 37 out of 45 questions.

---

## 🛠️ Skills and Tools Used

- **OpenAI GPT-4 API** for advanced language reasoning.
- **Python** and **JSON** for data processing and integration.
- **Prompt Engineering** to optimize interaction with GPT-4.
- **Colab Notebook Environment** for execution and experimentation.

---

## 🏁 How It Works

1. **Data Preparation**:
   - The K-SAT dataset is loaded directly from GitHub.
   - Each problem consists of a passage, a question, and multiple-choice answers.

2. **Prediction Function**:
   - A `prediction()` function formats the question and answers for GPT-4.
   - The function queries the model and evaluates the predicted answer.

3. **Evaluation**:
   - The model's performance is calculated programmatically.
   - The accuracy is determined by comparing GPT-4's predictions with the actual answers.

---

## 🚀 Getting Started

To replicate this project:
1. Install required libraries:
```bash
pip install datasets openai
```
2. Set up your **OpenAI API Key**.
3. Run the provided notebook step-by-step to evaluate GPT-4's performance.

---

## 📊 Results

The model demonstrated strong capabilities in non-English reasoning tasks:
- **82.22% Accuracy** on K-SAT questions.
- Highlights GPT-4's adaptability to diverse linguistic tasks.

---

## 🎓 Key Insight

This project showcases how **GPT-4** can effectively solve advanced reasoning tasks in non-English languages like Korean, paving the way for broader multilingual applications.
