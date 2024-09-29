---
layout: publication
title: Bad Actor Good Advisor Exploring The Role Of Large Language Models In Fake News Detection
authors: Hu Beizhe, Sheng Qiang, Cao Juan, Shi Yuhui, Li Yang, Wang Danding, Qi Peng
conference: "AAAI"
year: 2023
bibkey: hu2023bad
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.12247"}
tags: ['BERT', 'Distillation', 'Efficiency And Optimization', 'GPT', 'Model Architecture', 'Reinforcement Learning']
---
Detecting fake news requires both a delicate sense of diverse clues and a profound understanding of the real45;world background which remains challenging for detectors based on small language models (SLMs) due to their knowledge and capability limitations. Recent advances in large language models (LLMs) have shown remarkable performance in various tasks but whether and how LLMs could help with fake news detection remains underexplored. In this paper we investigate the potential of LLMs in fake news detection. First we conduct an empirical study and find that a sophisticated LLM such as GPT 3.5 could generally expose fake news and provide desirable multi45;perspective rationales but still underperforms the basic SLM fine45;tuned BERT. Our subsequent analysis attributes such a gap to the LLMs inability to select and integrate rationales properly to conclude. Based on these findings we propose that current LLMs may not substitute fine45;tuned SLMs in fake news detection but can be a good advisor for SLMs by providing multi45;perspective instructive rationales. To instantiate this proposal we design an adaptive rationale guidance network for fake news detection (ARG) in which SLMs selectively acquire insights on news analysis from the LLMs rationales. We further derive a rationale45;free version of ARG by distillation namely ARG45;D which services cost45;sensitive scenarios without querying LLMs. Experiments on two real45;world datasets demonstrate that ARG and ARG45;D outperform three types of baseline methods including SLM45;based LLM45;based and combinations of small and large language models.
