# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

## Scenario:
You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

Accuracy

Coherence

Simplicity

Speed

User experience

## Algorithm

# 1. Task Context

Content Team Use Case: Summarizing research papers into short, student-friendly notes.

Article Used: A 500-word technical article on Blockchain basics (same input for all platforms for fairness).

Audience: Undergraduate students (need clarity + simplicity).

Goal Output: Concise summary (~100 words).

# 2. Prompting Techniques

Zero-shot Prompting

Prompt: “Summarize the following 500-word article on the basics of blockchain technology for undergraduate students in ~100 words.”

Few-shot Prompting

Provide 2–3 examples of input text + good student-level summaries before asking for the real task.

Chain-of-Thought Prompting

Prompt: “Think step by step: identify key points in the article, organize them logically, then write a ~100-word summary suitable for undergraduates.”

Role-based Prompting

Prompt: “You are a university professor writing study notes. Summarize the following 500-word article on blockchain technology in ~100 words for first-year undergraduates.”

# 3. Platforms to Compare

ChatGPT (OpenAI, GPT-5)

Google Gemini

Anthropic Claude

GitHub Copilot Chat

(Optionally, you could add Perplexity AI or Llama-based assistants if you want open-source comparison.)

# 4. Evaluation Metrics

You’ll assess each platform + prompt combination using 4 criteria:

Accuracy → Does the summary capture correct blockchain concepts? (Scale 1–5)

Coherence → Is the flow logical and readable? (Scale 1–5)

Simplicity → Is it easy for undergraduates to understand? (Scale 1–5)

Speed & UX → Response time + ease of prompting (qualitative notes).

(Optional: Use two independent reviewers to reduce bias.)

# 5. Experimental Procedure

Select your 500-word blockchain article (same text input for all).

Prepare 4 prompts (one per technique).

Run each prompt across 4 platforms (16 experiments total).

Record:

Summary output

Time taken

Notes on UX (ease of use, formatting, need for retries).

Rate each output (1–5) for Accuracy, Coherence, Simplicity.

Compare averages across techniques & platforms.

# 6. Reporting

Your final report/table could look like this:

Platform	Prompting Technique	Accuracy (1–5)	Coherence (1–5)	Simplicity (1–5)	Speed (secs)	Notes
ChatGPT	Zero-shot	4.5	4.5	4.0	2s	Very fluent
Gemini	Few-shot	4.0	4.5	4.2	3s	Examples improved clarity
Claude	Chain-of-thought	4.7	4.8	4.3	4s	Step-by-step reasoning
Copilot	Role-based	3.8	4.0	4.5	2s	Simplified well

(Hypothetical numbers—your actual test will fill them in.)

# 7. Outcome

Identify best combination (e.g., Claude + CoT, or ChatGPT + Role-based).

Provide recommendations for your content team:

Which platform to use?

Which prompting style consistently gives the most accurate, simple summaries?

Trade-offs (e.g., Claude slower but more accurate, Copilot faster but less accurate.

## Result

<img width="1020" height="739" alt="Screenshot 2025-08-30 140926" src="https://github.com/user-attachments/assets/846a0326-53d1-4f0e-b820-12247881433d" />


Therefore 

For educational summarization tasks, role-based and chain-of-thought prompting consistently outperform zero/few-shot.

Claude excels at structured, accurate summaries but is slower.

ChatGPT provides the most natural, student-friendly output.

Copilot is best for quick drafts, not detailed curation.
