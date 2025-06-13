---
layout: publication
title: 'Zero-resource Hallucination Detection For Text Generation Via Graph-based Contextual Knowledge Triples Modeling'
authors: Xinyue Fang, Zhen Huang, Zhiliang Tian, Minghui Fang, Ziyi Pan, Quntian Fang, Zhihua Wen, Hengyue Pan, Dongsheng Li
conference: "Arxiv"
year: 2024
bibkey: fang2024zero
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.11283'}
tags: ['Reinforcement Learning', 'Language Modeling', 'Applications']
---
LLMs obtain remarkable performance but suffer from hallucinations. Most
research on detecting hallucination focuses on the questions with short and
concrete correct answers that are easy to check the faithfulness. Hallucination
detections for text generation with open-ended answers are more challenging.
Some researchers use external knowledge to detect hallucinations in generated
texts, but external resources for specific scenarios are hard to access. Recent
studies on detecting hallucinations in long text without external resources
conduct consistency comparison among multiple sampled outputs. To handle long
texts, researchers split long texts into multiple facts and individually
compare the consistency of each pairs of facts. However, these methods (1)
hardly achieve alignment among multiple facts; (2) overlook dependencies
between multiple contextual facts. In this paper, we propose a graph-based
context-aware (GCA) hallucination detection for text generations, which aligns
knowledge facts and considers the dependencies between contextual knowledge
triples in consistency comparison. Particularly, to align multiple facts, we
conduct a triple-oriented response segmentation to extract multiple knowledge
triples. To model dependencies among contextual knowledge triple (facts), we
construct contextual triple into a graph and enhance triples' interactions via
message passing and aggregating via RGCN. To avoid the omission of knowledge
triples in long text, we conduct a LLM-based reverse verification via
reconstructing the knowledge triples. Experiments show that our model enhances
hallucination detection and excels all baselines.
