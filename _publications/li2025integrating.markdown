---
layout: publication
title: 'Incomes: Integrating Compression And Selection Mechanisms Into Llms For Efficient Model Editing'
authors: Shuaiyi Li, Zhisong Zhang, Yang Deng, Chenlong Deng, Tianqing Fang, Hongming Zhang, Haitao Mi, Dong Yu, Wai Lam
conference: "Arxiv"
year: 2025
bibkey: li2025integrating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.22156"}
tags: ['Tools', 'Efficiency and Optimization', 'RAG', 'Model Architecture', 'Attention Mechanism', 'Prompting', 'In-Context Learning']
---
Although existing model editing methods perform well in recalling exact edit facts, they often struggle in complex scenarios that require deeper semantic understanding rather than mere knowledge regurgitation. Leveraging the strong contextual reasoning abilities of large language models (LLMs), in-context learning (ICL) becomes a promising editing method by comprehending edit information through context encoding. However, this method is constrained by the limited context window of LLMs, leading to degraded performance and efficiency as the number of edits increases. To overcome this limitation, we propose InComeS, a flexible framework that enhances LLMs' ability to process editing contexts through explicit compression and selection mechanisms. Specifically, InComeS compresses each editing context into the key-value (KV) cache of a special gist token, enabling efficient handling of multiple edits without being restricted by the model's context window. Furthermore, specialized cross-attention modules are added to dynamically select the most relevant information from the gist pools, enabling adaptive and effective utilization of edit information. We conduct experiments on diverse model editing benchmarks with various editing formats, and the results demonstrate the effectiveness and efficiency of our method.
