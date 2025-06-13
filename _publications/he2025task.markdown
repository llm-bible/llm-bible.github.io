---
layout: publication
title: 'Task As Context Prompting For Accurate Medical Symptom Coding Using Large Language Models'
authors: Chengyang He, Wenlong Zhang, Violet Xinying Chen, Yue Ning, Ping Wang
conference: "Arxiv"
year: 2025
bibkey: he2025task
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.03051"}
tags: ['Responsible AI', 'Tools', 'GPT', 'Applications', 'Model Architecture', 'Reinforcement Learning', 'Prompting']
---
Accurate medical symptom coding from unstructured clinical text, such as
vaccine safety reports, is a critical task with applications in
pharmacovigilance and safety monitoring. Symptom coding, as tailored in this
study, involves identifying and linking nuanced symptom mentions to
standardized vocabularies like MedDRA, differentiating it from broader medical
coding tasks. Traditional approaches to this task, which treat symptom
extraction and linking as independent workflows, often fail to handle the
variability and complexity of clinical narratives, especially for rare cases.
Recent advancements in Large Language Models (LLMs) offer new opportunities but
face challenges in achieving consistent performance. To address these issues,
we propose Task as Context (TACO) Prompting, a novel framework that unifies
extraction and linking tasks by embedding task-specific context into LLM
prompts. Our study also introduces SYMPCODER, a human-annotated dataset derived
from Vaccine Adverse Event Reporting System (VAERS) reports, and a two-stage
evaluation framework to comprehensively assess both symptom linking and mention
fidelity. Our comprehensive evaluation of multiple LLMs, including Llama2-chat,
Jackalope-7b, GPT-3.5 Turbo, GPT-4 Turbo, and GPT-4o, demonstrates TACO's
effectiveness in improving flexibility and accuracy for tailored tasks like
symptom coding, paving the way for more specific coding tasks and advancing
clinical text processing methodologies.
