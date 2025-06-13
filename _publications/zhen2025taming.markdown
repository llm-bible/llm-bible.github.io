---
layout: publication
title: 'Taming The Titans: A Survey Of Efficient LLM Inference Serving'
authors: Ranran Zhen, Juntao Li, Yixin Ji, Zhenlin Yang, Tong Liu, Qingrong Xia, Xinyu Duan, Zhefeng Wang, Baoxing Huai, Min Zhang
conference: "Arxiv"
year: 2025
bibkey: zhen2025taming
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.19720'}
tags: ['Attention Mechanism', 'Transformer', 'RAG', 'Model Architecture', 'Applications', 'Tools', 'Merging', 'Survey Paper']
---
Large Language Models (LLMs) for Generative AI have achieved remarkable
progress, evolving into sophisticated and versatile tools widely adopted across
various domains and applications. However, the substantial memory overhead
caused by their vast number of parameters, combined with the high computational
demands of the attention mechanism, poses significant challenges in achieving
low latency and high throughput for LLM inference services. Recent
advancements, driven by groundbreaking research, have significantly accelerated
progress in this field. This paper provides a comprehensive survey of these
methods, covering fundamental instance-level approaches, in-depth cluster-level
strategies, emerging scenario directions, and other miscellaneous but important
areas. At the instance level, we review model placement, request scheduling,
decoding length prediction, storage management, and the disaggregation
paradigm. At the cluster level, we explore GPU cluster deployment,
multi-instance load balancing, and cloud service solutions. For emerging
scenarios, we organize the discussion around specific tasks, modules, and
auxiliary methods. To ensure a holistic overview, we also highlight several
niche yet critical areas. Finally, we outline potential research directions to
further advance the field of LLM inference serving.
