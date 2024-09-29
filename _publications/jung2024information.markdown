---
layout: publication
title: Information45;theoretic Distillation For Reference45;less Summarization
authors: Jung Jaehun, Lu Ximing, Jiang Liwei, Brahman Faeze, West Peter, Koh Pang Wei, Choi Yejin
conference: "Arxiv"
year: 2024
bibkey: jung2024information
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.13780"}
tags: ['Applications', 'Distillation', 'Efficiency And Optimization', 'GPT', 'Model Architecture', 'Tools']
---
The current winning recipe for automatic summarization is using proprietary large45;scale language models (LLMs) such as ChatGPT as is or imitation learning from them as teacher models. While increasingly ubiquitous dependence on such large45;scale language models is convenient there remains an important question of whether small45;scale models could have achieved competitive results if we were to seek an alternative learning method 45;45; that allows for a more cost45;efficient controllable yet powerful summarizer. We present InfoSumm a novel framework to distill a powerful summarizer based on the information45;theoretic objective for summarization without relying on either the LLMs capability or human45;written references. To achieve this we first propose a novel formulation of the desiderata of summarization (saliency faithfulness and brevity) through the lens of mutual information between the original document and the summary. Based on this formulation we start off from Pythia45;2.8B as the teacher model which is not yet capable of summarization then self45;train the model to optimize for the information45;centric measures of ideal summaries. Distilling from the improved teacher we arrive at a compact but powerful summarizer with only 568M parameters that performs competitively against ChatGPT without ever relying on ChatGPTs capabilities. Extensive analysis demonstrates that our approach outperforms in45;domain supervised models in human evaluation let alone state45;of45;the45;art unsupervised methods and wins over ChatGPT in controllable summarization.
