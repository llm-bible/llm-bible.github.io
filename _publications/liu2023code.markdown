---
layout: publication
title: "Code Execution With Pre-trained Language Models"
authors: Liu Chenxiao, Lu Shuai, Chen Weizhu, Jiang Daxin, Svyatkovskiy Alexey, Fu Shengyu, Sundaresan Neel, Duan Nan
conference: "Arxiv"
year: 2023
bibkey: liu2023code
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.05383"}
tags: ['Applications', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques', 'Transformer']
---
Code execution is a fundamental aspect of programming language semantics that reflects the exact behavior of the code. However most pre-trained models for code intelligence ignore the execution trace and only rely on source code and syntactic structures. In this paper we investigate how well pre-trained models can understand and perform code execution. We develop a mutation-based data augmentation technique to create a large-scale and realistic Python dataset and task for code execution which challenges existing models such as Codex. We then present CodeExecutor a Transformer model that leverages code execution pre-training and curriculum learning to enhance its semantic comprehension. We evaluate CodeExecutor on code execution and show its promising performance and limitations. We also demonstrate its potential benefits for code intelligence tasks such as zero-shot code-to-code search and text-to-code generation. Our analysis provides insights into the learning and generalization abilities of pre-trained models for code execution.
