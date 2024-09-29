---
layout: publication
title: Pmc45;llama Towards Building Open45;source Language Models For Medicine
authors: Wu Chaoyi, Lin Weixiong, Zhang Xiaoman, Zhang Ya, Wang Yanfeng, Xie Weidi
conference: "Arxiv"
year: 2023
bibkey: wu2023pmc
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2304.14454"}
  - {name: "Code", url: "https://github.com/chaoyi&#45;wu/PMC&#45;LLaMA"}
tags: ['Applications', 'GPT', 'Has Code', 'Model Architecture']
---
Recently Large Language Models (LLMs) have showcased remarkable capabilities in natural language understanding. While demonstrating proficiency in everyday conversations and question45;answering situations these models frequently struggle in domains that require precision such as medical applications due to their lack of domain45;specific knowledge. In this paper we describe the procedure for building a powerful open45;source language model specifically designed for medicine applications termed as PMC45;LLaMA. Our contributions are threefold (i) we systematically investigate the process of adapting a general45;purpose foundation language model towards medical domain this involves data45;centric knowledge injection through the integration of 4.8M biomedical academic papers and 30K medical textbooks as well as comprehensive fine45;tuning for alignment with domain45;specific instructions; (ii) we contribute a large45;scale comprehensive dataset for instruction tuning. This dataset encompasses medical question45;answering (QA) rationale for reasoning and conversational dialogues comprising a total of 202M tokens; (iii) we conduct thorough ablation studies to demonstrate the effectiveness of each proposed component. While evaluating on various public medical question45;answering benchmarks our lightweight PMCLLaMA which consists of only 13 billion parameters exhibits superior performance even surpassing ChatGPT. All models codes datasets can be found in https://github.com/chaoyi&#45;wu/PMC&#45;LLaMA.
