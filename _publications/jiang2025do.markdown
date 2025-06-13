---
layout: publication
title: 'Do Large Language Models Excel In Complex Logical Reasoning With Formal Language?'
authors: Jin Jiang, Jianing Wang, Yuchen Yan, Yang Liu, Jianhua Zhu, Mengdi Zhang, Xunliang Cai, Liangcai Gao
conference: "Arxiv"
year: 2025
bibkey: jiang2025do
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.16998"}
  - {name: "Code", url: "https://github.com/jiangjin1999/FormalEval"}
tags: ['Pretraining Methods', 'Training Techniques', 'Fine-Tuning', 'Has Code']
---
Large Language Models (LLMs) have been shown to achieve breakthrough performance on complex logical reasoning tasks. Nevertheless, most existing research focuses on employing formal language to guide LLMs to derive reliable reasoning paths, while systematic evaluations of these capabilities are still limited. In this paper, we aim to conduct a comprehensive evaluation of LLMs across various logical reasoning problems utilizing formal languages. From the perspective of three dimensions, i.e., spectrum of LLMs, taxonomy of tasks, and format of trajectories, our key findings are: 1) Thinking models significantly outperform Instruct models, especially when formal language is employed; 2) All LLMs exhibit limitations in inductive reasoning capability, irrespective of whether they use a formal language; 3) Data with PoT format achieves the best generalization performance across other languages. Additionally, we also curate the formal-relative training data to further enhance the small language models, and the experimental results indicate that a simple rejected fine-tuning method can better enable LLMs to generalize across formal languages and achieve the best overall performance. Our codes and reports are available at https://github.com/jiangjin1999/FormalEval.
