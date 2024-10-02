---
layout: publication
title: 'Inversecoder: Unleashing The Power Of Instruction-tuned Code Llms With Inverse-instruct'
authors: Wu Yutong, Huang Di, Shi Wenxuan, Wang Wei, Gao Lingzhe, Liu Shihao, Nan Ziyuan, Yuan Kaizhao, Zhang Rui, Zhang Xishan, Du Zidong, Guo Qi, Pu Yewen, Yin Dawei, Hu Xing, Chen Yunji
conference: "Arxiv"
year: 2024
bibkey: wu2024unleashing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.05700"}
tags: ['Applications', 'Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
'Recent advancements in open-source code large language models (LLMs) have demonstrated remarkable coding abilities by fine-tuning on the data generated from powerful closed-source LLMs such as GPT-3.5 and GPT-4 for instruction tuning. This paper explores how to further improve an instruction-tuned code LLM by generating data from itself rather than querying closed-source LLMs. Our key observation is the misalignment between the translation of formal and informal languages: translating formal language (i.e., code) to informal language (i.e., natural language) is more straightforward than the reverse. Based on this observation, we propose INVERSE-INSTRUCT, which summarizes instructions from code snippets instead of the reverse. Specifically, given an instruction tuning corpus for code and the resulting instruction-tuned code LLM, we ask the code LLM to generate additional high-quality instructions for the original corpus through code summarization and self-evaluation. Then, we fine-tune the base LLM on the combination of the original corpus and the self-generated one, which yields a stronger instruction-tuned LLM. We present a series of code LLMs named InverseCoder, which surpasses the performance of the original code LLMs on a wide range of benchmarks, including Python text-to-code generation, multilingual coding, and data-science code generation.'
