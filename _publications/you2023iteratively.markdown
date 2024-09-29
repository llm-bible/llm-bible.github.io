---
layout: publication
title: Idealgpt Iteratively Decomposing Vision And Language Reasoning Via Large Language Models
authors: Haoxuan You, Rui Sun, Zhecan Wang, Long Chen, Gengyu Wang, Hammad A. Ayyubi, Kai-wei Chang, Shih-fu Chang
conference: "Arxiv"
year: 2023
bibkey: you2023iteratively
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2305.14985v1"}
  - {name: "Code", url: "https://github.com/Hxyou/IdealGPT"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Tools']
---
The field of vision45;and45;language (VL) understanding has made unprecedented progress with end45;to45;end large pre45;trained VL models (VLMs). However they still fall short in zero45;shot reasoning tasks that require multi45;step inferencing. To achieve this goal previous works resort to a divide45;and45;conquer pipeline. In this paper we argue that previous efforts have several inherent shortcomings 1) They rely on domain45;specific sub45;question decomposing models. 2) They force models to predict the final answer even if the sub45;questions or sub45;answers provide insufficient information. We address these limitations via IdealGPT a framework that iteratively decomposes VL reasoning using large language models (LLMs). Specifically IdealGPT utilizes an LLM to generate sub45;questions a VLM to provide corresponding sub45;answers and another LLM to reason to achieve the final answer. These three modules perform the divide45;and45;conquer procedure iteratively until the model is confident about the final answer to the main question. We evaluate IdealGPT on multiple challenging VL reasoning tasks under a zero45;shot setting. In particular our IdealGPT outperforms the best existing GPT45;445;like models by an absolute 1037; on VCR and 1537; on SNLI45;VE. Code is available at https://github.com/Hxyou/IdealGPT
