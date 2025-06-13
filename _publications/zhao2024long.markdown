---
layout: publication
title: 'LTGC: Long-tail Recognition Via Leveraging Llms-driven Generated Content'
authors: Qihao Zhao, Yalun Dai, Hao Li, Wei Hu, Fan Zhang, Jun Liu
conference: "Arxiv"
year: 2024
bibkey: zhao2024long
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.05854"}
tags: ['Training Techniques', 'Tools', 'RAG', 'Pretraining Methods', 'Fine-Tuning']
---
Long-tail recognition is challenging because it requires the model to learn
good representations from tail categories and address imbalances across all
categories. In this paper, we propose a novel generative and fine-tuning
framework, LTGC, to handle long-tail recognition via leveraging generated
content. Firstly, inspired by the rich implicit knowledge in large-scale models
(e.g., large language models, LLMs), LTGC leverages the power of these models
to parse and reason over the original tail data to produce diverse tail-class
content. We then propose several novel designs for LTGC to ensure the quality
of the generated data and to efficiently fine-tune the model using both the
generated and original data. The visualization demonstrates the effectiveness
of the generation module in LTGC, which produces accurate and diverse tail
data. Additionally, the experimental results demonstrate that our LTGC
outperforms existing state-of-the-art methods on popular long-tailed
benchmarks.
