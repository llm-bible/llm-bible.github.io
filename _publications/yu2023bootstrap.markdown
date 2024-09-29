---
layout: publication
title: Metamath Bootstrap Your Own Mathematical Questions For Large Language Models
authors: Yu Longhui, Jiang Weisen, Shi Han, Yu Jincheng, Liu Zhengying, Zhang Yu, Kwok James T., Li Zhenguo, Weller Adrian, Liu Weiyang
conference: "Arxiv"
year: 2023
bibkey: yu2023bootstrap
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.12284"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques']
---
Large language models (LLMs) have pushed the limits of natural language understanding and exhibited excellent problem45;solving ability. Despite the great success most existing open45;source LLMs (e.g. LLaMA45;2) are still far away from satisfactory for solving mathematical problem due to the complex reasoning procedures. To bridge this gap we propose MetaMath a fine45;tuned language model that specializes in mathematical reasoning. Specifically we start by bootstrapping mathematical questions by rewriting the question from multiple perspectives without extra knowledge which results in a new dataset called MetaMathQA. Then we fine45;tune the LLaMA45;2 models on MetaMathQA. Experimental results on two popular benchmarks (i.e. GSM8K and MATH) for mathematical reasoning demonstrate that MetaMath outperforms a suite of open45;source LLMs by a significant margin. Our MetaMath45;7B model achieves 66.437; on GSM8K and 19.437; on MATH exceeding the state45;of45;the45;art models of the same size by 11.537; and 8.737;. Particularly MetaMath45;70B achieves an accuracy of 82.337; on GSM8K slightly better than GPT45;3.545;Turbo. We release all the MetaMathQA dataset the MetaMath models with different model sizes and the training code for public use.
