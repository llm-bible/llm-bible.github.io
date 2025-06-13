---
layout: publication
title: 'Prompting Llms: Length Control For Isometric Machine Translation'
authors: Dávid Javorský, Ondřej Bojar, François Yvon
conference: "Arxiv"
year: 2025
bibkey: javorský2025prompting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.04855"}
tags: ['SLT', 'Applications', 'Few-Shot', 'Prompting', 'In-Context Learning']
---
In this study, we explore the effectiveness of isometric machine translation across multiple language pairs (En\\(\to\\)De, En\\(\to\\)Fr, and En\\(\to\\)Es) under the conditions of the IWSLT Isometric Shared Task 2022. Using eight open-source large language models (LLMs) of varying sizes, we investigate how different prompting strategies, varying numbers of few-shot examples, and demonstration selection influence translation quality and length control. We discover that the phrasing of instructions, when aligned with the properties of the provided demonstrations, plays a crucial role in controlling the output length. Our experiments show that LLMs tend to produce shorter translations only when presented with extreme examples, while isometric demonstrations often lead to the models disregarding length constraints. While few-shot prompting generally enhances translation quality, further improvements are marginal across 5, 10, and 20-shot settings. Finally, considering multiple outputs allows to notably improve overall tradeoff between the length and quality, yielding state-of-the-art performance for some language pairs.
