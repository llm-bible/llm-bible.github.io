---
layout: publication
title: 'Lookalike: Consistent Distractor Generation In Math Mcqs'
authors: Nisarg Parikh, Nigel Fernandez, Alexander Scarlatos, Simon Woodhead, Andrew Lan
conference: "Arxiv"
year: 2025
bibkey: parikh2025consistent
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.01903"}
tags: ['Fine-Tuning', 'Efficiency and Optimization', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
Large language models (LLMs) are increasingly used to generate distractors
for multiple-choice questions (MCQs), especially in domains like math
education. However, existing approaches are limited in ensuring that the
generated distractors are consistent with common student errors. We propose
LookAlike, a method that improves error-distractor consistency via preference
optimization. Our two main innovations are: (a) mining synthetic preference
pairs from model inconsistencies, and (b) alternating supervised fine-tuning
(SFT) with Direct Preference Optimization (DPO) to stabilize training. Unlike
prior work that relies on heuristics or manually annotated preference data,
LookAlike uses its own generation inconsistencies as dispreferred samples, thus
enabling scalable and stable training. Evaluated on a real-world dataset of
1,400+ math MCQs, LookAlike achieves 51.6% accuracy in distractor generation
and 57.2% in error generation under LLM-as-a-judge evaluation, outperforming an
existing state-of-the-art method (45.6% / 47.7%). These improvements highlight
the effectiveness of preference-based regularization and inconsistency mining
for generating consistent math MCQ distractors at scale.
