---
layout: publication
title: 'Relative Overfitting And Accept-reject Framework'
authors: Yanxin Liu, Yunqi Zhang
conference: "Arxiv"
year: 2025
bibkey: liu2025relative
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.07783'}
tags: ['Language Modeling', 'Tools', 'Model Architecture']
---
Currently, the scaling law of Large Language Models (LLMs) faces challenges and bottlenecks. This paper posits that noise effects, stemming from changes in the signal-to-noise ratio under diminishing marginal returns, are the root cause of these issues. To control this noise, we investigated the differences between models with performance advantages and disadvantages, introducing the concept of "relative overfitting." Based on their complementary strengths, we have proposed an application framework, Accept-Reject (AR), and the associated AR Law, which operates within this framework to elucidate the patterns of performance changes after model integration. In Natural Language Processing (NLP), we use LLMs and Small Language Models (SLMs) as the medium for discussion. This framework enables SLMs to exert a universal positive influence on LLM decision outputs, rather than the intuitively expected potential negative influence. We validated our approach using self-built models based on mainstream architectures and pre-trained mainstream models across multiple datasets, including basic language modeling, long-context tasks, subject examination, and question-answering (QA) benchmarks. The results demonstrate that through our framework, compared to increasing the LLM's parameters, we can achieve better performance improvements with significantly lower parameter and computational costs in many scenarios. These improvements are universal, stable, and effective. Furthermore, we explore the potential of "relative overfitting" and the AR framework in other machine learning domains, such as computer vision (CV) and AI for science. We hope the proposed approach can help scale laws overcome existing bottlenecks.
