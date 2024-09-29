---
layout: publication
title: Struc45;bench Are Large Language Models Really Good At Generating Complex Structured Data
authors: Tang Xiangru, Zong Yiming, Phang Jason, Zhao Yilun, Zhou Wangchunshu, Cohan Arman, Gerstein Mark
conference: "Arxiv"
year: 2023
bibkey: tang2023struc
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.08963"}
  - {name: "Code", url: "https://github.com/gersteinlab/Struc&#45;Bench"}
tags: ['Ethics And Bias', 'GPT', 'Has Code', 'Model Architecture', 'Prompting', 'RAG']
---
Despite the remarkable capabilities of Large Language Models (LLMs) like GPT45;4 producing complex structured tabular data remains challenging. Our study assesses LLMs proficiency in structuring tables and introduces a novel fine45;tuning method cognizant of data structures to bolster their performance. We unveil Struc45;Bench a comprehensive benchmark featuring prominent LLMs (GPT45;NeoX45;20B GPT45;3.5 GPT45;4 and Vicuna) which spans text tables HTML and LaTeX formats. Our proposed FormatCoT aids in crafting format45;specific instructions from the intended outputs to populate this benchmark. Addressing the gap in task45;centered evaluation we propose two innovative metrics P45;Score (Prompting Score) and H45;Score (Heuristical Score) to more accurately gauge LLM performance. Our experiments show that applying our structure45;aware fine45;tuning to LLaMA45;7B leads to substantial performance gains outshining its LLM counterparts across most measures. In45;depth error analysis and creating an ability map across six dimensions 45;45; coverage formatting reasoning comprehension pragmatics and hallucination 45;45; highlight areas for future enhancements and suggest forthcoming research trajectories. Our code and models can be found at https://github.com/gersteinlab/Struc&#45;Bench.
