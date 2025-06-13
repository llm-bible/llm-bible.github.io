---
layout: publication
title: 'Not All Contexts Are Equal: Teaching Llms Credibility-aware Generation'
authors: Ruotong Pan, Boxi Cao, Hongyu Lin, Xianpei Han, Jia Zheng, Sirui Wang, Xunliang Cai, Le Sun
conference: "Arxiv"
year: 2024
bibkey: pan2024not
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.06809"}
tags: ['RAG', 'Tools', 'Applications', 'Reinforcement Learning']
---
The rapid development of large language models has led to the widespread
adoption of Retrieval-Augmented Generation (RAG), which integrates external
knowledge to alleviate knowledge bottlenecks and mitigate hallucinations.
However, the existing RAG paradigm inevitably suffers from the impact of flawed
information introduced during the retrieval phrase, thereby diminishing the
reliability and correctness of the generated outcomes. In this paper, we
propose Credibility-aware Generation (CAG), a universally applicable framework
designed to mitigate the impact of flawed information in RAG. At its core, CAG
aims to equip models with the ability to discern and process information based
on its credibility. To this end, we propose an innovative data transformation
framework that generates data based on credibility, thereby effectively
endowing models with the capability of CAG. Furthermore, to accurately evaluate
the models' capabilities of CAG, we construct a comprehensive benchmark
covering three critical real-world scenarios. Experimental results demonstrate
that our model can effectively understand and utilize credibility for
generation, significantly outperform other models with retrieval augmentation,
and exhibit resilience against the disruption caused by noisy documents,
thereby maintaining robust performance. Moreover, our model supports customized
credibility, offering a wide range of potential applications.
