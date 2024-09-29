---
layout: publication
title: Look Before You Leap Towards Decision-aware And Generalizable Tool-usage For Large Language Models
authors: Gui Anchun, Li Jian, Dai Yong, Du Nan, Xiao Han
conference: "Arxiv"
year: 2024
bibkey: gui2024look
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.16696"}
tags: ['Attention Mechanism', 'GPT', 'In Context Learning', 'Model Architecture', 'Prompting', 'Tools']
---
Tool-augmented large language models (LLMs) are attracting widespread attention when accessing up-to-date knowledge and alleviating hallucination issues. Nowadays advanced closed-source LLMs (e.g. ChatGPT) have demonstrated surprising tool-usage capabilities through prompting and in-context learning techniques. To empower the capabilities of open-source LLMs (e.g. LLaMA) in manipulating tools current efforts focus on either template-driven or token-triggered tool-usage. However the former hampers LLMs flexibility to address diverse users queries due to constrained tool interactions while the latter limits the generalizability when engaging with new tools since tool-usage learning is based on task- and tool-specific datasets. To alleviate these concerns in this paper we propose a decision-aware and generalizable tool-usage framework (DEER). Specifically we first construct the tool-usage samples with multiple decision branches via an automatic generation pipeline thereby inspiring the decision-making awareness of LLMs under diverse scenarios. Meanwhile we propose a novel tool sampling strategy to enhance the generalizability of LLMs over unseen tools. Extensive experiments demonstrate that our proposed DEER is effective and significantly outperforms baselines across various datasets.
