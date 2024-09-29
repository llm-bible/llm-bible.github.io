---
layout: publication
title: Teaching Language Models To Self45;improve Through Interactive Demonstrations
authors: Yu Xiao, Peng Baolin, Galley Michel, Gao Jianfeng, Yu Zhou
conference: "Arxiv"
year: 2023
bibkey: yu2023teaching
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.13522"}
tags: ['Ethics And Bias', 'Prompting', 'Training Techniques']
---
The self45;improving ability of large language models (LLMs) enabled by prompting them to analyze and revise their own outputs has garnered significant interest in recent research. However this ability has been shown to be absent and difficult to learn for smaller models thus widening the performance gap between state45;of45;the45;art LLMs and more cost45;effective and faster ones. To reduce this gap we introduce TriPosT a training algorithm that endows smaller models with such self45;improvement ability and show that our approach can improve a LLaMA45;7bs performance on math and reasoning tasks by up to 7.1337;. In contrast to prior work we achieve this by using the smaller model to interact with LLMs to collect feedback and improvements on its own generations. We then replay this experience to train the small model. Our experiments on four math and reasoning datasets show that the interactive experience of learning from and correcting its own mistakes is crucial for small models to improve their performance.
