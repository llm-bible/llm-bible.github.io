---
layout: publication
title: FIAT Fusing learning paradigms with Instruction-Accelerated Tuning
authors: Wang Xinyi, Wieting John, Clark Jonathan H.
conference: "Arxiv"
year: 2023
bibkey: wang2023fiat
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.04663"}
tags: ['Fine Tuning', 'In Context Learning', 'Pretraining Methods', 'Prompting', 'Training Techniques']
---
Learning paradigms for large language models (LLMs) currently tend to fall within either in-context learning (ICL) or full fine-tuning. Each of these comes with their own trade-offs based on available data model size compute cost ease-of-use and final quality with neither solution performing well across-the-board. In this article we first describe ICL and fine-tuning paradigms in a way that highlights their natural connections. Based on these connections we propose a new learning paradigm called FIAT that fuses the best of these paradigms together enabling prompt-engineered instructions and chain-of-thought reasoning with the very largest models while also using similar methods to perform parameter updates on a modestly-sized LLM with parameter-efficient tuning. We evaluate FIATs effectiveness on a variety of multilingual tasks and observe that FIAT performs better than both ICL and fine-tuning at scales ranging from 100-10000 training examples. We hope that FIAT provides a practical way of harnessing the full potential of LLMs without needing to make a hard choice between learning paradigms.
