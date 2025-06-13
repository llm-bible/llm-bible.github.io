---
layout: publication
title: 'Optimizing Knowledge Integration In Retrieval-augmented Generation With Self-selection'
authors: Yan Weng, Fengbin Zhu, Tong Ye, Haoyan Liu, Fuli Feng, Tat-seng Chua
conference: "Arxiv"
year: 2025
bibkey: weng2025optimizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.06148"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG']
---
Retrieval-Augmented Generation (RAG), which integrates external knowledge
into Large Language Models (LLMs), has proven effective in enabling LLMs to
produce more accurate and reliable responses. However, it remains a significant
challenge how to effectively integrate external retrieved knowledge with
internal parametric knowledge in LLMs. In this work, we propose a novel
Self-Selection RAG framework, where the LLM is made to select from pairwise
responses generated with internal parametric knowledge solely and with external
retrieved knowledge together to achieve enhanced accuracy. To this end, we
devise a Self-Selection-RGP method to enhance the capabilities of the LLM in
both generating and selecting the correct answer, by training the LLM with
Direct Preference Optimization (DPO) over a curated Retrieval Generation
Preference (RGP) dataset. Experimental results with two open-source LLMs (i.e.,
Llama2-13B-Chat and Mistral-7B) well demonstrate the superiority of our
approach over other baseline methods on Natural Questions (NQ) and TrivialQA
datasets.
