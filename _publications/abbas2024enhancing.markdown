---
layout: publication
title: 'Enhancing In-context Learning Via Linear Probe Calibration'
authors: Momin Abbas, Yi Zhou, Parikshit Ram, Nathalie Baracaldo, Horst Samulowitz, Theodoros Salonidis, Tianyi Chen
conference: "Arxiv"
year: 2024
bibkey: abbas2024enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.12406"}
  - {name: "Code", url: "https://github.com/mominabbass/LinC"}
tags: ['Security', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'GPT', 'Pretraining Methods', 'Transformer', 'Has Code', 'Prompting', 'In-Context Learning']
---
In-context learning (ICL) is a new paradigm for natural language processing
that utilizes Generative Pre-trained Transformer (GPT)-like models. This
approach uses prompts that include in-context demonstrations to generate the
corresponding output for a new query input. However, applying ICL in real cases
does not scale with the number of samples, and lacks robustness to different
prompt templates and demonstration permutations. In this paper, we first show
that GPT-like models using ICL result in unreliable predictions based on a new
metric based on Shannon entropy. Then, to solve this problem, we propose a new
technique called the Linear Probe Calibration (LinC), a method that calibrates
the model's output probabilities, resulting in reliable predictions and
improved performance, while requiring only minimal additional samples (as few
as five labeled data samples). LinC significantly enhances the ICL test
performance of GPT models on various benchmark datasets, with an average
improvement of up to 21%, and up to a 50% improvement in some cases, and
significantly boosts the performance of PEFT methods, especially in the low
resource regime. Moreover, LinC achieves lower expected calibration error, and
is highly robust to varying label proportions, prompt templates, and
demonstration permutations. Our code is available at
\url\{https://github.com/mominabbass/LinC\}.
