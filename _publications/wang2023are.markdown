---
layout: publication
title: NEWTON Are Large Language Models Capable Of Physical Reasoning
authors: Wang Yi Ru, Duan Jiafei, Fox Dieter, Srinivasa Siddhartha
conference: "Arxiv"
year: 2023
bibkey: wang2023are
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.07018"}
  - {name: "Code", url: "https://newtonreasoning.github.io"}
tags: ['Fine Tuning', 'GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Tools']
---
Large Language Models (LLMs) through their contextualized representations have been empirically proven to encapsulate syntactic semantic word sense and common45;sense knowledge. However there has been limited exploration of their physical reasoning abilities specifically concerning the crucial attributes for comprehending everyday objects. To address this gap we introduce NEWTON a repository and benchmark for evaluating the physics reasoning skills of LLMs. Further to enable domain45;specific adaptation of this benchmark we present a pipeline to enable researchers to generate a variant of this benchmark that has been customized to the objects and attributes relevant for their application. The NEWTON repository comprises a collection of 2800 object45;attribute pairs providing the foundation for generating infinite45;scale assessment templates. The NEWTON benchmark consists of 160K QA questions curated using the NEWTON repository to investigate the physical reasoning capabilities of several mainstream language models across foundational explicit and implicit reasoning tasks. Through extensive empirical analysis our results highlight the capabilities of LLMs for physical reasoning. We find that LLMs like GPT45;4 demonstrate strong reasoning capabilities in scenario45;based tasks but exhibit less consistency in object45;attribute reasoning compared to humans (5037; vs. 8437;). Furthermore the NEWTON platform demonstrates its potential for evaluating and enhancing language models paving the way for their integration into physically grounded settings such as robotic manipulation. Project site https://newtonreasoning.github.io
