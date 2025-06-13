---
layout: publication
title: 'Towards Explainable Temporal Reasoning In Large Language Models: A Structure-aware Generative Framework'
authors: Zihao Jiang, Ben Liu, Miao Peng, Wenjie Xu, Yao Xiao, Zhenyan Shan, Min Peng
conference: "Arxiv"
year: 2025
bibkey: jiang2025towards
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.15245'}
  - {name: "Code", url: 'https://github.com/carryTatum/GETER'}
tags: ['Has Code', 'Interpretability and Explainability', 'RAG', 'Applications', 'Tools', 'Fine-Tuning', 'Prompting', 'Reinforcement Learning']
---
While large language models (LLMs) show great potential in temporal reasoning, most existing work focuses heavily on enhancing performance, often neglecting the explainable reasoning processes underlying the results. To address this gap, we introduce a comprehensive benchmark covering a wide range of temporal granularities, designed to systematically evaluate LLMs' capabilities in explainable temporal reasoning. Furthermore, our findings reveal that LLMs struggle to deliver convincing explanations when relying solely on textual information. To address challenge, we propose GETER, a novel structure-aware generative framework that integrates Graph structures with text for Explainable TEmporal Reasoning. Specifically, we first leverage temporal knowledge graphs to develop a temporal encoder that captures structural information for the query. Subsequently, we introduce a structure-text prefix adapter to map graph structure features into the text embedding space. Finally, LLMs generate explanation text by seamlessly integrating the soft graph token with instruction-tuning prompt tokens. Experimental results indicate that GETER achieves state-of-the-art performance while also demonstrating its effectiveness as well as strong generalization capabilities. Our dataset and code are available at https://github.com/carryTatum/GETER.
