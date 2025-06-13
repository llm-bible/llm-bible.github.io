---
layout: publication
title: 'Divide-verify-refine: Can Llms Self-align With Complex Instructions?'
authors: Xianren Zhang, Xianfeng Tang, Hui Liu, Zongyu Wu, Qi He, Dongwon Lee, Suhang Wang
conference: "Arxiv"
year: 2024
bibkey: zhang2024divide
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.12207"}
tags: ['Training Techniques', 'Few-Shot', 'Tools', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Prompting', 'In-Context Learning']
---
Recent studies show LLMs struggle with complex instructions involving
multiple constraints (e.g., length, format, sentiment). Existing works address
this issue by fine-tuning, which heavily relies on fine-tuning data quality and
is computational expensive. An alternative is leveraging LLMs' self-correction
to refine responses for better constraint adherence. However, this is limited
by the feedback quality, as LLMs cannot generate reliable feedback or detect
errors. Moreover, its effectiveness relies on few-shot examples illustrating
response modifications. As constraints in complex instructions are diverse,
manually crafting such examples for each constraint type can be labor-intensive
and sub-optimal. To address these two challenges, we propose the
Divide-Verify-Refine (DVR) framework with three steps: (1) Divide complex
instructions into single constraints and prepare appropriate tools; (2) Verify
responses using tools that provide rigorous check and textual guidance (e.g.,
Python toolkit for format checks or pre-trained classifiers for content
analysis); (3) Refine: To maximize refinement effectiveness, we propose dynamic
few-shot prompting, where a refinement repository collects successful
refinements, and these examples are selectively retrieved for future
refinements. Recognizing the lack of complexity in existing datasets, we create
a new dataset of complex instructions. DVR doubles Llama3.1-8B's constraint
adherence and triples Mistral-7B's performance.
