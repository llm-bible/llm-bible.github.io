---
layout: publication
title: 'If Pigs Could Fly... Can Llms Logically Reason Through Counterfactuals?'
authors: Ishwar B Balappanawar, Vamshi Krishna Bonagiri, Anish R Joishy, Manas Gaur, Krishnaprasad Thirunarayan, Ponnurangam Kumaraguru
conference: "Arxiv"
year: 2025
bibkey: balappanawar2025if
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.22318"}
tags: ['Prompting', 'RAG', 'Applications', 'Reinforcement Learning']
---
Large Language Models (LLMs) demonstrate impressive reasoning capabilities in familiar contexts, but struggle when the context conflicts with their parametric knowledge. To investigate this phenomenon, we introduce CounterLogic, a dataset containing 1,800 examples across 9 logical schemas, explicitly designed to evaluate logical reasoning through counterfactual (hypothetical knowledge-conflicting) scenarios. Our systematic evaluation of 11 LLMs across 6 different datasets reveals a consistent performance degradation, with accuracies dropping by 27% on average when reasoning through counterfactual information. We propose Self-Segregate, a prompting method enabling metacognitive awareness (explicitly identifying knowledge conflicts) before reasoning. Our method dramatically narrows the average performance gaps from 27% to just 11%, while significantly increasing the overall accuracy (+7.5%). We discuss the implications of these findings and draw parallels to human cognitive processes, particularly on how humans disambiguate conflicting information during reasoning tasks. Our findings offer practical insights for understanding and enhancing LLMs reasoning capabilities in real-world applications, especially where models must logically reason independently of their factual knowledge.
