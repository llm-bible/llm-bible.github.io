---
layout: publication
title: 'Inference-time Scaling For Complex Tasks: Where We Stand And What Lies Ahead'
authors: Vidhisha Balachandran, Jingya Chen, Lingjiao Chen, Shivam Garg, Neel Joshi, Yash Lara, John Langford, Besmira Nushi, Vibhav Vineet, Yue Wu, Safoora Yousefi
conference: "Arxiv"
year: 2025
bibkey: balachandran2025inference
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.00294"}
tags: ['RAG', 'Training Techniques', 'GPT', 'Model Architecture']
---
Inference-time scaling can enhance the reasoning capabilities of large
language models (LLMs) on complex problems that benefit from step-by-step
problem solving. Although lengthening generated scratchpads has proven
effective for mathematical tasks, the broader impact of this approach on other
tasks remains less clear. In this work, we investigate the benefits and
limitations of scaling methods across nine state-of-the-art models and eight
challenging tasks, including math and STEM reasoning, calendar planning,
NP-hard problems, navigation, and spatial reasoning. We compare conventional
models (e.g., GPT-4o) with models fine-tuned for inference-time scaling (e.g.,
o1) through evaluation protocols that involve repeated model calls, either
independently or sequentially with feedback. These evaluations approximate
lower and upper performance bounds and potential for future performance
improvements for each model, whether through enhanced training or multi-model
inference systems. Our extensive empirical analysis reveals that the advantages
of inference-time scaling vary across tasks and diminish as problem complexity
increases. In addition, simply using more tokens does not necessarily translate
to higher accuracy in these challenging regimes. Results from multiple
independent runs with conventional models using perfect verifiers show that,
for some tasks, these models can achieve performance close to the average
performance of today's most advanced reasoning models. However, for other
tasks, a significant performance gap remains, even in very high scaling
regimes. Encouragingly, all models demonstrate significant gains when inference
is further scaled with perfect verifiers or strong feedback, suggesting ample
potential for future improvements.
