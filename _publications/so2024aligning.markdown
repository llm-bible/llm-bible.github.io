---
layout: publication
title: 'Aligning Large Language Models For Enhancing Psychiatric Interviews Through Symptom Delineation And Summarization: Pilot Study'
authors: Jae-hee So, Joonhwan Chang, Eunji Kim, Junho Na, Jiyeon Choi, Jy-yong Sohn, Byung-hoon Kim, Sang Hui Chu
conference: "JMIR Form Res 2024;8e58418"
year: 2024
bibkey: so2024aligning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.17428"}
tags: ['Training Techniques', 'Model Architecture', 'RAG', 'GPT', 'Pretraining Methods', 'Fine-Tuning', 'Prompting', 'Applications']
---
Background: Advancements in large language models (LLMs) have opened new
possibilities in psychiatric interviews, an underexplored area where LLMs could
be valuable. This study focuses on enhancing psychiatric interviews by
analyzing counseling data from North Korean defectors who have experienced
trauma and mental health issues.
  Objective: The study investigates whether LLMs can (1) identify parts of
conversations that suggest psychiatric symptoms and recognize those symptoms,
and (2) summarize stressors and symptoms based on interview transcripts.
  Methods: LLMs are tasked with (1) extracting stressors from transcripts, (2)
identifying symptoms and their corresponding sections, and (3) generating
interview summaries using the extracted data. The transcripts were labeled by
mental health experts for training and evaluation.
  Results: In the zero-shot inference setting using GPT-4 Turbo, 73 out of 102
segments demonstrated a recall mid-token distance d < 20 in identifying
symptom-related sections. For recognizing specific symptoms, fine-tuning
outperformed zero-shot inference, achieving an accuracy, precision, recall, and
F1-score of 0.82. For the generative summarization task, LLMs using symptom and
stressor information scored highly on G-Eval metrics: coherence (4.66),
consistency (4.73), fluency (2.16), and relevance (4.67). Retrieval-augmented
generation showed no notable performance improvement.
  Conclusions: LLMs, with fine-tuning or appropriate prompting, demonstrated
strong accuracy (over 0.8) for symptom delineation and achieved high coherence
(4.6+) in summarization. This study highlights their potential to assist mental
health practitioners in analyzing psychiatric interviews.
