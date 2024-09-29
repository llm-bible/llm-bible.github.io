---
layout: publication
title: Connecting Large Language Models With Evolutionary Algorithms Yields Powerful Prompt Optimizers
authors: Guo Qingyan, Wang Rui, Guo Junliang, Li Bei, Song Kaitao, Tan Xu, Liu Guoqing, Bian Jiang, Yang Yujiu
conference: "Arxiv"
year: 2023
bibkey: guo2023connecting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.08532"}
tags: ['Efficiency And Optimization', 'GPT', 'Model Architecture', 'Prompting', 'RAG', 'Tools']
---
Large Language Models (LLMs) excel in various tasks but they rely on carefully crafted prompts that often demand substantial human effort. To automate this process in this paper we propose a novel framework for discrete prompt optimization called EvoPrompt which borrows the idea of evolutionary algorithms (EAs) as they exhibit good performance and fast convergence. To enable EAs to work on discrete prompts which are natural language expressions that need to be coherent and human45;readable we connect LLMs with EAs. This approach allows us to simultaneously leverage the powerful language processing capabilities of LLMs and the efficient optimization performance of EAs. Specifically abstaining from any gradients or parameters EvoPrompt starts from a population of prompts and iteratively generates new prompts with LLMs based on the evolutionary operators improving the population based on the development set. We optimize prompts for both closed45; and open45;source LLMs including GPT45;3.5 and Alpaca on 31 datasets covering language understanding generation tasks as well as BIG45;Bench Hard (BBH) tasks. EvoPrompt significantly outperforms human45;engineered prompts and existing methods for automatic prompt generation (e.g. up to 2537; on BBH). Furthermore EvoPrompt demonstrates that connecting LLMs with EAs creates synergies which could inspire further research on the combination of LLMs and conventional algorithms.
