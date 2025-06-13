---
layout: publication
title: 'A Stack-propagation Framework For Low-resource Personalized Dialogue Generation'
authors: Haoyu Song, Wei-nan Zhang, Kaiyan Zhang, Ting Liu
conference: "ACM Trans. Inf. Syst. 41 3 Article 68 (July 2023)"
year: 2024
bibkey: song2024stack
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.20174"}
tags: ['Training Techniques', 'Model Architecture', 'Tools', 'RAG', 'Pretraining Methods', 'Transformer', 'Applications', 'Attention Mechanism']
---
With the resurgent interest in building open-domain dialogue systems, the
dialogue generation task has attracted increasing attention over the past few
years. This task is usually formulated as a conditional generation problem,
which aims to generate a natural and meaningful response given dialogue
contexts and specific constraints, such as persona. And maintaining a
consistent persona is essential for the dialogue systems to gain trust from the
users. Although tremendous advancements have been brought, traditional
persona-based dialogue models are typically trained by leveraging a large
number of persona-dense dialogue examples. Yet, such persona-dense training
data are expensive to obtain, leading to a limited scale. This work presents a
novel approach to learning from limited training examples by regarding
consistency understanding as a regularization of response generation. To this
end, we propose a novel stack-propagation framework for learning a generation
and understanding pipeline.Specifically, the framework stacks a Transformer
encoder and two Transformer decoders, where the first decoder models response
generation and the second serves as a regularizer and jointly models response
generation and consistency understanding. The proposed framework can benefit
from the stacked encoder and decoders to learn from much smaller personalized
dialogue data while maintaining competitive performance. Under different
low-resource settings, subjective and objective evaluations prove that the
stack-propagation framework outperforms strong baselines in response quality
and persona consistency and largely overcomes the shortcomings of traditional
models that rely heavily on the persona-dense dialogue data.
