---
layout: publication
title: 'How Easily Do Irrelevant Inputs Skew The Responses Of Large Language Models?'
authors: Wu Siye, Xie Jian, Chen Jiangjie, Zhu Tinghui, Zhang Kai, Xiao Yanghua
conference: "Arxiv"
year: 2024
bibkey: wu2024how
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.03302"}
  - {name: "Code", url: "https://github.com/Di-viner/LLM-Robustness-to-Irrelevant-Information"}
tags: ['Has Code', 'RAG', 'Security', 'Tools', 'Uncategorized']
---
By leveraging the retrieval of information from external knowledge databases,
Large Language Models (LLMs) exhibit enhanced capabilities for accomplishing
many knowledge-intensive tasks. However, due to the inherent flaws of current
retrieval systems, there might exist irrelevant information within those
retrieving top-ranked passages. In this work, we present a comprehensive
investigation into the robustness of LLMs to different types of irrelevant
information under various conditions. We initially introduce a framework to
construct high-quality irrelevant information that ranges from semantically
unrelated, partially related, and related to questions. Furthermore, our
analysis demonstrates that the constructed irrelevant information not only
scores highly on similarity metrics, being highly retrieved by existing
systems, but also bears semantic connections to the context. Our investigation
reveals that current LLMs still face challenges in discriminating highly
semantically related information and can be easily distracted by these
irrelevant yet misleading content. Besides, we also find that current solutions
for handling irrelevant information have limitations in improving the
robustness of LLMs to such distractions. All the resources are available on
GitHub at https://github.com/Di-viner/LLM-Robustness-to-Irrelevant-Information.
