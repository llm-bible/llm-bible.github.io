---
layout: publication
title: FAITHSCORE Evaluating Hallucinations In Large Vision45;language Models
authors: Liqiang Jing, Ruosen Li, Yunmo Chen, Mengzhao Jia, Xinya Du
conference: "Arxiv"
year: 2023
bibkey: jing2023evaluating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2311.01477v1"}
tags: ['Multimodal Models']
---
We introduce FAITHSCORE (Faithfulness to Atomic Image Facts Score) a reference45;free and fine45;grained evaluation metric that measures the faithfulness of the generated free45;form answers from large vision45;language models (LVLMs). The FAITHSCORE evaluation first identifies sub45;sentences containing descriptive statements that need to be verified then extracts a comprehensive list of atomic facts from these sub45;sentences and finally conducts consistency verification between fine45;grained atomic facts and the input image. Meta45;evaluation demonstrates that our metric highly correlates with human judgments of faithfulness. We collect two benchmark datasets (i.e. LLaVA45;1k and MSCOCO45;Cap) for evaluating LVLMs instruction45;following hallucinations. We measure hallucinations in state45;of45;the45;art LVLMs with FAITHSCORE on the datasets. Results reveal that current systems are prone to generate hallucinated content unfaithful to the image which leaves room for future improvements. Further we find that current LVLMs despite doing well on color and counting still struggle with long answers relations and multiple objects.
