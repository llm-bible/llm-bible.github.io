---
layout: publication
title: Hint45;before45;solving Prompting Guiding Llms To Effectively Utilize Encoded Knowledge
authors: Fu Jinlan, Huangfu Shenzhen, Yan Hang, Ng See-kiong, Qiu Xipeng
conference: "Arxiv"
year: 2024
bibkey: fu2024hint
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.14310"}
  - {name: "Code", url: "https://github.com/jinlanfu/HSP&#125;"}
tags: ['Ethics And Bias', 'GPT', 'Has Code', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
Large Language Models (LLMs) have recently showcased remarkable generalizability in various domains. Despite their extensive knowledge LLMs still face challenges in efficiently utilizing encoded knowledge to develop accurate and logical reasoning processes. To mitigate this problem we introduced Hint45;before45;Solving Prompting (HSP) which guides the model to generate hints (e.g. specific knowledge or key ideas) for solving the problem and then generate solutions containing intermediate reasoning steps. Since HSP is orthogonal to prompting methods (e.g. Chain45;of45;Thought (CoT)) we applied HSP to CoT Least45;to45;Most Plan45;and45;Solve and Standard promptings. The results of extensive experiments on 6 reasoning benchmarks and 4 open45;source LLMs demonstrate that HSP can effectively improve the accuracy of reasoning tasks (1) By applying high45;quality hint45;enhanced HSP to CoT prompting Llama245;70B45;Chat shows an improvement of 9.7. (2) Beyond exploring training45;free LLM capabilities we built the HSPMATH dataset based on HSP and fine45;tuned Llemma45;7B reaching 64.3 accuracy surpassing GPT45;3.5 and WizardMath45;13B. We make our code and dataset publicly available at url123;https://github.com/jinlanfu/HSP&#125;.
