---
layout: publication
title: 'Tinyr1-32b-preview: Boosting Accuracy With Branch-merge Distillation'
authors: Lin Sun, Guangxiang Zhao, Xiaoqi Jian, Yuhan Wu, Weihong Lin, Yongfu Zhu, Change Jia, Linglin Zhang, Jinzhu Wu, Junfeng Ran, Sai-er Hu, Zihan Jiang, Junting Zhou, Wenrui Liu, Bin Cui, Tong Yang, Xiangzheng Zhang
conference: "Arxiv"
year: 2025
bibkey: sun2025boosting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.04872"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Distillation', 'Quantization', 'Pretraining Methods', 'Fine-Tuning', 'Attention Mechanism']
---
The challenge of reducing the size of Large Language Models (LLMs) while
maintaining their performance has gained significant attention. However,
existing methods, such as model distillation and transfer learning, often fail
to achieve high accuracy. To address this limitation, we introduce the
Branch-Merge distillation approach, which enhances model compression through
two phases: (1) the Branch Phase, where knowledge from a large teacher model is
\textit\{selectively distilled\} into specialized student models via
domain-specific supervised fine-tuning (SFT); And (2) the Merge Phase, where
these student models are merged to enable cross-domain knowledge transfer and
improve generalization. We validate our distillation approach using DeepSeek-R1
as the teacher and DeepSeek-R1-Distill-Qwen-32B as the student. The resulting
merged model, TinyR1-32B-Preview, outperforms its counterpart
DeepSeek-R1-Distill-Qwen-32B across multiple benchmarks, including Mathematics
(+5.5 points), Coding (+4.4 points) and Science (+2.9 points), while achieving
near-equal performance to DeepSeek-R1 on AIME 2024. The Branch-Merge
distillation approach provides a scalable solution for creating smaller,
high-performing LLMs with reduced computational cost and time.
