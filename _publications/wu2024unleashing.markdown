---
layout: publication
title: Inversecoder Unleashing The Power Of Instruction45;tuned Code Llms With Inverse45;instruct
authors: Wu Yutong, Huang Di, Shi Wenxuan, Wang Wei, Gao Lingzhe, Liu Shihao, Nan Ziyuan, Yuan Kaizhao, Zhang Rui, Zhang Xishan, Du Zidong, Guo Qi, Pu Yewen, Yin Dawei, Hu Xing, Chen Yunji
conference: "Arxiv"
year: 2024
bibkey: wu2024unleashing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.05700"}
tags: ['Applications', 'GPT', 'Model Architecture']
---
Recent advancements in open45;source code large language models (LLMs) have demonstrated remarkable coding abilities by fine45;tuning on the data generated from powerful closed45;source LLMs such as GPT45;3.5 and GPT45;4 for instruction tuning. This paper explores how to further improve an instruction45;tuned code LLM by generating data from itself rather than querying closed45;source LLMs. Our key observation is the misalignment between the translation of formal and informal languages translating formal language (i.e. code) to informal language (i.e. natural language) is more straightforward than the reverse. Based on this observation we propose INVERSE45;INSTRUCT which summarizes instructions from code snippets instead of the reverse. Specifically given an instruction tuning corpus for code and the resulting instruction45;tuned code LLM we ask the code LLM to generate additional high45;quality instructions for the original corpus through code summarization and self45;evaluation. Then we fine45;tune the base LLM on the combination of the original corpus and the self45;generated one which yields a stronger instruction45;tuned LLM. We present a series of code LLMs named InverseCoder which surpasses the performance of the original code LLMs on a wide range of benchmarks including Python text45;to45;code generation multilingual coding and data45;science code generation.
