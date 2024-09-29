---
layout: publication
title: Self45;distillation For Model Stacking Unlocks Cross45;lingual NLU In 200+ Languages
authors: Schmidt Fabian David, Borchert Philipp, Vulić Ivan, Glavaš Goran
conference: "Arxiv"
year: 2024
bibkey: schmidt2024self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.12739"}
tags: ['Applications', 'Distillation', 'Efficiency And Optimization', 'Language Modeling', 'Merging', 'Reinforcement Learning', 'Training Techniques']
---
LLMs have become a go45;to solution not just for text generation but also for natural language understanding (NLU) tasks. Acquiring extensive knowledge through language modeling on web45;scale corpora they excel on English NLU yet struggle to extend their NLU capabilities to underrepresented languages. In contrast machine translation models (MT) produce excellent multilingual representations resulting in strong translation performance even for low45;resource languages. MT encoders however lack the knowledge necessary for comprehensive NLU that LLMs obtain through language modeling training on immense corpora. In this work we get the best both worlds by integrating MT encoders directly into LLM backbones via sample45;efficient self45;distillation. The resulting MT45;LLMs preserve the inherent multilingual representational alignment from the MT encoder allowing lower45;resource languages to tap into the rich knowledge embedded in English45;centric LLMs. Merging the MT encoder and LLM in a single model we mitigate the propagation of translation errors and inference overhead of MT decoding inherent to discrete translation45;based cross45;lingual transfer (e.g. translate45;test). Evaluation spanning three prominent NLU tasks and 127 predominantly low45;resource languages renders MT45;LLMs highly effective in cross45;lingual transfer. MT45;LLMs substantially and consistently outperform translate45;test based on the same MT model showing that we truly unlock multilingual language understanding for LLMs.
