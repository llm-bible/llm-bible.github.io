---
layout: publication
title: 'The Best Of Both Worlds: Toward An Honest And Helpful Large Language Model'
authors: Gao Chujie, Zhang Qihui, Chen Dongping, Huang Yue, Wu Siyuan, Fu Zhengyan, Wan Yao, Zhang Xiangliang, Sun Lichao
conference: "Arxiv"
year: 2024
bibkey: gao2024best
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.00380"}
tags: ['Applications', 'Fine Tuning', 'Merging', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
Large Language Models (LLMs) have achieved remarkable success across various
industries due to their exceptional generative capabilities. However, for safe
and effective real-world deployments, ensuring honesty and helpfulness is
critical. This paper addresses the question: Can we prioritize the helpfulness
of LLMs while preserving their honesty? To begin with, we establish exhaustive
principles aimed at guaranteeing the honesty of LLM. Additionally, we introduce
a novel dataset, referred to as HoneSet, comprising 930 queries spanning six
categories meticulously crafted to assess an LLM's capacity for maintaining
honesty. Subsequently, we present two approaches to augmenting honesty and
helpfulness in LLMs: a training-free enhancement and a fine-tuning-based
improvement. The training-free approach, which is based on curiosity-driven
prompting, empowers LLMs to articulate internal confusion and uncertainty
regarding queries, thereby optimizing their responses. Conversely, the
fine-tuning-based method employs a two-stage process inspired by curriculum
learning: initially instructing LLMs to discern between honest and dishonest
responses, then refining their training to enhance helpfulness. Experiments
conducted on nine prominent LLMs demonstrate a significant improvement in
alignment with honesty across all models through the implementation of our
proposed enhancements. Particularly noteworthy is the 65.3% enhancement
observed in Llama3-8b and the remarkable 124.7% improvement in Mistral-7b, as
measured by the H\\(^\{2\}\\) (honest and helpful) assessment. We believe that our
work can pave the way for developing more trustworthy LLMs for real-world
applications.
