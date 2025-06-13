---
layout: publication
title: 'Schema As Parameterized Tools For Universal Information Extraction'
authors: Sheng Liang, Yongyue Zhang, Yaxiong Wu, Ruiming Tang, Yong Liu
conference: "Arxiv"
year: 2025
bibkey: liang2025schema
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2506.01276'}
tags: ['Fine-Tuning', 'Prompting', 'In-Context Learning', 'Tools']
---
Universal information extraction (UIE) primarily employs an extractive generation approach with large language models (LLMs), typically outputting structured information based on predefined schemas such as JSON or tables. UIE suffers from a lack of adaptability when selecting between predefined schemas and on-the-fly schema generation within the in-context learning paradigm, especially when there are numerous schemas to choose from. In this paper, we propose a unified adaptive text-to-structure generation framework, called Schema as Parameterized Tools (SPT), which reimagines the tool-calling capability of LLMs by treating predefined schemas as parameterized tools for tool selection and parameter filling. Specifically, our SPT method can be applied to unify closed, open, and on-demand IE tasks by adopting Schema Retrieval by fetching the relevant schemas from a predefined pool, Schema Filling by extracting information and filling slots as with tool parameters, or Schema Generation by synthesizing new schemas with uncovered cases. Experiments show that the SPT method can handle four distinct IE tasks adaptively, delivering robust schema retrieval and selection performance. SPT also achieves comparable extraction performance to LoRA baselines and current leading UIE systems with significantly fewer trainable parameters.
