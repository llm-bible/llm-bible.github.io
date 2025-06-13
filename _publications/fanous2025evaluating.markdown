---
layout: publication
title: 'Syceval: Evaluating LLM Sycophancy'
authors: Aaron Fanous, Jacob Goldberg, Ank A. Agarwal, Joanna Lin, Anson Zhou, Roxana Daneshjou, Sanmi Koyejo
conference: "Arxiv"
year: 2025
bibkey: fanous2025evaluating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.08177"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'GPT', 'Prompting', 'Applications']
---
Large language models (LLMs) are increasingly applied in educational,
clinical, and professional settings, but their tendency for sycophancy --
prioritizing user agreement over independent reasoning -- poses risks to
reliability. This study introduces a framework to evaluate sycophantic behavior
in ChatGPT-4o, Claude-Sonnet, and Gemini-1.5-Pro across AMPS (mathematics) and
MedQuad (medical advice) datasets. Sycophantic behavior was observed in 58.19%
of cases, with Gemini exhibiting the highest rate (62.47%) and ChatGPT the
lowest (56.71%). Progressive sycophancy, leading to correct answers, occurred
in 43.52% of cases, while regressive sycophancy, leading to incorrect answers,
was observed in 14.66%. Preemptive rebuttals demonstrated significantly higher
sycophancy rates than in-context rebuttals (61.75% vs. 56.52%, \\(Z=5.87\\),
\\(p<0.001\\)), particularly in computational tasks, where regressive sycophancy
increased significantly (preemptive: 8.13%, in-context: 3.54%, \\(p<0.001\\)).
Simple rebuttals maximized progressive sycophancy (\\(Z=6.59\\), \\(p<0.001\\)), while
citation-based rebuttals exhibited the highest regressive rates (\\(Z=6.59\\),
\\(p<0.001\\)). Sycophantic behavior showed high persistence (78.5%, 95% CI:
[77.2%, 79.8%]) regardless of context or model. These findings emphasize the
risks and opportunities of deploying LLMs in structured and dynamic domains,
offering insights into prompt programming and model optimization for safer AI
applications.
