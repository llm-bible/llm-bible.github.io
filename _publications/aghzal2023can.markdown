---
layout: publication
title: 'Can Large Language Models Be Good Path Planners? A Benchmark And Investigation On Spatial-temporal Reasoning'
authors: Aghzal Mohamed, Plaku Erion, Yao Ziyu
conference: "Arxiv"
year: 2023
bibkey: aghzal2023can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.03249"}
tags: ['Few Shot', 'Fine Tuning', 'GPT', 'In Context Learning', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Reinforcement Learning', 'TACL', 'Training Techniques']
---
Large language models (LLMs) have achieved remarkable success across a wide spectrum of tasks; however they still face limitations in scenarios that demand long-term planning and spatial reasoning. To facilitate this line of research in this work we propose a new benchmark termed ()ath ()lanning from ()atural ()anguage (()). Our benchmark evaluates LLMs spatial-temporal reasoning by formulating path planning tasks that require an LLM to navigate to target locations while avoiding obstacles and adhering to constraints. Leveraging this benchmark we systematically investigate LLMs including GPT-4 via different few-shot prompting methodologies as well as BART and T5 of various sizes via fine-tuning. Our experimental results show the promise of few-shot GPT-4 in spatial reasoning when it is prompted to reason and act interleavedly although it still fails to perform long-term temporal reasoning. In contrast while fine-tuned LLMs achieved impressive results on in-distribution reasoning tasks they struggled to generalize to larger environments or environments with more obstacles.
