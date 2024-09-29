---
layout: publication
title: Symbolic Working Memory Enhances Language Models For Complex Rule Application
authors: Wang Siyuan, Wei Zhongyu, Choi Yejin, Ren Xiang
conference: "Arxiv"
year: 2024
bibkey: wang2024symbolic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.13654"}
  - {name: "Code", url: "https://github.com/SiyuanWangw/RuleApplication&#125;.&#125;"}
tags: ['Has Code', 'Pretraining Methods', 'Reinforcement Learning', 'Security', 'Tools']
---
Large Language Models (LLMs) have shown remarkable reasoning performance but struggle with multi45;step deductive reasoning involving a series of rule application steps especially when rules are presented non45;sequentially. Our preliminary analysis shows that while LLMs excel in single45;step rule application their performance drops significantly in multi45;step scenarios due to the challenge in rule grounding. It requires anchoring the applicable rule and supporting facts at each step amidst multiple input rules facts and inferred facts. To address this we propose augmenting LLMs with external working memory and introduce a neurosymbolic framework for rule application. The memory stores facts and rules in both natural language and symbolic forms enabling precise tracking. Utilizing this memory our framework iteratively performs symbolic rule grounding and LLM45;based rule implementation. The former matches predicates and variables of symbolic rules and facts to ground applicable rules at each step. Experiments indicate our frameworks effectiveness in rule application and its robustness across various steps and settings~footnote123;Code and data are available at url123;https://github.com/SiyuanWangw/RuleApplication&#125;.&#125;.
