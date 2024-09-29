---
layout: publication
title: Xdial45;eval A Multilingual Open45;domain Dialogue Evaluation Benchmark
authors: Zhang Chen, D'haro Luis Fernando, Tang Chengguang, Shi Ke, Tang Guohua, Li Haizhou
conference: "Arxiv"
year: 2023
bibkey: zhang2023xdial
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.08958"}
  - {name: "Code", url: "https://github.com/e0397123/xDial&#45;Eval"}
tags: ['Applications', 'BERT', 'GPT', 'Has Code', 'Model Architecture', 'RAG']
---
Recent advancements in reference45;free learned metrics for open45;domain dialogue evaluation have been driven by the progress in pre45;trained language models and the availability of dialogue data with high45;quality human annotations. However current studies predominantly concentrate on English dialogues and the generalization of these metrics to other languages has not been fully examined. This is largely due to the absence of a multilingual dialogue evaluation benchmark. To address the issue we introduce xDial45;Eval built on top of open45;source English dialogue evaluation datasets. xDial45;Eval includes 12 turn45;level and 6 dialogue45;level English datasets comprising 14930 annotated turns and 8691 annotated dialogues respectively. The English dialogue data are extended to nine other languages with commercial machine translation systems. On xDial45;Eval we conduct comprehensive analyses of previous BERT45;based metrics and the recently45;emerged large language models. Lastly we establish strong self45;supervised and multilingual baselines. In terms of average Pearson correlations over all datasets and languages the best baseline outperforms OpenAIs ChatGPT by absolute improvements of 6.537; and 4.637; at the turn and dialogue levels respectively albeit with much fewer parameters. The data and code are publicly available at https://github.com/e0397123/xDial&#45;Eval.
