---
layout: publication
title: 'Supervised Fine-tuning Llms To Behave As Pedagogical Agents In Programming Education'
authors: Emily Ross, Yuval Kansal, Jake Renzella, Alexandra Vassar, Andrew Taylor
conference: "Arxiv"
year: 2025
bibkey: ross2025supervised
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.20527'}
tags: ['Agentic', 'Interpretability and Explainability', 'RAG', 'Training Techniques', 'Model Architecture', 'GPT', 'Fine-Tuning', 'Prompting', 'Pretraining Methods']
---
Large language models (LLMs) are increasingly being explored in higher
education, yet their effectiveness as teaching agents remains underexamined. In
this paper, we present the development of GuideLM, a fine-tuned LLM designed
for programming education. GuideLM has been integrated into the Debugging C
Compiler (DCC), an educational C compiler that leverages LLMs to generate
pedagogically sound error explanations. Previously, DCC relied on off-the-shelf
OpenAI models, which, while accurate, often over-assisted students by directly
providing solutions despite contrary prompting.
  To address this, we employed supervised fine-tuning (SFT) on a dataset of 528
student-question/teacher-answer pairs, creating two models: GuideLM and
GuideLM-mini, fine-tuned on ChatGPT-4o and 4o-mini, respectively. We conducted
an expert analysis of 400 responses per model, comparing their pedagogical
effectiveness against base OpenAI models. Our evaluation, grounded in
constructivism and cognitive load theory, assessed factors such as conceptual
scaffolding, clarity, and Socratic guidance.
  Results indicate that GuideLM and GuideLM-mini improve pedagogical
performance, with an 8% increase in Socratic guidance and a 58% improvement in
economy of words compared to GPT-4o. However, this refinement comes at the cost
of a slight reduction in general accuracy. While further work is needed, our
findings suggest that fine-tuning LLMs with targeted datasets is a promising
approach for developing models better suited to educational contexts.
