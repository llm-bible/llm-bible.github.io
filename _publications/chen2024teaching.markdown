---
layout: publication
title: "Teaching Large Language Models To Express Knowledge Boundary From Their Own Signals"
authors: Chen Lida, Liang Zujie, Wang Xintao, Liang Jiaqing, Xiao Yanghua, Wei Feng, Chen Jinglei, Hao Zhenghong, Han Bing, Wang Wei
conference: "Arxiv"
year: 2024
bibkey: chen2024teaching
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.10881"}
tags: ['Pretraining Methods', 'RAG', 'Training Techniques']
---
Large language models (LLMs) have achieved great success but their occasional content fabrication or hallucination limits their practical application. Hallucination arises because LLMs struggle to admit ignorance due to inadequate training on knowledge boundaries. We call it a limitation of LLMs that they can not accurately express their knowledge boundary answering questions they know while admitting ignorance to questions they do not know. In this paper we aim to teach LLMs to recognize and express their knowledge boundary so they can reduce hallucinations caused by fabricating when they do not know. We propose CoKE which first probes LLMs knowledge boundary via internal confidence given a set of questions and then leverages the probing results to elicit the expression of the knowledge boundary. Extensive experiments show CoKE helps LLMs express knowledge boundaries answering known questions while declining unknown ones significantly improving in-domain and out-of-domain performance.
