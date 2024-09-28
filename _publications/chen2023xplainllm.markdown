---
layout: publication
title: XplainLLM A QA Explanation Dataset for Understanding LLM Decision-Making
authors: Chen Zichen, Chen Jianda, Gaidhani Mitali, Singh Ambuj, Sra Misha
conference: "Arxiv"
year: 2023
bibkey: chen2023xplainllm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.08614"}
  - {name: "Code", url: "https://github.com/chen-zichen/XplainLLM_dataset.git"}
tags: ['Arxiv', 'Has Code', 'Interpretability', 'A', 'Explainability']
---
Large Language Models (LLMs) have recently made impressive strides in natural language understanding tasks. Despite their remarkable performance understanding their decision-making process remains a big challenge. In this paper we look into bringing some transparency to this process by introducing a new explanation dataset for question answering (QA) tasks that integrates knowledge graphs (KGs) in a novel way. Our dataset includes 12102 question-answer-explanation (QAE) triples. Each explanation in the dataset links the LLMs reasoning to entities and relations in the KGs. The explanation component includes a why-choose explanation a why-not-choose explanation and a set of reason-elements that underlie the LLMs decision. We leverage KGs and graph attention networks (GAT) to find the reason-elements and transform them into why-choose and why-not-choose explanations that are comprehensible to humans. Through quantitative and qualitative evaluations we demonstrate the potential of our dataset to improve the in-context learning of LLMs and enhance their interpretability and explainability. Our work contributes to the field of explainable AI by enabling a deeper understanding of the LLMs decision-making process to make them more transparent and thereby potentially more reliable to researchers and practitioners alike. Our dataset is available at https://github.com/chen-zichen/XplainLLM_dataset.git
