---
layout: publication
title: 'Can Llms Identify Gaps And Misconceptions In Students'' Code Explanations?'
authors: Priti Oli, Rabin Banjade, Andrew M. Olney, Vasile Rus
conference: "Arxiv"
year: 2024
bibkey: oli2024can
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.10365'}
tags: ['Interpretability and Explainability', 'Few-Shot', 'Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'GPT', 'Fine-Tuning', 'Prompting', 'In-Context Learning', 'Pretraining Methods']
---
This paper investigates various approaches using Large Language Models (LLMs)
to identify gaps and misconceptions in students' self-explanations of specific
instructional material, in our case explanations of code examples. This
research is a part of our larger effort to automate the assessment of students'
freely generated responses, focusing specifically on their self-explanations of
code examples during activities related to code comprehension. In this work, we
experiment with zero-shot prompting, Supervised Fine-Tuning (SFT), and
preference alignment of LLMs to identify gaps in students' self-explanation.
With simple prompting, GPT-4 consistently outperformed LLaMA3 and Mistral in
identifying gaps and misconceptions, as confirmed by human evaluations.
Additionally, our results suggest that fine-tuned large language models are
more effective at identifying gaps in students' explanations compared to
zero-shot and few-shot prompting techniques. Furthermore, our findings show
that the preference optimization approach using Odds Ratio Preference
Optimization (ORPO) outperforms SFT in identifying gaps and misconceptions in
students' code explanations.
