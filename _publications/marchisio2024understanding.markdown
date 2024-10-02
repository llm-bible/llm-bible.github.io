---
layout: publication
title: 'Understanding And Mitigating Language Confusion In Llms'
authors: Marchisio Kelly, Ko Wei-yin, Bérard Alexandre, Dehaze Théo, Ruder Sebastian
conference: "Arxiv"
year: 2024
bibkey: marchisio2024understanding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.20052"}
  - {name: "Code", url: "https://github.com/for-ai/language-confusion"}
tags: ['Applications', 'Few Shot', 'Fine Tuning', 'Has Code', 'In Context Learning', 'Merging', 'Prompting']
---
'We investigate a surprising limitation of LLMs: their inability to consistently generate text in a user''s desired language. We create the Language Confusion Benchmark (LCB) to evaluate such failures, covering 15 typologically diverse languages with existing and newly-created English and multilingual prompts. We evaluate a range of LLMs on monolingual and cross-lingual generation reflecting practical use cases, finding that Llama Instruct and Mistral models exhibit high degrees of language confusion and even the strongest models fail to consistently respond in the correct language. We observe that base and English-centric instruct models are more prone to language confusion, which is aggravated by complex prompts and high sampling temperatures. We find that language confusion can be partially mitigated via few-shot prompting, multilingual SFT and preference tuning. We release our language confusion benchmark, which serves as a first layer of efficient, scalable multilingual evaluation at https://github.com/for-ai/language-confusion.'
