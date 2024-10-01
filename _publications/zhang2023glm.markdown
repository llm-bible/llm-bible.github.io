---
layout: publication
title: 'Glm-dialog: Noise-tolerant Pre-training For Knowledge-grounded Dialogue Generation'
authors: Zhang Jing, Zhang Xiaokang, Zhang-li Daniel, Yu Jifan, Yao Zijun, Ma Zeyao, Xu Yiqi, Wang Haohua, Zhang Xiaohan, Lin Nianyi, Lu Sunrui, Li Juanzi, Tang Jie
conference: "Arxiv"
year: 2023
bibkey: zhang2023glm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2302.14401"}
tags: ['Applications', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
We present GLM-Dialog, a large-scale language model (LLM) with 10B parameters capable of knowledge-grounded conversation in Chinese using a search engine to access the Internet knowledge. GLM-Dialog offers a series of applicable techniques for exploiting various external knowledge including both helpful and noisy knowledge, enabling the creation of robust knowledge-grounded dialogue LLMs with limited proper datasets. To evaluate the GLM-Dialog more fairly, we also propose a novel evaluation method to allow humans to converse with multiple deployed bots simultaneously and compare their performance implicitly instead of explicitly rating using multidimensional metrics.Comprehensive evaluations from automatic to human perspective demonstrate the advantages of GLM-Dialog comparing with existing open source Chinese dialogue models. We release both the model checkpoint and source code, and also deploy it as a WeChat application to interact with users. We offer our evaluation platform online in an effort to prompt the development of open source models and reliable dialogue evaluation systems. The additional easy-to-use toolkit that consists of short text entity linking, query generation, and helpful knowledge classification is also released to enable diverse applications. All the source code is available on Github.
