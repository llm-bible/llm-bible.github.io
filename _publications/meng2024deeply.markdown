---
layout: publication
title: Deepstack Deeply Stacking Visual Tokens Is Surprisingly Simple And Effective For Lmms
authors: Meng Lingchen, Yang Jianwei, Tian Rui, Dai Xiyang, Wu Zuxuan, Gao Jianfeng, Jiang Yu-gang
conference: "Arxiv"
year: 2024
bibkey: meng2024deeply
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.04334"}
tags: ['Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Transformer']
---
Most large multimodal models (LMMs) are implemented by feeding visual tokens as a sequence into the first layer of a large language model (LLM). The resulting architecture is simple but significantly increases computation and memory costs as it has to handle a large number of additional tokens in its input layer. This paper presents a new architecture DeepStack for LMMs. Considering N layers in the language and vision transformer of LMMs we stack the visual tokens into N groups and feed each group to its aligned transformer layer textit123;from bottom to top125;. Surprisingly this simple method greatly enhances the power of LMMs to model interactions among visual tokens across layers but with minimal additional cost. We apply DeepStack to both language and vision transformer in LMMs and validate the effectiveness of DeepStack LMMs with extensive empirical results. Using the same context length our DeepStack 7B and 13B parameters surpass their counterparts by textbf123;2.7125; and textbf123;2.9125; on average across textbf123;9125; benchmarks respectively. Using only one45;fifth of the context length DeepStack rivals closely to the counterparts that use the full context length. These gains are particularly pronounced on high45;resolution tasks e.g. textbf123;4.2125; textbf123;11.0125; and textbf123;4.0125; improvements on TextVQA DocVQA and InfoVQA compared to LLaVA45;1.545;7B respectively. We further apply DeepStack to vision transformer layers which brings us a similar amount of improvements textbf123;3.8125; on average compared with LLaVA45;1.545;7B.
