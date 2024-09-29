---
layout: publication
title: Generate Then Select Open45;ended Visual Question Answering Guided By World Knowledge
authors: Fu Xingyu, Zhang Sheng, Kwon Gukyeong, Perera Pramuditha, Zhu Henghui, Zhang Yuhao, Li Alexander Hanbo, Wang William Yang, Wang Zhiguo, Castelli Vittorio, Ng Patrick, Roth Dan, Xiang Bing
conference: "Arxiv"
year: 2023
bibkey: fu2023generate
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.18842"}
  - {name: "Code", url: "http://cogcomp.org/page/publication&#95;view/1010"}
tags: ['Applications', 'Ethics And Bias', 'GPT', 'Has Code', 'Model Architecture', 'Prompting', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
The open45;ended Visual Question Answering (VQA) task requires AI models to jointly reason over visual and natural language inputs using world knowledge. Recently pre45;trained Language Models (PLM) such as GPT45;3 have been applied to the task and shown to be powerful world knowledge sources. However these methods suffer from low knowledge coverage caused by PLM bias 45;45; the tendency to generate certain tokens over other tokens regardless of prompt changes and high dependency on the PLM quality 45;45; only models using GPT45;3 can achieve the best result. To address the aforementioned challenges we propose RASO a new VQA pipeline that deploys a generate45;then45;select strategy guided by world knowledge for the first time. Rather than following the de facto standard to train a multi45;modal model that directly generates the VQA answer RASO first adopts PLM to generate all the possible answers and then trains a lightweight answer selection model for the correct answer. As proved in our analysis RASO expands the knowledge coverage from in45;domain training data by a large margin. We provide extensive experimentation and show the effectiveness of our pipeline by advancing the state45;of45;the45;art by 4.137; on OK45;VQA without additional computation cost. Code and models are released at http://cogcomp.org/page/publication&#95;view/1010
