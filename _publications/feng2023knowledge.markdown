---
layout: publication
title: 'Knowledge Solver: Teaching Llms To Search For Domain Knowledge From Knowledge Graphs'
authors: Chao Feng, Xinyu Zhang, Zichu Fei
conference: "Arxiv"
year: 2023
bibkey: feng2023knowledge
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.03118"}
tags: ['Training Techniques', 'Model Architecture', 'GPT', 'Interpretability', 'Interpretability and Explainability', 'Prompting', 'Applications']
---
Large language models (LLMs), such as ChatGPT and GPT-4, are versatile and
can solve different tasks due to their emergent ability and generalizability.
However, LLMs sometimes lack domain-specific knowledge to perform tasks, which
would also cause hallucination during inference. In some previous works,
additional modules like graph neural networks (GNNs) are trained on retrieved
knowledge from external knowledge bases, aiming to mitigate the problem of
lacking domain-specific knowledge. However, incorporating additional modules:
1) would need retraining additional modules when encountering novel domains; 2)
would become a bottleneck since LLMs' strong abilities are not fully utilized
for retrieval. In this paper, we propose a paradigm, termed Knowledge Solver
(KSL), to teach LLMs to search for essential knowledge from external knowledge
bases by harnessing their own strong generalizability. Specifically, we design
a simple yet effective prompt to transform retrieval into a multi-hop decision
sequence, which empowers LLMs with searching knowledge ability in zero-shot
manner. Additionally, KSL is able to provide complete retrieval paths and
therefore increase explainability of LLMs' reasoning processes. We conduct
experiments on three datasets: CommonsenseQA, OpenbookQA, and MedQA-USMLE, and
found that our approach improves LLM baseline performance by a relatively large
margin.
