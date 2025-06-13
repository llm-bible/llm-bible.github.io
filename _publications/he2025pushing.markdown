---
layout: publication
title: 'Gencls++: Pushing The Boundaries Of Generative Classification In Llms Through Comprehensive SFT And RL Studies Across Diverse Datasets'
authors: Mingqian He, Fei Zhao, Chonggang Lu, Ziyan Liu, Yue Wang, Haofu Qian
conference: "Arxiv"
year: 2025
bibkey: he2025pushing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.19898'}
tags: ['Agentic', 'RAG', 'Applications', 'Training Techniques', 'Tools', 'Fine-Tuning', 'Prompting', 'Reinforcement Learning', 'In-Context Learning']
---
As a fundamental task in machine learning, text classification plays a
crucial role in many areas. With the rapid scaling of Large Language Models
(LLMs), particularly through reinforcement learning (RL), there is a growing
need for more capable discriminators. Consequently, advances in classification
are becoming increasingly vital for enhancing the overall capabilities of LLMs.
Traditional discriminative methods map text to labels but overlook LLMs'
intrinsic generative strengths. Generative classification addresses this by
prompting the model to directly output labels. However, existing studies still
rely on simple SFT alone, seldom probing the interplay between training and
inference prompts, and no work has systematically leveraged RL for generative
text classifiers and unified SFT, RL, and inference-time prompting in one
framework. We bridge this gap with GenCLS++, a framework that jointly optimizes
SFT and RL while systematically exploring five high-level strategy
dimensions-in-context learning variants, category definitions, explicit
uncertainty labels, semantically irrelevant numeric labels, and
perplexity-based decoding-during both training and inference. After an SFT
"policy warm-up," we apply RL with a simple rule-based reward, yielding sizable
extra gains. Across seven datasets, GenCLS++ achieves an average accuracy
improvement of 3.46% relative to the naive SFT baseline; on public datasets,
this improvement rises to 4.00%. Notably, unlike reasoning-intensive tasks that
benefit from explicit thinking processes, we find that classification tasks
perform better without such reasoning steps. These insights into the role of
explicit reasoning provide valuable guidance for future LLM applications.
