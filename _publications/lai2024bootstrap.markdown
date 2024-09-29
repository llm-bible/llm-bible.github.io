---
layout: publication
title: Autowebglm Bootstrap And Reinforce A Large Language Model45;based Web Navigating Agent
authors: Lai Hanyu, Liu Xiao, Iong Iat Long, Yao Shuntian, Chen Yuxuan, Shen Pengbo, Yu Hao, Zhang Hanchen, Zhang Xiaohan, Dong Yuxiao, Tang Jie
conference: "Arxiv"
year: 2024
bibkey: lai2024bootstrap
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.03648"}
  - {name: "Code", url: "https://github.com/THUDM/AutoWebGLM&#125;"}
tags: ['Agentic', 'GPT', 'Has Code', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques']
---
Large language models (LLMs) have fueled many intelligent agent tasks such as web navigation 45;45; but most existing agents perform far from satisfying in real45;world webpages due to three factors (1) the versatility of actions on webpages (2) HTML text exceeding model processing capacity and (3) the complexity of decision45;making due to the open45;domain nature of web. In light of the challenge we develop AutoWebGLM a GPT45;445;outperforming automated web navigation agent built upon ChatGLM345;6B. Inspired by human browsing patterns we design an HTML simplification algorithm to represent webpages preserving vital information succinctly. We employ a hybrid human45;AI method to build web browsing data for curriculum training. Then we bootstrap the model by reinforcement learning and rejection sampling to further facilitate webpage comprehension browser operations and efficient task decomposition by itself. For testing we establish a bilingual benchmark 45;45; AutoWebBench 45;45; for real45;world web browsing tasks. We evaluate AutoWebGLM across diverse web navigation benchmarks revealing its improvements but also underlying challenges to tackle real environments. Related code model and data will be released at url123;https://github.com/THUDM/AutoWebGLM&#125;.
