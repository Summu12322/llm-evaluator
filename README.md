# LLM Response Evaluator

An AI-powered web application that evaluates the quality of LLM (Large Language Model) responses using structured criteria — built for Ethara AI's Round 1 assessment.

## Live Demo
🔗 [https://Summu12322.github.io/llm-evaluator](https://Summu12322.github.io/llm-evaluator)

## About the Project
Ethara AI works on RLHF (Reinforcement Learning from Human Feedback) and prompt-response evaluation. This app directly mirrors that workflow by allowing users to evaluate AI-generated responses on multiple quality dimensions.

## Features
- 📝 Input any prompt and AI response for evaluation
- 📊 Multi-criteria scoring: Accuracy, Relevance, Clarity, Coherence, Completeness, Safety/Bias
- 🤖 Real AI-powered evaluation using Gemini API
- ✅ Verdict system: Pass / Needs Review / Fail
- 💡 Detailed feedback and improvement suggestions
- 🕑 Evaluation history saved in browser
- 📤 Export results as JSON

## Tech Stack
- **Frontend:** HTML, CSS, JavaScript (Vanilla)
- **AI API:** Google Gemini API
- **Deployment:** GitHub Pages

## How to Run Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/Summu12322/llm-evaluator.git
   ```
2. Open `index.html` directly in your browser — no installation needed
3. Get a free Gemini API key from [aistudio.google.com/app/apikey](https://aistudio.google.com/app/apikey)
4. Paste the key in the API Key field and start evaluating

## How It Works
1. User enters a **Prompt** (what was asked) and an **AI Response** (what was answered)
2. User selects evaluation criteria
3. App sends the input to Gemini AI with a structured evaluation prompt
4. Gemini returns scores (0-10) for each criterion
5. App displays overall score, verdict, detailed feedback, and improvement suggestions

## Evaluation Criteria
| Criterion | Description |
|-----------|-------------|
| Accuracy | Is the information factually correct? |
| Relevance | Does the response address the prompt? |
| Clarity | Is the response clear and easy to understand? |
| Coherence | Is the response logically structured? |
| Completeness | Does the response fully answer the question? |
| Safety/Bias | Is the response free from harmful or biased content? |

## Why This Project
This project is directly inspired by Ethara AI's core work in LLM post-training, specifically prompt-response evaluation, RLHF, and quality benchmarking — the same workflows described in the job description.

## Author
Summu12322 — Ethara AI Campus Placement Drive 2026
