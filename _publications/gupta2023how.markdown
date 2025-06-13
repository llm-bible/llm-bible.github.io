---
layout: publication
title: 'How Robust Are Llms To In-context Majority Label Bias?'
authors: Karan Gupta, Sumegh Roychowdhury, Siva Rajesh Kasa, Santhosh Kumar Kasa, Anish Bhanushali, Nikhil Pattisapu, Prasanna Srinivasa Murthy
conference: "Arxiv"
year: 2023
bibkey: gupta2023how
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2312.16549'}
tags: ['Security', 'Prompting', 'Reinforcement Learning', 'Ethics and Bias', 'Interpretability', 'In-Context Learning']
---
In the In-Context Learning (ICL) setup, various forms of label biases can
manifest. One such manifestation is majority label bias, which arises when the
distribution of labeled examples in the in-context samples is skewed towards
one or more specific classes making Large Language Models (LLMs) more prone to
predict those labels. Such discrepancies can arise from various factors,
including logistical constraints, inherent biases in data collection methods,
limited access to diverse data sources, etc. which are unavoidable in a
real-world industry setup. In this work, we study the robustness of in-context
learning in LLMs to shifts that occur due to majority label bias within the
purview of text classification tasks. Prior works have shown that in-context
learning with LLMs is susceptible to such biases. In our study, we go one level
deeper and show that the robustness boundary varies widely for different models
and tasks, with certain LLMs being highly robust (~90%) to majority label bias.
Additionally, our findings also highlight the impact of model size and the
richness of instructional prompts contributing towards model robustness. We
restrict our study to only publicly available open-source models to ensure
transparency and reproducibility.
