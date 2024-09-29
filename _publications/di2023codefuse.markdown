---
layout: publication
title: CodeFuse-13B A Pretrained Multi-lingual Code Large Language Model
authors: Di Peng, Li Jianguo, Yu Hang, Jiang Wei, Cai Wenting, Cao Yang, Chen Chaoyu, Chen Dajun, Chen Hongwei, Chen Liang, Fan Gang, Gong Jie, Gong Zi, Hu Wen, Guo Tingting, Lei Zhichao, Li Ting, Li Zheng, Liang Ming, Liao Cong, Liu Bingchang, Liu Jiachen, Liu Zhiwei, Lu Shaojun, Shen Min, Wang Guangpei, Wang Huan, Wang Zhi, Xu Zhaogui, Yang Jiawei, Ye Qing, Zhang Gehao, Zhang Yu, Zhao Zelin, Zheng Xunjin, Zhou Hailian, Zhu Lifu, Zhu Xianying
conference: "Arxiv"
year: 2023
bibkey: di2023codefuse
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.06266"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
Code Large Language Models (Code LLMs) have gained significant attention in the industry due to their wide applications in the full lifecycle of software engineering. However the effectiveness of existing models in understanding non-English inputs for multi-lingual code-related tasks is still far from well studied. This paper introduces CodeFuse-13B an open-sourced pre-trained code LLM. It is specifically designed for code-related tasks with both English and Chinese prompts and supports over 40 programming languages. CodeFuse achieves its effectiveness by utilizing a high quality pre-training dataset that is carefully filtered by program analyzers and optimized during the training process. Extensive experiments are conducted using real-world usage scenarios the industry-standard benchmark HumanEval-x and the specially designed CodeFuseEval for Chinese prompts. To assess the effectiveness of CodeFuse we actively collected valuable human feedback from the AntGroups software development process where CodeFuse has been successfully deployed. The results demonstrate that CodeFuse-13B achieves a HumanEval pass64;1 score of 37.10 positioning it as one of the top multi-lingual code LLMs with similar parameter sizes. In practical scenarios such as code generation code translation code comments and testcase generation CodeFuse performs better than other models when confronted with Chinese prompts.
