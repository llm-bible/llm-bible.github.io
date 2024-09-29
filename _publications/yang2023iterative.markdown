---
layout: publication
title: 'Iterative Forward Tuning Boosts In-context Learning In Language Models'
authors: Yang Jiaxi, Hui Binyuan, Yang Min, Wang Bailin, Li Bowen, Li Binhua, Huang Fei, Li Yongbin
conference: "Arxiv"
year: 2023
bibkey: yang2023iterative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.13016"}
tags: ['Attention Mechanism', 'In Context Learning', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Tools', 'Training Techniques', 'Transformer']
---
Despite the advancements in in-context learning (ICL) for large language models (LLMs) current research centers on specific prompt engineering such as demonstration selection with the expectation that a single iteration of demonstrations processing can generalize effectively to a given test sample. However this perspective overlooks the potential benefits derived from multiple iterations involving demonstrations a practice aligning more closely with the iterative decision-making process exhibited by humans who often learn through analogy. In this study we introduce a novel two-stage framework to boost ICL in LLMs. Specifically our framework delineates the ICL process into two distinct stages Deep-Thinking and test stages. The Deep-Thinking stage incorporates a unique attention mechanism i.e. iterative enhanced attention which enables multiple rounds of information accumulation. This mechanism operates by manipulating the Key-Value matrices without training fostering enhanced understanding capabilities in LLMs by thinking demonstrations multiple times. We evaluated Deep-Thinking across a range of benchmarks and LLMs showing its superior performance over vanilla ICL methods and its effectiveness in challenging tasks where demonstration selection is infeasible.
