---
layout: publication
title: Design2code How Far Are We From Automating Front45;end Engineering
authors: Si Chenglei, Zhang Yanzhe, Yang Zhengyuan, Liu Ruibo, Yang Diyi
conference: "Arxiv"
year: 2024
bibkey: si2024how
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.03163"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Multimodal Models', 'Prompting', 'Reinforcement Learning', 'Tools']
---
Generative AI has made rapid advancements in recent years achieving unprecedented capabilities in multimodal understanding and code generation. This can enable a new paradigm of front45;end development in which multimodal LLMs might directly convert visual designs into code implementations. In this work we formalize this as a Design2Code task and conduct comprehensive benchmarking. Specifically we manually curate a benchmark of 484 diverse real45;world webpages as test cases and develop a set of automatic evaluation metrics to assess how well current multimodal LLMs can generate the code implementations that directly render into the given reference webpages given the screenshots as input. We also complement automatic metrics with comprehensive human evaluations. We develop a suite of multimodal prompting methods and show their effectiveness on GPT45;4V and Gemini Pro Vision. We further finetune an open45;source Design2Code45;18B model that successfully matches the performance of Gemini Pro Vision. Both human evaluation and automatic metrics show that GPT45;4V performs the best on this task compared to other models. Moreover annotators think GPT45;4V generated webpages can replace the original reference webpages in 4937; of cases in terms of visual appearance and content; and perhaps surprisingly in 6437; of cases GPT45;4V generated webpages are considered better than the original reference webpages. Our fine45;grained break45;down metrics indicate that open45;source models mostly lag in recalling visual elements from the input webpages and in generating correct layout designs while aspects like text content and coloring can be drastically improved with proper finetuning.
