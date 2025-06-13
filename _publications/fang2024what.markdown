---
layout: publication
title: 'What Is Wrong With Perplexity For Long-context Language Modeling?'
authors: Lizhe Fang, Yifei Wang, Zhaoyang Liu, Chenheng Zhang, Stefanie Jegelka, Jinyang Gao, Bolin Ding, Yisen Wang
conference: "Arxiv"
year: 2024
bibkey: fang2024what
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.23771"}
  - {name: "Code", url: "https://github.com/PKU-ML/LongPPL"}
tags: ['Fine-Tuning', 'Applications', 'Interpretability and Explainability', 'RAG', 'Language Modeling', 'Reinforcement Learning', 'Training Techniques', 'Has Code', 'Pretraining Methods', 'Prompting', 'In-Context Learning']
---
Handling long-context inputs is crucial for large language models (LLMs) in
tasks such as extended conversations, document summarization, and many-shot
in-context learning. While recent approaches have extended the context windows
of LLMs and employed perplexity (PPL) as a standard evaluation metric, PPL has
proven unreliable for assessing long-context capabilities. The underlying cause
of this limitation has remained unclear. In this work, we provide a
comprehensive explanation for this issue. We find that PPL overlooks key
tokens, which are essential for long-context understanding, by averaging across
all tokens and thereby obscuring the true performance of models in long-context
scenarios. To address this, we propose \textbf\{LongPPL\}, a novel metric that
focuses on key tokens by employing a long-short context contrastive method to
identify them. Our experiments demonstrate that LongPPL strongly correlates
with performance on various long-context benchmarks (e.g., Pearson correlation
of -0.96), significantly outperforming traditional PPL in predictive accuracy.
Additionally, we introduce \textbf\{LongCE\} (Long-context Cross-Entropy) loss, a
re-weighting strategy for fine-tuning that prioritizes key tokens, leading to
consistent improvements across diverse benchmarks. In summary, these
contributions offer deeper insights into the limitations of PPL and present
effective solutions for accurately evaluating and enhancing the long-context
capabilities of LLMs. Code is available at https://github.com/PKU-ML/LongPPL.
