---
layout: publication
title: Chatglm45;math Improving Math Problem45;solving In Large Language Models With A Self45;critique Pipeline
authors: Xu Yifan, Liu Xiao, Liu Xinghan, Hou Zhenyu, Li Yueyan, Zhang Xiaohan, Wang Zihan, Zeng Aohan, Du Zhengxiao, Zhao Wenyi, Tang Jie, Dong Yuxiao
conference: "Arxiv"
year: 2024
bibkey: xu2024chatglm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.02893"}
  - {name: "Code", url: "https://github.com/THUDM/ChatGLM&#45;Math&#125;"}
tags: ['Applications', 'Efficiency And Optimization', 'Has Code', 'Reinforcement Learning']
---
Large language models (LLMs) have shown excellent mastering of human language but still struggle in real45;world applications that require mathematical problem45;solving. While many strategies and datasets to enhance LLMs mathematics are developed it remains a challenge to simultaneously maintain and improve both language and mathematical capabilities in deployed LLM systems.In this work we tailor the Self45;Critique pipeline which addresses the challenge in the feedback learning stage of LLM alignment. We first train a general Math45;Critique model from the LLM itself to provide feedback signals. Then we sequentially employ rejective fine45;tuning and direct preference optimization over the LLMs own generations for data collection. Based on ChatGLM345;32B we conduct a series of experiments on both academic and our newly created challenging dataset MathUserEval. Results show that our pipeline significantly enhances the LLMs mathematical problem45;solving while still improving its language ability outperforming LLMs that could be two times larger. Related techniques have been deployed to ChatGLMfootnote123;url123;https://chatglm.cn&#125;&#125;, an online serving LLM. Related evaluation dataset and scripts are released at url123;https://github.com/THUDM/ChatGLM&#45;Math&#125;.
