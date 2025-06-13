---
layout: publication
title: 'No Need For Explanations: Llms Can Implicitly Learn From Mistakes In-context'
authors: Lisa Alazraki, Maximilian Mozes, Jon Ander Campos, Tan Yi-chern, Marek Rei, Max Bartolo
conference: "Arxiv"
year: 2025
bibkey: alazraki2025no
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.08550"}
tags: ['Prompting', 'Interpretability and Explainability']
---
Showing incorrect answers to Large Language Models (LLMs) is a popular strategy to improve their performance in reasoning-intensive tasks. It is widely assumed that, in order to be helpful, the incorrect answers must be accompanied by comprehensive rationales, explicitly detailing where the mistakes are and how to correct them. However, in this work we present a counterintuitive finding: we observe that LLMs perform better in math reasoning tasks when these rationales are eliminated from the context and models are left to infer on their own what makes an incorrect answer flawed. This approach also substantially outperforms chain-of-thought prompting in our evaluations. These results are consistent across LLMs of different sizes and varying reasoning abilities. To gain an understanding of why LLMs learn from mistakes more effectively without explicit corrective rationales, we perform a thorough analysis, investigating changes in context length and answer diversity between different prompting strategies, and their effect on performance. We also examine evidence of overfitting to the in-context rationales when these are provided, and study the extent to which LLMs are able to autonomously infer high-quality corrective rationales given only incorrect answers as input. We find evidence that, while incorrect answers are more beneficial for LLM learning than additional diverse correct answers, explicit corrective rationales over-constrain the model, thus limiting those benefits.
