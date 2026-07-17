<div align="center">
  <img src="https://img.shields.io/badge/Prompt%20Literacy-Project-%23ADD8E6?style=for-the-badge&logo=openai&logoColor=white" alt="Prompt Literacy Project Badge">
  <br><br>
  <h1 style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; color:#ADD8E6; font-weight:700; margin-bottom:0;">Prompt Literacy Project</h1>
  <p style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; font-size:1.2rem; color:#555; margin-top:0.5rem;"><em>Why do some people consistently get better results from AI than others?</em></p>
</div>

---

## Overview

The Prompt Literacy Project is an independent, evidence‑based investigation into what separates effective AI prompts from ineffective ones. It combines primary survey data from **80+ South African university students**, hands‑on experiments, and a practical teaching framework called **CLEAR** to answer one core question:

> **Why do some people consistently get better results from AI than others — and how can we teach everyone else to do the same?**

This project turns that insight into open‑source curriculum, experiments, and tools anyone can use to improve their AI communication skills.

---

## Quick Links

- [CLEAR Framework](research/prompt_framework.md)
- [AI Limitations & Failure Modes](research/ai_limitations.md)
- [Literature Review](research/literature_review.md)
- [Experiments](experiments/)
- [Curriculum](curriculum/)
- [Evaluation Rubric](evaluation_rubric.md)
- [Future Work](future_work.md)

---

## The CLEAR Framework

One major outcome of this project is the **CLEAR** prompt framework — a simple, memorable guide for writing better prompts:

- **C**ontext – Provide background, audience, and purpose.
- **L**imitations – Set boundaries (e.g., "Do not speculate," "Use only provided info").
- **E**xamples – Show the model the format or style you expect.
- **A**udience – Specify who the response is for (a 14‑year‑old, a CEO, etc.).
- **R**equirements – Give clear constraints (length, tone, must‑include elements).

[Explore the full framework →](research/prompt_framework.md)

---

## From Survey to Framework

This project didn't start in a lab — it started with real students.

In July 2026, as part of the **Socionext Social Entrepreneurship Challenge**, my team (EMZAMS AI) conducted a survey of **90+ South African university students** about their AI use. The results were striking:

- **94% use AI at least weekly**, mostly to understand concepts, summarise readings, and check work.
- The biggest frustrations: vague or irrelevant AI outputs ("slop"), not knowing how to ask for what they need.
- Unethical use (copy‑paste, ghostwriting) was widely recognised but still common — often driven by time pressure and poor prompting skills.

Those findings became the foundation of the Prompt Literacy Project. The CLEAR framework, failure‑mode catalogue, and curriculum are all designed to address the real gaps students told us about.

---

## Experiments

The `experiments/` folder contains structured prompt comparisons across five dimensions:

- **Ambiguity** – How clarity transforms output quality.
- **Reasoning** – The role of "step‑by‑step" instructions.
- **Creativity** – Why constraints produce more original ideas.
- **Factuality** – Techniques to reduce hallucination.
- **Instruction Following** – Testing complex, multi‑constraint prompts.

Each experiment follows a consistent template and includes a "Survey Connection" showing how the finding relates to real student experiences.

[Browse experiments →](experiments/)

---

## Curriculum

Three ready‑to‑use modules:

1. **AI Communication Basics** – Introduction to prompts, CLEAR framework, and the evaluation rubric.
2. **Avoiding Common Pitfalls** – Hallucination, over‑reliance, ambiguity, and how to fix them with better prompts.
3. **Critical Prompting & Responsible Use** – Fact‑checking, ethical boundaries, iterative prompting, and academic integrity.

Each module includes exercises, discussion prompts, and reflection activities — all built from real survey feedback.

[Start teaching →](curriculum/module1.md)

---

## Real Examples

The `examples/` folder shows the CLEAR framework in action. Using a single topic — **Machine Learning vs Traditional Programming** — we compare:

- **Bad prompt:** "What is machine learning?"  
- **Good prompt:** "Explain ML vs traditional programming to a student with two examples."  
- **Excellent prompt:** Full CLEAR prompt with tutor persona, structure, word limit, and a summary requirement.

Each example includes the original AI output, an analysis of what worked (or didn't), and a connection back to the survey data.

[See the examples →](examples/bad_prompt.md)

---

## Evaluation Rubric

To make prompt quality measurable, we developed a scoring rubric covering:

- Clarity
- Context
- Constraints
- Specificity
- Expected Output Format
- Ethical Considerations

Used throughout the curriculum and experiments.

[View the rubric →](evaluation_rubric.md)

---

## Getting Involved

This is a living project, and contributions are welcome.

- Try an experiment and add your own prompt chain.
- Use the curriculum in a workshop or tutorial and share feedback.
- Open an issue to discuss a research question or suggest a new experiment.

The goal is to build the most practical, student‑centred prompt literacy resource available — and that works best with many voices.

---

## Technologies & Tools

- **AI Models tested:** ChatGPT, Claude, Google Gemini
- **Analysis & Writing:** Markdown, structured frameworks
- **Primary Research:** Google Forms, qualitative survey analysis
- **Version Control:** GitHub

---

## License

This project is released under the MIT License. See `LICENSE` for details.

---

<div align="center">
  <p style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; color:#ADD8E6; font-weight:600;">Learn smarter. Use AI better.</p>
  <p style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; font-size:0.9rem; color:#888;">— The Prompt Literacy Project, July 2026</p>
</div>
