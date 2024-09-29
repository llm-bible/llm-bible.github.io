---
layout: publication
title: Loogle Can Long45;context Language Models Understand Long Contexts
authors: Li Jiaqi, Wang Mengmeng, Zheng Zilong, Zhang Muhan
conference: "Arxiv"
year: 2023
bibkey: li2023can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.04939"}
tags: ['Prompting']
---
Large language models (LLMs) despite their impressive performance in various language tasks are typically limited to processing texts within context45;window size. This limitation has spurred significant research efforts to enhance LLMs long45;context understanding with high45;quality long45;sequence benchmarks. However prior datasets in this regard suffer from shortcomings such as short context length compared to the context window of modern LLMs; outdated documents that have data leakage problems; and an emphasis on short dependency tasks rather than long dependency tasks. In this paper we present LooGLE a Long Context Generic Language Evaluation benchmark for LLMs long context understanding. LooGLE features relatively new documents post45;2022 with over 24000 tokens per document and 6000 newly generated questions spanning diverse domains. Human annotators meticulously crafted more than 1100 high45;quality question45;answer pairs to meet the long dependency requirements. These pairs underwent thorough cross45;validation yielding the most precise assessment of LLMs long dependency capabilities. The evaluation of eight state45;of45;the45;art LLMs on LooGLE revealed key findings (i) commercial models outperformed open45;sourced models; (ii) LLMs excelled in short dependency tasks like short question45;answering and cloze tasks but struggled with more intricate long dependency tasks; (iii) in45;context learning and chaining thoughts offered only marginal improvements; (iv) retrieval45;based techniques demonstrated substantial benefits for short question45;answering while strategies for extending context window length had limited impact on long context understanding. As such LooGLE not only provides a systematic and comprehensive evaluation schema on long45;context LLMs but also sheds light on future development of enhanced models towards true long45;context understanding.
