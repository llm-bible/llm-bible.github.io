---
layout: publication
title: Reasoning On Graphs\: Faithful And Interpretable Large Language Model Reasoning
authors: Luo Linhao, Li Yuan-fang, Haffari Gholamreza, Pan Shirui
conference: "Arxiv"
year: 2023
bibkey: luo2023reasoning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.01061"}
tags: ['Applications', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Large language models (LLMs) have demonstrated impressive reasoning abilities in complex tasks. However they lack up-to-date knowledge and experience hallucinations during reasoning which can lead to incorrect reasoning processes and diminish their performance and trustworthiness. Knowledge graphs (KGs) which capture vast amounts of facts in a structured format offer a reliable source of knowledge for reasoning. Nevertheless existing KG-based LLM reasoning methods only treat KGs as factual knowledge bases and overlook the importance of their structural information for reasoning. In this paper we propose a novel method called reasoning on graphs (RoG) that synergizes LLMs with KGs to enable faithful and interpretable reasoning. Specifically we present a planning-retrieval-reasoning framework where RoG first generates relation paths grounded by KGs as faithful plans. These plans are then used to retrieve valid reasoning paths from the KGs for LLMs to conduct faithful reasoning. Furthermore RoG not only distills knowledge from KGs to improve the reasoning ability of LLMs through training but also allows seamless integration with any arbitrary LLMs during inference. Extensive experiments on two benchmark KGQA datasets demonstrate that RoG achieves state-of-the-art performance on KG reasoning tasks and generates faithful and interpretable reasoning results.
