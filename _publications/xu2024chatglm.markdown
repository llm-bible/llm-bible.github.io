---
layout: publication
title: 'Chatglm-math: Improving Math Problem-solving In Large Language Models With A Self-critique Pipeline'
authors: Yifan Xu, Xiao Liu, Xinghan Liu, Zhenyu Hou, Yueyan Li, Xiaohan Zhang, Zihan Wang, Aohan Zeng, Zhengxiao Du, Wenyi Zhao, Jie Tang, Yuxiao Dong
conference: "Arxiv"
year: 2024
bibkey: xu2024chatglm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.02893"}
  - {name: "Code", url: "https://github.com/THUDM/ChatGLM-Math"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning', 'Has Code', 'Applications']
---
Large language models (LLMs) have shown excellent mastering of human
language, but still struggle in real-world applications that require
mathematical problem-solving. While many strategies and datasets to enhance
LLMs' mathematics are developed, it remains a challenge to simultaneously
maintain and improve both language and mathematical capabilities in deployed
LLM systems.In this work, we tailor the Self-Critique pipeline, which addresses
the challenge in the feedback learning stage of LLM alignment. We first train a
general Math-Critique model from the LLM itself to provide feedback signals.
Then, we sequentially employ rejective fine-tuning and direct preference
optimization over the LLM's own generations for data collection. Based on
ChatGLM3-32B, we conduct a series of experiments on both academic and our newly
created challenging dataset, MathUserEval. Results show that our pipeline
significantly enhances the LLM's mathematical problem-solving while still
improving its language ability, outperforming LLMs that could be two times
larger. Related techniques have been deployed to
ChatGLM\footnote\{\url\{https://chatglm.cn\}\}, an online serving LLM. Related
evaluation dataset and scripts are released at
\url\{https://github.com/THUDM/ChatGLM-Math\}.
