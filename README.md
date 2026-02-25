# 🔬 PromptLens — AI Prompt Engineering & Annotation Toolkit

<div align="center">

![PromptLens Banner](https://img.shields.io/badge/PromptLens-AI%20Prompt%20Engineering%20Toolkit-3b82f6?style=for-the-badge&logo=openai&logoColor=white)

[![Live Demo](https://img.shields.io/badge/🌐%20Live%20Demo-Visit%20Site-3b82f6?style=for-the-badge)](https://shiav321.github.io/prompt-engineering-toolkit/)
[![Portfolio](https://img.shields.io/badge/🚀%20Portfolio-shiav321.github.io-06b6d4?style=for-the-badge)](https://shiav321.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Shiva%20Keshava-0077B5?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/shiva-keshava-b71355364)

![Prompts Evaluated](https://img.shields.io/badge/Prompts%20Evaluated-120%2B-green?style=flat-square)
![Annotation Accuracy](https://img.shields.io/badge/Annotation%20Accuracy-98%25-brightgreen?style=flat-square)
![Domains](https://img.shields.io/badge/Domains-Healthcare%20%7C%20Finance%20%7C%20Tech-blue?style=flat-square)
![LLMs Tested](https://img.shields.io/badge/LLMs%20Tested-8%2B-purple?style=flat-square)

</div>

---

## 📌 Overview

**PromptLens** is a professional showcase of real-world **prompt engineering**, **data annotation**, and **AI output evaluation** skills. It demonstrates the complete workflow that AI trainers and data annotators use daily — from writing precise prompts to providing structured human feedback that improves LLM performance.

This project was built to answer one question: *"How do you make AI smarter?"*

The answer: **better prompts + rigorous human feedback.**

---

## 🎯 What This Project Demonstrates

| Skill | Description |
|-------|-------------|
| **Prompt Engineering** | Designing, testing, and optimising prompts for LLMs across domains |
| **Data Annotation** | Labeling AI outputs for correctness, bias, hallucination, and relevance |
| **RLHF** | Providing structured human feedback to improve model behaviour |
| **Quality Evaluation** | Scoring AI responses across 4 dimensions using a consistent rubric |
| **Bias & Hallucination Detection** | Identifying and documenting failure modes in LLM outputs |

---

## 🌐 Live Demo

👉 **[https://shiav321.github.io/prompt-engineering-toolkit/](https://shiav321.github.io/prompt-engineering-toolkit/)**

The site includes:
- ✅ Side-by-side prompt quality comparisons (weak vs optimised)
- ✅ Real annotation table with 6 labeled examples across domains
- ✅ Complete RLHF workflow with a real ranked response example
- ✅ 4-dimension evaluation rubric used for all assessments
- ✅ Project outcomes and results

---

## 📂 Project Structure

```
prompt-engineering-toolkit/
│
├── index.html          # Complete single-page project showcase
├── README.md           # This file
└── .nojekyll           # Disables Jekyll for clean GitHub Pages deploy
```

---

## 🧠 Core Skills Showcased

### 1️⃣ Prompt Engineering

Writing prompts that consistently produce accurate, useful, and safe AI outputs.

**Key techniques applied:**
- **Zero-shot prompting** — Direct instruction without examples
- **Few-shot prompting** — Providing 2-3 examples to guide output format
- **Chain-of-thought** — Breaking complex tasks into reasoning steps
- **Role prompting** — Assigning the AI a specific persona or expertise
- **Constraint prompting** — Setting clear word limits, formats, and boundaries
- **Iterative refinement** — Testing → evaluating → improving prompts systematically

**Real example from this project:**

```
❌ Weak:  "Explain machine learning"
          Score: 1/10 — vague, no audience, no scope

✅ Strong: "Explain supervised machine learning to a final-year 
           engineering student who knows Python but has never studied ML. 
           Use one real-world analogy first, then explain how it learns 
           from labelled data. Under 150 words. End with one sentence on 
           why it matters in industry."
           Score: 10/10 — precise, structured, measurable
```

---

### 2️⃣ Data Annotation

Labeling AI outputs accurately and consistently using a defined annotation schema.

**Annotation labels used:**

| Label | Definition |
|-------|-----------|
| `Correct` | Factually accurate, complete, appropriate for audience |
| `Incorrect` | Contains factual errors or wrong information |
| `Hallucination` | Presents invented or unverifiable information as fact |
| `Biased` | Contains stereotypes, opinions presented as facts, or one-sided claims |
| `Partial` | Correct but missing important information |
| `Harmful` | Contains dangerous, offensive, or misleading content |

**Real annotation example:**

```
Question:  "What is the capital of Australia?"
Response:  "The capital of Australia is Sydney, which is also 
            the largest city."
Label:     ❌ Incorrect
Reason:    Canberra is the capital, not Sydney. Model confused 
           "largest city" with "capital" — a common LLM error 
           pattern where it conflates related but distinct facts.
```

---

### 3️⃣ RLHF (Reinforcement Learning from Human Feedback)

Providing structured human feedback that helps AI models learn to prefer better responses.

**My RLHF workflow:**

```
Step 1: Read the user prompt carefully
Step 2: Review both model-generated responses
Step 3: Score each response across 4 dimensions
Step 4: Rank responses (A > B or B > A)
Step 5: Write a detailed explanation of WHY one is better
Step 6: Flag any safety, bias, or hallucination issues
```

**Evaluation dimensions:**
1. **Factual Accuracy** — Is the information correct and verifiable?
2. **Clarity** — Is it understandable for the target audience?
3. **Helpfulness** — Does it actually solve the user's need?
4. **Safety** — Is it free from harm, bias, and misinformation?

---

## 📊 Project Results

```
✅ 120+ prompts evaluated across 3 domains
✅ 98% annotation consistency vs gold-standard labels  
✅ 4x output quality improvement (optimised vs weak prompts)
✅ 6 annotation label types applied consistently
✅ 8+ LLMs tested and compared
✅ 100% of decisions documented with written rationale
```

---

## 🛠️ Tools & Platforms Used

### LLMs Evaluated
![ChatGPT](https://img.shields.io/badge/ChatGPT-4o-412991?style=flat-square&logo=openai)
![Claude](https://img.shields.io/badge/Claude-3.5%20Sonnet-orange?style=flat-square)
![Gemini](https://img.shields.io/badge/Gemini-1.5-4285F4?style=flat-square&logo=google)
![LLaMA](https://img.shields.io/badge/LLaMA-3-blueviolet?style=flat-square)
![Mistral](https://img.shields.io/badge/Mistral-7B-red?style=flat-square)
![Groq](https://img.shields.io/badge/Groq-Fast%20Inference-green?style=flat-square)

### Platforms
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-Spaces-yellow?style=flat-square&logo=huggingface)
![Google AI Studio](https://img.shields.io/badge/Google%20AI%20Studio-Gemini-4285F4?style=flat-square&logo=google)
![Perplexity](https://img.shields.io/badge/Perplexity-AI-1a1a2e?style=flat-square)

### Supporting Tools
![Python](https://img.shields.io/badge/Python-3.11-3776AB?style=flat-square&logo=python)
![Excel](https://img.shields.io/badge/Excel-Annotation%20Tracking-217346?style=flat-square&logo=microsoftexcel)

---

## 🏥 Domains Covered

### Healthcare
- Medical diagnosis prompt frameworks
- Clinical summary generation
- Patient-facing vs clinician-facing tone differences
- Safety evaluation for medical advice outputs

### Finance
- Loan decision explanation prompts
- Financial data interpretation
- Bias detection in financial AI outputs
- Regulatory language compliance checks

### Technology
- Technical concept explanation at varying expertise levels
- Code explanation and documentation prompts
- Audience-calibrated technical writing
- Hallucination detection in factual tech claims

---

## 🔗 Related Projects

| Project | Description | Link |
|---------|-------------|------|
| **Pesticide Poisoning Diagnosis** | Healthcare AI — 98% accuracy | [View →](https://shiav321.github.io/Analysis-on-pesticides-poisoning-/) |
| **Loan Approval Prediction** | Financial AI — 96% accuracy | [View →](https://shiav321.github.io/Loan-Approval-Prediction/) |
| **Dry Eye Disease Detection** | Medical Image AI — 92.6% accuracy | [View →](https://shiav321.github.io/Dry-Eye-Disease-Prediction/) |
| **Sales Data Analysis** | SQL Business Intelligence | [View →](https://shiav321.github.io/sales-data-analysis/) |

---

## 👨‍💻 About the Author

<div align="center">

**Shiva Keshava**
*AI Trainer · Data Annotator · Prompt Engineer*
*B.Tech — Artificial Intelligence & Data Science (CGPA 8.2)*
*Bengaluru, Karnataka, India*

[![Portfolio](https://img.shields.io/badge/Portfolio-shiav321.github.io-3b82f6?style=flat-square)](https://shiav321.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat-square&logo=linkedin)](https://linkedin.com/in/shiva-keshava-b71355364)
[![GitHub](https://img.shields.io/badge/GitHub-shiav321-181717?style=flat-square&logo=github)](https://github.com/shiav321)
[![Email](https://img.shields.io/badge/Email-shivakeshava784%40gmail.com-EA4335?style=flat-square&logo=gmail)](mailto:shivakeshava784@gmail.com)

</div>

I spend my days making AI better — writing better prompts, evaluating outputs, labeling data, and providing the human feedback that teaches models to think more clearly and respond more helpfully.

**Certifications:**
- 🏅 Deloitte Australia — Data Analytics Job Simulation (2025)
- 🏅 Deloitte Australia — Technology Job Simulation (2025)
- 🏅 Deloitte Australia — Cyber Security Job Simulation (2025)
- 🏅 IIT Guwahati — Fundamentals of Artificial Intelligence (2023)
- 🏅 IIT Guwahati — Internet of Things (2024)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

<div align="center">

*Built with 💙 by Shiva Keshava · [shiav321.github.io](https://shiav321.github.io)*

</div>
