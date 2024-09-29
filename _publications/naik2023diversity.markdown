---
layout: publication
title: 'Diversity Of Thought Improves Reasoning Abilities Of Llms'
authors: Naik Ranjita, Chandrasekaran Varun, Yuksekgonul Mert, Palangi Hamid, Nushi Besmira
conference: "Arxiv"
year: 2023
bibkey: naik2023diversity
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.07088"}
tags: ['Pretraining Methods', 'Prompting', 'RAG']
---
Large language models (LLMs) are documented to struggle in settings that require complex reasoning. Nevertheless instructing the model to break down the problem into smaller reasoning steps or ensembling various generations through modifying decoding steps boosts performance. However these methods assume that the input prompt is fixed and expect the decoding strategies to introduce the diversity needed for ensembling. In this work we discuss how one can create and leverage variations of the input prompt as a means of diversity of thought. We propose a method that automatically improves prompt diversity by soliciting feedback from the LLM to ideate approaches that are apt for the problem. We then ensemble the diverse prompts in our method DIVSE (DIVerse reasoning path Self-Ensemble) across multiple inference calls or use diverse approaches within a single inference call; we call the latter IDIV-SE (In-call DIVerse reasoning path Self-Ensemble). Apart from our approaches outperforming prior work DIV-SE(in particular) advances state-of-the-art performance on the challenging planning and graph coloring benchmarks. Our results improve the Pareto frontier of the accuracy-cost trade-off.
