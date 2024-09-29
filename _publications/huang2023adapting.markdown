---
layout: publication
title: Adapting Pre45;trained Language Models To Vision45;language Tasks Via Dynamic Visual Prompting
authors: Huang Shubin, Wu Qiong, Zhou Yiyi, Chen Weijie, Zhang Rongsheng, Sun Xiaoshuai, Ji Rongrong
conference: "Arxiv"
year: 2023
bibkey: huang2023adapting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.00409"}
tags: ['Attention Mechanism', 'BERT', 'Efficiency And Optimization', 'Fine Tuning', 'Merging', 'Model Architecture', 'Prompting']
---
Pre45;trained language models (PLMs) have played an increasing role in multimedia research. In terms of vision45;language (VL) tasks they often serve as a language encoder and still require an additional fusion network for VL reasoning resulting in excessive memory overhead. In this paper we focus on exploring PLMs as a stand45;alone model for VL reasoning tasks. Inspired by the recently popular prompt tuning we first prove that the processed visual features can be also projected onto the semantic space of PLMs and act as prompt tokens to bridge the gap between single45; and multi45;modal learning. However this solution exhibits obvious redundancy in visual information and model inference and the placement of prompt tokens also greatly affects the final performance. Based on these observations we further propose a novel transfer learning approach for PLMs termed Dynamic Visual Prompting (DVP). Concretely DVP first deploys a cross45;attention module to obtain text45;related and compact visual prompt tokens thereby greatly reducing the input length of PLMs. To obtain the optimal placement we also equip DVP with a reinforcement45;learning based search algorithm which can automatically merge DVP with PLMs for different VL tasks via a very short search process. In addition we also experiment DVP with the recently popular adapter approach to keep the most parameters of PLMs intact when adapting to VL tasks helping PLMs achieve a quick shift between single45; and multi45;modal tasks. We apply DVP to two representative PLMs namely BERT and T5 and conduct extensive experiments on a set of VL reasoning benchmarks including VQA2.0 GQA and SNLIVE. The experimental results not only show the advantage of DVP on efficiency and performance but also confirm its superiority in adapting pre45;trained language models to VL tasks.
