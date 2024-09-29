---
layout: publication
title: Hifi High45;information Attention Heads Hold For Parameter45;efficient Model Adaptation
authors: Gui Anchun, Xiao Han
conference: "Arxiv"
year: 2023
bibkey: gui2023high
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.04573"}
tags: ['Attention Mechanism', 'Fine Tuning', 'Model Architecture', 'RAG', 'Tools']
---
To fully leverage the advantages of large45;scale pre45;trained language models (PLMs) on downstream tasks it has become a ubiquitous adaptation paradigm to fine45;tune the entire parameters of PLMs. However this paradigm poses issues of inefficient updating and resource over45;consuming for fine45;tuning in data45;scarce and resource45;limited scenarios because of the large scale of parameters in PLMs. To alleviate these concerns in this paper we propose a parameter45;efficient fine45;tuning method HiFi that is only the highly informative and strongly correlated attention heads for the specific task are fine45;tuned. To search for those significant attention heads we develop a novel framework to analyze the effectiveness of heads. Specifically we first model the relationship between heads into a graph from two perspectives of information richness and correlation and then apply PageRank algorithm to determine the relative importance of each head. Extensive experiments on the GLUE benchmark demonstrate the effectiveness of our method and show that HiFi obtains state45;of45;the45;art performance over the prior baselines.
