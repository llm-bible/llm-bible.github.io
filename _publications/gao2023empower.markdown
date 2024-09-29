---
layout: publication
title: Empower Your Model with Longer and Better Context Comprehension
authors: Gao Yifei, Wang Lei, Fang Jun, Hu Longhua, Cheng Jun
conference: "Arxiv"
year: 2023
bibkey: gao2023empower
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.13365"}
tags: ['Attention Mechanism', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
Recently with the emergence of numerous Large Language Models (LLMs) the implementation of AI has entered a new era. Irrespective of these models own capacity and structure there is a growing demand for LLMs to possess enhanced comprehension of longer and more complex contexts with relatively smaller sizes. Models often encounter an upper limit when processing sequences of sentences that extend beyond their comprehension capacity and result in off-topic or even chaotic responses. While several recent works attempt to address this issue in various ways they rarely focus on why models are unable to compensate or strengthen their capabilities on their own. In this paper we thoroughly investigate the nature of information transfer within LLMs and propose a novel technique called Attention Transition. This technique empowers models to achieve longer and better context comprehension with minimal additional training or impact on generation fluency. Our experiments are conducted on the challenging XSum dataset using LLaMa-7b model with context token length ranging from 800 to 1900. Results demonstrate that we achieve substantial improvements compared with the original generation results evaluated by GPT4.
