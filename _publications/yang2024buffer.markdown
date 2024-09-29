---
layout: publication
title: Buffer Of Thoughts Thought45;augmented Reasoning With Large Language Models
authors: Yang Ling, Yu Zhaochen, Zhang Tianjun, Cao Shiyi, Xu Minkai, Zhang Wentao, Gonzalez Joseph E., Cui Bin
conference: "Arxiv"
year: 2024
bibkey: yang2024buffer
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.04271"}
  - {name: "Code", url: "https://github.com/YangLing0818/buffer&#45;of&#45;thought&#45;llm"}
tags: ['Efficiency And Optimization', 'Has Code', 'Pretraining Methods', 'Prompting', 'RAG', 'Security']
---
We introduce Buffer of Thoughts (BoT) a novel and versatile thought45;augmented reasoning approach for enhancing accuracy efficiency and robustness of large language models (LLMs). Specifically we propose meta45;buffer to store a series of informative high45;level thoughts namely thought45;template distilled from the problem45;solving processes across various tasks. Then for each problem we retrieve a relevant thought45;template and adaptively instantiate it with specific reasoning structures to conduct efficient reasoning. To guarantee the scalability and stability we further propose buffer45;manager to dynamically update the meta45;buffer thus enhancing the capacity of meta45;buffer as more tasks are solved. We conduct extensive experiments on 10 challenging reasoning45;intensive tasks and achieve significant performance improvements over previous SOTA methods 1137; on Game of 24 2037; on Geometric Shapes and 5137; on Checkmate45;in45;One. Further analysis demonstrate the superior generalization ability and model robustness of our BoT while requiring only 1237; of the cost of multi45;query prompting methods (e.g. tree/graph of thoughts) on average. Notably we find that our Llama345;8B+BoT has the potential to surpass Llama345;70B model. Our project is available at https://github.com/YangLing0818/buffer&#45;of&#45;thought&#45;llm
