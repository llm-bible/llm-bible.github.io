---
layout: publication
title: Mllmreid: Multimodal Large Language Model-based Person Re-identification
authors: Yang Shan, Zhang Yongfei
conference: "Arxiv"
year: 2024
bibkey: yang2024multimodal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.13201"}
tags: ['Fine Tuning', 'Multimodal Models', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
Multimodal large language models (MLLM) have achieved satisfactory results in many tasks. However their performance in the task of ReID (ReID) has not been explored to date. This paper will investigate how to adapt them for the task of ReID. An intuitive idea is to fine-tune MLLM with ReID image-text datasets and then use their visual encoder as a backbone for ReID. However there still exist two apparent issues (1) Designing instructions for ReID MLLMs may overfit specific instructions and designing a variety of instructions will lead to higher costs. (2) When fine-tuning the visual encoder of a MLLM it is not trained synchronously with the ReID task. As a result the effectiveness of the visual encoder fine-tuning cannot be directly reflected in the performance of the ReID task. To address these problems this paper proposes MLLMReID Multimodal Large Language Model-based ReID. Firstly we proposed Common Instruction a simple approach that leverages the essence ability of LLMs to continue writing avoiding complex and diverse instruction design. Secondly we propose a multi-task learning-based synchronization module to ensure that the visual encoder of the MLLM is trained synchronously with the ReID task. The experimental results demonstrate the superiority of our method.
