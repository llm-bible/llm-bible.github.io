---
layout: publication
title: Detectbench Can Large Language Model Detect And Piece Together Implicit Evidence
authors: Gu Zhouhong, Zhang Lin, Zhu Xiaoxuan, Chen Jiangjie, Huang Wenhao, Zhang Yikai, Wang Shusen, Ye Zheyu, Gao Yan, Feng Hongwei, Xiao Yanghua
conference: "Arxiv"
year: 2024
bibkey: gu2024can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.12641"}
tags: ['Pretraining Methods', 'Prompting', 'RAG']
---
Detecting evidence within the context is a key step in the process of reasoning task. Evaluating and enhancing the capabilities of LLMs in evidence detection will strengthen context-based reasoning performance. This paper proposes a benchmark called DetectBench for verifying the ability to detect and piece together implicit evidence within a long context. DetectBench contains 3928 multiple-choice questions with an average of 994 tokens per question. Each question contains an average of 4.55 pieces of implicit evidence and solving the problem typically requires 7.62 logical jumps to find the correct answer. To enhance the performance of LLMs in evidence detection this paper proposes Detective Reasoning Prompt and Finetune. Experiments demonstrate that the existing LLMs abilities to detect evidence in long contexts are far inferior to humans. However the Detective Reasoning Prompt effectively enhances the capability of powerful LLMs in evidence detection while the Finetuning method shows significant effects in enhancing the performance of weaker LLMs. Moreover when the abilities of LLMs in evidence detection are improved their final reasoning performance is also enhanced accordingly.
