---
layout: publication
title: "Concise And Organized Perception Facilitates Reasoning In Large Language Models"
authors: Liu Junjie, Yan Shaotian, Shen Chen, Xie Liang, Wang Wenxiao, Ye Jieping
conference: "Arxiv"
year: 2023
bibkey: liu2023concise
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.03309"}
tags: ['Attention Mechanism', 'Ethics And Bias', 'Model Architecture', 'Prompting']
---
Exploiting large language models (LLMs) to tackle reasoning has garnered growing attention. It still remains highly challenging to achieve satisfactory results in complex logical problems characterized by plenty of premises within the prompt and requiring multi-hop reasoning. In particular the reasoning capabilities of LLMs are brittle to disorder and distractibility. In this work we first examine the mechanism from the perspective of information flow and reveal that LLMs exhibit failure patterns akin to human-like cognitive biases when dealing with disordered and irrelevant content in reasoning tasks. However in contrast to LLMs disordered and irrelevant content does not significantly decrease human performance as humans have a propensity to distill the most relevant information and systematically organize their thoughts aiding them in responding to questions. Stem from that we further propose a novel reasoning approach named Concise and Organized Perception (COP). COP carefully analyzes the given statements to identify the most pertinent information while eliminating redundancy efficiently. It then prompts the LLMs in a more organized form that adapts to the models inference process. By perceiving concise and organized context the reasoning abilities of LLMs can be better elicited. Extensive experimental results on several popular logical benchmarks (ProofWriter PrOntoQA PrOntoQA-OOD and FOLIO) and math benchmark (DI-GSM) show that COP significantly outperforms previous state-of-the-art methods.
