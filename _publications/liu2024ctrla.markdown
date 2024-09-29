---
layout: publication
title: Ctrla Adaptive Retrieval-augmented Generation Via Probe-guided Control
authors: Liu Huanshuo, Zhang Hao, Guo Zhijiang, Dong Kuicai, Li Xiangyang, Lee Yi Quan, Zhang Cong, Liu Yong
conference: "Arxiv"
year: 2024
bibkey: liu2024ctrla
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.18727"}
  - {name: "Code", url: "https://github.com/HSLiu-Initial/CtrlA.git"}
tags: ['Fine Tuning', 'Has Code', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Retrieval-augmented generation (RAG) has emerged as a promising solution for mitigating hallucinations of large language models (LLMs) with retrieved external knowledge. Adaptive RAG enhances this approach by dynamically assessing the retrieval necessity aiming to balance external and internal knowledge usage. However existing adaptive RAG methods primarily realize retrieval on demand by relying on superficially verbalize-based or probability-based feedback of LLMs or directly fine-tuning LLMs via carefully crafted datasets resulting in unreliable retrieval necessity decisions heavy extra costs and sub-optimal response generation. We present the first attempts to delve into the internal states of LLMs to mitigate such issues by introducing an effective probe-guided adaptive RAG framework termed CtrlA. Specifically CtrlA employs an honesty probe to regulate the LLMs behavior by manipulating its representations for increased honesty and a confidence probe to monitor the internal states of LLM and assess confidence levels determining the retrieval necessity during generation. Experiments show that CtrlA is superior to existing adaptive RAG methods on a diverse set of tasks the honesty control can effectively make LLMs more honest and confidence monitoring is proven to be a promising indicator of retrieval trigger. Our codes are available at https://github.com/HSLiu-Initial/CtrlA.git.
