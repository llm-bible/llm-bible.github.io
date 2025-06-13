---
layout: publication
title: 'Tablegpt2: A Large Multimodal Model With Tabular Data Integration'
authors: Aofeng Su, Aowen Wang, Chao Ye, Chen Zhou, Ga Zhang, Gang Chen, Guangcheng Zhu, Haobo Wang, Haokai Xu, Hao Chen, Haoze Li, Haoxuan Lan, Jiaming Tian, Jing Yuan, Junbo Zhao, Junlin Zhou, Kaizhe Shou, Liangyu Zha, Lin Long, Liyao Li, Pengzuo Wu, Qi Zhang, Qingyi Huang, Saisai Yang, Tao Zhang, Wentao Ye, Wufang Zhu, Xiaomeng Hu, Xijun Gu, Xinjie Sun, Xiang Li, Yuhang Yang, Zhiqing Xiao
conference: "Arxiv"
year: 2024
bibkey: su2024large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.02059"}
tags: ['Multimodal Models', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'GPT', 'Applications']
---
The emergence of models like GPTs, Claude, LLaMA, and Qwen has reshaped AI
applications, presenting vast new opportunities across industries. Yet, the
integration of tabular data remains notably underdeveloped, despite its
foundational role in numerous real-world domains.
  This gap is critical for three main reasons. First, database or data
warehouse data integration is essential for advanced applications; second, the
vast and largely untapped resource of tabular data offers immense potential for
analysis; and third, the business intelligence domain specifically demands
adaptable, precise solutions that many current LLMs may struggle to provide.
  In response, we introduce TableGPT2, a model rigorously pre-trained and
fine-tuned with over 593.8K tables and 2.36M high-quality query-table-output
tuples, a scale of table-related data unprecedented in prior research. This
extensive training enables TableGPT2 to excel in table-centric tasks while
maintaining strong general language and coding abilities.
  One of TableGPT2's key innovations is its novel table encoder, specifically
designed to capture schema-level and cell-level information. This encoder
strengthens the model's ability to handle ambiguous queries, missing column
names, and irregular tables commonly encountered in real-world applications.
Similar to visual language models, this pioneering approach integrates with the
decoder to form a robust large multimodal model.
  We believe the results are compelling: over 23 benchmarking metrics,
TableGPT2 achieves an average performance improvement of 35.20% in the 7B model
and 49.32% in the 72B model over prior benchmark-neutral LLMs, with robust
general-purpose capabilities intact.
