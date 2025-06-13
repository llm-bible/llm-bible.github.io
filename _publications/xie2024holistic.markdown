---
layout: publication
title: 'Finben: A Holistic Financial Benchmark For Large Language Models'
authors: Qianqian Xie, Weiguang Han, Zhengyu Chen, Ruoyu Xiang, Xiao Zhang, Yueru He, Mengxi Xiao, Dong Li, Yongfu Dai, Duanyu Feng, Yijing Xu, Haoqiang Kang, Ziyan Kuang, Chenhan Yuan, Kailai Yang, Zheheng Luo, Tianlin Zhang, Zhiwei Liu, Guojun Xiong, Zhiyang Deng, Yuechen Jiang, Zhiyuan Yao, Haohang Li, Yangyang Yu, Gang Hu, Jiajia Huang, Xiao-yang Liu, Alejandro Lopez-lira, Benyou Wang, Yanzhao Lai, Hao Wang, Min Peng, Sophia Ananiadou, Jimin Huang
conference: "Arxiv"
year: 2024
bibkey: xie2024holistic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.12659"}
  - {name: "Code", url: "https://github.com/The-FinAI/PIXIU"}
tags: ['Agentic', 'GPT', 'Tools', 'Applications', 'RAG', 'Model Architecture', 'Language Modeling', 'IJCAI', 'Has Code']
---
LLMs have transformed NLP and shown promise in various fields, yet their
potential in finance is underexplored due to a lack of comprehensive evaluation
benchmarks, the rapid development of LLMs, and the complexity of financial
tasks. In this paper, we introduce FinBen, the first extensive open-source
evaluation benchmark, including 36 datasets spanning 24 financial tasks,
covering seven critical aspects: information extraction (IE), textual analysis,
question answering (QA), text generation, risk management, forecasting, and
decision-making. FinBen offers several key innovations: a broader range of
tasks and datasets, the first evaluation of stock trading, novel agent and
Retrieval-Augmented Generation (RAG) evaluation, and three novel open-source
evaluation datasets for text summarization, question answering, and stock
trading. Our evaluation of 15 representative LLMs, including GPT-4, ChatGPT,
and the latest Gemini, reveals several key findings: While LLMs excel in IE and
textual analysis, they struggle with advanced reasoning and complex tasks like
text generation and forecasting. GPT-4 excels in IE and stock trading, while
Gemini is better at text generation and forecasting. Instruction-tuned LLMs
improve textual analysis but offer limited benefits for complex tasks such as
QA. FinBen has been used to host the first financial LLMs shared task at the
FinNLP-AgentScen workshop during IJCAI-2024, attracting 12 teams. Their novel
solutions outperformed GPT-4, showcasing FinBen's potential to drive innovation
in financial LLMs. All datasets, results, and codes are released for the
research community: https://github.com/The-FinAI/PIXIU.
