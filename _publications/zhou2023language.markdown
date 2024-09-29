---
layout: publication
title: Language Agent Tree Search Unifies Reasoning Acting and Planning in Language Models
authors: Zhou Andy, Yan Kai, Shlapentokh-rothman Michal, Wang Haohan, Wang Yu-xiong
conference: "Arxiv"
year: 2023
bibkey: zhou2023language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.04406"}
  - {name: "Code", url: "https://github.com/lapisrocks/LanguageAgentTreeSearch"}
tags: ['Agent', 'Agentic', 'Fine Tuning', 'GPT', 'Has Code', 'In Context Learning', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
While language models (LMs) have shown potential across a range of decision-making tasks their reliance on simple acting processes limits their broad deployment as autonomous agents. In this paper we introduce Language Agent Tree Search (LATS) -- the first general framework that synergizes the capabilities of LMs in reasoning acting and planning. By leveraging the in-context learning ability of LMs we integrate Monte Carlo Tree Search into LATS to enable LMs as agents along with LM-powered value functions and self-reflections for proficient exploration and enhanced decision-making. A key feature of our approach is the incorporation of an environment for external feedback which offers a more deliberate and adaptive problem-solving mechanism that surpasses the constraints of existing techniques. Our experimental evaluation across diverse domains including programming interactive question-answering (QA) web navigation and math validates the effectiveness and generality of LATS in decision-making while maintaining competitive or improved reasoning performance. Notably LATS achieves state-of-the-art pass64;1 accuracy (92.7) for programming on HumanEval with GPT-4 and demonstrates gradient-free performance (average score of 75.9) comparable to gradient-based fine-tuning for web navigation on WebShop with GPT-3.5. Code can be found at https://github.com/lapisrocks/LanguageAgentTreeSearch
