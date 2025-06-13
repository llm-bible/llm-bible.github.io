---
layout: publication
title: 'Mmlongbench-doc: Benchmarking Long-context Document Understanding With Visualizations'
authors: Yubo Ma, Yuhang Zang, Liangyu Chen, Meiqi Chen, Yizhu Jiao, Xinze Li, Xinyuan Lu, Ziyu Liu, Yan Ma, Xiaoyi Dong, Pan Zhang, Liangming Pan, Yu-gang Jiang, Jiaqi Wang, Yixin Cao, Aixin Sun
conference: "Arxiv"
year: 2024
bibkey: ma2024mmlongbench
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.01523"}
tags: ['Multimodal Models', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'GPT']
---
Understanding documents with rich layouts and multi-modal components is a
long-standing and practical task. Recent Large Vision-Language Models (LVLMs)
have made remarkable strides in various tasks, particularly in single-page
document understanding (DU). However, their abilities on long-context DU remain
an open problem. This work presents MMLongBench-Doc, a long-context,
multi-modal benchmark comprising 1,062 expert-annotated questions. Distinct
from previous datasets, it is constructed upon 130 lengthy PDF-formatted
documents with an average of 49.4 pages and 20,971 textual tokens. Towards
comprehensive evaluation, answers to these questions rely on pieces of evidence
from (1) different sources (text, image, chart, table, and layout structure)
and (2) various locations (i.e. page number). Moreover, 33.2% of the questions
are cross-page questions requiring evidence across multiple pages. 22.8% of the
questions are designed to be unanswerable for detecting potential
hallucinations. Experiments on 14 LVLMs demonstrate that long-context DU
greatly challenges current models. Notably, the best-performing model, GPT-4o,
achieves an F1 score of only 42.7%, while the second-best, GPT-4V, scores
31.4%. Furthermore, 12 LVLMs (all except GPT-4o and GPT-4V) even present worse
performance than their LLM counterparts which are fed with lossy-parsed OCR
documents. These results validate the necessity of future research toward more
capable long-context LVLMs. Project Page:
https://mayubo2333.github.io/MMLongBench-Doc
