---
layout: publication
title: Beamaggr Beam Aggregation Reasoning Over Multi45;source Knowledge For Multi45;hop Question Answering
authors: Chu Zheng, Chen Jingchang, Chen Qianglong, Wang Haotian, Zhu Kun, Du Xiyuan, Yu Weijiang, Liu Ming, Qin Bing
conference: "Arxiv"
year: 2024
bibkey: chu2024beam
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.19820"}
tags: ['Applications', 'Tools']
---
Large language models (LLMs) have demonstrated strong reasoning capabilities. Nevertheless they still suffer from factual errors when tackling knowledge45;intensive tasks. Retrieval45;augmented reasoning represents a promising approach. However significant challenges still persist including inaccurate and insufficient retrieval for complex questions as well as difficulty in integrating multi45;source knowledge. To address this we propose Beam Aggregation Reasoning BeamAggR a reasoning framework for knowledge45;intensive multi45;hop QA. BeamAggR explores and prioritizes promising answers at each hop of question. Concretely we parse the complex questions into trees which include atom and composite questions followed by bottom45;up reasoning. For atomic questions the LLM conducts reasoning on multi45;source knowledge to get answer candidates. For composite questions the LLM combines beam candidates explores multiple reasoning paths through probabilistic aggregation and prioritizes the most promising trajectory. Extensive experiments on four open45;domain multi45;hop reasoning datasets show that our method significantly outperforms SOTA methods by 8.537;. Furthermore our analysis reveals that BeamAggR elicits better knowledge collaboration and answer aggregation.
