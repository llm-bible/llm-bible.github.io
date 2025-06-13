---
layout: publication
title: 'When Do Llms Admit Their Mistakes? Understanding The Role Of Model Belief In Retraction'
authors: Yuqing Yang, Robin Jia
conference: "Arxiv"
year: 2025
bibkey: yang2025when
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.16170"}
  - {name: "Code", url: "https://github.com/ayyyq/llm-retraction"}
tags: ['Fine-Tuning', 'RAG', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Has Code', 'Pretraining Methods']
---
Can large language models (LLMs) admit their mistakes when they should know better? In this work, we define the behavior of acknowledging errors in previously generated answers as "retraction" and aim to understand when and why LLMs choose to retract. We first construct model-specific datasets to evaluate whether a model will retract an incorrect answer that contradicts its own parametric knowledge. While LLMs are capable of retraction, they do so only infrequently. We demonstrate that retraction is closely tied to previously identified indicators of models' internal belief: models fail to retract wrong answers that they "believe" to be factually correct. Steering experiments further demonstrate that internal belief causally influences model retraction. In particular, when the model does not believe its answer, this not only encourages the model to attempt to verify the answer, but also alters attention behavior during self-verification. Finally, we demonstrate that simple supervised fine-tuning significantly improves retraction performance by helping the model learn more accurate internal beliefs. Code and datasets are available on https://github.com/ayyyq/llm-retraction.
