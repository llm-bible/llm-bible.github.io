---
layout: publication
title: HAMMR: Hierarchical Multimodal React Agents For Generic VQA
authors: Castrejon Lluis, Mensink Thomas, Zhou Howard, Ferrari Vittorio, Araujo Andre, Uijlings Jasper
conference: "Arxiv"
year: 2024
bibkey: castrejon2024hierarchical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.05465"}
tags: ['Agentic', 'Applications', 'Multimodal Models', 'Reinforcement Learning', 'Tools']
---
Combining Large Language Models (LLMs) with external specialized tools (LLMs+tools) is a recent paradigm to solve multimodal tasks such as Visual Question Answering (VQA). While this approach was demonstrated to work well when optimized and evaluated for each individual benchmark in practice it is crucial for the next generation of real-world AI systems to handle a broad range of multimodal problems. Therefore we pose the VQA problem from a unified perspective and evaluate a single system on a varied suite of VQA tasks including counting spatial reasoning OCR-based reasoning visual pointing external knowledge and more. In this setting we demonstrate that naively applying the LLM+tools approach using the combined set of all tools leads to poor results. This motivates us to introduce HAMMR HierArchical MultiModal React. We start from a multimodal ReAct-based system and make it hierarchical by enabling our HAMMR agents to call upon other specialized agents. This enhances the compositionality of the LLM+tools approach which we show to be critical for obtaining high accuracy on generic VQA. Concretely on our generic VQA suite HAMMR outperforms the naive LLM+tools approach by 19.537;. Additionally HAMMR achieves state-of-the-art results on this task outperforming the generic standalone PaLI-X VQA model by 5.037;.
