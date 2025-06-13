---
layout: publication
title: 'Shared Imagination: Llms Hallucinate Alike'
authors: Yilun Zhou, Caiming Xiong, Silvio Savarese, Chien-sheng Wu
conference: "Arxiv"
year: 2024
bibkey: zhou2024shared
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.16604"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Prompting', 'Pre-Training', 'Applications']
---
Despite the recent proliferation of large language models (LLMs), their
training recipes -- model architecture, pre-training data and optimization
algorithm -- are often very similar. This naturally raises the question of the
similarity among the resulting models. In this paper, we propose a novel
setting, imaginary question answering (IQA), to better understand model
similarity. In IQA, we ask one model to generate purely imaginary questions
(e.g., on completely made-up concepts in physics) and prompt another model to
answer. Surprisingly, despite the total fictionality of these questions, all
models can answer each other's questions with remarkable success, suggesting a
"shared imagination space" in which these models operate during such
hallucinations. We conduct a series of investigations into this phenomenon and
discuss implications on model homogeneity, hallucination, and computational
creativity.
